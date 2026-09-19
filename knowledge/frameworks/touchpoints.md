---
type: Framework
title: "Touchpoints"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: origin
    resource: "tools/flattened/market-orientation-m1-video.txt#00:38:38"
    title: "Transcript source — M1"
  - id: definition
    resource: "tools/flattened/product-m7-video.txt#00:33:05-00:35:34"
    title: "Transcript source — M7"
  - id: measurement
    resource: "tools/flattened/product-m7-video.txt#00:35:34-00:40:32"
    title: "Transcript source — M7"
  - id: prioritisation
    resource: "tools/flattened/product-m7-video.txt#00:41:02-00:42:29"
    title: "Transcript source — M7"
  - id: positioning
    resource: "tools/flattened/product-m7-video.txt#00:42:29-00:46:17"
    title: "Transcript source — M7"
  - id: nps
    resource: "tools/flattened/product-m7-video.txt#00:47:52-00:54:59"
    title: "Transcript source — M7"
tags:
  - tactics
  - touchpoints
---

# Touchpoints

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Reach for this whenever the question is about the ongoing experience a person has with a brand — not the sequential path to purchase (that's the [Funnel](funnel.md)) — and especially when deciding where limited improvement effort should go.

## Purpose

Touchpoints are the places and interactions through which a person experiences
an organisation or brand. The framework identifies which experiences need to be
understood, measured, improved, and aligned with the intended position.
[^definition]

Advertising is one touchpoint among many and is not necessarily the most
important one. [^origin]

## Invokes

- [Positioning is internal strategy expressed through touchpoints](../principles/positioning-is-internal-strategy-expressed-through-touchpoints.md) (Principle) — governs how the intended position should appear across the customer experience.
- [Existing products should be continuously improved](../principles/existing-products-should-be-continuously-improved.md) (Principle) — frames customer experience as evidence for ongoing product improvement.
- [Touchpoints and funnels answer different questions](../principles/touchpoints-and-funnels-answer-different-questions.md) (Principle) — preserves the distinction between individual experience and market conversion.
- [Touchpoint priorities must be measured, not assumed](../principles/touchpoint-priorities-must-be-measured-not-assumed.md) (Principle) — governs evidence-based prioritisation.
- [NPS is a contextual learning measure, not a growth predictor](../principles/nps-is-a-contextual-learning-measure-not-a-growth-predictor.md) (Principle) — governs interpretation of the embedded NPS measure.

## Touchpoints and funnels

A funnel describes a sequential route through the market toward purchase. A
touchpoint map describes the person’s ongoing experience with the organisation.
The funnel supports strategy and objective-setting; touchpoints support
experience improvement. [^definition]

## Operating procedure

1. List the significant interactions in the customer experience. [^definition]
   **Step type:** Evidence-and-judgement — support here is softer than the other steps below; this is framed as the general discipline of not underestimating the journey's width, not a discrete first sub-step of the measurement procedure (see Citation status).
2. Ask customers to identify and describe the experiences they have had. *(Adapted for agent execution — states the evidence standard, not a transcript claim; see Citation status.)* The touchpoint list must be built from real, customer-described accounts of specific experiences with the organisation — not the team's assumptions about what those experiences are like. Where no such account exists for a given interaction, that gap must be stated plainly rather than filled with an assumed description.
   **Step type:** Data-gathering — real customer-described experiences, never invented.
3. Rate each experience. *(Adapted for agent execution — states the evidence standard, not a transcript claim; see Citation status.)* Each described experience must be checked against a real, customer-given rating — not an inferred or assumed score. Where no real rating exists for an experience, that gap must be stated plainly rather than filled with an estimated value.
   **Step type:** Data-gathering — real customer ratings, never invented.
4. Code similar experiences into recurring touchpoint categories. [^operating-4]
   **Step type:** Evidence-and-judgement — grouping open-text responses into categories is a judgement call, not a lookup.
5. Calculate the average rating and the variation in ratings. [^operating-4]
   **Step type:** Decision (criteria-guided) — a deterministic computation once ratings are gathered; the agent can run this itself.
6. Assess how common each touchpoint is. [^operating-6]
   **Step type:** Decision (criteria-guided) — a deterministic count once experiences are coded.
7. Prioritise a weak or important touchpoint for qualitative investigation and
   improvement. [^measurement] [^prioritisation]
   **Step type:** Decision (criteria-guided) — focus on the sub-average touchpoint(s), not every touchpoint at once.

The source does not specify a universal number of touchpoints, rating scale, or
prioritisation threshold.

## Positioning alignment

Touchpoint improvement has two requirements: make the interaction work better
and ensure that it expresses the intended positioning. A touchpoint that is
efficient but inconsistent with the position remains a brand problem.
[^positioning]

## Supporting Case Studies

### Signup touchpoint

The signup experience is selected for qualitative investigation because it is
the lowest-rated touchpoint in the example. The case illustrates prioritising an
experience for improvement rather than attempting to redesign every touchpoint
simultaneously. [^prioritisation]

### Apple stores

Apple stores illustrate a system of touchpoints in which layout, product use,
and staff presence express simplicity, creativity, and humanity consistently.
[^positioning]

## Supporting Metric: Net Promoter Score

The cited NPS method classifies scores of 0–6 as detractors, 7–8 as passives,
and 9–10 as promoters. NPS is calculated as the percentage of promoters minus
the percentage of detractors. [^nps]

Interpret NPS against category and country response norms, historical results,
and competitor scores rather than as an absolute universal score. [^nps]

## Boundaries and failure modes

- Do not use a funnel as a substitute for a touchpoint map.
- Do not measure only advertising when other important interactions exist.
- Do not prioritise only by average rating; consider frequency and variation.
- Do not treat NPS as self-explanatory without contextual benchmarks.
- Do not improve touchpoints without checking whether they deliver the intended
  positioning.
- Do not invent a universal rating scale, cadence, or priority threshold.

## Citation status

Unlike `market-orientation.md` and `research-informs-understanding-not-strategy.md`, this file's "Operating procedure" list was NOT invented — checked against `tools/flattened/product-m7-video.txt#00:36:36-00:42:29`, 6 of 7 steps trace to real, sequential content (ask for experiences → rate → code → average/variance → frequency → prioritise), now individually cited. Step 1 ("list the significant interactions") has softer support: the transcript frames the underlying point (companies underestimate the journey's width) as general discipline, not a discrete first sub-step of the measurement procedure — flagged in the step's own note rather than silently cited as if it were as strong as the rest.

**Agent-execution translation (2026-09-19):** Operating procedure steps 2 and 3 were rewritten per [ADR-0019](../../docs/adr/0019-translate-evidence-standard-not-ritual-or-tool.md) to state the evidence standard each step must satisfy, rather than the human-executed ritual (asking customers directly, live rating collection) the source describes. The original human-taught wording remains below in `## Sources` for provenance; it is no longer the live instruction for these two steps.

## Sources

[^origin]: market-orientation-m1-video — 00:38:38
[^definition]: product-m7-video — 00:33:05-00:35:34
[^measurement]: product-m7-video — 00:35:34-00:40:32
[^prioritisation]: product-m7-video — 00:41:02-00:42:29
[^positioning]: product-m7-video — 00:42:29-00:46:17
[^nps]: product-m7-video — 00:47:52-00:54:59
[^operating-2]: product-m7-video — 00:39:29-00:40:02
[^operating-4]: product-m7-video — 00:40:02-00:40:32
[^operating-6]: product-m7-video — 00:40:32

