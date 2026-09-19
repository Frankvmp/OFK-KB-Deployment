---
type: Playbook
title: "Market Research Method Sequence (secondary -> qualitative -> quantitative -> mid-stage focus groups)"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: origin
    resource: "tools/flattened/market-research-m2-video.txt#00:03:03"
    title: "Transcript source"
  - id: step-1
    resource: "tools/flattened/market-research-m2-video.txt#00:05:53"
    title: "Transcript source"
  - id: step-2
    resource: "tools/flattened/market-research-m2-video.txt#00:27:05"
    title: "Transcript source"
  - id: step-3
    resource: "tools/flattened/market-research-m2-video.txt#00:16:38"
    title: "Transcript source"
  - id: step-4
    resource: "tools/flattened/market-research-m2-video.txt#00:33:33"
    title: "Transcript source"
tags:
  - diagnosis
  - research
  - customer-understanding
---

# Market Research Method Sequence (secondary -> qualitative -> quantitative -> mid-stage focus groups)

## When to use this

*(Process framing — not a sourced claim; no footnote.)* This is the Playbook other concepts invoke whenever they need the agent to gather real evidence rather than assert a claim without support — see the `Data-gathering` step type in [CONTEXT.md](../../CONTEXT.md). Run it whenever a diagnosis, a funnel population, or a strategic decision needs grounding in real research and no research has been gathered yet.

## Purpose

This playbook defines an ordered process for market research method sequence (secondary -> qualitative -> quantitative -> mid-stage focus groups). The sequence and decision points are retained from the registered evidence.

## Invokes

- [Customer scope extends beyond the immediate buyer](../principles/customer-scope-extends-beyond-the-immediate-buyer.md) (Principle) — helps define which customer rings the research should cover.
- [Market orientation must precede market research](../principles/market-orientation-must-precede-market-research.md) (Principle) — establishes the orientation required before choosing and using research methods.
- [Research methods are trade-offs, not a ranking](../principles/research-methods-are-trade-offs-not-a-ranking.md) (Principle) — governs method selection by evidential strengths and limitations.
- [Target portraits must come from evidence, not invention](../principles/target-portraits-must-come-from-evidence-not-invention.md) (Principle) — requires the portrait input to be gathered through research rather than fabricated.
- [Triangulate secondary data without assuming it is correct](../principles/triangulate-secondary-data-without-assuming-it-is-correct.md) (Principle) — governs the evaluation of the first-stage secondary evidence.
- [Quantitative extrapolation requires a representative sample](../principles/quantitative-extrapolation-requires-a-representative-sample.md) (Principle) — sets the condition for generalising survey results.
- [Discover options qualitatively before measuring them](../principles/discover-options-qualitatively-before-measuring-them.md) (Principle) — explains why qualitative exploration precedes quantitative measurement.
- [Qualitative depth does not establish population magnitude](../principles/qualitative-depth-does-not-establish-population-magnitude.md) (Principle) — preserves the distinct evidential role of qualitative methods.
- [Understand customers in their real context](../principles/understand-customers-in-their-real-context.md) (Principle) — explains when contextual observation is required.
- [Revealed choices can be more informative than stated explanations](../principles/revealed-choices-can-be-more-informative-than-stated-explanations.md) (Principle) — connects the sequence to choice-based evidence.
- [Research reveals complexity; segmentation organises it](../principles/research-reveals-complexity-segmentation-organises-it.md) (Principle) — explains how the research output becomes the input to segmentation.
- [Discover behavioural groups before using demographics as identifiers](../principles/discover-behavioural-groups-before-using-demographics-as-identifiers.md) (Principle) — governs how questionnaire evidence should be used in behavioural segmentation.
- [Positioning must use customer data, not internal opinion](../principles/positioning-must-use-customer-data-not-internal-opinion.md) (Principle) — requires positioning inputs to come from market evidence.
- [Existing-customer evidence can refine positioning](../principles/existing-customer-evidence-can-refine-positioning.md) (Principle) — supports research with customers who already prefer the offer.
- [The value of creative pre-testing depends on method and context](../principles/the-value-of-creative-pre-testing-depends-on-method-and-context.md) (Principle) — applies method trade-offs to late-stage creative testing.

