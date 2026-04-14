---
title: Taxonomy and Metadata Systems
slug: taxonomy-and-metadata
layer: systems
parent:
children: []
related: [information-architecture, content-operations, knowledge-management-systems, lms, learning-analytics, xapi]
tags: [systems, taxonomy, metadata, tagging, classification, findability, governance]
evidence_level: practitioner
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Taxonomy and Metadata Systems

## Summary

Taxonomy is how you CLASSIFY content (the categories and hierarchy). Metadata is how you DESCRIBE individual content items (the tags, attributes, and properties). Together they determine whether content is findable, filterable, reusable, and reportable at scale. Without them, a content library becomes a digital junk drawer.

## Key Concepts

### Taxonomy
A controlled vocabulary organized in a hierarchy:
```
Learning Domain
├── Leadership
│   ├── Communication
│   ├── Decision-Making
│   └── Change Management
├── Technical Skills
│   ├── Data Analysis
│   └── Software Proficiency
└── Compliance
    ├── Safety
    └── Regulatory
```

### Metadata schema
Properties attached to each content item:

| Field | Purpose | Example values |
|---|---|---|
| **Title** | Human-readable name | "Cognitive Load Theory" |
| **Topic/category** | Taxonomy classification | Leadership > Communication |
| **Content type** | Format | Article, video, simulation, quiz, job aid |
| **Audience** | Who it's for | New managers, all employees, senior leaders |
| **Difficulty level** | Expertise match | Foundational, intermediate, advanced |
| **Learning objectives** | What it teaches | Aligned to competency framework |
| **Duration** | Time commitment | 5 min, 30 min, 2 hours |
| **Created/updated date** | Currency | 2026-04-14 |
| **Owner** | Responsible person | Content operations team |
| **Status** | Lifecycle stage | Draft, published, under review, archived |

### Tagging
Freeform or semi-controlled labels that supplement taxonomy:
- Tags provide cross-cutting findability: "remote work" cuts across Leadership, Communication, and Technology categories
- Controlled tags (from a defined list) are more consistent; freeform tags are more flexible
- Without governance, tags proliferate into synonym chaos ("remote work" vs "WFH" vs "distributed teams")

## Key Principles

- **Design for the searcher, not the organizer** — categories should match how LEARNERS look for content, not how designers organize it. Test with real users.
- **Consistent application** — a taxonomy only works if content is consistently classified. Build tagging into the content creation workflow, not as an afterthought.
- **Governance is maintenance** — taxonomies evolve. Review annually: are categories still relevant? Are there orphan categories? New topics that need categories?
- **This knowledge base IS a taxonomy** — the 7-layer stack (foundations → patterns) with sub-paths is a taxonomy. The YAML frontmatter is metadata. The `_index.md` is the browsing interface.

## Knowledge Graphs and Structured Knowledge Systems

Beyond flat taxonomies, **knowledge graphs** represent entities AND the relationships between them — enabling richer queries, recommendations, and AI-assisted discovery:

- **Nodes**: concepts, skills, content items, learners, roles
- **Edges**: "requires," "builds on," "applies to," "assessed by," "related to"
- **Queries**: "What skills are prerequisites for this role?" "What content supports this competency?" "What's the shortest learning path from current skills to target skills?"

Knowledge graphs power: adaptive learning pathways, skill-gap analysis, content recommendation engines, and competency-based progression at scale. They are the structural backbone of sophisticated [personalized learning](../techniques/instructional/personalized-learning.md) and [adaptive learning](adaptive-learning.md) systems.

**This knowledge base's `related:` frontmatter arrays are a simple knowledge graph** — each entry is a node, each `related` slug is an edge. A more sophisticated version would type the edges (builds-on, applies, contrasts-with).

## Sources

- Hedden, H. (2016). *The Accidental Taxonomist* (2nd ed.). Information Today.
