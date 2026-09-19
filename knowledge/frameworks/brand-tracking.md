---
type: Framework
title: "Brand tracking"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: mortn-context
    resource: "tools/flattened/market-orientation-m1-video.txt#00:45:57"
    title: "Transcript source — M1"
  - id: tracksuit-context
    resource: "tools/flattened/objectives-m6-video.txt#01:05:53"
    title: "Transcript source — M6"
  - id: objective-context
    resource: "tools/flattened/objectives-m6-video.txt#01:02:14-01:02:51"
    title: "Transcript source — M6"
  - id: long-short-measurement
    resource: "tools/flattened/marketing-communications-m9-video.txt#00:26:23"
    title: "Transcript source — M9"
  - id: mcdonalds-long-brand-building
    resource: "tools/flattened/marketing-communications-m9-video.txt#00:29:44-00:31:51"
    title: "Transcript source — M9"
  - id: campaign-versus-company
    resource: "tools/flattened/marketing-communications-m9-video.txt#01:26:02-01:28:14"
    title: "Transcript source — M9"
  - id: brand-lift-context
    resource: "tools/flattened/marketing-communications-m9-video.txt#01:28:14-01:29:45"
    title: "Transcript source — M9"
tags:
  - diagnosis
  - brand
  - research
---

# Brand tracking

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Reach for this whenever a communications investment needs to be evaluated — first to check whether it's long-term brand-building (use this) or short-term activation (use return-on-investment measures instead), then to actually run the measurement.

## Purpose

Brand tracking measures whether long-term brand-building activity is changing
the intended brand outcomes. The measures identified here are awareness,
consideration, and brand perceptions. [^long-short-measurement]

It is an evaluation framework. It does not select the target market, define the
brand position, set the communications budget, or choose the activity.

## Definition

Brand tracking is the primary measurement approach for long-term brand
building. Short-term activation is measured differently: spend is compared
with resulting uplift using return-on-investment measures. [^long-short-measurement]

The distinction follows the intended effect. Long-term activity builds memory
structures, awareness, and perceptions that influence future demand. Short-term
activity is intended to produce a more immediate response. [^mcdonalds-long-brand-building]

## Invokes

- [Long-term brand building and short-term activation require different measures](../principles/long-term-brand-building-and-short-term-activation-require-different-measures.md) (Principle) — governs when brand tracking is the appropriate measure.
- [Effective campaign platforms should be renewed, not routinely replaced](../principles/effective-campaign-platforms-should-be-renewed-not-routinely-replaced.md) (Principle) — uses tracking evidence to test continuing effectiveness rather than assume wearout.
- [Communications should be measured at campaign level and used to improve](../principles/communications-should-be-measured-at-campaign-level-and-used-to-improve.md) (Principle) — makes campaign outcomes and learning the measurement purpose.

## Measurement model

The model has five elements:

1. **Activity:** the brand-building investment being evaluated.
2. **Target market:** the people for whom the brand outcome is being assessed.
3. **Brand outcome:** awareness, consideration, or a specified brand
   perception.
4. **Benchmark:** the current value of the selected outcome.
5. **Goal and period:** the intended value and the date by which it should be
   reached.

The benchmark and goal should belong to a stated objective with a named target
market and delivery period. The objective structure identifies the target
market, current benchmark, goal, and delivery date as the relevant decision
context. [^objective-context]

The source material does not specify one mandatory questionnaire, sampling
plan, tracking cadence, or calculation formula. Those details remain design
choices until the available research and business context specify them.

## Operating procedure

### 1. Identify the intended effect

**Step type:** Decision (criteria-guided) — long-term vs. short-term intent determines which measurement approach applies.

Record what the activity is intended to change. Use brand tracking when the
intended effect is long-term movement in awareness, consideration, or brand
perception. Use return-on-investment measures when the intended effect is
short-term activation and immediate uplift. [^long-short-measurement]

### 2. Define the measurement frame

**Step type:** Data-gathering — reuses the real target market, benchmark, goal, and period from the stated objective, never invented.

Specify the target market, selected brand outcome, current benchmark, desired
goal, and delivery period. These fields prevent a result from being interpreted
without knowing which people, measure, starting point, target, and time period
it represents. [^objective-context]

**Invokes:** [Stated Objective Structure](../schemas/stated-objective-structure.md) (Schema).

### 3. Select the brand measures

**Step type:** Constraint check — must be awareness, consideration, or brand perception; not sales or profit.

Choose measures that correspond to the intended outcome. Awareness,
consideration, and brand perceptions are explicitly named measures. Do not
replace them with sales or profit merely because those figures are easier to
obtain. [^long-short-measurement]

### 4. Measure the later result

