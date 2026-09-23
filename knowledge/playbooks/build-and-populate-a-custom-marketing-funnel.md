---
type: Playbook
title: "Build and Populate a Custom Marketing Funnel"
status: draft
tags:
  - diagnosis
  - funnel
---

# Build and Populate a Custom Marketing Funnel

*(New here? See AGENTS.md at this repository's root for how to use it.)*

## When to use this

Reach for this once the total market or target segment is known and a generic imported funnel isn't good enough — building a category-specific funnel is what makes objective-setting meaningful for this business, not a borrowed one.

## Purpose

This playbook defines an ordered process for build and populate a custom marketing funnel. The sequence and decision points are retained from the registered evidence.

## Invokes

- [Funnels must fit the market and buying process](../principles/funnels-must-fit-the-market-and-buying-process.md) (Principle) — governs the design of custom stages.
- [The funnel base must match the selected target](../principles/funnel-base-must-match-the-selected-target.md) (Principle) — governs the initial population and denominator.

## Inputs and preconditions

Step 1 explicitly depends on Module 3 (total potential market already identified).

## Ordered steps

### 1. Identify the total potential market (the funnel's 100% base)

**Step type:** Data-gathering — reuses the real total market already identified in Segmentation, never re-invented.

The first step, then, in the process is what we've already done, way back in Module 3, which is identify the total potential market. This will become your 100%.

**Invokes:** [Segmentation Process](segmentation-process-top-level-5-step-sequence.md) (Playbook, Module 3, explicit cross-module dependency).

**Nested sequence:**

1. **Choose total-market-base over sequential-base convention.** My advice is, build it from the 100 at the top and stay in that place.
   **Step type:** Constraint check — total-market-base is the stated correct convention; sequential-base is flagged as confusing, not a free choice.
2. **Rebase to the target segment if targeting a specific segment.** if you're targeting a specific segment, your objective and therefore your funnel should also be derived from that segment.
   **Step type:** Constraint check — the 100% base must match the actual target (segment vs. whole market), not be assumed.

### 2. Identify the main funnel stages from real customer evidence

**Step type:** Data-gathering — real customer-sourced evidence, never invented; stages should not be copied from a generic template.

*(Adapted for agent execution — states the evidence standard, not a transcript claim.)* The funnel's stages must reflect a real, evidence-grounded understanding of how customers in this category actually move toward the offering — genuine customer-sourced insight into that process, not a stage sequence copied from a generic template or invented from assumption. If no such evidence exists yet for this market, that gap must be stated openly rather than filled with a plausible-sounding set of stages.

**Invokes:** [Market Research Method Sequence](market-research-method-sequence-secondary-qualitative-quantitative-mid-stage-focus-groups.md) (Playbook).

### 3. Populate the funnel via quantitative research

**Step type:** Data-gathering — real, representative measurement data, never invented.

*(Adapted for agent execution — states the evidence standard, not a transcript claim.)* Each stage's percentage must come from a real, sufficiently large and representative measurement of the target population against the funnel stages already identified in step 2 — not an estimate. If that measurement doesn't exist yet, the funnel must show the gap honestly rather than being populated with assumed or invented percentages.

**Invokes:** [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema), Sample Size Calculator Procedure (embedded in [Research informs understanding, not strategy](../frameworks/research-informs-understanding-not-strategy.md#sample-size-calculator-procedure)).

## Output

A fully populated, percentage-filled custom funnel. "12% of them... are aware of [the offering]. 7% then consider..." (00:41:01)

## Explicit consumers

No explicit cross-module consumer is recorded in the register.

## Boundaries and failure modes

No additional boundary is recorded in the source register. Do not add steps, thresholds, or prerequisites that the source does not specify.

- Preserve the registered order, including nested sequences.
- Do not convert this process into a set of interchangeable steps.
- Do not invent missing timing, thresholds, inputs, or outputs.
- Keep real client data outside the knowledge base.

## Referenced by

Other files in this knowledge base that link here -- useful starting points if this file alone doesn't fully answer a question:

- [Funnels must fit the market and buying process](../principles/funnels-must-fit-the-market-and-buying-process.md) (Principle)
- [Objectives should follow funnel diagnosis](../principles/objectives-should-follow-funnel-diagnosis.md) (Principle)
- [The funnel base must match the selected target](../principles/funnel-base-must-match-the-selected-target.md) (Principle)
