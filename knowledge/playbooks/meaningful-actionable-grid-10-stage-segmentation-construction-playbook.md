---
type: Playbook
title: "Meaningful Actionable Grid (10-stage segmentation-construction playbook)"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: origin
    resource: "tools/flattened/segmentation-m3-video.txt#00:49:40"
    title: "Transcript source"
  - id: step-1
    resource: "tools/flattened/segmentation-m3-video.txt#00:50:34"
    title: "Transcript source"
  - id: step-2
    resource: "tools/flattened/segmentation-m3-video.txt#00:52:21"
    title: "Transcript source"
  - id: step-3
    resource: "tools/flattened/segmentation-m3-video.txt#00:54:29"
    title: "Transcript source"
  - id: step-4
    resource: "tools/flattened/segmentation-m3-video.txt#00:56:17"
    title: "Transcript source"
  - id: step-5
    resource: "tools/flattened/segmentation-m3-video.txt#00:56:46"
    title: "Transcript source"
  - id: step-6
    resource: "tools/flattened/segmentation-m3-video.txt#00:57:38"
    title: "Transcript source"
  - id: step-7
    resource: "tools/flattened/segmentation-m3-video.txt#01:02:50"
    title: "Transcript source"
  - id: step-8
    resource: "tools/flattened/segmentation-m3-video.txt#01:07:37"
    title: "Transcript source"
  - id: step-8-1
    resource: "tools/flattened/segmentation-m3-video.txt#01:08:30"
    title: "Transcript source"
  - id: step-8-2
    resource: "tools/flattened/segmentation-m3-video.txt#01:12:02"
    title: "Transcript source"
  - id: step-8-3
    resource: "tools/flattened/segmentation-m3-video.txt#01:13:30"
    title: "Transcript source"
  - id: step-8-4
    resource: "tools/flattened/segmentation-m3-video.txt#01:14:43"
    title: "Transcript source"
  - id: step-9
    resource: "tools/flattened/segmentation-m3-video.txt#01:19:22"
    title: "Transcript source"
  - id: step-10
    resource: "tools/flattened/segmentation-m3-video.txt#01:21:33"
    title: "Transcript source"
  - id: step-10-1
    resource: "tools/flattened/segmentation-m3-video.txt#01:22:01"
    title: "Transcript source"
  - id: step-10-2
    resource: "tools/flattened/segmentation-m3-video.txt#01:22:27"
    title: "Transcript source"
  - id: step-10-3
    resource: "tools/flattened/segmentation-m3-video.txt#01:22:52"
    title: "Transcript source"
  - id: step-10-4
    resource: "tools/flattened/segmentation-m3-video.txt#01:23:45"
    title: "Transcript source"
tags:
  - diagnosis
  - segmentation
---

# Meaningful Actionable Grid (10-stage segmentation-construction playbook)

## When to use this

*(Process framing — not a sourced claim; no footnote.)* This is the concrete method [Segmentation Process](segmentation-process-top-level-5-step-sequence.md) step 3 invokes to actually carve the mass market into segments — reach for it once the mass market is defined and a segmentation method needs to be chosen and executed, not merely named.

## Purpose

This playbook defines an ordered process for meaningful actionable grid (10-stage segmentation-construction playbook). The sequence and decision points are retained from the registered evidence.

## Invokes

- [Segments must be coherent and large enough to serve](../principles/segments-must-be-coherent-and-large-enough-to-serve.md) (Principle) — governs the balance between segment integrity and viable scale.
- [Segment boundaries must preserve meaningful differences](../principles/segment-boundaries-must-preserve-meaningful-differences.md) (Principle) — governs cut-off lines and cell collapse.
- [A segmentation is a map, not the market](../principles/a-segmentation-is-a-map-not-the-market.md) (Principle) — keeps calculated populations and values explicit as approximations.
- [Segment names should carry insight, not priority](../principles/segment-names-should-carry-insight-not-priority.md) (Principle) — governs the final naming step.
- [Record cross-segment influence only when the relationship is specific](../principles/record-cross-segment-influence-only-when-the-relationship-is-specific.md) (Principle) — governs the spillover step.

## Inputs and preconditions

Follows Segmentation Process step 1 (mass market already defined).

## Ordered steps

### 1. Generate variables (shopping list of 10+)

**Step type:** Evidence-and-judgement — the team's own knowledge of what makes customers different, not gathered survey data.

you're trying to come up with a shopping list of at least 10, ideally more than 10 variables, on which you may segment the market later. [^step-1]

### 2. Score meaningfulness (1-10)

**Step type:** Evidence-and-judgement, optionally grounded in real correlation data.

How meaningful are each of those variables in terms of influencing and driving behavior and choice? [^step-2]

**Invokes:** [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema, optional data source for correlation check).

### 3. Score actionability (1-10)

**Step type:** Evidence-and-judgement — how available accessible the data really is.

How actionable are these variables? One means we will never be able to get this data. Ten means I literally already have it on my laptop. [^step-3]

### 4. Multiply meaningful x actionable

**Step type:** Decision (criteria-guided) — a deterministic computation once both scores exist; the agent can run this itself.

We're now going to do multiplication... multiply meaningful by actionable to get a score out of 100. [^step-4]

### 5. Select high-scoring variables

**Step type:** Decision (criteria-guided) — select the higher-scoring variables; how many is left to judgement, not a fixed threshold.

