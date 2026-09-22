---
type: Playbook
title: "Three-Section Questionnaire Build Order (demographic -> attitudinal -> behavioural)"
status: draft
tags:
  - diagnosis
  - research
  - customer-understanding
---

# Three-Section Questionnaire Build Order (demographic -> attitudinal -> behavioural)

## When to use this

Reach for this when designing the online quantitative survey referenced across the Market Research Method Sequence — it's the standard three-part shape that survey should take, not a one-off design decision per project.

## Purpose

This playbook defines an ordered process for three-section questionnaire build order (demographic -> attitudinal -> behavioural). The sequence and decision points are retained from the registered evidence.

## Invokes

- [Quantitative extrapolation requires a representative sample](../principles/quantitative-extrapolation-requires-a-representative-sample.md) (Principle) — governs whether questionnaire results can support market-wide claims.
- [Discover options qualitatively before measuring them](../principles/discover-options-qualitatively-before-measuring-them.md) (Principle) — requires the questionnaire's closed options to be grounded before measurement.

## Inputs and preconditions

None stated.

## Ordered steps

### 1. Demographic section

**Step type:** Constraint check — demographic is the required first section; not a free ordering choice.

The first section of the questionnaire is all about demographics... income through to location through to the general questions of age and gender.

**Invokes:** [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema).

### 2. Attitudinal section

**Step type:** Constraint check — attitudinal is the required second section.

Next up, we get to attitudinal questions... measured... with what's called Likert scale data.

**Invokes:** Likert scale (Metric). *(not yet drafted)*

### 3. Behavioural section

**Step type:** Constraint check — behavioural is the required third section.

The final type of data we want to measure in our questionnaire are behavioural questions... related to specific activity in the category.

## Output

Produces the Three-Section Questionnaire schema (schema-register.json); '30 or 35 questions... slicing and dicing that data... a remarkable array of insights.'

## Explicit consumers

- Module 6: Marketing Objectives: Explicit reuse recorded in the register.
- Module 7: Product Strategy: Explicit reuse recorded in the register.

## Boundaries and failure modes

No additional boundary is recorded in the source register. Do not add steps, thresholds, or prerequisites that the source does not specify.

- Preserve the registered order, including nested sequences.
- Do not convert this process into a set of interchangeable steps.
- Do not invent missing timing, thresholds, inputs, or outputs.
- Keep real client data outside the knowledge base.

## Referenced by

Other files in this knowledge base that link here -- useful starting points if this file alone doesn't fully answer a question:

- [Quantitative extrapolation requires a representative sample](../principles/quantitative-extrapolation-requires-a-representative-sample.md) (Principle)
- [Three-Section Questionnaire (demographic / attitudinal / behavioural)](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema)
