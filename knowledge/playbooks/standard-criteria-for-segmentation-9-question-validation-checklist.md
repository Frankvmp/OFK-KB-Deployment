---
type: Playbook
title: "Standard Criteria for Segmentation (9-question validation checklist)"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: origin
    resource: "tools/flattened/segmentation-m3-video.txt#01:24:41"
    title: "Transcript source"
  - id: step-1
    resource: "tools/flattened/segmentation-m3-video.txt#01:25:16"
    title: "Transcript source"
  - id: step-3
    resource: "tools/flattened/segmentation-m3-video.txt#01:25:45"
    title: "Transcript source"
  - id: step-5
    resource: "tools/flattened/segmentation-m3-video.txt#01:26:15"
    title: "Transcript source"
  - id: step-7
    resource: "tools/flattened/segmentation-m3-video.txt#01:26:44"
    title: "Transcript source"
  - id: step-9
    resource: "tools/flattened/segmentation-m3-video.txt#01:27:36"
    title: "Transcript source"
tags:
  - diagnosis
  - segmentation
---

# Standard Criteria for Segmentation (9-question validation checklist)

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Run this once a segmentation is fully populated and triangulated, before treating it as final — it's the gate between the diagnosis phase and targeting, and every question must pass before moving on.

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

is the whole market captured in my segmentation? [^step-1]

### 2. One map for the whole market

**Step type:** Constraint check.

Do you have a single segmentation for the whole market? [^step-2]

### 3. Similar within / different without

**Step type:** Constraint check.

are they similar within and different outside to the other segments? [^step-3]

### 4. Mutual exclusivity

**Step type:** Constraint check.

Can each customer only be a member of one segment? [^step-4]

### 5. Plausible population totals

**Step type:** Constraint check.

Do your population numbers tally? [^step-5]

**Invokes:** Triangulation (this playbook's own step 10 in the [Meaningful Actionable Grid](meaningful-actionable-grid-10-stage-segmentation-construction-playbook.md)).

### 6. Uneven value distribution

**Step type:** Constraint check.

do you have uneven distributions? [^step-6]

### 7. Segment dynamics captured

**Step type:** Constraint check.

Have you got segment dynamics in place? [^step-7]

**Invokes:** [Segment Spillover Record](../schemas/segment-spillover-record-segment-a-influences-segment-b.md) (Schema).

### 8. Annual updates without wholesale redesign

**Step type:** Constraint check.

Have you annually updated your numbers?... have you not gone and changed everything and done a completely new segmentation? [^step-8]

### 9. Strategic usefulness ("speaks to you")

**Step type:** Evidence-and-judgement — this is framed as a subjective, experience-based check, not a rule.

when you've finished your segmentation, is it speaking to you? [^step-9]

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

## Citation status

Four of the nine questions (`[^step-2]`, `[^step-4]`, `[^step-6]`, `[^step-8]`) had no matching footnote definitions — only the odd-numbered steps were defined. All nine questions actually appear as consecutive sentences in the same short span (01:25:16-01:27:36); added the four missing definitions pointing at the specific sentence each covers, rather than leaving them undefined.

## Sources

[^origin]: segmentation-m3-video — 01:24:41
[^step-1]: segmentation-m3-video — 01:25:16
[^step-2]: segmentation-m3-video — 01:25:16
[^step-3]: segmentation-m3-video — 01:25:45
[^step-4]: segmentation-m3-video — 01:25:45
[^step-5]: segmentation-m3-video — 01:26:15
[^step-6]: segmentation-m3-video — 01:26:15
[^step-7]: segmentation-m3-video — 01:26:44
[^step-8]: segmentation-m3-video — 01:27:11
[^step-9]: segmentation-m3-video — 01:27:36
