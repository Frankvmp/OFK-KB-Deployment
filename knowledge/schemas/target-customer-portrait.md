---
type: Schema
title: "Target Customer Portrait"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: structure
    resource: "tools/flattened/targeting-m4-video.txt#00:58:40-00:59:39"
    title: "Transcript source — M4"
  - id: example
    resource: "tools/flattened/targeting-m4-video.txt#00:56:11-00:58:40"
    title: "Transcript source — M4"
  - id: positioning
    resource: "tools/flattened/positioning-m5-video.txt#01:23:06"
    title: "Transcript source — M5"
  - id: communications
    resource: "tools/flattened/marketing-communications-m9-video.txt#00:08:28"
    title: "Transcript source — M9"
tags:
  - strategy
  - targeting
  - customer-understanding
---

# Target Customer Portrait

## Purpose

This schema turns researched target-segment data into an overall picture of the
customer. It is a categorical template: the content boxes are fixed, while the
values must come from research for the actual target. [^structure]

## Shape

| Content box | Required meaning |
|---|---|
| Who | Identifying characteristics of the target customer. |
| Current category behaviour | What the customer currently does in the category. |
| Drivers and turn-ons | Motivations, benefits, or conditions that encourage action. |
| Barriers and perceptions | Obstacles, concerns, or beliefs that inhibit action. |
| Other | Additional relevant context that does not fit the preceding boxes. |

For B2B, add the buying-committee members, how they decide, how they interact,
and what matters to each member. This is a variant of the same portrait, not a
separate schema. [^b2b-structure]

## Grounded good example

The Global Plus portrait identifies a multinational country division, its global
CMO and head of marketing excellence as decision makers, its current in-house
training, concerns about inconsistent strategy, and budget constraints that may
delay action. [^example]

## Grounded bad or failure example

Do not create an invented, idealised persona. The portrait must be populated
with quantitative and qualitative evidence about the chosen target. [^structure]

## Consumers

Positioning summarises the portrait when constructing the “to” part of a
positioning statement. Communications briefs require clear, data-filled
portraits for the targets being addressed. [^positioning] [^communications]

## Boundaries

- Keep actual client data outside this knowledge-base schema.
- Do not replace evidence with a fictional name, photograph, or personality.
- Do not confuse a portrait with a general description of all customers.

## Citation status

`[^structure]` originally covered both the general categorical-template framing (accurate at 00:58:40-00:59:39) and the B2B buying-committee sentence in Shape, which is a near-verbatim match to a *different* span (00:55:43) — "we'll now break out the different members of the buying committee, how they decide, how they interact, and what's important to them." Split into a separate `[^b2b-structure]` citation pointing at the correct span, rather than widening `[^structure]` to cover both (they're genuinely two separate claims). Everything else in this file checked out.

## Sources

[^structure]: ../../transcripts/targeting-m4-video.md#00:58:40-00:59:39
[^b2b-structure]: ../../transcripts/targeting-m4-video.md#00:55:43
[^example]: ../../transcripts/targeting-m4-video.md#00:56:11-00:58:40
[^positioning]: ../../transcripts/positioning-m5-video.md#01:23:06
[^communications]: ../../transcripts/marketing-communications-m9-video.md#00:08:28
