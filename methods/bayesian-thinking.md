---
title: Bayesian Thinking
slug: bayesian-thinking
layer: methods
parent:
children: []
related: [uncertainty-and-probabilistic-thinking, causal-inference, evidence-evaluation, critical-thinking, calibration-and-judgment-accuracy, decision-theory]
tags: [methods, decision-making, probability, updating, evidence, reasoning]
evidence_level: mixed
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Bayesian Thinking

## Definition

Bayesian thinking is the practice of updating your beliefs systematically when new evidence arrives — starting with a prior belief (what you thought before), considering new evidence (how likely is this evidence if your belief is true vs false?), and arriving at a posterior belief (what you think now). Named after Bayes' theorem, but the practical skill is conceptual, not mathematical.

## How It Works (Conceptual)

1. **Start with a prior**: what do I currently believe, and how strongly? "I think this program design will improve transfer — maybe 60% confident."
2. **Encounter evidence**: new data arrives. "The pilot showed 40% retention improvement at 90 days."
3. **Evaluate the evidence**: how likely is this result IF my belief is correct? How likely if I'm wrong? "Strong results are more likely if the design works than if it doesn't."
4. **Update**: adjust confidence based on evidence strength. "I'm now 80% confident, but I want to see it replicated."

The key discipline: **your beliefs should change when evidence arrives.** Not all evidence changes them equally — strong, relevant evidence moves you more; weak, tangential evidence moves you less.

## Key Principles

- **All beliefs are provisional** — hold them with appropriate confidence and update when evidence warrants. This is the opposite of "I've already decided."
- **Prior beliefs matter** — what you thought before the evidence affects what you think after. A single positive study shouldn't flip you from 10% to 90% confidence.
- **Evidence quality matters** — a well-designed RCT moves your beliefs more than an anecdote. Not all evidence is equal. See [Evidence Evaluation](../strategy/evidence-evaluation.md).
- **Seek disconfirming evidence** — confirmation bias makes us seek evidence that supports our beliefs. Bayesian thinking requires actively asking: "What would change my mind?"
- **Calibration is Bayesian** — [Calibration and Judgment Accuracy](../principles/calibration-and-judgment-accuracy.md) is essentially asking: are my posterior beliefs well-calibrated to the evidence I've seen?

## Application to Learning Design

| Situation | Bayesian approach |
|---|---|
| **New research finding** | How much should this change my design practice? Depends on: quality of evidence, relevance to my context, consistency with other evidence |
| **Pilot results** | Promising but small sample. Update moderately, don't overclaim. Plan a larger test. |
| **Stakeholder claims** | "Our people learn best through videos." What's the prior evidence? What would change this belief? |
| **AI recommendation** | AI suggests a design change. How much to trust depends on: AI track record, relevance of training data, ability to verify |

## Common Anti-Bayesian Errors

- **Anchoring to first evidence**: over-weighting the first thing you learned
- **Ignoring base rates**: being swayed by a vivid case while ignoring population statistics
- **Binary thinking**: "it works" or "it doesn't" instead of "how confident am I, and what would change that?"
- **Updating asymmetrically**: updating strongly on confirming evidence, weakly on disconfirming evidence

## Sources

- McGrayne, S. B. (2011). *The Theory That Would Not Die: How Bayes' Rule Cracked the Enigma Code*. Yale University Press.
- Tetlock, P. E., & Gardner, D. (2015). *Superforecasting: The Art and Science of Prediction*. Crown.
