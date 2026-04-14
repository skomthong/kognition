---
title: Network Visualization
slug: network-visualization
layer: techniques/visual
parent:
children: []
related: [visualization-taxonomy, conceptual-visualization, chart-selection, visual-encoding, communities-of-practice, connectivism, systems-thinking]
tags: [craft-skill, visual-design, networks, relationships, graphs, systems, stakeholders]
evidence_level: practitioner
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Network Visualization

## Summary

Network visualization shows RELATIONSHIPS — who connects to whom, what influences what, how information flows, where clusters form. It's distinct from other chart types because the primary data is the CONNECTIONS, not the individual values. Essential for stakeholder mapping, knowledge flow analysis, organizational design, community analysis, and systems thinking.

## Types

| Type | What it shows | When to use |
|---|---|---|
| **Node-link diagram** | Entities (nodes) connected by relationships (links) | Social networks, organizational relationships, knowledge flow |
| **Chord diagram** | Bilateral flows between categories around a circle | Migration, communication patterns, inter-departmental flows |
| **Sankey diagram** | Flow volume between stages/categories | Learner pathways, budget allocation, process flows with volume |
| **Adjacency matrix** | Grid showing connections between all pairs | Dense networks where node-link becomes "hairball" |
| **Stakeholder map** | People/groups positioned by influence, interest, relationship | Change management, program planning, political navigation |
| **Systems map** | Elements + feedback loops + causal arrows | Understanding complex dynamics, identifying leverage points |

## Design Principles

- **Node size = importance** — degree centrality (how connected), influence, or another meaningful metric
- **Link weight = strength** — thicker lines for stronger/more frequent connections
- **Color = category** — departments, roles, types of relationship
- **Layout matters** — force-directed layouts reveal clusters naturally; hierarchical layouts show levels; circular layouts show symmetry
- **Reduce clutter** — large networks become "hairball" graphs. Filter to show only the most important connections, or use interactive exploration.
- **Label key nodes** — not every node needs a label, but the important ones do
- **Tell the story** — annotate: "Notice this cluster has no connection to the main network" or "This node is the bridge between two otherwise disconnected groups"

## Application to Learning Design

- **Stakeholder mapping** — who influences the learning program? Who needs to be engaged?
- **Knowledge flow analysis** — where does expertise flow in the organization? Where are the bottlenecks?
- **Community network analysis** — who interacts with whom in a CoP? Are there isolated members?
- **Curriculum dependency mapping** — which courses depend on which prerequisites?
- **Causal systems mapping** — what feedback loops drive or undermine learning transfer? (See [Structured Thinking](../../techniques/writing/structured-thinking.md))

## Common Mistakes

- **Hairball syndrome** — showing every connection in a large network without filtering. Unreadable.
- **No meaningful encoding** — all nodes same size, all links same weight, no color coding. The visualization adds nothing beyond a list.
- **Static display of dynamic data** — networks change over time; a snapshot may mislead about the current state
- **No annotation** — the viewer has to figure out the pattern themselves

## Sources

- Lima, M. (2011). *Visual Complexity: Mapping Patterns of Information*. Princeton Architectural Press.
- Newman, M. E. J. (2010). *Networks: An Introduction*. Oxford University Press.
