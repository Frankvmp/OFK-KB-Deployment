---
type: Framework
title: "Funnel"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: definition
    resource: "tools/flattened/objectives-m6-video.txt#00:13:01"
    title: "Transcript source — M6"
  - id: design
    resource: "tools/flattened/objectives-m6-video.txt#00:35:26-00:37:22"
    title: "Transcript source — M6"
  - id: conversion
    resource: "tools/flattened/objectives-m6-video.txt#00:42:01"
    title: "Transcript source — M6"
  - id: bridge
    resource: "tools/flattened/objectives-m6-video.txt#00:47:00-00:51:00"
    title: "Transcript source — M6"
  - id: reuse-product
    resource: "tools/flattened/product-m7-video.txt#00:33:05-00:34:05"
    title: "Transcript source — M7"
tags:
  - diagnosis
  - funnel
---

# Funnel

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Reach for this whenever demand needs to be made visible as a sequence — before setting an objective, before diagnosing where a business is losing customers, or before choosing where to focus effort. It's the diagnostic layer between [Diagnosis → Strategy → Tactics](diagnosis-strategy-tactics.md)'s evidence-gathering and a stated objective.

## Purpose

A marketing funnel represents the sequential movement from the total potential
market to the source of recurring revenue. It makes the stages of demand and
conversion visible so they can be measured, compared, budgeted, and converted
into focused objectives. [^definition]

## Invokes

- [Objectives should follow funnel diagnosis](../principles/objectives-should-follow-funnel-diagnosis.md) (Principle) — requires objectives to be chosen from a diagnostic view rather than isolated outcomes.
- [Funnels must fit the market and buying process](../principles/funnels-must-fit-the-market-and-buying-process.md) (Principle) — governs the choice of market-specific stages.
- [The funnel base must match the selected target](../principles/funnel-base-must-match-the-selected-target.md) (Principle) — governs the population used as the 100 percent base.
- [Funnel performance needs conversion and competitive context](../principles/funnel-performance-needs-conversion-and-competitive-context.md) (Principle) — governs interpretation of stage results.
- [Strategy requires choice and sacrifice](../principles/strategy-requires-choice-and-sacrifice.md) (Principle) — governs the final choice of one or two focus stages.
- [Objective targets must balance ambition and realism](../principles/objective-targets-must-balance-ambition-and-realism.md) (Principle) — governs calibration of the selected objective.
- [Objective count is a team-level limit](../principles/objective-count-is-a-team-level-limit.md) (Principle) — constrains the total objective set created from funnel choices.
- [Touchpoints and funnels answer different questions](../principles/touchpoints-and-funnels-answer-different-questions.md) (Principle) — prevents a market-conversion model from being used as an individual experience map.

## Funnel design

There is no universal set of stages. The funnel should be built for the market,
offer, and decision being examined. The first stage is the total target market.
Stages should be tight and hierarchical, with each stage describing a
successive state in the route toward the chosen commercial outcome. [^design]

Possible stage measures include awareness, consideration, preference, and
purchase, but the selected measures must fit the category and objective. A
funnel may also include advocacy or churn where those measures are appropriate.
[^design]

## Operating procedure

1. Define the total target market. [^operating-1]
   **Step type:** Constraint check — the top stage must be the total target market; not a free design choice.
2. Select the sequential stages that represent the category’s route to the
   commercial outcome. [^operating-2]
   **Step type:** Decision (criteria-guided) — stages must be tight and hierarchical.
3. Define one measure for each stage. [^operating-3]
   **Step type:** Decision (criteria-guided) — one metric per stage, chosen to fit the category and objective.
4. Populate the stages with research data. [^operating-4]
   **Step type:** Data-gathering — real quantitative survey data, never invented.
   **Invokes:** [Market Research Method Sequence](../playbooks/market-research-method-sequence-secondary-qualitative-quantitative-mid-stage-focus-groups.md) (Playbook).