**Step type:** Data-gathering — real re-measured outcomes, never invented.

Re-measure the selected outcomes after the activity has had time to operate.
The long-term example describes campaigns running for weeks or months; no
universal timing rule is specified. [^mcdonalds-long-brand-building]

### 5. Compare with the benchmark

**Step type:** Decision (criteria-guided) — a deterministic comparison once benchmark and later measure both exist.

Compare the later measure with the starting benchmark and assess whether the
intended brand outcome changed during the delivery period. Interpret the result
against the stated goal, not against an unspecified general standard.

### 6. Set realistic expectations

**Step type:** Evidence-and-judgement — contextual benchmarks inform, but don't mechanically determine, what counts as a good result.

Use relevant category and objective benchmarks as guardrails when they are
available. In the TrackSuit example, a 1% awareness increase is described as
good and a 4% increase as outstanding for the specific example. These figures
are contextual benchmarks, not universal targets. [^tracksuit-context]

The same source notes that large increases become harder further down the
funnel: double-digit annual increases are presented as possible for awareness,
rare for consideration, and generally single-digit for preference and
purchase. This informs expectation-setting; it does not replace a
business-specific benchmark. [^tracksuit-context]

## Interpreting performance

Communication should be assessed against its own performance and stated
objectives, not solely against overall company sales or profit. Product or
pricing problems can reduce company performance independently of communication
quality. [^campaign-versus-company]

A movement in a tracked measure should not automatically be treated as proof
that one advertisement caused the movement. First-touch and last-touch
attribution can understate the contribution of the wider channel mix.
[^brand-lift-context]

## Related measurement methods

### Brand-lift study

A brand-lift study compares an audience exposed to an advertisement with a
control audience that was not shown it. After a short period, the groups can be
compared on ad recall, brand awareness, consideration, and purchase intent.
This method is useful for evaluating a single channel, but it does not measure
the combined effect of a multiple-channel media mix. [^brand-lift-context]

### Media mix modelling

Media mix modelling is used when the question concerns the combined effect of
multiple channels. It is a separate measurement method and is not required for
every brand-tracking application. [^brand-lift-context]

## Worked example

The McDonald’s long-term brand-building example describes a broad campaign
aimed at building future demand by refreshing memory structures, increasing
awareness, and changing perceptions of the brand. It is not presented as an
immediate product-sales activation. The appropriate primary evaluation is
whether the brand measures changed, using brand tracking rather than relying on
short-term return on investment. [^mcdonalds-long-brand-building]

## Boundaries and failure modes

- Do not use short-term return on investment as the sole measure of long-term
  brand-building. [^long-short-measurement]
- Do not use overall company sales or profit as a clean proxy for communication
  performance. [^campaign-versus-company]
- Do not turn an example benchmark into a universal target. [^tracksuit-context]
- Do not claim that a before-and-after movement proves that one advertisement
  caused the change. [^brand-lift-context]
- Do not use the MORTN scale as a consumer brand-tracking questionnaire. Its
  cited purpose is to diagnose, benchmark, and track an organisation’s market
  orientation using a ten-item, five-point instrument. [^mortn-context]
- Do not add a mandatory questionnaire, sample design, cadence, or formula that
  is not specified by the source material.

## Supporting concepts

### Principle: Long versus short measurement

Long-term brand-building investment is assessed with brand tracking. Short-term
activation investment is assessed with return-on-investment measures.
[^long-short-measurement]

### Principle: Campaign metrics versus company results

Campaign performance should be assessed against the campaign’s own performance
or stated objectives. Overall company results are not a clean communication
measure when product or pricing problems may also affect them.
[^campaign-versus-company]

### Case Study: McDonald’s long-term brand-building example

A broad, top-of-funnel campaign is used to illustrate long-term brand building:
it changes memory structures and brand perceptions, builds future demand, and is
assessed through brand tracking. [^mcdonalds-long-brand-building]

### Metrics

No direct supporting Metric is established in the current registers. MORTN is
excluded because it measures organisational market orientation. TrackSuit is
retained as contextual benchmarking evidence rather than treated as a Metric
belonging to this Framework. [^mortn-context] [^tracksuit-context]

## Sources

[^mortn-context]: market-orientation-m1-video — 00:45:57
[^tracksuit-context]: objectives-m6-video — 01:05:53
[^objective-context]: objectives-m6-video — 01:02:14-01:02:51
[^long-short-measurement]: marketing-communications-m9-video — 00:26:23
[^mcdonalds-long-brand-building]: marketing-communications-m9-video — 00:29:44-00:31:51
[^campaign-versus-company]: marketing-communications-m9-video — 01:26:02-01:28:14
[^brand-lift-context]: marketing-communications-m9-video — 01:28:14-01:29:45

