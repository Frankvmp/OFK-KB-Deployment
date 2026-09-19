---
type: Schema
title: "Segment Profile (name / population / value / market share)"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: fields
    resource: "tools/flattened/segmentation-m3-video.txt#01:08:04"
    title: "Transcript source — M3"
  - id: example
    resource: "tools/flattened/segmentation-m3-video.txt#01:16:29"
    title: "Transcript source — M3"
  - id: consumer
    resource: "tools/flattened/objectives-m6-video.txt#00:38:18"
    title: "Transcript source — M6"
tags:
  - diagnosis
  - segmentation
  - customer-understanding
---

# Segment Profile (name / population / value / market share)

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Reach for this whenever a segment produced by the [Meaningful Actionable Grid](../playbooks/meaningful-actionable-grid-10-stage-segmentation-construction-playbook.md) needs to be recorded as a discrete, comparable record — or when a downstream step (targeting, funnel population, objective-setting) needs a segment's real name, size, value, or share.

## Purpose

This schema defines the complete record for a market segment. It is a fixed-
field structure with exactly four fields: name, population, value, and market
share. [^fields]

## Shape

| Field | Required meaning |
|---|---|
| Name | A memorable name based on behaviour or insight, not a targeting priority or abstract theme. |
| Population | The number of accounts or customers in the segment. |
| Value | The segment’s total expected category spending, not spending with the firm. |
| Market share | The firm’s expected share of that segment’s value with no new activity. |

The four fields are invariant. The values are specific to the market being
analysed. [^fields]

## Grounded good example

“Big testers” has a population of 60, potential annual value of £7 million,
and a current share of 3%. [^example]

## Grounded bad or failure example

NOT FOUND as a complete bad record in the source material. Do not add fields
such as priority, demographics, or a portrait to this segment record merely
because they may be useful elsewhere.

## Consumers

The segment population can become the total-market base for a later funnel.
This is an explicit cross-module use. [^consumer]

## Boundaries

- Value means total category value, not current firm revenue.
- Market share is the expected no-new-activity share, not the target share
  after a campaign.
- The schema describes the market map; targeting decisions are made separately.

## Sources

[^fields]: segmentation-m3-video — 01:08:04
[^example]: segmentation-m3-video — 01:16:29
[^consumer]: objectives-m6-video — 00:38:18
