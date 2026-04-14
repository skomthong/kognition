---
title: Animation and Motion
slug: animation-and-motion
layer: techniques/interaction
parent:
children: []
related: [attention, cognitive-load, multimedia-learning, video-design, gestalt-in-design, wcag]
tags: [craft-skill, interaction-design, motion, animation, accessibility, pacing]
evidence_level: mixed
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Animation and Motion

## Summary

Animation and motion in learning materials can guide attention, reveal process, show change over time, and create engagement — or they can distract, overload, and exclude. The distinction is whether the motion serves a learning function or is decorative.

## When Motion Supports Learning

| Function | Example | Why it works |
|---|---|---|
| **Revealing process** | Animated flowchart building step by step | Shows sequence and causation; segmenting principle |
| **Guiding attention** | Highlight moving to the next element | Signaling principle — directs focus |
| **Showing change** | Before/after morphing, data changing over time | Makes temporal patterns visible |
| **Demonstrating procedure** | Screen recording of software steps | Shows exactly what to do |
| **Building complexity** | Diagram elements appearing progressively | Manages load by controlling information flow |

## When Motion Harms Learning

| Problem | Example | Why it fails |
|---|---|---|
| **Decorative animation** | Spinning logos, bouncing icons, slide transitions | Extraneous load — attracts attention to nothing |
| **Continuous motion** | Background video, animated backgrounds | Splits attention between content and motion |
| **Auto-advancing** | Slides or content that advance without learner control | Removes learner pacing — overloads fast or bores slow |
| **Competing animations** | Multiple elements moving simultaneously | Divided attention — which one should I watch? |

## Key Principles

- **Learner-controlled > auto-play** — let the learner control pacing (play, pause, replay)
- **One motion at a time** — single focal animation, not competing movements
- **Meaningful, not decorative** — if removing the animation doesn't lose information, remove it
- **Accessible** — provide alternatives for motion-sensitive users (vestibular disorders). Respect `prefers-reduced-motion` in web design. WCAG requires pause/stop/hide controls for anything that auto-plays.

## Sources

- Mayer, R. E. (2009). *Multimedia Learning* (2nd ed.). Cambridge University Press.
- W3C (2023). *WCAG 2.2*. Success Criterion 2.3.1 (Three Flashes), 2.2.2 (Pause, Stop, Hide).
