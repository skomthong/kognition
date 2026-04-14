---
title: Conversational Interface Design
slug: conversational-interface-design
layer: techniques/interaction
parent:
children: []
related: [ai-in-education, adaptive-learning, feedback-models, scaffolding, coaching-techniques, nist-privacy]
tags: [craft-skill, interaction-design, chatbots, AI-tutors, dialogue, prompts]
evidence_level: practitioner
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Conversational Interface Design

## Summary

Conversational interfaces — chatbots, AI tutors, dialogue-based practice systems — are becoming standard in learning design. Designing them requires combining instructional design principles (scaffolding, feedback, retrieval practice) with interaction design principles (turn-taking, persona, error handling, graceful failure).

## Design Considerations

### Instructional design
| Consideration | Principle |
|---|---|
| **What's the learning goal?** | The conversation must serve a learning objective, not just be "interactive" |
| **Scaffolding level** | How much does the system guide vs. let the learner explore? Adjust by expertise level |
| **Feedback quality** | Task-level feedback is easy to automate; process and self-regulation feedback require careful design |
| **Retrieval prompts** | Use conversation to trigger retrieval: "Before I explain, what do you remember about...?" |
| **Metacognitive prompts** | "What's your confidence level?" "What would you check first?" |

### Interaction design
| Consideration | Principle |
|---|---|
| **Persona** | The AI has an implicit personality. Design it deliberately: warm guide, neutral assistant, Socratic questioner |
| **Turn length** | Short exchanges keep pace. Long AI responses lose the learner. |
| **Repair and fallback** | What happens when the AI doesn't understand? Graceful failure beats confident nonsense. |
| **Transparency** | Disclose that this is an AI. Be honest about limitations. |
| **Guardrails** | Prevent the AI from giving harmful, incorrect, or off-topic responses |

### Ethics and governance
- **Privacy**: what conversation data is stored, who sees it, how long it's kept ([NIST PF](../../systems/nist-privacy.md))
- **Bias**: AI responses may reflect training data biases
- **Over-reliance**: learners may trust AI feedback uncritically — build in metacognitive prompts and human checkpoints
- **Academic integrity**: clear boundaries on what AI assistance is acceptable

## When to Use / When Not To

**Use when:** practice dialogue (Socratic questioning, language practice, scenario role-play), just-in-time support, retrieval practice delivery, coaching augmentation.

**Don't use when:** high-stakes feedback requiring nuance, sensitive topics requiring human judgment, contexts where AI errors have serious consequences.

## Sources

- Holmes, W., Bialik, M., & Fadel, C. (2019). *Artificial Intelligence in Education*. Center for Curriculum Redesign.
