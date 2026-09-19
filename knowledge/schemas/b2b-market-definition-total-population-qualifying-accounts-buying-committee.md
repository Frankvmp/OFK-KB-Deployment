---
type: Schema
title: "B2B Market Definition (total population → qualifying accounts → buying committee)"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: structure
    resource: "tools/flattened/segmentation-m3-video.txt#00:27:38"
    title: "Transcript source — M3"
  - id: example
    resource: "tools/flattened/segmentation-m3-video.txt#00:26:22"
    title: "Transcript source — M3"
  - id: consumer
    resource: "tools/flattened/targeting-m4-video.txt#00:55:22-00:55:43"
    title: "Transcript source — M4"
tags:
  - cross-cutting
  - market-orientation
---

# B2B Market Definition (total population → qualifying accounts → buying committee)

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Reach for this whenever the market being segmented or targeted is B2B — it's the variant of mass-market definition that adds the qualifying-account filter and buying-committee breakdown a B2C market doesn't need.

## Purpose

This schema separates the B2B market into two levels: identify qualifying
accounts from the total population of companies, then identify the decision-
making unit within each qualifying account. [^structure]

## Shape

1. **Total company population:** all companies or institutions in the relevant
   market.
2. **Qualifying-account filter:** the criteria that identify which accounts are
   large, advanced, relevant, or otherwise capable of needing the offer.
3. **Buying committee:** the decision-making unit within each qualifying
   account.

The filter criteria and committee membership are categorical-template values.
They must come from the specific market and offer. The buying committee is
described later through the account portrait, not added to the segmentation map
itself. [^structure] [^consumer]

## Grounded good example

Hospitals are the total population in the example. There are 1,148 UK hospitals,
but only some are large or advanced enough to need a CAT scanner; the example
uses 25% with one and assumes 50% could potentially benefit. [^example]

## Grounded bad or failure example

NOT FOUND as a named bad example. A common structural error to avoid is putting
individual decision makers into the account-level segmentation map instead of
breaking out the buying committee in the portrait. [^consumer]

## Consumers

Target Customer Portrait uses the qualifying account as its base and then
describes the committee members, their interactions, and what matters to them.
[^consumer]

## Boundaries

- Keep segmentation at the firm or account level.
- Do not assume every company in the total population is in the market.
- Do not prescribe demographic or firmographic filters without business-
  specific evidence.

## Sources

[^structure]: segmentation-m3-video — 00:27:38
[^example]: segmentation-m3-video — 00:26:22
[^consumer]: targeting-m4-video — 00:55:22-00:55:43
