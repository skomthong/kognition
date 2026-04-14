---
title: Analytical Concepts for Visualization
slug: analytical-concepts-for-visualization
layer: techniques/visual
parent:
children: []
related: [visual-encoding, chart-selection, data-storytelling, critical-thinking, evidence-and-reasoning, learning-analytics]
tags: [craft-skill, visual-design, statistics, data-literacy, interpretation, analytical]
evidence_level: mixed
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Analytical Concepts for Visualization

## Summary

Poor charts often come from poor data understanding, not poor design skills. A learning designer who doesn't understand variance, correlation, or uncertainty will make charts that mislead even with perfect visual design. These are the analytical concepts you need to visualize data honestly and effectively.

## Core Concepts

### Central tendency and spread
| Concept | What it shows | Why it matters for visualization |
|---|---|---|
| **Mean** | Average value | Can be misleading with skewed data or outliers |
| **Median** | Middle value | More robust than mean for skewed distributions |
| **Range** | Min to max | Shows extremes but ignores distribution shape |
| **Standard deviation** | Typical spread around the mean | Determines whether a difference is meaningful or noise |
| **Percentiles/quartiles** | Distribution landmarks (25th, 50th, 75th) | What box plots display |

**Visualization rule**: never show only the mean. Always show spread — error bars, box plots, or individual data points.

### Comparison and significance
| Concept | What it means | Visualization implication |
|---|---|---|
| **Baseline** | Reference point for comparison | Always show what you're comparing against |
| **Normalization** | Adjusting for different scales | Compare rates, not raw counts, when group sizes differ |
| **Benchmarking** | Comparing to a standard or peer group | Include reference lines or bands |
| **Effect size** | Magnitude of a difference | More important than statistical significance for practical decisions |
| **Confidence interval** | Range of plausible values | Show as error bars or bands — not reporting uncertainty is misleading |

### Relationships
| Concept | Meaning | Visualization trap |
|---|---|---|
| **Correlation** | Two variables move together | Correlation ≠ causation. ALWAYS. |
| **Causation** | One variable drives another | Requires controlled evidence, not just a chart |
| **Confounds** | A third variable explains the apparent relationship | Hidden in scatter plots unless you control for it |
| **Simpson's paradox** | A trend that appears in groups reverses when groups are combined | Always check aggregated AND disaggregated data |

### Data quality
| Concept | Issue | Impact |
|---|---|---|
| **Outliers** | Extreme values | Can distort means and chart scales; investigate before removing |
| **Missing data** | Incomplete records | Can bias conclusions; be transparent about gaps |
| **Sampling bias** | Non-representative data | Conclusions don't generalize; note the limitation |
| **Survivorship bias** | Only seeing what survived | Common in program evaluation — you see completers, not dropouts |

## The Golden Rule

**A person can make poor charts simply because they do not understand the data logic behind them.** Visual design skill without analytical literacy produces beautiful misinformation.

## Sources

- Cairo, A. (2019). *How Charts Lie*. W.W. Norton.
- Few, S. (2012). *Show Me the Numbers* (2nd ed.). Analytics Press.
