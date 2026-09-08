---
type: Framework
title: "Research informs understanding, not strategy"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: origin
    resource: "tools/flattened/market-orientation-m1-video.txt#00:29:46"
    title: "Transcript source — M1"
  - id: reuse-objectives
    resource: "tools/flattened/objectives-m6-video.txt#00:13:01"
    title: "Transcript source — M6"
  - id: reuse-pricing
    resource: "tools/flattened/pricing-m8-video.txt#00:17:17"
    title: "Transcript source — M8"
tags:
  - diagnosis
  - research
---

# Research informs understanding, not strategy

## When to use this

*(Process framing — not a transcript claim; no footnote.)* Reach for this whenever a research finding (a survey result, a focus-group quote, an ethnographic observation) is about to be treated as if it were itself the strategic answer — who to target, what to charge, what to say. Use it to keep the boundary clear: research is an input to a strategic choice, never a substitute for making one.

## Purpose

Research clarifies what is happening in the market. It provides evidence about
customers, competitors, behaviour, needs, and performance so that marketers
can construct an informed strategy. Research does not supply the strategy
itself. [^origin]

## Invokes

- [Research methods are trade-offs, not a ranking](../principles/research-methods-are-trade-offs-not-a-ranking.md) (Principle) — keeps the Framework's embedded methods tied to their evidential strengths and limits.
- [Quantitative extrapolation requires a representative sample](../principles/quantitative-extrapolation-requires-a-representative-sample.md) (Principle) — governs the embedded sample-size procedure.
- [Qualitative depth does not establish population magnitude](../principles/qualitative-depth-does-not-establish-population-magnitude.md) (Principle) — limits what the embedded ethnographic procedure can establish.
- [Understand customers in their real context](../principles/understand-customers-in-their-real-context.md) (Principle) — supplies the reasoning for the embedded ethnographic procedure.
- [Pricing decisions require customer evidence, not internal intuition](../principles/pricing-decisions-require-customer-evidence-not-internal-intuition.md) (Principle) — applies the research boundary to price setting.
- [The value of creative pre-testing depends on method and context](../principles/the-value-of-creative-pre-testing-depends-on-method-and-context.md) (Principle) — keeps creative-test evidence within its methodological strengths and limitations.

## How this executes

