---
type: Playbook
title: "Build and Populate a Custom Marketing Funnel"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: origin
    resource: tools/flattened/objectives-m6-video.txt#00:24:33-00:24:49
    title: Transcript source
  - id: step-1-1
    resource: tools/flattened/objectives-m6-video.txt#00:26:55
    title: Transcript source
  - id: step-2
    resource: tools/flattened/objectives-m6-video.txt#00:30:43
    title: Transcript source
  - id: step-3
    resource: tools/flattened/objectives-m6-video.txt#00:38:45
    title: Transcript source
tags:
  - diagnosis
  - funnel
---

# Build and Populate a Custom Marketing Funnel

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Reach for this once the total market or target segment is known and a generic imported funnel isn't good enough — building a category-specific funnel is what makes objective-setting meaningful for this business, not a borrowed one.

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

The first step, then, in the process is what we've already done, way back in Module 3, which is identify the total potential market. This will become your 100%. [^origin]

**Invokes:** [Segmentation Process](segmentation-process-top-level-5-step-sequence.md) (Playbook, Module 3, explicit cross-module dependency).

**Nested sequence:**

1. **Choose total-market-base over sequential-base convention.** My advice is, build it from the 100 at the top and stay in that place. [^step-1-1]
   **Step type:** Constraint check — total-market-base is the stated correct convention; sequential-base is flagged as confusing, not a free choice.
2. **Rebase to the target segment if targeting a specific segment.** if you're targeting a specific segment, your objective and therefore your funnel should also be derived from that segment. [^step-1-2]
   **Step type:** Constraint check — the 100% base must match the actual target (segment vs. whole market), not be assumed.

### 2. Identify the main funnel stages from real customer evidence

**Step type:** Data-gathering — real customer-sourced evidence, never invented; stages should not be copied from a generic template.

*(Adapted for agent execution — states the evidence standard, not a transcript claim; see Citation status.)* The funnel's stages must reflect a real, evidence-grounded understanding of how customers in this category actually move toward the offering — genuine customer-sourced insight into that process, not a stage sequence copied from a generic template or invented from assumption. If no such evidence exists yet for this market, that gap must be stated openly rather than filled with a plausible-sounding set of stages.

**Invokes:** [Market Research Method Sequence](market-research-method-sequence-secondary-qualitative-quantitative-mid-stage-focus-groups.md) (Playbook).

### 3. Populate the funnel via quantitative research

**Step type:** Data-gathering — real, representative measurement data, never invented.

*(Adapted for agent execution — states the evidence standard, not a transcript claim; see Citation status.)* Each stage's percentage must come from a real, sufficiently large and representative measurement of the target population against the funnel stages already identified in step 2 — not an estimate. If that measurement doesn't exist yet, the funnel must show the gap honestly rather than being populated with assumed or invented percentages.

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

## Citation status

`[^step-1-2]` had no matching definition. Checked against `tools/flattened/objectives-m6-video.txt`, the near-verbatim source sentence is at 00:27:22; added it as a real definition. A mechanical audit pass (`tools/audit_harness.py`) later found step 1's own body marker was written as `[^step-1]`, with no matching definition — the covering citation existed under the unused id `[^origin]`. Fixed by pointing the body marker at `[^origin]` and widening its span from a single timestamp (00:24:25) to 00:24:33-00:24:49, which is where the actual sentence runs. Everything else checked out.

**Agent-execution translation (2026-09-19):** steps 2 and 3's instructional text was rewritten per [ADR-0019](../../docs/adr/0019-translate-evidence-standard-not-ritual-or-tool.md) to state the evidence standard each step must satisfy, rather than the human-executed ritual (qualitative interviews, an online quantitative survey) the source describes. The original human-taught wording remains below in `## Sources` for provenance; it is no longer the live instruction for these two steps.

## Sources

[^origin]: objectives-m6-video — 00:24:33-00:24:49
[^step-1-1]: objectives-m6-video — 00:26:55
[^step-1-2]: objectives-m6-video — 00:27:22
[^step-2]: objectives-m6-video — 00:30:43
[^step-3]: objectives-m6-video — 00:38:45
