---
type: Playbook
title: "Segmentation Process (top-level 5-step sequence)"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: origin
    resource: tools/flattened/segmentation-m3-video.txt#00:18:50-00:18:55
    title: Transcript source
  - id: step-1-1
    resource: tools/flattened/segmentation-m3-video.txt#00:27:38
    title: Transcript source
  - id: step-2
    resource: tools/flattened/segmentation-m3-video.txt#00:19:03
    title: Transcript source
  - id: step-5
    resource: tools/flattened/segmentation-m3-video.txt#00:19:31
    title: Transcript source
tags:
  - diagnosis
  - segmentation
---

# Segmentation Process (top-level 5-step sequence)

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Reach for this once the mass market is understood and a business needs to move from raw market understanding to a validated set of describable, valuable segments — the bridge between diagnosis and the targeting decision that follows it.

## Purpose

This playbook defines an ordered process for segmentation process (top-level 5-step sequence). The sequence and decision points are retained from the registered evidence.

## Invokes

- [Customer scope extends beyond the immediate buyer](../principles/customer-scope-extends-beyond-the-immediate-buyer.md) (Principle) — provides the broader customer scope before segmentation structures the market.
- [Customer alternatives define segment-relative competition](../principles/customer-alternatives-define-segment-relative-competition.md) (Principle) — preserves the segment-relative competitive context.
- [Research reveals complexity; segmentation organises it](../principles/research-reveals-complexity-segmentation-organises-it.md) (Principle) — requires research evidence before the process structures recurring market patterns.
- [Map the whole market before choosing targets](../principles/map-the-whole-market-before-choosing-targets.md) (Principle) — keeps the process diagnostic and prevents early target selection.
- [Segmentation is an option, not a default](../principles/segmentation-is-an-option-not-a-default.md) (Principle) — keeps mass marketing available when useful segments do not emerge.
- [Segment B2B markets at the account level](../principles/segment-b2b-markets-at-the-account-level.md) (Principle) — sets the unit of segmentation for B2B markets.
- [Do not combine markets when aggregation erases differences](../principles/do-not-combine-markets-when-aggregation-erases-differences.md) (Principle) — governs whether one market map can validly cover several countries or categories.
- [Discover behavioural groups before using demographics as identifiers](../principles/discover-behavioural-groups-before-using-demographics-as-identifiers.md) (Principle) — governs the order of behavioural grouping and demographic identification.

## Inputs and preconditions

None for step 1 (starting point of the module).

## Ordered steps

### 1. Define the mass market

**Step type:** Data-gathering — the total market size and boundary must be a real, constructed definition, never invented, per the Pampers/Tide/GE Medical examples that follow.

Paradoxically, the first step in the process is to define the mass market. [^origin]

**Nested sequence:**

1. **B2B two-level sophistication (qualifying population, then buying committee).** identifying from the total population of companies which ones are actually in the market. And then identifying the decision making unit or buying committee that makes a decision in each of those accounts. [^step-1-1]
   **Step type:** Data-gathering — real qualifying-population and buying-committee data, never invented.
   **Invokes:** [B2B Market Definition](../schemas/b2b-market-definition-total-population-qualifying-accounts-buying-committee.md) (Schema).

### 2. Select a segmentation method

**Step type:** Decision (criteria-guided) — choosing among the available segmentation methods.

we have to select our segmentation method. There are many different ways to carve up the market. [^step-2]

### 3. Segment (separate customers into segments)

**Step type:** Evidence-and-judgement — executed via the chosen method's own procedure.

Then there's the segmentation process itself, which involves separating out the customers into their various different segments. [^step-3]

**Invokes:** [Meaningful Actionable Grid](../playbooks/meaningful-actionable-grid-10-stage-segmentation-construction-playbook.md) (or other method) (Playbook).

### 4. Populate each segment with data

**Step type:** Data-gathering — real segment data (value, size), never invented.

the all-important stage of populating each segment with the relevant data, so we can identify these different segments, their value, and set up the targeting process ahead. [^step-4]

**Invokes:** [Segment Profile](../schemas/segment-profile-name-population-value-market-share.md), [Segment Spillover Record](../schemas/segment-spillover-record-segment-a-influences-segment-b.md) (Schemas).

### 5. Triangulate

**Step type:** Constraint check — confirm the segmentation is broadly accurate via multiple checks before proceeding.

Finally, there's an extra step at the end, triangulation. Just checking a number of different ways that the segmentation is broadly accurate and represents the market. [^step-5]

## Output

A validated market map. "it's time to end diagnosis and move into the start of strategy, which is targeting" (01:28:43).

## Explicit consumers

- Module 4: Targeting: consumes the Segment Profile and Segment Spillover Record schemas per schema-register.json
- Module 6: Marketing Objectives: consumes Segment Profile per schema-register.json

## Boundaries and failure modes

No additional boundary is recorded in the source register. Do not add steps, thresholds, or prerequisites that the source does not specify.

- Preserve the registered order, including nested sequences.
- Do not convert this process into a set of interchangeable steps.
- Do not invent missing timing, thresholds, inputs, or outputs.
- Keep real client data outside the knowledge base.

## Citation status

Two findings from checking against `tools/flattened/segmentation-m3-video.txt`:

1. `[^step-1-1]` (the B2B two-level sophistication note) was cited at 00:25:58, but the near-verbatim matching sentence — "identifying from the total population of companies which ones are actually in the market. And then identifying the decision making unit or buying committee that makes a decision in each of those accounts" — is actually at 00:27:38. Fixed to point at the correct span.
2. Steps 3 and 4 cited `[^step-3]` and `[^step-4]` with no matching definitions. The source sentence covering steps 2, 3, and 4 is a single breath at 00:19:03 ("we have to select our segmentation method... Then there's the segmentation process itself... And then the all-important stage of populating each segment"). Added both as real definitions pointing at that shared span rather than leaving them undefined.

A later mechanical audit pass (`tools/audit_harness.py`) found a third issue: step 1's body marker was written as `[^step-1]`, with no matching definition, while the actual covering citation existed under the unused id `[^origin]` — but pointed at the wrong span (00:18:36, a Sally Dibb quote, not the step-1 sentence). Fixed by pointing the body marker at `[^origin]` and correcting its span to 00:18:50-00:18:55, where "Paradoxically, the first step in the process is to define the mass market" actually is.

Everything else checked out — steps 2 and 5 cite accurately.

## Sources

[^origin]: segmentation-m3-video — 00:18:50-00:18:55
[^step-1-1]: segmentation-m3-video — 00:27:38
[^step-2]: segmentation-m3-video — 00:19:03
[^step-3]: segmentation-m3-video — 00:19:03
[^step-4]: segmentation-m3-video — 00:19:03
[^step-5]: segmentation-m3-video — 00:19:31