## Inputs and preconditions

None for step 1 (starting point).

## Ordered steps

### 1. Start with secondary data

**Step type:** Data-gathering — check for pre-existing data before generating anything new; the agent's own knowledge is not a substitute for a real secondary-data search.

This is always where you begin. Before you even start thinking about research design or doing experiments or paying for focus groups, make sure you haven't already got the data because chances are it might already be there. [^step-1]

### 2. Do qualitative exploration before designing the quantitative survey

**Step type:** Data-gathering — real qualitative input, not invented, establishing the option space before anything is measured.

*(Adapted for agent execution — states the evidence standard, not a transcript claim; see Citation status.)* Before anything is measured with precision, the real range of options, language, and behaviour patterns customers actually use in this category must be established from genuine evidence — not assumed or invented — so that later quantitative measurement is checking the right things, not a guessed list. If no such exploration exists yet, that gap must be stated openly before anything is measured on top of it.

**Invokes:** [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema, inferred link — not named explicitly in this sentence).

### 3. Run the quantitative survey (implicit -- not separately narrated as a step transition)

**Step type:** Data-gathering — real, representative measurement, not invented.

*(Adapted for agent execution — states the evidence standard, not a transcript claim; see Citation status.)* The resulting figures must come from a real, sufficiently large and representative measurement of the target population's actual attitudes and behaviour — not an estimate or assumption. If that measurement doesn't exist yet, the gap must be stated plainly rather than filled with an assumed figure.

**Invokes:** [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema); [Sample Size Calculator Procedure](../frameworks/research-informs-understanding-not-strategy.md#sample-size-calculator-procedure) (embedded Playbook).

### 4. Use focus groups again, mid-stage, once tentative strategic decisions exist

**Step type:** Data-gathering — real diagnosis evidence, not invented, checked against tentative strategic decisions already made.

*(Adapted for agent execution — states the evidence standard, not a transcript claim; see Citation status.)* Once tentative decisions exist across target, position, product, message, price, and channel, they must be checked against the real diagnosis research already gathered about the target profile in this sequence — not the agent's own simulation of how they would respond. If that diagnosis evidence doesn't actually cover a specific decision, that gap must be stated honestly rather than assumed to be favourable.

**Invokes:** [Target Customer Portrait](../schemas/target-customer-portrait.md) (Schema) and the later targeting, positioning, product, communications, pricing, and distribution decisions being checked; the register records this as a forward reference.

## Output

Named end-state: 'Research architecture' -- 'how do you pick and blend your methods together' -- but the source material is cut off before this is explained (00:59:04-00:59:31, file's last line).

## Explicit consumers

No explicit cross-module consumer is recorded in the register.

## Boundaries and failure modes

IMPORTANT TENSION, not resolved by the source material: this teaches methods in the order secondary -> survey -> focus groups -> ethnography -> conjoint (stated explicitly at 00:03:03), but separately states the RECOMMENDED EXECUTION order is secondary -> qualitative exploration -> quantitative survey (stated at 00:27:05, illustrated by the Sweet Baby Ray's/Weatherchem focus-group case at 00:28:54). Do not collapse these into one clean sequence; record both.

- Preserve the registered order, including nested sequences.
- Do not convert this process into a set of interchangeable steps.
- Do not invent missing timing, thresholds, inputs, or outputs.
- Keep real client data outside the knowledge base.

## Citation status

**Agent-execution translation (2026-09-19):** steps 2, 3, and 4's instructional text was rewritten per [ADR-0019](../../docs/adr/0019-translate-evidence-standard-not-ritual-or-tool.md) to state the evidence standard each step must satisfy, rather than the human-executed ritual (qualitative interviews, a live-administered survey, mid-stage focus groups) the source describes. The original human-taught wording remains below in `## Sources` for provenance; it is no longer the live instruction for these three steps. Step 1 is untouched — it was already agent-native as written.

## Sources

[^origin]: market-research-m2-video — 00:03:03
[^step-1]: market-research-m2-video — 00:05:53
[^step-2]: market-research-m2-video — 00:27:05
[^step-3]: market-research-m2-video — 00:16:38
[^step-4]: market-research-m2-video — 00:33:33