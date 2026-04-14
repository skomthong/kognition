---
title: Uncertainty Visualization
slug: uncertainty-visualization
layer: techniques/visual
parent:
children: []
related: [chart-selection, visual-encoding, analytical-concepts-for-visualization, data-storytelling, evidence-and-reasoning, trust-and-credibility]
tags: [craft-skill, visual-design, uncertainty, confidence-intervals, ranges, ambiguity, honesty]
evidence_level: mixed
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Uncertainty Visualization

## Summary

Most real-world data involves uncertainty — confidence intervals, ranges, probabilities, missing data, measurement error. Visualizations that hide uncertainty present false precision, misleading decision-makers. Showing uncertainty honestly is both an ethical obligation and a design challenge: too much uncertainty information overwhelms; too little misleads.

## Techniques

| Technique | What it shows | When to use |
|---|---|---|
| **Error bars** | Confidence interval or standard deviation around a mean | Bar charts, line charts — show range around point estimates |
| **Confidence bands** | Shaded area around a trend line | Time series — show the range of plausible values |
| **Fan charts** | Widening bands for increasing uncertainty over time | Forecasts, projections — uncertainty grows with distance |
| **Gradient/density** | Darker = more likely, lighter = less likely | Probability distributions, geographic uncertainty |
| **Range bars** | Min-max or interquartile range | Show the full spread, not just the average |
| **Annotation** | Text callout stating the uncertainty | Any chart: "Note: based on N=47; confidence interval crosses zero" |
| **Multiple scenarios** | Show 2-3 plausible outcomes rather than one "prediction" | Strategic planning, forecasting |
| **Small multiples of possible outcomes** | Grid of plausible results | Monte Carlo-style: "here are 20 possible futures" |

## Key Principles

- **Never present a point estimate without context** — "Retention: 73%" means nothing without: compared to what? With what confidence? Based on how many learners?
- **Match uncertainty display to audience sophistication** — executives may need "high/medium/low" zones; researchers need actual confidence intervals
- **Uncertainty is not weakness** — showing it builds [trust and credibility](../../principles/trust-and-credibility.md). Hiding it destroys trust when decisions go wrong.
- **Show the range, not just the mean** — a program with mean score 75% and range 30-100% is VERY different from one with mean 75% and range 70-80%
- **Label the type of uncertainty** — is it measurement error? Sampling variability? Model uncertainty? Genuine unknowability? Each has different implications for decisions.

## Common Mistakes

- **No uncertainty shown at all** — false precision is the most common data visualization lie
- **Error bars without explanation** — "error bars" could mean SD, SE, 95% CI, or range. Always label.
- **Confidence intervals that cross meaningful thresholds** — if the CI includes zero (no effect), that's critical information to surface, not hide
- **Over-complicated uncertainty displays** — a chart with 5 overlapping uncertainty bands is unreadable. Simplify.

## How To Practice

1. Take a chart you've made with point estimates and add error bars or confidence bands. Does the story change?
2. Present the same data to two audiences: one with full uncertainty, one with only point estimates. Compare the decisions they'd make.
3. Find a public data visualization that hides uncertainty. Redraw it with uncertainty shown. What changes?

## Sources

- Spiegelhalter, D. (2017). Risk and uncertainty communication. *Annual Review of Statistics and Its Application*, 4, 31-60.
- Hullman, J., & Diakopoulos, N. (2011). Visualization rhetoric: Framing effects in narrative visualization. *IEEE Transactions on Visualization and Computer Graphics*, 17(12), 2231-2240.