5. Calculate stage-to-stage conversion rates. [^conversion]
   **Step type:** Decision (criteria-guided) — a deterministic computation once the funnel is populated; the agent can run this itself.
6. Compare the pattern with competitors or relevant benchmarks. [^operating-6]
   **Step type:** Data-gathering — real competitor data, never invented.
7. Use bridge analysis to identify the most important gap or opportunity. [^bridge]
   **Step type:** Evidence-and-judgement — interpreting why a gap exists, not a lookup.
   **Invokes:** the **Interpret the Populated Funnel to Choose a Focus** embedded Playbook below, which carries this step forward in more granular, per-step-cited detail.
8. Select a focused objective rather than attempting to improve every stage at
   once. [^operating-8]
   **Step type:** Decision (criteria-guided) — choose one or two focus stages, not every stage.

## Interpretation

The funnel is a diagnostic and management view, not a claim that every market
follows the same psychological process. A large drop between stages identifies
where movement is being lost; it does not by itself explain why. Qualitative
research or other diagnosis is needed to understand the barrier.

Funnel data can support dashboards, budgeting, and alignment between sales and
marketing. It can also show competitor differences at particular stages.
[^definition] [^bridge]

## Supporting Principle: funnels are not touchpoint maps

A funnel describes a sequential route through the market for strategic and
objective-setting purposes. Touchpoints describe a person’s ongoing experience
with an organisation and are used to identify experience improvements. The two
views answer different questions and should not be merged. [^reuse-product]

## Supporting Metrics

Stage-to-stage conversion is calculated by comparing the number or proportion
at one stage with the number or proportion at the next stage. The source
material does not specify a single universal formula notation or benchmark.
[^conversion]

## Boundaries and failure modes

- Do not impose a textbook funnel on a category whose buying process differs.
- Do not start with a segment when the design requires the total target market
  as the base.
- Do not treat a stage gap as an explanation of the barrier.
- Do not set an objective for every stage; use the full funnel to select a
  focused “big bet.”
- Do not use a funnel as a substitute for a touchpoint or customer-experience
  map. [^design] [^bridge] [^reuse-product]

## Citation status

Unlike `market-orientation.md` and `research-informs-understanding-not-strategy.md`, this file's "Operating procedure" list was NOT invented — checked against `tools/flattened/objectives-m6-video.txt#00:35:26-00:54:37`, all 8 steps trace to real, sequential content (funnel design guidance, then populate/calculate/compare/bridge/focus). It carried only 2 of 8 footnotes originally; the other 6 have now been added, pointing at the specific span that supports each step. No content was removed.

## Sources

## Embedded Playbooks

### Interpret the Populated Funnel to Choose a Focus

This ordered process is embedded here because it is self-contained within the originating Framework.

**Inputs and preconditions:** Explicit: consumes the populated funnel from 'Build and Populate a Custom Marketing Funnel'.

**Steps:**

1. **Calculate stage-to-stage conversion rates.** we can look at the conversion from step to step. These conversions are super important because the percentages sometimes hide the real potential and challenges. [^interpret-the-populated-funnel-to-choose-a-focus-1]
   **Step type:** Decision (criteria-guided) — a deterministic computation once the funnel is populated.
2. **Add competitor comparison for context.** although we said our 12% awareness was pretty weak, actually, it's much better than the average for our competitors. [^interpret-the-populated-funnel-to-choose-a-focus-2]
   **Step type:** Data-gathering — real competitor data, never invented.
3. **Run bridge analysis on the identified weak stage.** something I call bridge analysis... what is it that the yellow people have in their perceptions, in their attitudes, in their demographics, that makes them different from the red people? [^interpret-the-populated-funnel-to-choose-a-focus-3]
   **Step type:** Evidence-and-judgement — interpreting what distinguishes the two populations, informed by real evidence.
4. **Full-funnel review, then choose one or two focus stages (big-bet).** I'm going to make a choice or a couple of choices based on my full funnel analysis of where I'm going to focus rather than a machine gun. [^interpret-the-populated-funnel-to-choose-a-focus-4]
   **Step type:** Decision (criteria-guided) — select one or two stages rather than every stage.