This framework does not itself state a specific numbered procedure for moving from question to strategy — an earlier draft of this section presented a 5-step "Operating logic" in that shape, but no footnote in the transcript actually supports that specific step breakdown, so it has been removed rather than re-cited on a guess (see Citation status below). The two concrete, cited procedures below — the [Sample Size Calculator Procedure](#sample-size-calculator-procedure) and the [Ethnographic Research Procedure](#ethnographic-research-procedure) — are what the transcript actually gives as ordered sequences; both are research-execution Playbooks, invoked from the [Market Research Method Sequence](../playbooks/market-research-method-sequence-secondary-qualitative-quantitative-mid-stage-focus-groups.md) when quantitative or ethnographic evidence is needed.

The research output is understanding; the strategic output is a choice. Mixing
these outputs makes descriptive evidence appear to be a recommendation.

## Application boundaries

Research can show what customers do, value, or currently perceive. It cannot
make the strategic trade-offs on behalf of the organisation. Strategy still
requires choices about whom to serve, what to offer, and how to compete.

The principle is reused when funnels are interpreted into objectives and when
pricing decisions are developed from value and market evidence. [^reuse-objectives]
[^reuse-pricing]

## Supporting Principles

### Challenge assumptions with data

Boardroom assumptions should be identified and checked against evidence before
they direct product development or other decisions. [^origin]

### Research has different roles

Research may be limited when an organisation is seeking non-incremental
innovation, but it remains useful for testing and checking an idea against the
market. Do not use this distinction to dismiss research generally.

## Boundaries and failure modes

- Do not convert a research finding into a strategy without an explicit choice.
- Do not ask research to decide the target, position, or objective automatically.
- Do not treat a consumer’s stated preference as a complete account of actual
  behaviour.
- Do not use research method labels as evidence that the method answered the
  decision.

## Citation status

Two findings from checking this file against `tools/flattened/market-orientation-m1-video.txt` and `tools/flattened/market-research-m2-video.txt`:

1. The originally-drafted "Operating logic" section (5 numbered steps: define, gather, interpret, convert, direct) carried no footnotes at all. No span states that specific breakdown; it reads as a plausible synthesis, not a transcript-grounded procedure. Removed rather than re-cited on a guess.
2. `[^origin]`'s single timestamp (00:29:46) undersold its own citation — the Purpose section's core claim ("that's not the point of research to give a strategy... the point of research is to help us understand") is the near-verbatim source text, but it actually falls at 00:30:20, not 00:29:46. Widened to a range (00:29:46-00:30:20) covering both the framing sentence and the exact-match quote, rather than left pointing only at the framing.

Everything else — both embedded Playbooks, the reuse citations — checked out accurately.

## Sources

## Embedded Playbooks

### Sample Size Calculator Procedure

This ordered process is embedded here because it is self-contained within the originating Framework.

**Inputs and preconditions:** None stated.

**Steps:**

1. **Determine total population / market size.** What is the total market size that we need to be representative of?... about 39 million British people drink wine at some point every year. [^sample-size-calculator-procedure-1]
   **Step type:** Data-gathering — the total-population figure must be real (secondary data or client-supplied), never invented.
2. **Enter confidence level (95% default).** The first one is, what's the confidence level you want from your research?... An acceptable confidence level in our industry is 95%. [^sample-size-calculator-procedure-2]
   **Step type:** Constraint check — 95% is the stated industry default; a different value is a deliberate override, not a free choice.
3. **Enter population size.** The next question is our population size... We already know that that number would be 39 million. [^sample-size-calculator-procedure-3]
   **Step type:** Data-gathering — same real-population requirement as step 1.
4. **Enter margin of error (5% default).** Next, you're going to be asked for a margin of error... in marketing, we accept a margin of error of about 5%. [^sample-size-calculator-procedure-4]
   **Step type:** Constraint check — 5% is the stated marketing-industry default.
5. **Calculate.** With all that data, we can now click calculate. And hey, presto, we discover our ideal sample size is 385. [^sample-size-calculator-procedure-5]
   **Step type:** Decision (criteria-guided) — a deterministic computation once the three inputs above are set; the agent can run this itself.
6. **Annotate the result (N / CL / margin of error).** you'd put your sample size, N equals 385. And underneath it, you'd write CL, confidence level equals 95%, and then plus or minus 5%. [^sample-size-calculator-procedure-6]
   **Step type:** Decision (criteria-guided) — mechanical formatting of the computed result.

**Output:** Required sample size N, used to run the survey (worked example: Constellation UK wine survey, N=400 in practice vs 385 calculated).

**Boundary:** Do not add steps, thresholds, or prerequisites that the source does not specify.

[^sample-size-calculator-procedure-1]: ../../transcripts/market-research-m2-video.md#00:11:07
[^sample-size-calculator-procedure-2]: ../../transcripts/market-research-m2-video.md#00:12:29
[^sample-size-calculator-procedure-3]: ../../transcripts/market-research-m2-video.md#00:12:57
[^sample-size-calculator-procedure-4]: ../../transcripts/market-research-m2-video.md#00:13:23
[^sample-size-calculator-procedure-5]: ../../transcripts/market-research-m2-video.md#00:13:52
[^sample-size-calculator-procedure-6]: ../../transcripts/market-research-m2-video.md#00:14:53
### Ethnographic Research Procedure

This ordered process is embedded here because it is self-contained within the originating Framework.

**Inputs and preconditions:** None stated.

**Steps:**

1. **Extended immersion, fully inductive start.** Day one of an ethnographic mission is basically to turn up and start to understand what's going on around you. [^ethnographic-research-procedure-1]
   **Step type:** Data-gathering — real immersion in the field, not something the agent can simulate.
2. **Observe and record (diary or digital video).** The core source of data is observational... Increasingly, that's digital video. [^ethnographic-research-procedure-2]
   **Step type:** Data-gathering — the agent's role is to structure the recorded observation, not invent it.
3. **Use observation to drive in-situ interviews.** recording what you're seeing and using that evidence to drive in situ interviews. So these are much more casual. They're on the spot. [^ethnographic-research-procedure-3]
   **Step type:** Data-gathering — real interview responses, not invented.
4. **Output: deep ethnographic insight.** this combination of observation and interview over extended periods of time produces this deep, extremely complex series of ethnographic insights. 'Get your ass into the market.' [^ethnographic-research-procedure-4]
   **Step type:** Evidence-and-judgement — synthesizing the gathered observation and interview data into insight.

**Output:** Deep ethnographic insight (B2C); for B2B, a naturally-sampled view of the buying committee.

**Boundary:** Do not add steps, thresholds, or prerequisites that the source does not specify.

[^ethnographic-research-procedure-1]: ../../transcripts/market-research-m2-video.md#00:42:58
[^ethnographic-research-procedure-2]: ../../transcripts/market-research-m2-video.md#00:43:28
[^ethnographic-research-procedure-3]: ../../transcripts/market-research-m2-video.md#00:43:28
[^ethnographic-research-procedure-4]: ../../transcripts/market-research-m2-video.md#00:43:57


[^origin]: ../../transcripts/market-orientation-m1-video.md#00:29:46-00:30:20
[^reuse-objectives]: ../../transcripts/objectives-m6-video.md#00:13:01
[^reuse-pricing]: ../../transcripts/pricing-m8-video.md#00:17:17