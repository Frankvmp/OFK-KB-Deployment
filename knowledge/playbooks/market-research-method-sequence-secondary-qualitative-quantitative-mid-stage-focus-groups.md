---
type: Playbook
title: "Market Research Method Sequence (secondary -> qualitative -> quantitative -> mid-stage focus groups)"
status: draft
generated:
  by: "process:extraction"
sources:
  - id: origin
    resource: "tools/flattened/market-research-m2-video.txt#00:03:03"
    title: "Transcript source"
  - id: step-1
    resource: "tools/flattened/market-research-m2-video.txt#00:05:53"
    title: "Transcript source"
  - id: step-2
    resource: "tools/flattened/market-research-m2-video.txt#00:27:05"
    title: "Transcript source"
  - id: step-3
    resource: "tools/flattened/market-research-m2-video.txt#00:16:38"
    title: "Transcript source"
  - id: step-4
    resource: "tools/flattened/market-research-m2-video.txt#00:33:33"
    title: "Transcript source"
tags:
  - diagnosis
  - research
  - customer-understanding
---

# Market Research Method Sequence (secondary -> qualitative -> quantitative -> mid-stage focus groups)

## When to use this

*(Process framing — not a sourced claim; no footnote.)* This is the Playbook other concepts invoke whenever they need the agent to gather real evidence rather than assert a claim without support — see the `Data-gathering` step type in [CONTEXT.md](../../CONTEXT.md). Run it whenever a diagnosis, a funnel population, or a strategic decision needs grounding in real research and no research has been gathered yet.

Steps 2 through 4 below describe human-executed methods (qualitative interviews feeding survey design, administering a live quantitative survey, mid-stage focus groups) exactly as the source material presents them — accurate, but not something an agent can run itself. Where no human collaborator is available to execute them, run [Agent-Executable Customer Insight Synthesis](../playbooks/agent-executable-customer-insight-synthesis-identify-sources-extract-variables-flag-gaps.md) instead, for the variables it can actually gather; see that playbook's own Boundaries for what it cannot replace, and this file's own Boundaries and failure modes below for what has no substitute at all. See [ADR-0018](../../docs/adr/0018-agent-executable-path-is-primary-not-side-by-side.md) for why this is the default an agent is routed to.

## Purpose

This playbook defines an ordered process for market research method sequence (secondary -> qualitative -> quantitative -> mid-stage focus groups). The sequence and decision points are retained from the registered evidence.

## Invokes

- [Customer scope extends beyond the immediate buyer](../principles/customer-scope-extends-beyond-the-immediate-buyer.md) (Principle) — helps define which customer rings the research should cover.
- [Market orientation must precede market research](../principles/market-orientation-must-precede-market-research.md) (Principle) — establishes the orientation required before choosing and using research methods.
- [Research methods are trade-offs, not a ranking](../principles/research-methods-are-trade-offs-not-a-ranking.md) (Principle) — governs method selection by evidential strengths and limitations.
- [Target portraits must come from evidence, not invention](../principles/target-portraits-must-come-from-evidence-not-invention.md) (Principle) — requires the portrait input to be gathered through research rather than fabricated.
- [Triangulate secondary data without assuming it is correct](../principles/triangulate-secondary-data-without-assuming-it-is-correct.md) (Principle) — governs the evaluation of the first-stage secondary evidence.
- [Quantitative extrapolation requires a representative sample](../principles/quantitative-extrapolation-requires-a-representative-sample.md) (Principle) — sets the condition for generalising survey results.
- [Discover options qualitatively before measuring them](../principles/discover-options-qualitatively-before-measuring-them.md) (Principle) — explains why qualitative exploration precedes quantitative measurement.
- [Qualitative depth does not establish population magnitude](../principles/qualitative-depth-does-not-establish-population-magnitude.md) (Principle) — preserves the distinct evidential role of qualitative methods.
- [Understand customers in their real context](../principles/understand-customers-in-their-real-context.md) (Principle) — explains when contextual observation is required.
- [Revealed choices can be more informative than stated explanations](../principles/revealed-choices-can-be-more-informative-than-stated-explanations.md) (Principle) — connects the sequence to choice-based evidence.
- [Research reveals complexity; segmentation organises it](../principles/research-reveals-complexity-segmentation-organises-it.md) (Principle) — explains how the research output becomes the input to segmentation.
- [Discover behavioural groups before using demographics as identifiers](../principles/discover-behavioural-groups-before-using-demographics-as-identifiers.md) (Principle) — governs how questionnaire evidence should be used in behavioural segmentation.
- [Positioning must use customer data, not internal opinion](../principles/positioning-must-use-customer-data-not-internal-opinion.md) (Principle) — requires positioning inputs to come from market evidence.
- [Existing-customer evidence can refine positioning](../principles/existing-customer-evidence-can-refine-positioning.md) (Principle) — supports research with customers who already prefer the offer.
- [The value of creative pre-testing depends on method and context](../principles/the-value-of-creative-pre-testing-depends-on-method-and-context.md) (Principle) — applies method trade-offs to late-stage creative testing.
- [Agent-Executable Customer Insight Synthesis](../playbooks/agent-executable-customer-insight-synthesis-identify-sources-extract-variables-flag-gaps.md) (Playbook) — the agent-executable path for steps 2–4 when no human collaborator is available; see [ADR-0018](../../docs/adr/0018-agent-executable-path-is-primary-not-side-by-side.md).
- [Agent-gathered secondary evidence is directional, not equivalent to primary research](../principles/agent-gathered-secondary-evidence-is-directional-not-equivalent-to-primary-research.md) (Principle) — governs the confidence discount on that substitute's output.

