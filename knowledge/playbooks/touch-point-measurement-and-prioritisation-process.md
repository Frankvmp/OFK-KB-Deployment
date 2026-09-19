---
type: Playbook
title: "Touch-Point Measurement and Prioritisation Process"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: origin
    resource: "tools/flattened/product-m7-video.txt#00:38:52"
    title: "Transcript source"
  - id: step-2
    resource: "tools/flattened/product-m7-video.txt#00:39:29"
    title: "Transcript source"
  - id: step-4
    resource: "tools/flattened/product-m7-video.txt#00:40:02"
    title: "Transcript source"
  - id: step-5
    resource: "tools/flattened/product-m7-video.txt#00:40:32"
    title: "Transcript source"
  - id: step-6
    resource: "tools/flattened/product-m7-video.txt#00:41:57"
    title: "Transcript source"
  - id: step-7
    resource: "tools/flattened/product-m7-video.txt#00:42:29"
    title: "Transcript source"
  - id: step-7-1
    resource: "tools/flattened/product-m7-video.txt#00:44:10"
    title: "Transcript source"
tags:
  - diagnosis
  - touchpoints
  - research
---

# Touch-Point Measurement and Prioritisation Process

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Reach for this whenever touchpoints need to be measured rather than assumed — identifying the weakest one to fix, and checking that positioning is actually being expressed consistently across all of them.

## Purpose

This playbook defines an ordered process for touch-point measurement and prioritisation process. The sequence and decision points are retained from the registered evidence.

## Invokes

- [Existing products should be continuously improved](../principles/existing-products-should-be-continuously-improved.md) (Principle) — frames measured touchpoints as inputs to ongoing product work.
- [Touchpoint priorities must be measured, not assumed](../principles/touchpoint-priorities-must-be-measured-not-assumed.md) (Principle) — governs the evidence and remeasurement requirements.

## Inputs and preconditions

Explicit: 'It's crucial that we don't just conjure up touch points, that we actually measure them from a market oriented point of view.' (00:38:52)

## Ordered steps

### 1. Add touch-point questions to the existing Module 2 questionnaire

**Step type:** Constraint check — use the existing questionnaire; do not create a separate touchpoint survey.

make sure some of that overall questionnaire you're designing back in module two includes a few touch point questions. [^origin]

**Invokes:** [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema, Module 2, explicit cross-module dependency).

### 2. Ask for up to 10 open-ended brand experiences

**Step type:** Data-gathering — real customer-described experiences, never invented.

*(Adapted for agent execution — states the evidence standard, not a transcript claim; see Citation status.)* The touchpoint list must be built from real, customer-described accounts of specific interactions with the brand — up to around ten distinct experiences, genuinely reported, not the agent's own assumption of what a typical touchpoint would be. If no such accounts exist yet, that gap must be stated honestly rather than filled with an invented list.

### 3. Rate each experience 1-10

**Step type:** Data-gathering — real customer ratings, never invented.

*(Adapted for agent execution — states the evidence standard, not a transcript claim; see Citation status.)* Each described experience must carry a real rating reflecting how it actually made that customer feel — genuine customer response, not an assumed or estimated score. Where no such rating exists yet for a given experience, that gap must be stated honestly rather than filled with a guessed number.

### 4. Code into common categories

**Step type:** Evidence-and-judgement — grouping open-text responses into categories is a judgement call, not a lookup.

you can code them into the commonly occurring similar experiences... coalesced into seven or eight major touch points. [^step-4]

### 5. Compute average, standard deviation, and frequency

**Step type:** Decision (criteria-guided) — a deterministic computation once experiences are rated and coded; the agent can run this itself.

you can average the rating... a standard deviation to check how much variance is there... how common these touch points are. [^step-5]

**Invokes:** Touch-Point Measurement Structure (Schema). *(not yet drafted)*

### 6. Job 1: fix the weakest sub-average touch point

**Step type:** Decision (criteria-guided) — focus on the sub-average touchpoint(s), not every touchpoint at once.

there's one obvious place I would focus my attention right now... Right now, the sign-up is our weakest link. [^step-6]

### 7. Job 2: embed positioning into every touch point

**Step type:** Constraint check — positioning must be expressed consistently across every touchpoint, not just the weakest one.

there's a second, more specific, more brand-centric, more positioning-linked challenge... injecting our positioning into all of the touch points. [^step-7]

**Invokes:** [Positioning and brand codes](../frameworks/positioning-and-brand-codes.md) (Framework).

**Nested sequence:**

1. **Worked examples.** course content language, Q&A format, exam redesign, Michael O'Leary/Ryanair as a living touch point. [^step-7-1]
   **Step type:** Evidence-and-judgement.

### 8. Re-measure to verify improvement

**Step type:** Data-gathering — real re-measured ratings, never assumed to have improved.

*(Adapted for agent execution — states the evidence standard, not a transcript claim; see Citation status.)* After the fix is made, the same touchpoint must be re-assessed using real, current customer response to confirm whether it actually improved — never assumed to have improved simply because the fix was implemented. If no re-measurement exists yet, that gap must be stated honestly rather than the improvement being asserted.

## Output

Identification and remediation of the single weakest touchpoint, verified by re-running the same measurement; plus positioning consistently embedded across all touchpoints.

## Explicit consumers

No explicit cross-module consumer is recorded in the register.

## Boundaries and failure modes

No additional boundary is recorded in the source register. Do not add steps, thresholds, or prerequisites that the source does not specify.

- Preserve the registered order, including nested sequences.
- Do not convert this process into a set of interchangeable steps.
- Do not invent missing timing, thresholds, inputs, or outputs.
- Keep real client data outside the knowledge base.

## Citation status

Three body footnotes (`[^step-1]`, `[^step-3]`, `[^step-8]`) had no matching definitions. Checked against `tools/flattened/product-m7-video.txt#00:38:52-00:44:10`: step 1's content is part of the same sentence as `[^origin]` (00:38:52); step 3's content is part of the same sentence as step 2 (00:39:29); step 8's content is part of the same passage as step 7 (00:42:29). Fixed by pointing each body marker at the correct existing definition rather than adding duplicate ones. Everything else checked out.

**Agent-execution translation (2026-09-19):** steps 2, 3, and 8's instructional text was rewritten per ADR-0019 to state the evidence standard each step must satisfy, rather than the human-executed ritual (asking a consumer directly, live rating collection) the source describes. The original human-taught wording remains below in `## Sources` for provenance; it is no longer the live instruction for these three steps.

## Sources

[^origin]: product-m7-video — 00:38:52
[^step-2]: product-m7-video — 00:39:29
[^step-4]: product-m7-video — 00:40:02
[^step-5]: product-m7-video — 00:40:32
[^step-6]: product-m7-video — 00:41:57
[^step-7]: product-m7-video — 00:42:29
[^step-7-1]: product-m7-video — 00:44:10
