---
type: Framework
title: "Market orientation"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: definition
    resource: "tools/flattened/market-orientation-m1-video.txt#00:16:20-00:16:45"
    title: "Transcript source — M1"
  - id: intelligence
    resource: "tools/flattened/market-orientation-m1-video.txt#00:42:30-00:43:59"
    title: "Transcript source — M1"
  - id: measurement
    resource: "tools/flattened/market-orientation-m1-video.txt#00:45:20-00:47:19"
    title: "Transcript source — M1"
  - id: capgemini
    resource: "tools/flattened/market-orientation-m1-video.txt#00:47:56-00:49:34"
    title: "Transcript source — M1"
  - id: prime-directive
    resource: "tools/flattened/market-orientation-m1-video.txt#01:08:46-01:11:18"
    title: "Transcript source — M1"
tags:
  - diagnosis
  - market-orientation
---

# Market orientation

## When to use this

*(Process framing — not a sourced claim; no footnote.)* Reach for this before accepting any strategic or tactical input at face value — whenever a claim about "what the customer wants" or "what will work" is grounded only in internal opinion, a founder's instinct, or an untested assumption, rather than real customer or competitor evidence. It is also the diagnostic lens for explaining why a business's marketing isn't landing: a market-orientation gap is a common root cause.

## Purpose

Market orientation is an organisation-wide commitment to understanding the
market and representing the customer inside the organisation. It prevents
internal assumptions from becoming the unchecked basis for marketing decisions.
[^definition] [^prime-directive]

The terms market-driven, customer focus, customer centricity, customer
obsession, and customer-centred are used as alternative names for this same
customer-focused orientation. [^definition]

## Invokes

