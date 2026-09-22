---
type: Schema
title: "B2B Market Definition (total population → qualifying accounts → buying committee)"
status: draft
tags:
  - cross-cutting
  - market-orientation
---

# B2B Market Definition (total population → qualifying accounts → buying committee)

## When to use this

Reach for this whenever the market being segmented or targeted is B2B — it's the variant of mass-market definition that adds the qualifying-account filter and buying-committee breakdown a B2C market doesn't need.

## Purpose

This schema separates the B2B market into two levels: identify qualifying
accounts from the total population of companies, then identify the decision-
making unit within each qualifying account.

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
itself.

## Grounded good example

Hospitals are the total population in the example. There are 1,148 UK hospitals,
but only some are large or advanced enough to need a CAT scanner; the example
uses 25% with one and assumes 50% could potentially benefit.

## Grounded bad or failure example

NOT FOUND as a named bad example. A common structural error to avoid is putting
individual decision makers into the account-level segmentation map instead of
breaking out the buying committee in the portrait.

## Consumers

Target Customer Portrait uses the qualifying account as its base and then
describes the committee members, their interactions, and what matters to them.

## Boundaries

- Keep segmentation at the firm or account level.
- Do not assume every company in the total population is in the market.
- Do not prescribe demographic or firmographic filters without business-
  specific evidence.

## Referenced by

Other files in this knowledge base that link here -- useful starting points if this file alone doesn't fully answer a question:

- [Marketing Plan Structure (Diagnosis → Strategy → Tactics assembly)](marketing-plan-structure-diagnosis-strategy-tactics-assembly.md) (Schema)
- [Segmentation Process (top-level 5-step sequence)](../playbooks/segmentation-process-top-level-5-step-sequence.md) (Playbook)
