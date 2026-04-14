---
title: Business Intelligence and Decision Support
slug: business-intelligence-and-decision-support
layer: systems
parent:
children: []
related: [learning-analytics, dashboard-design, visualization-tools, decision-visualization, data-storytelling, xapi]
tags: [systems, BI, analytics, reporting, decision-making, data-pipelines]
evidence_level: practitioner
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Business Intelligence and Decision Support

## Summary

Business intelligence (BI) systems transform raw data into actionable insights through collection, integration, analysis, and visualization. Decision support systems (DSS) go further — they're designed to directly support specific decisions by presenting relevant data in decision-ready formats. In learning design, BI/DSS connects [learning analytics](learning-analytics.md) to organizational decision-making.

## The Analytics Pipeline

```
Data sources → Collection → Integration → Analysis → Visualization → Decision → Action
```

| Stage | L&D application |
|---|---|
| **Data sources** | LMS, xAPI/LRS, HRIS, performance management, business KPIs |
| **Collection** | Automated via xAPI statements, LMS logs, survey tools |
| **Integration** | Connecting learning data to business data (performance, retention, revenue) |
| **Analysis** | Identifying patterns: who completes, who transfers, what predicts success |
| **Visualization** | [Dashboards](../techniques/visual/dashboard-design.md), reports, scorecards |
| **Decision** | Program investment, design changes, learner interventions |
| **Action** | Redesign, scale, retire, intervene |

## From BI to Decision Intelligence

The analytics maturity ladder:

| Level | Type | Question | L&D example |
|---|---|---|---|
| **Descriptive** | BI reporting | "What happened?" | "Completion was 73%" |
| **Diagnostic** | Analysis | "Why did it happen?" | "Drop-off concentrated in Module 5 due to cognitive overload" |
| **Predictive** | Forecasting | "What will happen?" | "Based on current patterns, 40% of Cohort 3 is at risk of non-completion" |
| **Prescriptive** | Decision support | "What should we do?" | "Trigger manager outreach for at-risk learners; redesign Module 5" |
| **Decision intelligence** | Action systems | Analytics → decision → automated action + human oversight | "System auto-triggers spaced boosters when practice frequency drops; flags to facilitator when pattern suggests disengagement" |

Decision intelligence (Pratt, 2019) connects analytics to decisions explicitly — every metric is tied to a specific decision it informs, with clear thresholds for action. This prevents the "data-rich, insight-poor" syndrome where dashboards exist but don't drive behavior.

## Key Principles

- **Connect learning metrics to business outcomes** — L&D reporting that stops at completion rates will be funded like overhead. Link to: time-to-competence, error rates, customer satisfaction, employee retention, revenue impact.
- **Decision-ready, not data-rich** — a dashboard with 50 metrics serves no one. Design for the 3-5 decisions the audience actually makes. See [Dashboard Design](../techniques/visual/dashboard-design.md).
- **Automate the routine, humanize the judgment** — automated reports for status; human analysis for interpretation and strategy.
- **Privacy governance** — more data integration = more privacy risk. Apply [NIST PF](nist-privacy.md) rigorously.

## Sources

- Davenport, T. H. (2006). Competing on analytics. *Harvard Business Review*, 84(1), 98-107.