- [Marketers are not the consumer](../principles/marketers-are-not-the-consumer.md) (Principle) — the personal discipline that supports the Framework's customer perspective.
- [Customer scope extends beyond the immediate buyer](../principles/customer-scope-extends-beyond-the-immediate-buyer.md) (Principle) — broadens the customer view beyond the immediate buyer.
- [Market intelligence must circulate, and response is judgement](../principles/market-intelligence-must-circulate-and-response-is-judgement.md) (Principle) — highlights the organisational movement and response implications.
- [Customer alternatives define segment-relative competition](../principles/customer-alternatives-define-segment-relative-competition.md) (Principle) — applies the customer perspective to competitor interpretation.
- [Marketing's prime directive is to represent the customer](../principles/marketing-prime-directive-represent-the-customer.md) (Principle) — states marketing's distinctive responsibility within market orientation.
- [Market orientation must precede market research](../principles/market-orientation-must-precede-market-research.md) (Principle) — carries this Framework's orientation into the research stage.
- [Product success requires quality and market preparation](../principles/product-success-requires-quality-and-market-preparation.md) (Principle) — applies market orientation during product development and launch preparation.
- [Customers buy solutions to jobs, not products as defined internally](../principles/customers-buy-solutions-to-jobs-not-products-as-defined-internally.md) (Principle) — applies the customer perspective to product and category definitions.

## Organisational model

The model requires three connected behaviours:

1. customer orientation;
2. competitor orientation; and
3. inter-functional coordination.

Customer and competitor intelligence must move beyond the marketing function
so the organisation can respond. Responsiveness does not mean obeying every
customer request; it means knowing the request and deciding how the
organisation should act on it. [^intelligence]

## How this executes

This framework does not itself state one single ordered procedure covering identification, evidence-gathering, sharing, deciding, and measuring as discrete numbered steps — an earlier draft of this section presented a 6-step "Operating procedure" in that shape, but no footnote actually supports that specific step breakdown, so it has been removed rather than re-cited on a guess (see Citation status below). What's actually given, with real citations, are the two concrete sequences below: the [Producer-Consumer Development Wheel](#producer-consumer-development-wheel) (how a product/market loop should run) and the [Organizational Market-Orientation Intelligence Chain](#organizational-market-orientation-intelligence-chain-generate---irrigate---respond) (generate → irrigate → respond, itself flagged `CONTESTED / lower confidence`). Measurement (the MORTN scale, Capgemini benchmark) is covered in **Measurement and diagnosis** and **Supporting Metrics** below.

## Measurement and diagnosis

The Capgemini example compares an organisation’s own perception of its
customer-centricity with the perception held by representative customers. In
the cited sample, 56% of companies believed they were customer-centric while
their customers disagreed. The figure is an example from that study, not a
general market statistic. [^capgemini]

## Supporting Case Study: Think TV

Think TV compared the media behaviour and perceptions of marketing professionals
with those of consumers. The comparison illustrates the risk that marketers
project their own behaviour onto the market instead of measuring consumer
behaviour directly. [^definition]

## Supporting Metrics

The MORTN scale is a measurement instrument for organisational market
orientation, not a consumer brand-health tracker. It supports diagnosis,
benchmarking, and later tracking of market orientation. [^measurement]

The Capgemini 56% figure is a contextual case-study metric. It should not be
used as a universal estimate of organisational self-perception gaps.
[^capgemini]

## Boundaries and failure modes

- Do not treat personal experience as a substitute for market evidence.
- Do not restrict market understanding to the immediate buyer when retailers,
  intermediaries, or end users also shape the market.
- Do not treat responsiveness as automatic compliance.
- Do not confuse a market-oriented organisation with one that merely uses
  customer-centred language.
- Do not use the MORTN scale as a consumer brand-tracking measure.

## Citation status

The originally-drafted "Operating procedure" section (6 numbered steps: identify customers, gather customer evidence, gather competitor evidence, share intelligence, decide, measure) carried no footnotes at all — not a wrong timestamp, no citation whatsoever. Checked against `tools/flattened/market-orientation-m1-video.txt`, no span states that specific 6-step breakdown; it reads as a plausible synthesis rather than a transcript-grounded procedure, and duplicates (less precisely, and without the transcript's own hedging) the properly-cited **Organizational Market-Orientation Intelligence Chain** below. Removed rather than re-cited on a guess, per this project's anti-fabrication rule. Everything else in this file was checked against the transcript and holds up.

**Agent-execution translation (2026-09-19):** the Producer-Consumer Development Wheel's step 3 ("test the prototype with other consumers") was rewritten per ADR-0019 to state the evidence standard the step must satisfy, rather than the human-executed ritual the source describes. The original human-taught wording remains below in `## Sources` for provenance. Step 1 ("lead users immediately") was reviewed and confirmed to need no change — its existing annotation already states an honest limit rather than a ritual assumption.

## Sources

## Embedded Playbooks

### Producer-Consumer Development Wheel

This ordered process is embedded here because it is self-contained within the originating Framework.

**Inputs and preconditions:** None stated beyond having either a product idea or a consumer insight to start from.

**Steps:**

1. **Get a product idea into the market with lead users immediately.** If we have a great product idea, instantly get into the market and test it out among some lead users. [^producer-consumer-development-wheel-1]
   **Step type:** Data-gathering — the agent's role is to advise/track that this real-world test happens and capture what it returns, not to invent the result.
2. **Bring back insights, develop a prototype.** Bring back those insights from the lead users and develop a prototype. [^producer-consumer-development-wheel-2]
   **Step type:** Evidence-and-judgement — synthesizing gathered lead-user insight into a design decision.
3. **Test the prototype with other consumers.** *(Adapted for agent execution — states the evidence standard, not a transcript claim; see Citation status.)* The prototype must be checked against real reactions from people outside the original lead-user group who have genuinely experienced it — not the team's assumption of how they would respond. If no such reaction exists yet, that absence must be stated plainly rather than filled with an assumed response.
   **Step type:** Data-gathering — real consumer response, not invented.
4. **Bring back insights from a soft launch.** Bring back those insights, gain insight from a soft launch. [^producer-consumer-development-wheel-4]
   **Step type:** Data-gathering — real soft-launch results, not invented.
5. **Repeat -- turn the wheel regardless of where the process started.** Turn the wheel between producer and consumer, wherever it may start. [^producer-consumer-development-wheel-5]
   **Step type:** none of the four defined types fits cleanly — this is a loop-back instruction (return to step 1), not a gathering, decision, or judgement act. Flagged rather than force-labelled; a genuine gap in the Step-type vocabulary (see CONTEXT.md), not a silent omission.

**Output:** Continuously market-validated product/market fit, contrasted with product orientation's 'begin with a product and hope, pray, the market is there' (negative case: 3M Post-it Note; positive case: Nike consumer-led innovation).

**Boundary:** Do not add steps, thresholds, or prerequisites that the source does not specify.

[^producer-consumer-development-wheel-1]: market-orientation-m1-video — 00:55:43
[^producer-consumer-development-wheel-2]: market-orientation-m1-video — 00:55:43
[^producer-consumer-development-wheel-3]: market-orientation-m1-video — 00:55:43
[^producer-consumer-development-wheel-4]: market-orientation-m1-video — 00:55:43
[^producer-consumer-development-wheel-5]: market-orientation-m1-video — 00:56:15
### Organizational Market-Orientation Intelligence Chain (generate -> irrigate -> respond)

This ordered process is embedded here because it is self-contained within the originating Framework.

**Inputs and preconditions:** None stated.

**Steps:**

1. **Generate market and competitor intelligence.** ... [^organizational-market-orientation-intelligence-chain-generate-irrigate-respond-1]
   **Step type:** Data-gathering — real market/competitor evidence, not invented.
   **Invokes:** [Market Research Method Sequence](../playbooks/market-research-method-sequence-secondary-qualitative-quantitative-mid-stage-focus-groups.md) (Playbook).
2. **Irrigate (disseminate) that intelligence through the organization.** Once they gathered that information, though, there had to be at the heart of any market oriented company an ability to irrigate that information [^organizational-market-orientation-intelligence-chain-generate-irrigate-respond-2]
   **Step type:** Evidence-and-judgement — not something the agent computes; it's the organisation's dissemination act the agent can flag as needed or not yet done.
3. **Respond -- not necessarily by complying.** there had to be a responsiveness ultimately to all of that intelligence... response doesn't always mean doing what the customer wants... Responsiveness can be saying no or doing nothing. [^organizational-market-orientation-intelligence-chain-generate-irrigate-respond-3]
   **Step type:** Evidence-and-judgement — deciding how (or whether) to act on gathered intelligence.

**Output:** An organization that has acted on (or deliberately not acted on) market intelligence.

**Boundary:** CONTESTED / lower confidence: the surrounding text is stated in definitional tense ('market orientation meant... there was...'), describing traits of market-oriented firms, not an imperative build procedure. Only this 3-link back half (generate->irrigate->respond) has genuine sequential dependency language ('once they gathered... finally'). Do not over-state as a 5-step 'how to build market orientation' playbook.

[^organizational-market-orientation-intelligence-chain-generate-irrigate-respond-1]: market-orientation-m1-video — 00:41:53
[^organizational-market-orientation-intelligence-chain-generate-irrigate-respond-2]: market-orientation-m1-video — 00:42:30
[^organizational-market-orientation-intelligence-chain-generate-irrigate-respond-3]: market-orientation-m1-video — 00:43:01


[^definition]: market-orientation-m1-video — 00:16:20-00:16:45
[^intelligence]: market-orientation-m1-video — 00:42:30-00:43:59
[^measurement]: market-orientation-m1-video — 00:45:20-00:47:19
[^capgemini]: market-orientation-m1-video — 00:47:56-00:49:34
[^prime-directive]: market-orientation-m1-video — 01:08:46-01:11:18

