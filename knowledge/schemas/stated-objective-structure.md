---
type: Schema
title: "Stated Objective Structure"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: structure
    resource: "tools/flattened/objectives-m6-video.txt#00:58:17-00:58:48"
    title: "Transcript source — M6"
  - id: example
    resource: "tools/flattened/objectives-m6-video.txt#00:58:48"
    title: "Transcript source — M6"
  - id: consumer
    resource: "tools/flattened/marketing-communications-m9-video.txt#00:08:58"
    title: "Transcript source — M9"
tags:
  - strategy
  - objectives
---

# Stated Objective Structure

## When to use this

*(Process framing — not a transcript claim; no footnote.)* Reach for this once a funnel stage or measure has been chosen as the focus — whenever a marketing objective needs to be recorded as something checkable, not a vague aspiration or a revenue number.

## Purpose

This schema defines a marketing objective as a stated focus made explicit. It
has four fixed fields: target market, benchmark, goal, and delivery period.
[^structure]

## Shape

| Field | Required meaning |
|---|---|
| Target market | The segment or market to which the objective applies. |
| Benchmark | The current value of the selected measure. |
| Goal | The intended future value of the selected measure. |
| Delivery period | The date or period by which the goal should be achieved. |

The measure itself must be clear, such as a named funnel stage. The four fields
describe the objective’s structure; the values are business-specific.
[^structure]

## Grounded good example

“Increase the proportion of UK marketers who are aware of the Mini MBA in
Marketing as a development option from 12% to 25% by the end of the year.”
This supplies the target market, benchmark, goal, and delivery period.
[^example]

## Grounded bad or failure example

An objective expressed only as “increase awareness” is incomplete because it
does not state the target market, benchmark, goal, or delivery period.
[^structure]

## Consumers

Communications briefs require specific, hard objectives rather than vague goals
or revenue numbers that do not identify the intended marketing outcome.
[^consumer]

## Boundaries

- Do not omit the benchmark or replace it with an aspiration.
- Do not state a goal without a delivery period.
- Do not use company revenue as a substitute for the marketing outcome.
- Do not add client values to this schema file.

## Sources

[^structure]: ../../transcripts/objectives-m6-video.md#00:58:17-00:58:48
[^example]: ../../transcripts/objectives-m6-video.md#00:58:48
[^consumer]: ../../transcripts/marketing-communications-m9-video.md#00:08:58
