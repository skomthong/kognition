---
title: SCORM
slug: scorm
layer: systems
parent:
children: []
related: [xapi, lti, lms]
tags: [interoperability, standards, packaging, tracking]
evidence_level: practitioner
created: 2026-04-13
updated: 2026-04-13
status: seed
---

# SCORM

## Definition

SCORM (Sharable Content Object Reference Model) is an ADL-backed specification for packaging and runtime expectations for LMS-delivered content. It defines how content is packaged (zip with manifest), how it communicates with the LMS (API calls), and what data is tracked (completion, score, time).

## When To Use It

- Use SCORM when content is LMS-centric: self-contained modules delivered and tracked within a single LMS
- Use SCORM when the tracking requirement is basic: completion, pass/fail, score, time spent
- Widely supported — nearly every LMS accepts SCORM packages

## Limitations

- LMS-centric: cannot track experiences outside the LMS (mobile apps, job performance, simulations in other systems)
- Limited data model: completion and score, not rich activity statements
- For cross-system tracking or richer activity data, use [xAPI](xapi.md)

## Sources

- ADL (Advanced Distributed Learning). *SCORM 2004 4th Edition*. Technical specification.