## Inputs and preconditions

None for step 1 (starting point).

## Ordered steps

### 1. Start with secondary data

**Step type:** Data-gathering — check for pre-existing data before generating anything new; the agent's own knowledge is not a substitute for a real secondary-data search.

This is always where you begin. Before you even start thinking about research design or doing experiments or paying for focus groups, make sure you haven't already got the data because chances are it might already be there. [^step-1]

### 2. Do qualitative exploration before designing the quantitative survey

**Step type:** Data-gathering — real qualitative input, not invented, feeding into survey design.

Before you start quantitatively measuring things with great exactitude, make sure you understand what the qualitative options are, and that they've all been plugged into the quantitative survey. [^step-2]

**Invokes:** [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema, inferred link — not named explicitly in this sentence).

### 3. Run the quantitative survey (implicit -- not separately narrated as a step transition)

**Step type:** Data-gathering — real survey responses, not invented.

(No explicit 'now run the survey' connective sentence exists; the module simply proceeds to survey design mechanics: Sample Size Calculator, Three-Section Questionnaire, Survey Result Annotation.) [^step-3]

**Invokes:** [Three-Section Questionnaire](../schemas/three-section-questionnaire-demographic-attitudinal-behavioural.md) (Schema); [Sample Size Calculator Procedure](../frameworks/research-informs-understanding-not-strategy.md#sample-size-calculator-procedure) (embedded Playbook).

### 4. Use focus groups again, mid-stage, once tentative strategic decisions exist

**Step type:** Data-gathering — real focus-group reactions, not invented, checked against tentative strategic decisions already made.

Think about the moment before you go too far down that path where you have tentative answers to most of these things [target/position/product/comms/price/distribution]. And imagine being able to spend a day where we bring in three or four different focus groups of the target customers you've already identified. [^step-4]

**Invokes:** [Target Customer Portrait](../schemas/target-customer-portrait.md) (Schema) and the later targeting, positioning, product, communications, pricing, and distribution decisions being checked; the register records this as a forward reference.

## Output

Named end-state: 'Research architecture' -- 'how do you pick and blend your methods together' -- but the source material is cut off before this is explained (00:59:04-00:59:31, file's last line).

## Explicit consumers

No explicit cross-module consumer is recorded in the register.

## Boundaries and failure modes

IMPORTANT TENSION, not resolved by the source material: this teaches methods in the order secondary -> survey -> focus groups -> ethnography -> conjoint (stated explicitly at 00:03:03), but separately states the RECOMMENDED EXECUTION order is secondary -> qualitative exploration -> quantitative survey (stated at 00:27:05, illustrated by the Sweet Baby Ray's/Weatherchem focus-group case at 00:28:54). Do not collapse these into one clean sequence; record both.

- Preserve the registered order, including nested sequences.
- Do not convert this process into a set of interchangeable steps.
- Do not invent missing timing, thresholds, inputs, or outputs.
- Keep real client data outside the knowledge base.
- Steps 2–4 require a live respondent this Playbook cannot supply on its own; where no human collaborator is available, route to [Agent-Executable Customer Insight Synthesis](../playbooks/agent-executable-customer-insight-synthesis-identify-sources-extract-variables-flag-gaps.md) for the variables it can gather. Its output is directional only — never equivalent to a real mid-stage focus-group reaction — see [Agent-gathered secondary evidence is directional, not equivalent to primary research](../principles/agent-gathered-secondary-evidence-is-directional-not-equivalent-to-primary-research.md).

## Sources

[^origin]: market-research-m2-video — 00:03:03
[^step-1]: market-research-m2-video — 00:05:53
[^step-2]: market-research-m2-video — 00:27:05
[^step-3]: market-research-m2-video — 00:16:38
[^step-4]: market-research-m2-video — 00:33:33