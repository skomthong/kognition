---
title: Prompt Systems and Orchestration
slug: prompt-systems
layer: systems
parent:
children: []
related: [ai-copilot-systems, ai-in-education, ai-assisted-interaction, conversational-interface-design, scaffolding, structured-thinking]
tags: [systems, AI, prompts, orchestration, structured-interaction, engineering]
evidence_level: practitioner
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Prompt Systems and Orchestration

## Summary

Prompt systems define how humans structure their interactions with AI to get reliable, high-quality outputs. Orchestration is the design of multi-step AI workflows where outputs from one prompt feed into the next. For learning designers, prompt engineering is becoming a core production skill — the quality of the prompt determines the quality of the output.

## Prompt Design Principles

### Structure beats length
A well-structured prompt outperforms a long, vague one:

| Component | Purpose | Example |
|---|---|---|
| **Role** | Set the AI's perspective | "You are an instructional designer specializing in adult workplace learning" |
| **Task** | State what you want | "Write 5 retrieval practice questions" |
| **Context** | Provide relevant background | "for a module on cognitive load theory, aimed at new L&D professionals" |
| **Constraints** | Define boundaries | "Multiple choice, 4 options each, aligned to Bloom's Apply level" |
| **Format** | Specify output structure | "Return as a table with columns: question, correct answer, distractor rationale" |
| **Examples** | Show what good looks like | "Here's an example of the quality I expect: [example]" |

### Orchestration patterns

| Pattern | Structure | Use case |
|---|---|---|
| **Chain** | Output of prompt 1 → input to prompt 2 | Draft → review → refine |
| **Branch** | Same input → multiple prompts → compare outputs | Generate 3 alternative approaches, then evaluate |
| **Iterate** | Output → human feedback → revised prompt → improved output | Progressive refinement with human-in-the-loop |
| **Template** | Standardized prompt with variable slots | Batch generation of similar content (quiz items, feedback) |

## Application to Learning Design

| Task | Prompt approach |
|---|---|
| Generate quiz items from objectives | Template prompt with objective + Bloom level + format constraints |
| Draft scenario branches | Chain: context → character → decision point → consequences |
| Summarize research for lit review | Structured prompt with synthesis requirements + qualification expectations |
| Generate accessibility alt text | Template with image description + purpose + context constraints |
| Create spaced practice schedules | Context + content map + spacing parameters |

## Key Principles

- **Garbage in, garbage out** — vague prompts produce vague outputs. Invest in prompt structure.
- **Iteration is normal** — first outputs rarely meet standards. Build review-revise loops into the workflow.
- **Save and systematize good prompts** — prompt libraries (reusable, tested prompts for common tasks) are organizational assets.
- **Prompts are scaffolds** — a well-designed prompt IS a scaffold for the AI, following the same principles as learner scaffolding: clear goals, constraints, examples, and feedback.
- **Evaluate critically** — never trust AI output without review. Apply the same [critical thinking](../techniques/writing/critical-thinking.md) to AI outputs that you'd apply to any source.

## Sources

- Anthropic (2024). *Prompt Engineering Guide*.
- OpenAI (2023). *Best Practices for Prompt Engineering*.
