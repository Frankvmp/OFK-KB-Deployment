---
type: Playbook
title: "Conjoint Analysis Procedure"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: origin
    resource: "tools/flattened/market-research-m2-video.txt#00:50:08"
    title: "Transcript source"
  - id: step-2
    resource: "tools/flattened/market-research-m2-video.txt#00:50:46"
    title: "Transcript source"
  - id: step-3
    resource: "tools/flattened/market-research-m2-video.txt#00:51:24"
    title: "Transcript source"
  - id: step-4
    resource: "tools/flattened/market-research-m2-video.txt#00:52:00"
    title: "Transcript source"
  - id: step-5
    resource: "tools/flattened/market-research-m2-video.txt#00:52:28"
    title: "Transcript source"
tags:
  - diagnosis
  - research
  - customer-understanding
---

# Conjoint Analysis Procedure

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Reach for this when stated preference (asking consumers what they want) isn't reliable enough — when you need to derive what actually drives choice, and the trade-off between price and other attributes, from revealed behaviour rather than spoken explanation.

## Purpose

This playbook defines an ordered process for conjoint analysis procedure. The sequence and decision points are retained from the registered evidence.

## Invokes

- [Quantitative extrapolation requires a representative sample](../principles/quantitative-extrapolation-requires-a-representative-sample.md) (Principle) — governs the sample needed before repeated choice tasks.
- [Discover options qualitatively before measuring them](../principles/discover-options-qualitatively-before-measuring-them.md) (Principle) — requires relevant attributes and alternatives to be established before analysis.
- [Revealed choices can be more informative than stated explanations](../principles/revealed-choices-can-be-more-informative-than-stated-explanations.md) (Principle) — explains why this Playbook uses observed trade-offs rather than direct importance questions.
- [Price should follow customer perceived value, not cost-plus arithmetic](../principles/price-should-follow-customer-perceived-value-not-cost-plus-arithmetic.md) (Principle) — governs use of conjoint-derived willingness to pay in price setting.
- [Pricing decisions require customer evidence, not internal intuition](../principles/pricing-decisions-require-customer-evidence-not-internal-intuition.md) (Principle) — explains why the Playbook uses observed trade-offs as pricing evidence.

## Inputs and preconditions

Explicit: requires 'a simple and divisible series of attributes' and that the correct/complete set of attributes is already known (00:56:05) -- the same 'know the right options first' principle governing the survey stage above.

## Ordered steps

### 1. Recruit a representative sample

**Step type:** Data-gathering — a real sample of consumers in the market, never invented.

you recruit a representative sample of consumers who are in the market, in this case for a mobile phone. [^origin]

### 2. Present a choice task built from options/alternatives/attributes

**Step type:** Constraint check — requires the correct/complete set of attributes to already be known before the task can be built.

a consumer might be confronted with the following three choices: a 5-inch Samsung handset with 250 gigabytes of memory for $1,200 versus a Sony or an LG alternative... [^step-2]

**Invokes:** [Conjoint Choice Structure](../schemas/conjoint-choice-structure-options-alternatives-attributes.md) (Schema).

### 3. Record choice; generate a new trade-off with altered variables

**Step type:** Data-gathering — the real recorded choice, not invented.

That choice is recorded by the computer, and then a new series of trade-offs is offered to them again... the price options are altered. [^step-3]

### 4. Repeat 12-15 times

**Step type:** Constraint check — 12-15 trade-offs is the stated range.

imagine lots of trade-offs happening, sometimes 12 or 15 trade-offs. [^step-4]

### 5. Derive attribute importance and option utility

**Step type:** Decision (criteria-guided) — a computation over the recorded choices, not a judgement call.

we're able to impute the importance and then the utility, positive or negative, of each of those different options. [^step-5]

## Output

Derived attribute importance and option utility (not stated preference).

## Explicit consumers

- Module 8: Pricing Strategy: Explicit reuse recorded in the register.

## Boundaries and failure modes

No additional boundary is recorded in the source register. Do not add steps, thresholds, or prerequisites that the source does not specify.

- Preserve the registered order, including nested sequences.
- Do not convert this process into a set of interchangeable steps.
- Do not invent missing timing, thresholds, inputs, or outputs.
- Keep real client data outside the knowledge base.

## Citation status

Step 1's body footnote was written as `[^step-1]`, but no `[^step-1]` definition existed — the matching content is covered by `[^origin]` (00:50:08), which already carries the whole step-1 sentence. Fixed by pointing the body marker at `[^origin]`. All other citations checked against `tools/flattened/market-research-m2-video.txt#00:50:08-00:52:57` and hold up — near-verbatim, no fabrication.

## Sources

[^origin]: market-research-m2-video — 00:50:08
[^step-2]: market-research-m2-video — 00:50:46
[^step-3]: market-research-m2-video — 00:51:24
[^step-4]: market-research-m2-video — 00:52:00
[^step-5]: market-research-m2-video — 00:52:28
