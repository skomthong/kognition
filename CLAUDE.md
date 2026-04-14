# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a markdown-based knowledge base for learning experience design (LXD) with 248 entries across a 7-layer dependency stack, AND a single-page web application (`index.html`) that renders the knowledge base as an interactive viewer. The KB contains its own design principles — and the viewer should apply them.

## Repository Structure

```
index.html             # Single-page viewer app (HTML + CSS + JS, no build tools)
_index.md              # Master navigation map — source of truth for file discovery

foundations/           # Layer 1: Core mechanisms (memory, attention, emotion, motivation, social cognition)
principles/            # Layer 2: Cross-cutting rules (CLT, CTML, desirable difficulties, framing, trust)
techniques/            # Layer 3: Applied skills (5 paths)
  writing/             #   Writing craft (36 entries)
  visual/              #   Visual communication (20 entries)
  narrative/           #   Storytelling and communication (15 entries)
  instructional/       #   Learning design techniques (26 entries)
  interaction/         #   Media and interaction design (11 entries)
methods/               # Layer 4: Complete design workflows (ADDIE, SAM, backward design, Cynefin, etc.)
systems/               # Layer 5: Infrastructure (LMS, xAPI, analytics, AI, privacy)
patterns/              # Layer 6: Context-specific solutions (onboarding, reskilling, certification, etc.)
strategy/              # Layer 7: Judgment and intelligence (decision theory, systems thinking, validity)

source/                # Raw research inventories (inventory.md, addendum-1 through 5)
```

## Entry Format

Every entry is a markdown file with YAML frontmatter:

```yaml
---
title: Human-readable title
slug: kebab-case-matching-filename
layer: foundations | principles | techniques/writing | techniques/visual | techniques/narrative | techniques/instructional | techniques/interaction | methods | systems | patterns | strategy
related: [slugs-of-related-entries-across-any-layer]
parent:            # (optional) slug of parent entry
children: []       # (optional) slugs of child entries
tags: [freeform, tags]
evidence_level: empirical | mixed | theoretical | practitioner
created: YYYY-MM-DD
updated: YYYY-MM-DD
status: seed | growing | mature
---
```

## Key Conventions

- File names are kebab-case and must match the `slug` field in frontmatter
- Every topic gets its own file — parent/child is expressed via frontmatter, not folder nesting
- Cross-layer relationships go in the `related` frontmatter array (source of truth) AND as inline markdown links in the body
- Relative links between entries: same layer uses `slug.md`, cross-layer uses `../layer/slug.md`
- When adding entries, also add them to `_index.md` under the appropriate layer section
- Evidence levels (empirical, mixed, theoretical, practitioner) come from the source inventories
- The `_index.md` file is the file discovery mechanism for the viewer app — all entry paths are extracted from its markdown links

## The Viewer App (index.html)

A single HTML file with embedded CSS and JavaScript. No build tools. External dependencies loaded via CDN:
- **marked.js** — markdown rendering
- **D3.js** — force-directed graph visualization

### How the app works
1. On load, fetches `_index.md` and extracts all `.md` file paths from markdown links
2. Fetches each .md file, parses YAML frontmatter + markdown body
3. Builds in-memory index: entries array, relationship graph, layer groupings, tag index
4. Renders three views: Reader, Graph, Stats

### Views
- **Stats (homepage)** — dashboard with entry counts, evidence distribution, top hubs, top tags, cross-layer connections
- **Reader** — sidebar navigation + entry content with metadata badges and related entry chips
- **Graph** — D3 force-directed network, nodes colored by layer, click-to-highlight neighbors, layer toggle filters

### Design principles applied (from the KB itself)
The viewer is designed using principles from its own entries. When modifying the viewer, consult and apply:

- **Cognitive load** (`principles/cognitive-load.md`) — progressive disclosure in sidebar; one content area at a time
- **Visual encoding** (`principles/visual-encoding.md`) — layer colors are consistent across sidebar, badges, graph, and stats; evidence levels use a second consistent color system
- **Gestalt similarity** (`techniques/visual/gestalt-in-design.md`) — same color = same meaning everywhere; proximity groups related elements
- **Processing fluency** (`principles/processing-fluency.md`) — system fonts, high contrast, clean typography, minimal decoration
- **Information architecture** (`systems/information-architecture.md`) — layer → sublayer → entry hierarchy; search for findability
- **Attention economy** (`principles/attention-economy.md`) — search is prominent; most important info visible immediately
- **Dashboard design** (`techniques/visual/dashboard-design.md`) — stats page follows overview-first, decision-ready principles
- **Chunking** (`techniques/writing/chunking-and-information-hierarchy.md`) — metadata separated from content; related entries in their own section
- **Annotation** (`techniques/visual/annotation-techniques.md`) — tooltips explain what metadata means (evidence levels, status), not just show labels
- **Typography** (`techniques/visual/typography.md`) — clear size/weight hierarchy: layer headings > entry titles > body
- **Color theory** (`techniques/visual/color-theory.md`) — limited palette, consistent meaning, WCAG contrast compliance
- **Slide design** (`techniques/visual/slide-design.md`) — one idea per view; don't overwhelm

### Color systems

**Layer colors** (11 distinct paths):
| Layer | Color |
|---|---|
| foundations | #1e40af |
| principles | #7c3aed |
| techniques/writing | #059669 |
| techniques/visual | #d97706 |
| techniques/narrative | #e11d48 |
| techniques/instructional | #0d9488 |
| techniques/interaction | #4f46e5 |
| methods | #b45309 |
| systems | #475569 |
| patterns | #0891b2 |
| strategy | #a21caf |

**Evidence level colors** (used in sidebar dots, badges, stats charts, graph tooltips):
| Level | Color |
|---|---|
| empirical | #059669 |
| mixed | #7c3aed |
| theoretical | #d97706 |
| practitioner | #6b7280 |

### Mobile-first responsive design
- Base CSS is mobile (full-width, off-canvas sidebar with overlay, larger touch targets)
- `@media (min-width: 768px)` adds desktop layout (sidebar visible, wider content area)
- `@media (min-width: 1200px)` widens sidebar
- Tables scroll horizontally on mobile
- Graph and stats adapt to viewport

### When modifying the viewer
- All data comes from .md files — the viewer contains NO hardcoded content data
- `_index.md` is the file manifest — if you add entries, add them to `_index.md` or they won't appear
- The `NAV_TREE` constant in JS defines the sidebar hierarchy (layers and sub-layers)
- The `LAYERS` object is built from `NAV_TREE` and provides color/label lookups
- Layer overview pages are generated dynamically from loaded entries
- To serve locally: `python -m http.server 8000` then open `http://localhost:8000/index.html`
