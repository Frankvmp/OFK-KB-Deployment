---
type: Schema
title: "Segment Spillover Record (segment A influences segment B)"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: structure
    resource: "tools/flattened/segmentation-m3-video.txt#01:19:22-01:20:39"
    title: "Transcript source — M3"
  - id: example
    resource: "tools/flattened/segmentation-m3-video.txt#01:20:39-01:21:33"
    title: "Transcript source — M3"
  - id: consumer
    resource: "tools/flattened/targeting-m4-video.txt#00:38:34"
    title: "Transcript source — M4"
tags:
  - diagnosis
  - segmentation
  - customer-understanding
---

# Segment Spillover Record (segment A influences segment B)

## When to use this

*(Process framing — not a transcript claim; no footnote.)* Reach for this during [Meaningful Actionable Grid](../playbooks/meaningful-actionable-grid-10-stage-segmentation-construction-playbook.md) step 9, or when a targeting decision needs to weigh a segment's influence on other segments — never assert a spillover relationship without a real, specific rationale.

## Purpose

This schema records an influence relationship between two market segments. It
extends a segmentation map when one segment affects another segment’s behaviour
or decisions. [^structure]

## Shape

| Field | Required meaning |
|---|---|
| Source segment | Segment A, the segment exerting influence. |
| Target segment | Segment B, the segment being influenced. |
| Direction or nature | The stated positive or negative influence. |
| Evidence basis | The specific rationale for claiming the relationship. |

The segment identities and evidence are client-specific. The structure is fixed,
but the relationship must not be invented. [^structure]

## Grounded good example

The source describes experienced marketing professionals moving between large
companies and contacting the service in their new organisations. It also
describes large outsourcers influencing companies where they have worked to
consider the service. These are examples of a stated influence path between
segments. [^example]

## Grounded bad or failure example

An unsupported claim that segment A influences segment B is the stated failure
mode. A relationship needs a specific, credible rationale; a vague belief that
segments “talk to each other” is insufficient. [^structure]

## Consumers

Targeting may select a smaller segment when its influence on larger segments is
substantial. Spillover informs that targeting choice; it does not replace the
targeting decision. [^consumer]

## Boundaries

- Record direction: A influences B, not merely that A and B are related.
- State the evidence basis for the link.
- Do not treat the link as statistically proven when the source only supports
  an anecdotal rationale.

## Sources

[^structure]: ../../transcripts/segmentation-m3-video.md#01:19:22-01:20:39
[^example]: ../../transcripts/segmentation-m3-video.md#01:20:39-01:21:33
[^consumer]: ../../transcripts/targeting-m4-video.md#00:38:34