**Output:** A chosen focus stage, becoming the 'target' field of the Stated Objective Structure (Schema). "it makes most sense to go up to the top of the funnel and go after that brand awareness stage." (00:57:51)

**Boundary:** Do not add steps, thresholds, or prerequisites that the source does not specify.

[^interpret-the-populated-funnel-to-choose-a-focus-1]: ../../transcripts/objectives-m6-video.md#00:42:01
[^interpret-the-populated-funnel-to-choose-a-focus-2]: ../../transcripts/objectives-m6-video.md#00:45:10
[^interpret-the-populated-funnel-to-choose-a-focus-3]: ../../transcripts/objectives-m6-video.md#00:46:43
[^interpret-the-populated-funnel-to-choose-a-focus-4]: ../../transcripts/objectives-m6-video.md#00:54:37
### Write a SMART Objective (DARE walkthrough)

This ordered process is embedded here because it is self-contained within the originating Framework.

**Inputs and preconditions:** Step 3c explicitly reuses this module's own funnel output ('thanks to your funnel').

**Steps:**

1. **Specific.** we need brand awareness. So, we need the specific step in the funnel... we also need to be cognizant of the fact that we have to be specific about the target market. [^write-a-smart-objective-dare-walkthrough-1]
   **Step type:** Constraint check — an objective must name a specific funnel stage and target market to count as SMART.
2. **Measurable.** we need to have... a benchmark. In this case, 70%... the objective level you're going to achieve. In this case, 80%. [^write-a-smart-objective-dare-walkthrough-2]
   **Step type:** Data-gathering — the benchmark must be a real measured value, never invented.
3. **Ambitious/Realistic -- calibrate the target number.** there's a tension between the A and the R in SMART that an experienced manager understands and somehow manages to navigate. [^write-a-smart-objective-dare-walkthrough-3]
   **Step type:** Evidence-and-judgement — this is framed as a judgement call, not a formula.
4. **Time-bound.** we also have to have timing as well. And here it is... by the end of 2016. [^write-a-smart-objective-dare-walkthrough-4]
   **Step type:** Constraint check — an objective without a date is not SMART.

**Output:** A completed SMART objective (e.g. the DARE awareness and consideration objectives). Bounded downstream by 'Optimal number of objectives: a handful per team' (Principle).

**Boundary:** Do not add steps, thresholds, or prerequisites that the source does not specify.

[^write-a-smart-objective-dare-walkthrough-1]: ../../transcripts/objectives-m6-video.md#01:02:14
[^write-a-smart-objective-dare-walkthrough-2]: ../../transcripts/objectives-m6-video.md#01:02:51
[^write-a-smart-objective-dare-walkthrough-3]: ../../transcripts/objectives-m6-video.md#01:03:27
[^write-a-smart-objective-dare-walkthrough-4]: ../../transcripts/objectives-m6-video.md#01:06:50


[^definition]: ../../transcripts/objectives-m6-video.md#00:13:01
[^design]: ../../transcripts/objectives-m6-video.md#00:35:26-00:37:22
[^conversion]: ../../transcripts/objectives-m6-video.md#00:42:01
[^bridge]: ../../transcripts/objectives-m6-video.md#00:47:00-00:51:00
[^reuse-product]: ../../transcripts/product-m7-video.md#00:33:05-00:34:05
[^operating-1]: ../../transcripts/objectives-m6-video.md#00:35:26
[^operating-2]: ../../transcripts/objectives-m6-video.md#00:35:58
[^operating-3]: ../../transcripts/objectives-m6-video.md#00:36:27
[^operating-4]: ../../transcripts/objectives-m6-video.md#00:38:18-00:38:45
[^operating-6]: ../../transcripts/objectives-m6-video.md#00:45:37-00:46:09
[^operating-8]: ../../transcripts/objectives-m6-video.md#00:54:37