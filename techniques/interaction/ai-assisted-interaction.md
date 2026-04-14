---
title: AI-Assisted Interaction Patterns
slug: ai-assisted-interaction
layer: techniques/interaction
parent:
children: []
related: [ai-in-education, conversational-interface-design, adaptive-learning, feedback-models, scaffolding, retrieval-practice, nist-privacy]
tags: [craft-skill, interaction-design, AI, co-creation, feedback-loops, augmentation]
evidence_level: practitioner
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# AI-Assisted Interaction Patterns

## Summary

AI-assisted interaction patterns define how AI augments (not replaces) the learning experience — from generating practice content to providing feedback to co-creating with the learner. These patterns are emerging rapidly; the design challenge is ensuring AI serves learning objectives rather than creating dependency or replacing productive struggle.

## Pattern Catalog

| Pattern | How AI participates | Learning value | Risk |
|---|---|---|---|
| **AI as practice partner** | Role-plays the "other side" in scenarios (client, patient, stakeholder) | Unlimited practice without scheduling humans | Inconsistent behavior, unrealistic responses |
| **AI as Socratic tutor** | Asks questions rather than giving answers; guides reasoning | Scaffolds thinking, builds metacognition | Can feel frustrating if questioning is poor |
| **AI as feedback provider** | Reviews learner work and provides task/process-level feedback | Immediate, scalable feedback | Shallow feedback on complex work; false confidence |
| **AI as content generator** | Creates practice items, scenarios, case variations on demand | Personalized practice at scale | Quality variation, hallucination, needs QA |
| **AI as co-creator** | Learner + AI build something together (draft, analysis, design) | Mirrors real-world AI-augmented work | Learner may outsource thinking to AI |
| **AI as retrieval prompt** | Generates spaced retrieval questions from studied material | Automated spacing + personalization | Items may miss nuance or test trivial knowledge |
| **AI as explanation engine** | Explains concepts at adjustable difficulty/analogy level | Adaptive explanation for diverse learners | May reinforce misconceptions if explanation is wrong |
| **AI as assessment support** | Scores rubric-based work, flags anomalies, drafts feedback | Reduces assessment workload | Bias, fairness concerns, must be human-reviewed for stakes |

## Design Principles

### Scaffold thinking, don't replace it
The most important principle: AI should make learners THINK MORE, not less. If AI does the analysis for the learner, the learner doesn't learn to analyze. Design prompts that require the learner to do the cognitive work:
- "Before I give you feedback, write what you think the strengths and weaknesses are" (self-assessment first)
- "I'll give you three options — which is best and why?" (evaluation, not just consumption)

### Human-in-the-loop for high stakes
AI feedback on a draft essay: fine. AI determining whether someone passes a certification: requires human review. The higher the stakes, the more human oversight is needed.

### Transparent about limitations
- Disclose that AI is being used
- Warn learners that AI can be wrong
- Teach learners to evaluate AI output critically — this IS a 21st-century skill

### Privacy by design
- What learner data does the AI process?
- Is conversation data used for model training?
- Who has access to AI interaction logs?
- [NIST Privacy Framework](../../systems/nist-privacy.md) applies

## When to Use / When Not To

**Use when:** you need scale (more practice than humans can facilitate), personalization (adaptive difficulty), or availability (24/7 practice access).

**Don't use when:** the learning goal is interpersonal skill that requires human nuance, when errors have serious consequences without human review, or when the learner population can't critically evaluate AI output.

## Sources

- Holmes, W., Bialik, M., & Fadel, C. (2019). *Artificial Intelligence in Education*. Center for Curriculum Redesign.
- UNESCO (2023). *Guidance for Generative AI in Education and Research*.
