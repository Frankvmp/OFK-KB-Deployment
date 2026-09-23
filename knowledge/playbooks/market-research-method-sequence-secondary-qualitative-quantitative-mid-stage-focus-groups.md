---
type: Playbook
title: "Market Research Method Sequence (secondary -> qualitative -> quantitative -> mid-stage focus groups)"
status: stable
tags:
  - diagnosis
  - research
  - customer-understanding
---

# Market Research Method Sequence (secondary -> qualitative -> quantitative -> mid-stage focus groups)

*(New here? See AGENTS.md at this repository's root for how to use it.)*

## When to use this

This is the Playbook other concepts invoke whenever they need the agent to gather real evidence rather than assert a claim without support. Run it whenever a diagnosis, a funnel population, or a strategic decision needs grounding in real research and no research has been gathered yet.

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

This is always where you begin. Before you even start thinking about research design or doing experiments or paying for focus groups, make sure you haven't already got the data because chances are it might already be there.

### 2. Do qualitative exploration before designing the quantitative survey

**Step type:** Data-gathering — real qualitative input, not invented, establishing the option space before anything is measured.

*(Adapted for agent execution — states the evidence standard, not a transcript claim.)* Before anything is measured with precision, the real range of options, language, and behaviour patterns customers actually use in this category must be established from genuine evidence — not assumed or invented — so that later quantitative measurement is checking the right things, not a guessed list. If no such exploration exists yet, that gap must be stated openly before anything is measured on top of it.

**Invokes:** [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema, inferred link — not named explicitly in this sentence).

### 3. Run the quantitative survey (implicit -- not separately narrated as a step transition)

**Step type:** Data-gathering — real, representative measurement, not invented.

*(Adapted for agent execution — states the evidence standard, not a transcript claim.)* The resulting figures must come from a real, sufficiently large and representative measurement of the target population's actual attitudes and behaviour — not an estimate or assumption. If that measurement doesn't exist yet, the gap must be stated plainly rather than filled with an assumed figure.

**Invokes:** [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema); [Sample Size Calculator Procedure](../frameworks/research-informs-understanding-not-strategy.md#sample-size-calculator-procedure) (embedded Playbook).

### 4. Use focus groups again, mid-stage, once tentative strategic decisions exist

**Step type:** Data-gathering — real diagnosis evidence, not invented, checked against tentative strategic decisions already made.

*(Adapted for agent execution — states the evidence standard, not a transcript claim.)* Once tentative decisions exist across target, position, product, message, price, and channel, they must be checked against the real diagnosis research already gathered about the target profile in this sequence — not the agent's own simulation of how they would respond. If that diagnosis evidence doesn't actually cover a specific decision, that gap must be stated honestly rather than assumed to be favourable.

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

## Referenced by

Other files in this knowledge base that link here -- useful starting points if this file alone doesn't fully answer a question:

- [Build and Populate a Custom Marketing Funnel](build-and-populate-a-custom-marketing-funnel.md) (Playbook)
- [Customer scope extends beyond the immediate buyer](../principles/customer-scope-extends-beyond-the-immediate-buyer.md) (Principle)
- [Diagnosis → Strategy → Tactics](../frameworks/diagnosis-strategy-tactics.md) (Framework)
- [Discover behavioural groups before using demographics as identifiers](../principles/discover-behavioural-groups-before-using-demographics-as-identifiers.md) (Principle)
- [Discover options qualitatively before measuring them](../principles/discover-options-qualitatively-before-measuring-them.md) (Principle)
- [Existing-customer evidence can refine positioning](../principles/existing-customer-evidence-can-refine-positioning.md) (Principle)
- [Funnel](../frameworks/funnel.md) (Framework)
- [Line of Sight to the Customer (humility -> vacuum -> recognize barriers -> remove barriers)](line-of-sight-to-the-customer-humility-vacuum-recognize-barriers-remove-barriers.md) (Playbook)
- [Market intelligence must circulate, and response is judgement](../principles/market-intelligence-must-circulate-and-response-is-judgement.md) (Principle)
- [Market orientation](../frameworks/market-orientation.md) (Framework)
- [Market orientation must precede market research](../principles/market-orientation-must-precede-market-research.md) (Principle)
- [Marketers are not the consumer](../principles/marketers-are-not-the-consumer.md) (Principle)
- [Marketing Plan Structure (Diagnosis → Strategy → Tactics assembly)](../schemas/marketing-plan-structure-diagnosis-strategy-tactics-assembly.md) (Schema)
- [Module 4 Targeting Sequence (strategic framing -> philosophy choice -> apply criteria -> build portrait -> ensure clarity)](module-4-targeting-sequence-strategic-framing-philosophy-choice-apply-criteria-build-portrait-ensure-clarity.md) (Playbook)
- [Positioning must use customer data, not internal opinion](../principles/positioning-must-use-customer-data-not-internal-opinion.md) (Principle)
- [Qualitative depth does not establish population magnitude](../principles/qualitative-depth-does-not-establish-population-magnitude.md) (Principle)
- [Research informs understanding, not strategy](../frameworks/research-informs-understanding-not-strategy.md) (Framework)
- [Research methods are trade-offs, not a ranking](../principles/research-methods-are-trade-offs-not-a-ranking.md) (Principle)
- [Research reveals complexity; segmentation organises it](../principles/research-reveals-complexity-segmentation-organises-it.md) (Principle)
- [Revealed choices can be more informative than stated explanations](../principles/revealed-choices-can-be-more-informative-than-stated-explanations.md) (Principle)
- [Target portraits must come from evidence, not invention](../principles/target-portraits-must-come-from-evidence-not-invention.md) (Principle)
- [The value of creative pre-testing depends on method and context](../principles/the-value-of-creative-pre-testing-depends-on-method-and-context.md) (Principle)
- [Three-Section Questionnaire (demographic / attitudinal / behavioural)](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema)
- [Triangulate secondary data without assuming it is correct](../principles/triangulate-secondary-data-without-assuming-it-is-correct.md) (Principle)
- [Understand customers in their real context](../principles/understand-customers-in-their-real-context.md) (Principle)