you're looking for those higher scoring variables that suggest both a big impact on behavior, but something we can actually get our hands on. [^step-5]

### 6. Build axes (2x2 or more)

**Step type:** Decision (criteria-guided) — slicing the market using the selected variables.

We're going to build a two by two, which is going to slice and dice the market into its different segments. [^step-6]

**Invokes:** Meaningful cut-off lines (Principle). *(not yet drafted)*

### 7. Collapse cells into a manageable number of segments

**Step type:** Evidence-and-judgement — balancing fewer segments against preserving each segment's integrity.

we're going to do what's called collapsing. [^step-7]

**Invokes:** Over-collapsing warning (Principle). *(not yet drafted)*

### 8. Populate each segment (name / population / value / market share)

**Step type:** Data-gathering — real segment data, never invented.

we have to populate it with the basic information required. [^step-8]

**Invokes:** [Segment Profile](../schemas/segment-profile-name-population-value-market-share.md) (Schema).

**Nested sequence:**

1. **Population.** You start with the population. It's the best place to begin. [^step-8-1]
   **Step type:** Data-gathering.
2. **Value.** we have to work out the next thing, which is value. How much is this segment worth? [^step-8-2]
   **Step type:** Data-gathering.
3. **Market share.** Now we've got to move to market share, the third thing. [^step-8-3]
   **Step type:** Data-gathering.
4. **Name.** Finally, we're going to name each segment. [^step-8-4]
   **Step type:** Evidence-and-judgement — naming is a judgement call, not a lookup.

### 9. Spillover (inter-segment influence)

**Step type:** Evidence-and-judgement — identifying which segments genuinely influence each other, grounded in evidence.

spillover is inter-segment influence. We know all the different segments, but some of them speak to each other. [^step-9]

**Invokes:** [Segment Spillover Record](../schemas/segment-spillover-record-segment-a-influences-segment-b.md) (Schema); Avoid BS spillover (Principle). *(not yet drafted)*

### 10. Triangulate

**Step type:** Constraint check — confirm the model's sums and estimates hold together before treating the segmentation as final.

check your model is correct. There's a couple of approximate ways to use triangulation to check that your sums and your estimations... [^step-10]

**Nested sequence:**

1. **Population-sum check.** if I add up all the different populations in the segment, do they add up to what I think the total mass market is? [^step-10-1]
   **Step type:** Decision (criteria-guided) — a deterministic sum-check.
2. **Value-sum check.** look at the sum of all the segment values and see if that tallies with our overall estimate of what the market value should be. [^step-10-2]
   **Step type:** Decision (criteria-guided) — a deterministic sum-check.
3. **Revenue back-calculation check.** look at the sum of the value of each segment multiplied by our market share. That should be pretty close to what our total revenue is. [^step-10-3]
   **Step type:** Decision (criteria-guided) — a deterministic computation.
4. **Sales-team validation.** Bring in the sales team. Show them the segmentation. Take them through the numbers. [^step-10-4]
   **Step type:** Evidence-and-judgement — real-world human validation, not something the agent can substitute for.

## Output

A validated market map of named segments, each with a completed Segment Profile, plus recorded spillover. "make sure you're generating a map of the market that you can use for the journey ahead" (01:24:41).

## Explicit consumers

- Module 4: Targeting: Explicit reuse recorded in the register.
- Module 6: Marketing Objectives: Explicit reuse recorded in the register.

## Boundaries and failure modes

No additional boundary is recorded in the source register. Do not add steps, thresholds, or prerequisites that the source does not specify.

- Preserve the registered order, including nested sequences.
- Do not convert this process into a set of interchangeable steps.
- Do not invent missing timing, thresholds, inputs, or outputs.
- Keep real client data outside the knowledge base.

## Citation status

Spot-checked steps 1, 2, 4, 5, 6, 7, and 8 against `tools/flattened/segmentation-m3-video.txt#00:50:10-01:07:37` — all resolve accurately, most near-verbatim (step 3 lands \~26 seconds before its exact quote but within the same continuous discussion, not a real span error). Consistent with this register's prior independent spot-verification recorded in project-context.md. Nested steps 8-1..8-4 and 10-1..10-4 not individually re-checked this pass.

## Sources

[^origin]: segmentation-m3-video — 00:49:40
[^step-1]: segmentation-m3-video — 00:50:34
[^step-2]: segmentation-m3-video — 00:52:21
[^step-3]: segmentation-m3-video — 00:54:29
[^step-4]: segmentation-m3-video — 00:56:17
[^step-5]: segmentation-m3-video — 00:56:46
[^step-6]: segmentation-m3-video — 00:57:38
[^step-7]: segmentation-m3-video — 01:02:50
[^step-8]: segmentation-m3-video — 01:07:37
[^step-8-1]: segmentation-m3-video — 01:08:30
[^step-8-2]: segmentation-m3-video — 01:12:02
[^step-8-3]: segmentation-m3-video — 01:13:30
[^step-8-4]: segmentation-m3-video — 01:14:43
[^step-9]: segmentation-m3-video — 01:19:22
[^step-10]: segmentation-m3-video — 01:21:33
[^step-10-1]: segmentation-m3-video — 01:22:01
[^step-10-2]: segmentation-m3-video — 01:22:27
[^step-10-3]: segmentation-m3-video — 01:22:52
[^step-10-4]: segmentation-m3-video — 01:23:45
