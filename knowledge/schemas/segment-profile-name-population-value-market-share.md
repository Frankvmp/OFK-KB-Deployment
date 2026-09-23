---
type: Schema
title: "Segment Profile (name / population / value / market share)"
status: draft
tags:
  - diagnosis
  - segmentation
  - customer-understanding
---

# Segment Profile (name / population / value / market share)

*(New here? See AGENTS.md at this repository's root for how to use it.)*

## When to use this

Reach for this whenever a segment produced by the [Meaningful Actionable Grid](../playbooks/meaningful-actionable-grid-10-stage-segmentation-construction-playbook.md) needs to be recorded as a discrete, comparable record — or when a downstream step (targeting, funnel population, objective-setting) needs a segment's real name, size, value, or share.

## Purpose

This schema defines the complete record for a market segment. It is a fixed-
field structure with exactly four fields: name, population, value, and market
share.

## Shape

| Field | Required meaning |
|---|---|
| Name | A memorable name based on behaviour or insight, not a targeting priority or abstract theme. |
| Population | The number of accounts or customers in the segment. |
| Value | The segment’s total expected category spending, not spending with the firm. |
| Market share | The firm’s expected share of that segment’s value with no new activity. |

The four fields are invariant. The values are specific to the market being
analysed.

## Grounded good example

“Big testers” has a population of 60, potential annual value of £7 million,
and a current share of 3%.

## Grounded bad or failure example

NOT FOUND as a complete bad record in the source material. Do not add fields
such as priority, demographics, or a portrait to this segment record merely
because they may be useful elsewhere.

## Consumers

The segment population can become the total-market base for a later funnel.
This is an explicit cross-module use.

## Boundaries

- Value means total category value, not current firm revenue.
- Market share is the expected no-new-activity share, not the target share
  after a campaign.
- The schema describes the market map; targeting decisions are made separately.

## Referenced by

Other files in this knowledge base that link here -- useful starting points if this file alone doesn't fully answer a question:

- [Marketing Plan Structure (Diagnosis → Strategy → Tactics assembly)](marketing-plan-structure-diagnosis-strategy-tactics-assembly.md) (Schema)
- [Meaningful Actionable Grid (10-stage segmentation-construction playbook)](../playbooks/meaningful-actionable-grid-10-stage-segmentation-construction-playbook.md) (Playbook)
- [Segmentation Process (top-level 5-step sequence)](../playbooks/segmentation-process-top-level-5-step-sequence.md) (Playbook)
