---
type: Schema
title: "Conjoint Choice Structure (options / alternatives / attributes)"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: structure
    resource: "tools/flattened/market-research-m2-video.txt#00:50:46"
    title: "Transcript source — M2"
  - id: example
    resource: "tools/flattened/market-research-m2-video.txt#00:50:46-00:51:24"
    title: "Transcript source — M2"
  - id: consumer
    resource: "tools/flattened/pricing-m8-video.txt#00:38:40"
    title: "Transcript source — M8"
tags:
  - diagnosis
  - research
  - pricing
---

# Conjoint Choice Structure (options / alternatives / attributes)

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Reach for this when structuring a choice task inside the [Conjoint Analysis Procedure](../playbooks/conjoint-analysis-procedure.md) — it's the shape each trade-off presented to a consumer must take.

## Purpose

This schema defines the structure of a conjoint choice task. Each task presents
options, compares alternatives, and varies attributes so that choices reveal
trade-offs. [^structure]

## Shape

1. **Options:** the specific configurations presented for selection.
2. **Alternatives:** the competing configurations available in the same task.
3. **Attributes:** the dimensions that compose and vary across the options,
   such as brand, size, memory, or price.

The three elements are fixed. The attribute values and number of alternatives
vary according to the research question. [^structure]

## Grounded good example

A choice task may present a 5-inch Samsung handset with 250 GB of memory for
$1,200 alongside Sony and LG alternatives. The brands, handset size, memory,
and price are attributes; each handset configuration is an option.
[^example]

## Grounded bad or failure example

NOT FOUND as a complete bad choice task. Do not use attributes that are not
meaningfully divisible or that cannot represent the trade-offs under study.

## Consumers

Including price allows conjoint analysis to estimate the value of different
attributes in combination, supporting pricing decisions. [^consumer]

## Boundaries

- Do not confuse an attribute with an option or alternative.
- Do not choose an attribute set that cannot represent the decision.
- Do not assume the example’s brands, sizes, memory, or price apply to another
  category.
- Do not infer a price recommendation without analysing the resulting choices.

## Sources

[^structure]: market-research-m2-video — 00:50:46
[^example]: market-research-m2-video — 00:50:46-00:51:24
[^consumer]: pricing-m8-video — 00:38:40
