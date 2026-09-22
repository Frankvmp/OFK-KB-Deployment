---
type: Playbook
title: "Standard Criteria for Segmentation (9-question validation checklist)"
status: draft
tags:
  - diagnosis
  - segmentation
---

# Standard Criteria for Segmentation (9-question validation checklist)

## When to use this

Run this once a segmentation is fully populated and triangulated, before treating it as final — it's the gate between the diagnosis phase and targeting, and every question must pass before moving on.

## Purpose

This playbook defines an ordered process for standard criteria for segmentation (9-question validation checklist). The sequence and decision points are retained from the registered evidence.

## Invokes

- [Segments must be coherent and large enough to serve](../principles/segments-must-be-coherent-and-large-enough-to-serve.md) (Principle) — supplies the core similarity, difference, and scale test.
- [Map the whole market before choosing targets](../principles/map-the-whole-market-before-choosing-targets.md) (Principle) — requires complete market coverage before targeting.
- [Do not combine markets when aggregation erases differences](../principles/do-not-combine-markets-when-aggregation-erases-differences.md) (Principle) — governs whether a single map remains valid.
- [Segment boundaries must preserve meaningful differences](../principles/segment-boundaries-must-preserve-meaningful-differences.md) (Principle) — explains the integrity test for final groups.
- [A segmentation is a map, not the market](../principles/a-segmentation-is-a-map-not-the-market.md) (Principle) — governs directional accuracy and annual updates.

## Inputs and preconditions

Explicit: applied to a segmentation that is already fully populated and triangulated -- 'when you've finished your segmentation... you finish the populations and you finish the numbers.'

## Ordered steps

### 1. Whole-market capture

**Step type:** Constraint check.

is the whole market captured in my segmentation?

### 2. One map for the whole market

**Step type:** Constraint check.

Do you have a single segmentation for the whole market?

### 3. Similar within / different without

**Step type:** Constraint check.

are they similar within and different outside to the other segments?

### 4. Mutual exclusivity

**Step type:** Constraint check.

Can each customer only be a member of one segment?

### 5. Plausible population totals

**Step type:** Constraint check.

Do your population numbers tally?

**Invokes:** Triangulation (this playbook's own step 10 in the [Meaningful Actionable Grid](meaningful-actionable-grid-10-stage-segmentation-construction-playbook.md)).

### 6. Uneven value distribution

**Step type:** Constraint check.

do you have uneven distributions?

### 7. Segment dynamics captured

**Step type:** Constraint check.

Have you got segment dynamics in place?

**Invokes:** [Segment Spillover Record](../schemas/segment-spillover-record-segment-a-influences-segment-b.md) (Schema).

### 8. Annual updates without wholesale redesign

**Step type:** Constraint check.

Have you annually updated your numbers?... have you not gone and changed everything and done a completely new segmentation?

### 9. Strategic usefulness ("speaks to you")

**Step type:** Evidence-and-judgement — this is framed as a subjective, experience-based check, not a rule.

when you've finished your segmentation, is it speaking to you?

## Output

Confirmation the map is fit for purpose, gating entry into Module 4. "it's time to end diagnosis and move into the start of strategy, which is targeting" (01:28:43).

## Explicit consumers

- Module 4: Targeting: pass/fail result gates entry into targeting, stated explicitly at 01:28:43

## Boundaries and failure modes

No additional boundary is recorded in the source register. Do not add steps, thresholds, or prerequisites that the source does not specify.

- Preserve the registered order, including nested sequences.
- Do not convert this process into a set of interchangeable steps.
- Do not invent missing timing, thresholds, inputs, or outputs.
- Keep real client data outside the knowledge base.

## Referenced by

Other files in this knowledge base that link here -- useful starting points if this file alone doesn't fully answer a question:

- [A segmentation is a map, not the market](../principles/a-segmentation-is-a-map-not-the-market.md) (Principle)
- [Do not combine markets when aggregation erases differences](../principles/do-not-combine-markets-when-aggregation-erases-differences.md) (Principle)
- [Segment boundaries must preserve meaningful differences](../principles/segment-boundaries-must-preserve-meaningful-differences.md) (Principle)
- [Segmentation is an option, not a default](../principles/segmentation-is-an-option-not-a-default.md) (Principle)
- [Segments must be coherent and large enough to serve](../principles/segments-must-be-coherent-and-large-enough-to-serve.md) (Principle)
