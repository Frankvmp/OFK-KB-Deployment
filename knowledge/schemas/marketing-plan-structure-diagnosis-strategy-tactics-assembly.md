---
type: Schema
title: "Marketing Plan Structure (Diagnosis → Strategy → Tactics assembly)"
status: draft
tags:
  - cross-cutting
  - market-orientation
---

# Marketing Plan Structure (Diagnosis → Strategy → Tactics assembly)

## When to use this

Reach for this once a Diagnosis → Strategy → Tactics engagement has actually produced real work in at least one phase, and that work needs to be assembled into a single, presentable document a client can share within their own organisation — not while any individual piece (a segmentation, a positioning statement) is still being worked out on its own.

## Purpose

This schema defines the *shape* of a marketing plan as an ordered assembly of Schemas this knowledge base already defines — rather than a concept extracted from a single source. It exists because the [Diagnosis → Strategy → Tactics](../frameworks/diagnosis-strategy-tactics.md) framework already sequences this domain's own work, and every piece of data that sequence produces already has real, existing content in this knowledge base to draw from — a dedicated Schema for some pieces (segments, the target portrait, the positioning statement, the objective), and the [Four Ps](../frameworks/four-ps.md) framework's own per-P sections, embedded playbooks, and Principles for the four tactical areas, which have no single dedicated Schema of their own. This file's job is to name the assembly order once, so it isn't reinvented informally by every consuming agent that builds this artifact.

## Shape

| Section | Stage | Populated from (existing concept) | Present only when |
|---|---|---|---|
| Market understanding | Diagnosis | Findings produced by the [Market Research Method Sequence](../playbooks/market-research-method-sequence-secondary-qualitative-quantitative-mid-stage-focus-groups.md) — no fixed schema exists for this content itself, since real research findings vary by method | Real diagnosis work has happened |
| Segments | Diagnosis | [Segment Profile](segment-profile-name-population-value-market-share.md) (one per real segment); [B2B Market Definition](b2b-market-definition-total-population-qualifying-accounts-buying-committee.md) where relevant | At least one segment has actually been profiled |
| Target customer | Strategy | [Target Customer Portrait](target-customer-portrait.md) | A target has actually been chosen, not just discussed |
| Positioning | Strategy | [Positioning Statement](positioning-statement-to-what-versus-is.md) | A positioning statement has actually been built |
| Objectives | Strategy | [Stated Objective Structure](stated-objective-structure.md) | An objective has been stated with all four required fields |
| Product | Tactics | [Four Ps — Product](../frameworks/four-ps.md#product); the embedded [New Product Development Sequence](../frameworks/four-ps.md#new-product-development-sequence), [Product Rationalisation Path](../frameworks/four-ps.md#product-rationalisation-path-temporary-revenue-reduction-to-focus), or [NPS Exit-Survey Reading Workflow](../frameworks/four-ps.md#nps-exit-survey-reading-workflow) where the specific decision calls for one | A real product decision has actually been made, not just discussed |
| Pricing | Tactics | [Four Ps — Pricing](../frameworks/four-ps.md#pricing) for the core decision; [Value and profitability](../frameworks/value-and-profitability.md) for the profit-vs-revenue test; value-based setting via [Price should follow customer perceived value, not cost-plus arithmetic](../principles/price-should-follow-customer-perceived-value-not-cost-plus-arithmetic.md); presentation via [Price presentation shapes perceived value and demand](../principles/price-presentation-shapes-perceived-value-and-demand.md); discount recovery via [Seven-Step Route Out of Discounting](../playbooks/seven-step-route-out-of-discounting.md) where discounting is specifically the issue | A real pricing decision has actually been made |
| Marketing communications | Tactics | [Four Ps — Marketing communications](../frameworks/four-ps.md#marketing-communications); [Brand Palette](brand-palette-selected-small-code-set.md) where a code set has been chosen; [Brand tracking](../frameworks/brand-tracking.md) once measurement starts | A real communications decision has actually been made |
| Distribution | Tactics | [Four Ps — Distribution](../frameworks/four-ps.md#distribution) for the core decision; [Distribution Cadence](../playbooks/distribution-cadence-brand-first-phased-channel-rollout.md) for phased channel rollout; [Three Phases to Omnichannel](../playbooks/three-phases-to-omnichannel.md) for omnichannel integration; channel-partner risk via [Channel management depends on interdependent partners](../principles/channel-management-depends-on-interdependent-partners.md) and [Grey-market leakage can become self-reinforcing](../principles/grey-market-leakage-can-become-self-reinforcing.md) | A real distribution decision has actually been made |

This is a categorical-template shape, not a fixed-field one: the section list above is fixed, but which sections actually appear in a real plan varies with how far a real engagement has progressed — a plan may legitimately contain only the first two rows for weeks. Never fill a row here with placeholder or invented content to make the table look complete; an absent row means exactly that, nothing more.

## Grounded good example

NOT FOUND as a source-grounded example — this shape has not yet been used to produce a real plan for a real client. Do not invent one.

## Grounded bad or failure example

Also not independently sourced, since this isn't an extracted concept — but the failure modes below were reasoned through directly with the project owner and are worth stating rather than left implicit: a plan section built from an unconfirmed client claim and presented with the same confidence as a section built from real evidence; a section that exists for a phase no real work has actually happened in yet, dressed up to look further along than it is; a plan that goes stale once an underlying fact changes because nothing re-checked what had already been built on top of it.

## Consumers

No consuming skill or agent implementation exists yet.

## Boundaries

- Never populate this schema file itself with a real client's plan content — it defines the shape only, the same boundary every other Schema in this knowledge base already holds.
- A section belongs in an actual populated plan only once real work backs it — no placeholder sections presented as further along than they are.
- Confidence and provenance must travel with populated content — an unconfirmed fact used in a real plan needs to be labelled as such, not smoothed into apparent settled fact.
- Do not add a section to this shape that isn't backed by a real Schema or Framework already in this knowledge base — a genuine gap is a decision for a fresh design pass, not a silent addition here.
