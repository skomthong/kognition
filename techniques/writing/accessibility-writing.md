---
title: Accessibility Writing
slug: accessibility-writing
layer: techniques/writing
parent:
children: []
related: [clarity-and-plain-language, wcag, udl, neurodiversity, designing-for-neurodivergent-learners, designing-for-low-literacy, cognitive-load]
tags: [craft-skill, writing, genre, accessibility, alt-text, captions, plain-language, inclusion]
evidence_level: practitioner
created: 2026-04-14
updated: 2026-04-14
status: seed
---

# Accessibility Writing

## Summary

Accessibility writing ensures that written content is usable by people with diverse abilities — including those using screen readers, those with cognitive disabilities, those with low vision, and those with limited literacy. It's a specialized application of [plain language](clarity-and-plain-language.md) and [UDL](../../systems/udl.md) principles to the act of writing.

## Key Skills

### Alt text for images
- Describe the FUNCTION, not the appearance: "Bar chart showing retention rates: spaced practice 85%, massed practice 42%" not "Image of a chart"
- For decorative images, use empty alt text (alt="") so screen readers skip them
- For complex diagrams, provide a text description or data table as an alternative
- Be concise: 1-2 sentences for most images

### Captions and transcripts
- Captions: synchronized text of spoken audio for video/audio content
- Transcripts: full text version of audio/video content (includes speaker identification and relevant non-speech sounds)
- Captions ≠ subtitles — captions include non-speech information ("[doorbell rings]", "[laughing]")
- Auto-generated captions need human review — accuracy matters for learning

### Plain language for accessibility
- Readability level: aim for 8th-grade reading level for general audiences (Flesch-Kincaid)
- Short sentences, common words, active voice
- Define technical terms on first use
- One idea per paragraph
- Consistent terminology — don't alternate between synonyms for the same concept

### Heading structure for screen readers
- Use proper heading hierarchy (H1 → H2 → H3), not just bold text
- Screen reader users navigate by headings — they function as a table of contents
- Headings must be informative (describe content) not decorative ("Section 3")

### Link text
- "Read the full report on spaced practice" not "Click here"
- Screen readers may announce links out of context — the link text must make sense standalone

### Color and contrast
- Never use color alone to convey meaning (red = wrong, green = right) — add text labels or icons
- Minimum contrast ratios: 4.5:1 for normal text, 3:1 for large text (WCAG AA)

## How To Practice

1. Write alt text for 5 images in an existing course. Test by reading only the alt text — does a listener understand what the image communicates?
2. Take a paragraph of instructional text and check its readability score. Rewrite to reduce the score by 2 grade levels.
3. Navigate a learning module using only a keyboard (no mouse). Where does the experience break?

## Sources

- W3C (2023). *Web Content Accessibility Guidelines (WCAG) 2.2*. W3C Recommendation.
- WebAIM. *Alternative Text Guide*. webaim.org/techniques/alttext/.
