# Kognition

A structured knowledge base for learning experience design — 248 entries across learning science, instructional design, educational technology, communication craft, and strategic thinking.

Built by **Supakorn Ted Komthong** as a personal project to make knowledge accessible and help people reach their desired potential.

## Live Viewer

Open `index.html` with a local server to browse the knowledge base interactively:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/index.html` — the viewer provides search, a relationship graph, and layer-based navigation.

## Structure

Knowledge is organized into a 7-layer dependency stack, where each layer builds on the ones below it:

| Layer | Path | What lives here | Entries |
|-------|------|-----------------|---------|
| **1. Foundations** | `foundations/` | Core mechanisms — memory, attention, emotion, motivation, social cognition | 18 |
| **2. Principles** | `principles/` | Cross-cutting rules — cognitive load, multimedia learning, desirable difficulties, framing, trust | 32 |
| **3. Techniques** | `techniques/` | Applied skills across 5 paths | 108 |
| | `techniques/writing/` | Writing craft — clarity, structure, rhetoric, genres | 36 |
| | `techniques/visual/` | Visual communication — composition, charts, dashboards, color | 20 |
| | `techniques/narrative/` | Storytelling — story arc, scenarios, data storytelling | 15 |
| | `techniques/instructional/` | Learning design — retrieval practice, assessment, feedback, scaffolding | 26 |
| | `techniques/interaction/` | Media and interaction — gamification, video, immersive, AI interfaces | 11 |
| **4. Methods** | `methods/` | Complete design workflows — ADDIE, backward design, action mapping, Cynefin | 39 |
| **5. Systems** | `systems/` | Infrastructure — LMS, xAPI, analytics, accessibility, AI, privacy | 25 |
| **6. Patterns** | `patterns/` | Context-specific solutions — onboarding, certification, reskilling, AI-augmented | 14 |
| **7. Strategy** | `strategy/` | Judgment and intelligence — decision theory, systems thinking, validity, sensemaking | 12 |

## Entry Format

Every entry is a markdown file with YAML frontmatter:

```yaml
---
title: Human-readable title
slug: kebab-case-matching-filename
layer: foundations
related: [cognitive-load, attention, dual-process-models]
tags: [memory, encoding, retrieval]
evidence_level: empirical | mixed | theoretical | practitioner
status: seed | growing | mature
---
```

Entries link across layers via the `related` field and inline markdown links.

## Evidence Levels

| Level | Meaning |
|-------|---------|
| **empirical** | Supported by experimental studies, meta-analyses, validated instruments |
| **mixed** | Substantial theory plus meaningful empirical research |
| **theoretical** | Primarily conceptual, limited direct hypothesis testing |
| **practitioner** | Originated in practice, limited rigorous validation |

## Navigation

See [`_index.md`](_index.md) for the full entry map.

## License

- **Code** (HTML, CSS, JavaScript): [MIT License](LICENSE)
- **Content** (markdown knowledge base): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

You are free to share and adapt this material with appropriate credit.
