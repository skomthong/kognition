---
title: Chart Selection
slug: chart-selection
layer: techniques/visual
parent: visualization-taxonomy
children: []
related: [visual-encoding, data-storytelling, cognitive-load, analytical-concepts-for-visualization, data-visualization, slide-design]
tags: [craft-skill, visual-design, charts, data-visualization, comparison, trend, distribution]
evidence_level: practitioner
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Chart Selection

## Summary

Chart selection is matching the right visual form to the data type and analytical task. Wrong chart choices obscure patterns; right choices reveal them instantly. This entry provides the detailed taxonomy by purpose.

## Chart Taxonomy by Purpose

### A. Comparison (comparing categories)
| Chart | Best for | Notes |
|---|---|---|
| Bar chart (horizontal) | Ranking, long category labels | Default for comparison |
| Column chart (vertical) | Few categories, natural left-to-right | Use when category count is small |
| Dot plot | Precise comparison, minimal ink | Cleaner than bars for some contexts |
| Lollipop chart | Comparison with emphasis | Dot + line; visually lighter than bars |
| Table with highlights | Exact values matter | Add conditional formatting for patterns |

### B. Time series (change over time)
| Chart | Best for | Notes |
|---|---|---|
| Line chart | Continuous trends, multiple series | Default for time data |
| Area chart | Volume over time, stacked contribution | Use sparingly — can obscure individual series |
| Sparkline | Inline trend in tables/dashboards | Compact, no axes — shows shape, not precision |
| Slope chart | Before/after comparison | Two time points, shows direction of change |
| Timeline | Events in sequence, milestones | Qualitative time, not quantitative |

### C. Distribution (spread and variation)
| Chart | Best for | Notes |
|---|---|---|
| Histogram | Shape of a single distribution | Bin width matters — experiment |
| Box plot | Comparing distributions across groups | Shows median, quartiles, outliers |
| Violin plot | Shape + density of distributions | Richer than box plot, harder to read for novices |
| Strip/jitter plot | Small datasets, individual points visible | Shows actual data, not summary |

### D. Relationship (association between variables)
| Chart | Best for | Notes |
|---|---|---|
| Scatter plot | Correlation, clusters, outliers | Default for relationship |
| Bubble chart | Three variables (x, y, size) | Area encoding is weak — annotate |
| Correlation matrix | Many pairwise relationships | Overview, not precision |
| Connected scatter | Change in two variables over time | Tricky to read — annotate heavily |

### E. Composition (part of whole)
| Chart | Best for | Notes |
|---|---|---|
| Stacked bar | Composition across categories | Better than pie for comparison |
| 100% stacked bar | Proportional comparison | When total doesn't matter, proportions do |
| Treemap | Hierarchical composition | Space-efficient for many categories |
| Waterfall | How components add/subtract to a total | Great for financial bridges |
| Pie chart | 2-3 slices maximum | Overused; bars are almost always better |

### F. Hierarchy
Tree diagram, treemap, sunburst, dendrogram — use when things contain sub-things.

### G. Flow and network
Sankey diagram (flow volume), alluvial chart (categorical flow), network graph (connections), chord diagram (bilateral flow), process flow map.

### H. Geospatial
Choropleth map (regions colored by value), point map (locations), proportional symbol map (sized markers), heat map on map (density).

## Common Mistakes

- Using pie charts for more than 3 categories (angles are hard to compare)
- 3D charts that distort spatial perception
- Truncated y-axes on bar charts (exaggerates differences)
- Too many series on one chart (>4-5 lines become unreadable)
- No clear takeaway — the viewer shouldn't have to figure out the point
- Weak or missing labels and annotations

## Checklist Before Making Any Chart

1. What is the **single main message**?
2. Who is the **audience**?
3. What **task** should the chart support?
4. What **data type** am I showing?
5. What chart form best fits that task + data type?
6. What should the audience notice **first**?
7. What can I **remove**?

## Sources

- Few, S. (2012). *Show Me the Numbers* (2nd ed.). Analytics Press.
- Schwabish, J. (2021). *Better Data Visualizations*. Columbia University Press.
- Tufte, E. R. (2001). *The Visual Display of Quantitative Information*. Graphics Press.
