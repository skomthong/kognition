---
title: Geospatial Visualization
slug: geospatial-visualization
layer: techniques/visual
parent: visualization-taxonomy
children: []
related: [chart-selection, visual-encoding, color-theory, dashboard-design, analytical-concepts-for-visualization]
tags: [craft-skill, visual-design, maps, geography, spatial-data, choropleth]
evidence_level: practitioner
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Geospatial Visualization

## Summary

Geospatial visualization shows data tied to location — where something happens, how values vary across geography, and how spatial patterns relate to outcomes. In learning design, it's relevant for global program analytics, regional needs assessment, and any context where PLACE matters.

## Types

| Type | What it shows | When to use |
|---|---|---|
| **Choropleth map** | Regions shaded by value (e.g., completion rate by country) | Comparing values across defined regions |
| **Point map** | Individual locations as dots/markers | Showing where events or learners are located |
| **Proportional symbol map** | Markers sized by value | Showing magnitude at specific locations |
| **Heat map (geographic)** | Density/intensity gradient overlaid on a map | Showing concentration patterns |
| **Flow/route map** | Lines connecting origins and destinations | Showing movement, migration, knowledge flow |
| **Cartogram** | Region size distorted by data value | When the DATA matters more than geographic accuracy |

## Key Principles

- **Use maps only when location matters** — if the insight is "Region A outperforms Region B," a bar chart is clearer. Maps add value when spatial PATTERNS matter (clusters, corridors, proximity effects).
- **Choropleth pitfalls**: large regions dominate visually even if they have small populations. Normalize data (rates per capita, not raw counts). Choose color scales carefully — sequential for magnitude, diverging for above/below a threshold.
- **Projection matters** — all flat maps distort the globe. For global views, be aware that Mercator exaggerates areas at high latitudes. For regional views, use appropriate local projections.
- **Label key features** — don't assume viewers know geography. Label the regions or locations that carry the insight.
- **Accessibility**: don't rely on color alone. Add labels, annotations, or a companion table.

## Application to Learning Design

- **Global program dashboards**: completion rates, assessment scores, or participation by region
- **Needs assessment**: mapping skill gaps or training demand by location
- **Access analysis**: identifying regions with connectivity or infrastructure barriers
- **Transfer tracking**: where are learned skills being applied? Where are transfer gaps?

## Sources

- Few, S. (2012). *Show Me the Numbers* (2nd ed.). Analytics Press.
- Cairo, A. (2016). *The Truthful Art*. New Riders.
