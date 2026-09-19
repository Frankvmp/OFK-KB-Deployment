---
type: Playbook
title: Agent-Executable Customer Insight Synthesis (identify sources → extract variables → tag confidence → flag gaps)
status: draft
generated:
  by: claude/sonnet-5
sources: []
tags:
  - diagnosis
  - research
  - customer-understanding
  - agent-execution
---

# Agent-Executable Customer Insight Synthesis (identify sources → extract variables → tag confidence → flag gaps)

## When to use this

*(Process framing — not a sourced claim; no footnote.)* This is the default path an agent runs to gather customer-understanding variables — demographic, attitudinal, behavioural, or the content boxes of a [Target Customer Portrait](../schemas/target-customer-portrait.md) — whenever the step that would normally require a live human method (an interview, a focus group, in-situ ethnographic observation) has no human collaborator available to run it. See [ADR-0018](../../docs/adr/0018-agent-executable-path-is-primary-not-side-by-side.md) for why this is the default an agent is routed to, not an alternative sitting beside those methods. Run it whenever [Market Research Method Sequence](market-research-method-sequence-secondary-qualitative-quantitative-mid-stage-focus-groups.md) routes here.

## Purpose

This playbook is original synthesis, not an extracted concept — see [Citation status](#citation-status). It defines how an agent, working alone, approximates the *variables* a human-executed research method would gather (who the customer is, what they believe, what they do) by synthesising what's already publicly available about them, rather than by observing or interviewing anyone directly. It produces directional signal, not primary-research-equivalent evidence — see [Agent-gathered secondary evidence is directional, not equivalent to primary research](../principles/agent-gathered-secondary-evidence-is-directional-not-equivalent-to-primary-research.md), which governs every use of this playbook's output.

## Invokes

- [Agent-gathered secondary evidence is directional, not equivalent to primary research](../principles/agent-gathered-secondary-evidence-is-directional-not-equivalent-to-primary-research.md) (Principle) — governs the confidence discount on this playbook's entire output.
- [Triangulate secondary data without assuming it is correct](../principles/triangulate-secondary-data-without-assuming-it-is-correct.md) (Principle) — governs how each individual source is evaluated before use.
- [Understand customers in their real context](../principles/understand-customers-in-their-real-context.md) (Principle) — states directly why this playbook's output is weaker than in-context observation; do not let that boundary be forgotten by using this playbook's output.
- [Qualitative depth does not establish population magnitude](../principles/qualitative-depth-does-not-establish-population-magnitude.md) (Principle) — the same magnitude boundary applies with even less force to secondary-source synthesis than to a real small-sample study.
- [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema) and [Target Customer Portrait](../schemas/target-customer-portrait.md) (Schema) — the output shapes this playbook populates; both are method-agnostic by design, so nothing about using this playbook to populate them is a new or bespoke structure.

## Inputs and preconditions

A defined variable set to fill (the boxes of a Target Customer Portrait, or the three sections of a questionnaire) and a real category, product, or segment to research. No live respondent access is required or assumed.

## Ordered steps

### 1. Identify candidate secondary sources

**Step type:** Data-gathering — real, checkable sources, never invented.

Search for material likely to carry the target variable set for the real category and segment in question: published reviews, forum and community discussion, social listening, analyst or category commentary, competitor review sections, and any existing survey or research data already public. Prefer sources that let the customer's own words through directly over sources that summarise or editorialise them.

### 2. Extract only statements that map to a defined variable slot

**Step type:** Data-gathering — real extracted statements, never invented or paraphrased into a stronger claim than the source supports.

For each source, pull only the statements that map cleanly onto a Demographic, Attitudinal, or Behavioural variable (per the Three-Section Questionnaire shape) or a Target Customer Portrait content box (Who / Current category behaviour / Drivers and turn-ons / Barriers and perceptions / Other). Do not force a statement into a slot it doesn't actually fit, and do not infer a variable value the source doesn't state.

### 3. Tag every extracted fact with its source and its pattern strength

**Step type:** Evidence-and-judgement — characterising what the gathered evidence actually supports, not inventing a conclusion beyond it.

Record where each fact came from, and note plainly whether it reflects a single account or a pattern repeated across multiple independent sources. A single review saying one thing is a lead, not a finding; the same point appearing independently across several sources is stronger, though still not primary research.

### 4. Mark any slot with insufficient evidence as not found

**Step type:** Constraint check — the slot stays honestly empty rather than filled with a plausible-sounding guess.

Where secondary sources don't cover a variable slot at all, mark it "NOT FOUND" in the populated schema rather than inferring a plausible value — the same convention this knowledge base's own Schema files already use for their own "Grounded bad or failure example" sections when no such example exists.

### 5. Apply the confidence discount before this output is used downstream

**Step type:** Constraint check — a fixed framing rule, not a judgement call.

Before any populated Schema built from this playbook's output is used in positioning, targeting, or another downstream decision, it must carry a visible note that it was built from secondary-source synthesis, not primary research — per [Agent-gathered secondary evidence is directional, not equivalent to primary research](../principles/agent-gathered-secondary-evidence-is-directional-not-equivalent-to-primary-research.md). Never present this output with the same confidence as a live interview, focus group, or in-context observation, and never use it to assert a population-level magnitude.

## Output

A populated [Target Customer Portrait](../schemas/target-customer-portrait.md) or [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md), sourced entirely from secondary material, with every filled slot traceable to a real source and every unfilled slot marked "NOT FOUND" rather than invented.

## Consumers

[Market Research Method Sequence](market-research-method-sequence-secondary-qualitative-quantitative-mid-stage-focus-groups.md) routes here for the steps that would otherwise require a live respondent (qualitative exploration, quantitative survey response-gathering, the mid-stage focus-group check) when no human collaborator is available. [Conjoint Analysis Procedure](conjoint-analysis-procedure.md) and the Ethnographic Research Procedure embedded in [Research informs understanding, not strategy](../frameworks/research-informs-understanding-not-strategy.md) reference this playbook for what an agent *can* still gather about the same customer, but neither treats it as a substitute for their own core mechanism — see each file's own "When to use this" for the honest boundary.

## Boundaries

- Not a substitute for a method that requires a live respondent doing something in real time under controlled conditions. It cannot replace live conjoint trade-off elicitation ([Conjoint Analysis Procedure](conjoint-analysis-procedure.md)) or physical ethnographic immersion and observation (the embedded Ethnographic Research Procedure) — do not stretch this playbook to cover either.
- Do not average, roll up, or otherwise combine secondary-source impressions into a manufactured population estimate. This playbook produces directional signal about what individual sources say, never a statistic.
- Do not present this output's confidence as equivalent to primary research anywhere downstream — the discount travels with the content, not just with this playbook's own output.
- Do not silently drop the "NOT FOUND" marking on an unfilled slot once this output is reused elsewhere — an absent finding must stay visibly absent.

## Citation status

This playbook is a deliberate, openly-stated exception to how every other Playbook in this knowledge base is built: it introduces no new sourced claim about the marketing domain, so it carries no footnotes and no populated `sources` entries. `generated.by` reflects that honestly (`claude/sonnet-5`, not `process:extraction`). Its grounding is the union of what it invokes — the source-cited Principles governing secondary-data evaluation and confidence discounting, and the method-agnostic Schemas it populates — plus the project owner's own explicit decision, recorded in [ADR-0018](../../docs/adr/0018-agent-executable-path-is-primary-not-side-by-side.md), that this technique is what an agent should run in place of a human-only method it cannot execute. Treat this file the way [ADR-0018](../../docs/adr/0018-agent-executable-path-is-primary-not-side-by-side.md) itself is treated: a real, deliberate design decision, not a transcript-grounded claim.

## Sources

(None — see Citation status above.)
