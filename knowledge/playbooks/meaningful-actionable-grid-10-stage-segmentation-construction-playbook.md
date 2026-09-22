---
type: Playbook
title: "Meaningful Actionable Grid (10-stage segmentation-construction playbook)"
status: draft
tags:
  - diagnosis
  - segmentation
---

# Meaningful Actionable Grid (10-stage segmentation-construction playbook)

## When to use this

This is the concrete method [Segmentation Process](segmentation-process-top-level-5-step-sequence.md) step 3 invokes to actually carve the mass market into segments — reach for it once the mass market is defined and a segmentation method needs to be chosen and executed, not merely named.

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

you're trying to come up with a shopping list of at least 10, ideally more than 10 variables, on which you may segment the market later.

### 2. Score meaningfulness (1-10)

**Step type:** Evidence-and-judgement, optionally grounded in real correlation data.

How meaningful are each of those variables in terms of influencing and driving behavior and choice?

**Invokes:** [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema, optional data source for correlation check).

### 3. Score actionability (1-10)

**Step type:** Evidence-and-judgement — how available accessible the data really is.

How actionable are these variables? One means we will never be able to get this data. Ten means I literally already have it on my laptop.

### 4. Multiply meaningful x actionable

**Step type:** Decision (criteria-guided) — a deterministic computation once both scores exist; the agent can run this itself.

We're now going to do multiplication... multiply meaningful by actionable to get a score out of 100.

### 5. Select high-scoring variables

**Step type:** Decision (criteria-guided) — select the higher-scoring variables; how many is left to judgement, not a fixed threshold.

you're looking for those higher scoring variables that suggest both a big impact on behavior, but something we can actually get our hands on.

### 6. Build axes (2x2 or more)

**Step type:** Decision (criteria-guided) — slicing the market using the selected variables.

We're going to build a two by two, which is going to slice and dice the market into its different segments.

**Invokes:** Meaningful cut-off lines (Principle). *(not yet drafted)*

### 7. Collapse cells into a manageable number of segments

**Step type:** Evidence-and-judgement — balancing fewer segments against preserving each segment's integrity.

we're going to do what's called collapsing.

**Invokes:** Over-collapsing warning (Principle). *(not yet drafted)*

### 8. Populate each segment (name / population / value / market share)

**Step type:** Data-gathering — real segment data, never invented.

we have to populate it with the basic information required.

**Invokes:** [Segment Profile](../schemas/segment-profile-name-population-value-market-share.md) (Schema).

**Nested sequence:**

1. **Population.** You start with the population. It's the best place to begin.
   **Step type:** Data-gathering.
2. **Value.** we have to work out the next thing, which is value. How much is this segment worth?
   **Step type:** Data-gathering.
3. **Market share.** Now we've got to move to market share, the third thing.
   **Step type:** Data-gathering.
4. **Name.** Finally, we're going to name each segment.
   **Step type:** Evidence-and-judgement — naming is a judgement call, not a lookup.

### 9. Spillover (inter-segment influence)

**Step type:** Evidence-and-judgement — identifying which segments genuinely influence each other, grounded in evidence.

spillover is inter-segment influence. We know all the different segments, but some of them speak to each other.

**Invokes:** [Segment Spillover Record](../schemas/segment-spillover-record-segment-a-influences-segment-b.md) (Schema); Avoid BS spillover (Principle). *(not yet drafted)*

### 10. Triangulate

**Step type:** Constraint check — confirm the model's sums and estimates hold together before treating the segmentation as final.

check your model is correct. There's a couple of approximate ways to use triangulation to check that your sums and your estimations...

**Nested sequence:**

1. **Population-sum check.** if I add up all the different populations in the segment, do they add up to what I think the total mass market is?
   **Step type:** Decision (criteria-guided) — a deterministic sum-check.
2. **Value-sum check.** look at the sum of all the segment values and see if that tallies with our overall estimate of what the market value should be.
   **Step type:** Decision (criteria-guided) — a deterministic sum-check.
3. **Revenue back-calculation check.** look at the sum of the value of each segment multiplied by our market share. That should be pretty close to what our total revenue is.
   **Step type:** Decision (criteria-guided) — a deterministic computation.
4. **Sales-team validation.** Bring in the sales team. Show them the segmentation. Take them through the numbers.
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

## Referenced by

Other files in this knowledge base that link here -- useful starting points if this file alone doesn't fully answer a question:

- [A segmentation is a map, not the market](../principles/a-segmentation-is-a-map-not-the-market.md) (Principle)
- [Record cross-segment influence only when the relationship is specific](../principles/record-cross-segment-influence-only-when-the-relationship-is-specific.md) (Principle)
- [Segment Profile (name / population / value / market share)](../schemas/segment-profile-name-population-value-market-share.md) (Schema)
- [Segment Spillover Record (segment A influences segment B)](../schemas/segment-spillover-record-segment-a-influences-segment-b.md) (Schema)
- [Segment boundaries must preserve meaningful differences](../principles/segment-boundaries-must-preserve-meaningful-differences.md) (Principle)
- [Segment names should carry insight, not priority](../principles/segment-names-should-carry-insight-not-priority.md) (Principle)
- [Segmentation Process (top-level 5-step sequence)](segmentation-process-top-level-5-step-sequence.md) (Playbook)
- [Segments must be coherent and large enough to serve](../principles/segments-must-be-coherent-and-large-enough-to-serve.md) (Principle)
- [Standard Criteria for Segmentation (9-question validation checklist)](standard-criteria-for-segmentation-9-question-validation-checklist.md) (Playbook)
