---
title: Dashboard Design
slug: dashboard-design
layer: techniques/visual
parent: visualization-taxonomy
children: []
related: [visual-encoding, chart-selection, learning-analytics, cognitive-load, attention, gestalt-in-design, usability]
tags: [craft-skill, visual-design, dashboards, KPI, monitoring, decision-support, Few]
evidence_level: practitioner
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Dashboard Design

## Summary

A dashboard is a decision interface — a visual display of the most important information needed to achieve one or more objectives, arranged on a single screen so it can be monitored at a glance (Few). It is NOT a collection of charts. It is a designed tool for a specific user making specific decisions.

## Key Concepts

### KPI vs. diagnostic metrics
- **KPIs** (Key Performance Indicators) — the vital few numbers that signal overall health. Dashboard headline.
- **Diagnostic metrics** — the detail that explains WHY a KPI moved. Available on drill-down, not on the overview.

### Overview first, detail on demand
The dashboard landing view should answer: "Is everything OK?" in 5 seconds. Detail (filtering, drill-down, date range expansion) is available when the user needs to investigate.

### Threshold cues and alerts
- Use color and icons to signal status: green = on track, yellow = watch, red = act now
- Thresholds must be meaningful (based on real standards, not arbitrary)
- Never use color alone — add text labels or icons for accessibility

## Design Principles

| Principle | Application |
|---|---|
| **Single screen** | All critical information visible without scrolling |
| **Visual consistency** | Same chart types for same data types throughout |
| **Minimal decoration** | No 3D, no gradients, no chartjunk — every pixel serves a purpose |
| **Direct labeling** | Labels on the chart, not in a separate legend |
| **Logical layout** | Group related metrics by Gestalt proximity; most important KPIs top-left (for left-to-right readers) |
| **Scannability** | A user should be able to scan the full dashboard and spot issues in under 10 seconds |
| **Context** | Show comparison (vs. last period, vs. target, vs. benchmark) — a number without context is meaningless |

## Dashboard Anti-Patterns

- **Dashboard as art gallery** — every chart uses a different type, color scheme, and layout
- **Too many metrics** — if everything is on the dashboard, nothing stands out
- **No hierarchy** — all metrics given equal visual weight
- **Missing targets/comparisons** — "Completion rate: 73%" means nothing without "Target: 85%"
- **Real-time fetish** — updating every second when decisions are made weekly
- **No drill-down** — the overview raises questions it can't answer

## Application to Learning Design

- **Program dashboards**: completion rates, assessment scores, practice frequency, learner satisfaction — with thresholds and trend lines
- **Facilitator dashboards**: real-time session engagement, poll results, participation patterns
- **Transfer dashboards**: post-program behavior indicators, supervisor ratings, performance metrics
- **Design dashboards**: content usage, drop-off points, time-on-task patterns — for iterative improvement

## Sources

- Few, S. (2013). *Information Dashboard Design* (2nd ed.). Analytics Press.
- Few, S. (2012). *Show Me the Numbers* (2nd ed.). Analytics Press.
