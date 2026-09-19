---
type: Principle
title: Agent-gathered secondary evidence is directional, not equivalent to primary research
description: Secondary-source synthesis run by an agent can approximate some primary-research variables, but must never be presented with the same confidence as a live interview, focus group, or in-context observation, and must never assert a population-level magnitude.
status: draft
generated:
  by: claude/sonnet-5
sources: []
tags:
  - diagnosis
  - customer-understanding
  - agent-execution
---

# Agent-gathered secondary evidence is directional, not equivalent to primary research

## When to use this

Reach for this Principle whenever [Agent-Executable Customer Insight Synthesis](../playbooks/agent-executable-customer-insight-synthesis-identify-sources-extract-variables-flag-gaps.md) has been used — or whenever an agent is about to present secondary-source synthesis as if it answered the same question a live interview, focus group, or in-context observation would have answered.

## Principle

An agent synthesising customer-understanding variables from secondary and online sources can approximate some of what a live human-executed method would gather, but that output is directional signal about what individual sources say — never equivalent-confidence evidence to a live interview, a focus group, or in-context observation, and never a population-magnitude claim.

This is not a claim this knowledge base's own extraction verified against a transcript — it is a design constraint for how this knowledge base's own agent-executable substitute must be used, decided directly with the project owner. See [Citation status](#citation-status).

## Why it matters

[Understand customers in their real context](understand-customers-in-their-real-context.md) already establishes, from the source material itself, why decontextualized recall is weaker than in-context observation — an artificial setting can remove the context needed to interpret what someone says or does. Secondary-source synthesis is a further step removed again: not even a recalled account given directly to a researcher, but a third party's own published account, gathered with no ability to ask a follow-up question or observe context at all. Whatever confidence discount applies to a recalled interview answer applies with more force here, not less.

[Qualitative depth does not establish population magnitude](qualitative-depth-does-not-establish-population-magnitude.md) already establishes the same discipline for a real small qualitative sample. Secondary-source synthesis has an even weaker claim to representativeness than a genuine qualitative study, since the sources found are shaped by what happens to be published and discoverable, not by any sampling design at all.

## Related distinctions

This Principle does not compete with or soften [Understand customers in their real context](understand-customers-in-their-real-context.md) — it extends the same reasoning to a channel that Principle didn't need to address, because [Agent-Executable Customer Insight Synthesis](../playbooks/agent-executable-customer-insight-synthesis-identify-sources-extract-variables-flag-gaps.md) didn't exist when that Principle was extracted. Both Principles agree: the further evidence is from direct, in-context observation, the more its confidence must be discounted before it informs a decision.

## Invokes

- [Agent-Executable Customer Insight Synthesis](../playbooks/agent-executable-customer-insight-synthesis-identify-sources-extract-variables-flag-gaps.md) (Playbook) — the technique this Principle governs.
- [Understand customers in their real context](understand-customers-in-their-real-context.md) (Principle) — the source-grounded reasoning this Principle extends to a channel it didn't originally cover.
- [Qualitative depth does not establish population magnitude](qualitative-depth-does-not-establish-population-magnitude.md) (Principle) — the existing magnitude boundary, which applies with even more force here.
- [Triangulate secondary data without assuming it is correct](triangulate-secondary-data-without-assuming-it-is-correct.md) (Principle) — governs the reliability check on each individual secondary source before this Principle's confidence discount is even applied.

## Boundaries and failure modes

- Do not present secondary-source synthesis with the same confidence as a live interview, focus group, or in-context observation.
- Do not use secondary-source synthesis to assert a population-level magnitude or proportion.
- Do not let a downstream use of this content silently drop the confidence discount — it must travel with the content, not just accompany its first mention.
- Do not treat a single source's account as a pattern; only note a pattern when it's genuinely repeated across independent sources.

## Citation status

This Principle carries no footnotes and no populated `sources` entries. It states a design constraint for this knowledge base's own agent-executable substitute ([ADR-0018](../../docs/adr/0018-agent-executable-path-is-primary-not-side-by-side.md)), not a claim extracted from the source transcripts. `generated.by` reflects that honestly (`claude/sonnet-5`, not `process:extraction`). Its grounding is the reasoning already established, and independently source-cited, in [Understand customers in their real context](understand-customers-in-their-real-context.md) and [Qualitative depth does not establish population magnitude](qualitative-depth-does-not-establish-population-magnitude.md) — extended here to a channel neither original Principle needed to address.

## Sources

(None — see Citation status above.)
