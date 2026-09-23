---
type: Schema
title: "Segment Spillover Record (segment A influences segment B)"
status: draft
tags:
  - diagnosis
  - segmentation
  - customer-understanding
---

# Segment Spillover Record (segment A influences segment B)

*(New here? See AGENTS.md at this repository's root for how to use it.)*

## When to use this

Reach for this during [Meaningful Actionable Grid](../playbooks/meaningful-actionable-grid-10-stage-segmentation-construction-playbook.md) step 9, or when a targeting decision needs to weigh a segment's influence on other segments — never assert a spillover relationship without a real, specific rationale.

## Purpose

This schema records an influence relationship between two market segments. It
extends a segmentation map when one segment affects another segment’s behaviour
or decisions.

## Shape

| Field | Required meaning |
|---|---|
| Source segment | Segment A, the segment exerting influence. |
| Target segment | Segment B, the segment being influenced. |
| Direction or nature | The stated positive or negative influence. |
| Evidence basis | The specific rationale for claiming the relationship. |

The segment identities and evidence are client-specific. The structure is fixed,
but the relationship must not be invented.

## Grounded good example

The source describes experienced marketing professionals moving between large
companies and contacting the service in their new organisations. It also
describes large outsourcers influencing companies where they have worked to
consider the service. These are examples of a stated influence path between
segments.

## Grounded bad or failure example

An unsupported claim that segment A influences segment B is the stated failure
mode. A relationship needs a specific, credible rationale; a vague belief that
segments “talk to each other” is insufficient.

## Consumers

Targeting may select a smaller segment when its influence on larger segments is
substantial. Spillover informs that targeting choice; it does not replace the
targeting decision.

## Boundaries

- Record direction: A influences B, not merely that A and B are related.
- State the evidence basis for the link.
- Do not treat the link as statistically proven when the source only supports
  an anecdotal rationale.

## Referenced by

Other files in this knowledge base that link here -- useful starting points if this file alone doesn't fully answer a question:

- [Meaningful Actionable Grid (10-stage segmentation-construction playbook)](../playbooks/meaningful-actionable-grid-10-stage-segmentation-construction-playbook.md) (Playbook)
- [Segmentation Process (top-level 5-step sequence)](../playbooks/segmentation-process-top-level-5-step-sequence.md) (Playbook)
- [Standard Criteria for Segmentation (9-question validation checklist)](../playbooks/standard-criteria-for-segmentation-9-question-validation-checklist.md) (Playbook)
