---
title: Causal Inference
slug: causal-inference
layer: strategy
parent:
children: []
related: [evidence-and-reasoning, critical-thinking, analytical-concepts-for-visualization, uncertainty-and-probabilistic-thinking, validity-and-reliability, kirkpatrick]
tags: [strategy, research, causation, correlation, counterfactual, evidence]
evidence_level: mixed
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Causal Inference

## Definition

Causal inference is the logic of establishing whether X actually CAUSES Y — not just that X and Y are correlated. In learning design, every effectiveness claim is a causal claim: "This program CAUSED learners to perform better." The rigor of the causal evidence determines whether that claim is defensible.

## The Fundamental Problem

You can never observe both what happened AND what would have happened without the intervention (the counterfactual) for the same person at the same time. Causal inference methods try to estimate the counterfactual.

## Evidence Hierarchy for Causal Claims

| Design | Causal strength | Feasibility in L&D |
|---|---|---|
| **Randomized controlled trial (RCT)** | Strongest — random assignment controls for confounds | Rare — ethical and practical barriers to randomizing training |
| **Quasi-experiment** (comparison group, pre-post) | Moderate — controls for some confounds | Common — compare trained vs untrained groups, or before vs after |
| **Regression/matching** | Moderate — statistically controls for observed confounds | Feasible with good data |
| **Interrupted time series** | Moderate — shows change at intervention point | Good for system-level changes (new LMS, new policy) |
| **Case study / qualitative** | Weak for causation, strong for mechanism | Very feasible — explains HOW and WHY, not just WHETHER |
| **Correlation only** | Weakest — no causal warrant | Easy but misleading if treated as causal |

## Common Causal Reasoning Errors

| Error | Example | The problem |
|---|---|---|
| **Correlation as causation** | "Programs with higher engagement have higher transfer" — engagement CAUSES transfer? | Maybe. Or maybe both are caused by better design, better learners, or better managers. |
| **Post hoc ergo propter hoc** | "We added gamification, then completion went up" | Maybe. But completion might have gone up anyway (seasonal effect, new manager push). |
| **Selection bias** | "Learners who completed the optional program performed better" | Of course — they were already more motivated. Completion didn't cause performance. |
| **Survivorship bias** | "Our top performers all went through the leadership program" | But you're not seeing the people who went through it and DIDN'T become top performers. |
| **Confounding** | "Spaced practice group outperformed massed practice group" | But the spaced group also had more total study time. Was it spacing or time? |

## Key Principles

- **Every "this works" claim is a causal claim** — treat it with appropriate rigor
- **Correlation is a START, not a conclusion** — when you see correlation, ask: what else could explain this?
- **Mixed methods strengthens causal arguments** — quant shows WHETHER an effect exists; qual shows HOW and WHY (mechanism)
- **Be honest about your evidence level** — "This quasi-experimental evidence suggests..." is more credible than "This proves..."

## Sources

- Shadish, W. R., Cook, T. D., & Campbell, D. T. (2002). *Experimental and Quasi-Experimental Designs for Generalized Causal Inference*. Houghton Mifflin.
- Pearl, J. (2009). *Causality* (2nd ed.). Cambridge University Press.
