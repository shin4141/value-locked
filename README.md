# Value-Locked

**Control is not necessarily the cost of acceleration. It may be the mechanism of acceleration.**

Value-Locked combines accumulated operating assets with a method for turning uncertain problems into testable control distinctions. Developed around existing AI models, it connects investigation, repair, verification, and resumption with human decisions about what must be protected and what counts as completion. No new foundation model was developed.

**The value is not limited to what has already been learned. It also lies in how new distinctions are discovered, tested, preserved, and carried into future AI work.**

The commercial question is whether selected existing assets, or a separately scoped collaboration to generate new knowledge, could close a real gap sooner or at lower total cost than using your existing stack, building internally, or waiting. The answer may be **build, acquire, collaborate, or decline**. Value-Locked's incremental advantage has not been causally established; buying existing assets and commissioning future research are separate decisions and transactions.

Maintained by **Shin ([shin4141](https://github.com/shin4141))**. This repository provides public evidence for technical and commercial evaluation; the core implementation and working materials remain separately controlled.

## The outcome that warrants examination

> Why did a non-programmer repeatedly achieve maintainer-accepted repairs across unrelated codebases without personally reading the source code?

Shin describes himself as a non-programmer who delegated source analysis, implementation, tests, and diff inspection to AI while retaining direction, authorization, and residual-risk decisions. The absence of personal source reading is **the owner's account**, not an independently verified condition for every contribution. The public PRs establish particular changes and upstream acceptance; the research and operating records describe how work was arranged. They do not isolate Value-Locked's contribution from the models, human preparation, prior contributors, or maintainer review.

| Public contribution | Language / ecosystem | Accepted behavior and evidence boundary |
| --- | --- | --- |
| [Apple Swift OpenAPI Generator #939](https://github.com/apple/swift-openapi-generator/pull/939) | Swift / API code generation | Detects duplicate generated schema names before a dictionary-construction crash. Continues substantial prior repair work and review direction; no original discovery or sole authorship is claimed. |
| [Microsoft Power Platform Terraform Provider #1254](https://github.com/microsoft/terraform-provider-power-platform/pull/1254) | Go / infrastructure provider | Rechecks requested remote state after HTTP 409 and bounds retries when state has not converged, in the specified managed-environment and enterprise-policy paths. |
| [Toyota Connected emb_cli #240](https://github.com/toyota-connected/emb_cli/pull/240) | Dart / packaging tooling | Batches `chmod` while preserving repeated-destination order, argument bounds, and failure propagation. Fewer process invocations in tested cases; no measured end-to-end wall-clock speedup is claimed. |

These selected examples show acceptance across different organizations, languages, and codebases. They are not a controlled sample of equivalent tasks, a current portfolio count, or evidence of endorsement, employment, partnership, purchasing intent, or independent deployment of Value-Locked.

As of **October 11, 2026**, the [public merge portfolio](https://github.com/shin4141/shin4141/blob/7689580d9f2eda0a331a95e1cb8aef5b9c176463/MERGE_PORTFOLIO.md) records **39 direct upstream merges across 34 independent public repositories**. Maintainer-committed adoption, including OpenSSL, is tracked separately. This portfolio snapshot does not establish a comparative success rate or Value-Locked's incremental effect.

## Research → operation → outcome

Value-Locked sits within roughly a year of Decision-OS research and practical iteration through October 2026. The [public research timeline](https://github.com/shin4141/decision-os-paper/blob/932fa974cb1749bf50556299bf195ae6d66297df/docs/research_timeline.md) begins with a deposit in October 2025. The work developed foundations for retaining human direction, checking completion, preserving restartable context, and deciding whether another AI work cycle should proceed.

V13 LoopKit translated these ideas into an [operating prototype](https://github.com/shin4141/decision-os-v13-loopkit). Value-Locked began separately on **August 9, 2026**, selecting principles needed for practical work rather than importing LoopKit's entire runtime. In the owner's account, it was carved out to reduce the explanation, coordination, and restart friction encountered while operating V13. Its repair boundaries and verification practices became more concrete through actual work and maintainer feedback.

The September 17, 2026 paper, [*Decision-OS V13: From Human Aspiration to Working AI Loops*](https://raw.githubusercontent.com/shin4141/decision-os-paper/932fa974cb1749bf50556299bf195ae6d66297df/notes/v13/Decision-OS_V13_From_Human_Aspiration_to_Working_AI_Loops_EN.pdf), traces this selective inheritance and later external outcomes. It is a retrospective case study involving the creator and related projects, **not proof of Value-Locked's comparative performance**. It also reports a negative before/after comparison: merges within seven days were **18/28 (64.3%) before** the specified rule-recording point and **11/26 (42.3%) after**. This did not establish an improvement; changing case composition, review conditions, models, and validation methods prevent a causal interpretation. Research lineage, operational use, external acceptance, and causal improvement remain separate claims.

## From an unknown problem to reusable control knowledge

Shin's approach begins by questioning conditions that appear interchangeable in an otherwise normal-looking structure: which hidden variable could change the outcome while the visible success signal stays the same? Illustrative problem-framing distinctions include:

- **Successful authentication ≠ a safe decision.**
- **A successful API response ≠ the requested state being established.**
- **An AI's safe stop ≠ completion of the cleanup left to a human.**

A candidate distinction becomes useful through a bounded hypothesis, a countercase, system-specific verification, and a record of its conditions, evidence, limitations, and restart point. A later AI must check applicability before reuse. A negative result can narrow or reject the hypothesis; it need not become another rule.

The models contribute source analysis, technical hypotheses, implementation, tests, and diff inspection. Shin contributes problem framing, protected outcomes, judgment boundaries, and decisions about what knowledge should carry forward. Prior contributors and maintainers also shape accepted repairs. These contributions can reinforce one another, but the public results do not isolate their effects or establish that either side could reproduce the whole outcome alone.

Evaluation therefore includes both **the usefulness of selected existing assets** and **whether this human–AI method can produce useful new failure distinctions, control boundaries, or evaluation cases in a specific domain**. The latter is a prospective research question. Discovery of unknown failures, future inventions, comparative performance, and commercial usefulness are not guaranteed.

## Two kinds of friction, two sets of evidence

**For the person directing AI:** the intended benefit is less repeated explanation, source-level supervision, reconstruction after interruption, and cleanup. Owner-operated examples delegate investigation, repair, verification, evidence preservation, handoff, and routine cleanup to AI within a human-authorized scope. Short instructions rely on accumulated preparation and records; transferring a short prompt alone is not evidence of reproducibility. Total human effort, including setup and maintenance, has not been comparatively measured.

**For the maintainer receiving a contribution:** the intended benefit is a bounded change with a clear behavioral contract, relevant tests, explicit limitations, and manageable review scope. A minimal repair must be sufficient for the required behavior; a small diff alone is not enough. Checks for competing work, project acceptance policies, repairable boundaries, focused verification, review responses, and stopping when evidence is insufficient are part of the operating approach. Acceptance is observable. Maintainer time saved and review-cost reduction are **unmeasured**.

Control could accelerate work by preventing repeated explanation, misplaced repairs, unsupported completion, and expensive reconstruction. That is the mechanism proposed for evaluation, not a measured acceleration result.

## Memory that connects a failure to the next execution

One part of the proposed asset is **the operational connection between a distinction learned from a past failure and what a later AI execution investigates or verifies**. The knowledge-generation method above is also an object of evaluation; the fixed memory snapshot is not its full scope or proof of future discovery. For example, receiving a response and establishing the requested state are different conditions, as the Microsoft repair illustrates. The accumulated records preserve relevant conditions, evidence limits, verification results, and restart points.

The fixed evidence snapshot describes **22 Pattern Memory records**, a limited probe improvement on a **known failure**, and instances of another AI session resuming from saved records. The probe improvement was non-blind; ordinary investigation had already found the cause. It supports a traceable revision in inspection coverage, not additional discovery on unknown tasks or superiority over standard Codex. The underlying pattern texts, probes, instructions, and forensic records remain private.

In one owner-run **Trial 019** of cross-session evidence reconnection, a fresh AI without the original chat history received a fixed canonical snapshot and three entry records, but no selected Trial 017 result packet. It located that earlier trial's Gate, Owner, bounded technical result, and unresolved completion evidence without additional human explanation. Under the fixed eight-item assessment, safe judgments were **8/8 PASS** and evidence transfer was **6/8 PASS, 2/8 PARTIAL** (overall PARTIAL), with **zero navigation misses and judgment errors** in the assessed items. Both PARTIAL items reflect the same missing independent receipt for post-terminal remote read-back and cleanup; the recipient left final completion unconfirmed. The recipient self-reported **about two minutes and 12 tool calls**; timing and the full tool transcript were not independently verified. An earlier trial summary was visible in the entry records, and the recipient shared technical access to the same files, so this was not a fully blinded or isolated test. It does not establish operation in another company without Shin, an advantage over standard Codex, quantified labor savings, or full autonomy.

Saving experience, applying it later, and improving performance are different stages. Continuous improvement, a compounding performance effect, and cross-organization reuse remain unproven.

## Capability, deployment, and outcome

| Layer | What a buyer should establish | Present evidence / missing evidence |
| --- | --- | --- |
| **Capability** | Can the model or tool perform the behavior under suitable conditions? | The PRs show particular accepted repairs. They do not establish an incremental capability unavailable in existing agents or tools. |
| **Deployment** | Is that capability integrated into a repeatable workflow with authority, verification, memory, and responsible handoff? | Owner-operated delegation and resumption are recorded. Independent buyer installation, operation without Shin, integration effort, and support requirements remain unverified. |
| **Outcome** | Does use produce accepted, useful results at a justified total cost? | Selected third-party acceptance is public. Comparative success, human and maintainer burden reduction, total cost, and commercial return remain unmeasured. |

The operating knowledge was formed independently in an **OpenAI/Codex-centered environment**. Its transfer to Anthropic or other model ecosystems is an evaluation question, not a demonstrated result or an affiliation claim. Model access, runtime behavior, permissions, and buyer decision ownership would all need qualification.

## Beyond Value-Locked: a separate V5 patent application

Shin's **V5 Japanese patent application, 特願2025-248070 (JP2025-248070)**, is a separate example of problem framing and structural design: separating successful authentication from the person's safety, while considering privacy protection, confirmation by an authorized third party, and stop conditions. Potential applications include financial services, authentication, and assisted monitoring. These are possible application areas, not demonstrated deployments.

Shin reports a receipt record for a procedural amendment in **March 2026**; the latest legal procedural status has not been verified here. Patent grant, commercial deployment, performance, and effectiveness have not been established. No nonpublic claims or technical details are disclosed.

**V5 patent rights are excluded from every Value-Locked licensing or acquisition scope described here.** Any future V5 collaboration requires an independent agreement.

## Contributor research: breadth, not repair speed

An existing analysis used a pinned [AIDev-7.6M dataset](https://huggingface.co/datasets/hao-li/AIDev-7.6M/tree/37bbe1533e26cc1e1374917dba1186d1c8a4dc81) containing **7,685,281 PRs**. Under fixed qualification rules and an initial 52-day window, it reported a **provisional top-ten range for breadth across qualifying external organizations**. Shin's provisional activity window was compared separately after the dataset cutoff.

This is a conditional organization-breadth result, **not a worldwide repair-speed rank, skill leaderboard, coding-agent benchmark, or asset valuation**. Actual start dates and some qualifications remain unresolved. [Definitions, dates, counts, and limitations](RESEARCH_NOTE.md) retain these conditions. The full qualification audit has not been published here or independently reproduced; the dataset link alone does not reproduce the result.

## Strategic build versus acquire

The object of asset evaluation is selected accumulated operating knowledge and materials, with upstream ownership and attribution preserved. A prospective knowledge-generation partnership has a separately agreed research scope and is evaluated on its own terms. Compare against the **least costly credible alternative that meets your actual need**:

| Option | Costs and questions to include |
| --- | --- |
| Existing internal capability or public tools | Which behaviors already exist, and which are actually deployed? Can configuration, ordinary engineering, or public research close the gap? If so, an external purchase may add no value. |
| Internal reconstruction | Time to collect relevant failure experience, turn it into usable operating material, validate it prospectively, integrate it, and maintain it. Account for staff time and uncertainty; do not assume the owner's research duration equals your rebuild time. |
| Acquire or license selected assets | Evaluation and acquisition cost, rights clearance, adaptation, deployment, retained human judgment, support, and ongoing maintenance. Access to accumulated history could advance the start of a learning loop, but portability and incremental benefit need evidence. |
| Bounded research partnership | Whether a defined unresolved problem merits paid, time- and cost-limited work with Shin and AI. Agree the question, baseline, validation, deliverables, ownership, responsibilities, and stop conditions; a useful new distinction or positive result may not emerge. |
| Wait | Work or learning foregone before equivalent deployment, weighed against the value of better tools and information later. The cost of delay may be small or zero; no artificial urgency or quantified opportunity loss is asserted. |

Possible scopes to discuss, subject to technical fit and rights review:

| Form | What would need to be agreed |
| --- | --- |
| **Snapshot license** | A defined selection at a fixed version; permitted uses and rights; no assumption of future updates. |
| **License with updates** | Selection, update scope, cadence, validation, support, and continuing cost. Updates do not guarantee performance improvement. |
| **Limited asset acquisition** | Precisely selected transferable assets, retained and acquired rights, exclusions, and transition obligations. |
| **Whole-asset acquisition** | A separately defined Value-Locked transaction scope, rights chain, third-party exclusions, transfer readiness, and continuing dependence on Shin. This is not a blanket transfer of this evidence repository, upstream OSS, or V5 patent rights. |
| **Bounded Knowledge-Generation Partnership** | Paid collaboration for a specific problem domain, using Shin and AI's operating method to discover and verify new failure distinctions, control boundaries, or evaluation cases. Individually agree duration, cost ceiling, deliverables, intellectual-property ownership, confidentiality, stop conditions, and responsible parties. No discovery or outcome is guaranteed. |

Acquiring existing assets and commissioning future research are **separate transactions**; neither includes the other by default. V5 remains an independent asset. Non-exclusive licensing, limited exclusivity, and ownership transfer carry different future-use and opportunity costs. No form, scope, price, exclusivity, availability, or willingness to pay is established here. Value-Locked-specific purchase probability is unknown. Buyer-specific net value could be zero or negative after evaluation, integration, and operating costs.

## Questions for a technical leader or the buyer's AI

Evaluate **build, acquire, collaborate, and decline** on equal terms. Distinguish public verification, owner reports, inference, and unknowns; identify counterevidence rather than assuming uniqueness or a purchase case.

1. Can your existing models, agent harnesses, memory, tests, CI, and review practices produce comparable accepted results? Which examples are relevant to your actual need, and which are not?
2. Is the relevant capability already integrated into your current product or operation? What evidence demonstrates routine deployment rather than an isolated possibility?
3. Is there additional value in reducing the expertise, explanation, and checking burden required of the human operator or maintainer? Could the burden simply move elsewhere? What comparable measurement would distinguish these outcomes?
4. What would internal reconstruction require in research, implementation, prospective validation, integration, staff time, and ongoing cost? Could public material or a smaller internal change suffice?
5. How do acquisition now, internal deployment later, and waiting compare—including the timing of a learning loop, foregone useful work, uncertainty, and future tools? Under which conditions is waiting preferable?
6. Which selected existing asset, if any, warrants **paid technical evaluation**? Separately, is there an unresolved problem worth a bounded knowledge-generation partnership? What scope, baseline, unseen cases, validation, success and stop criteria, human involvement, and cost ceiling would make either decision testable?
7. Which portability, rights, confidentiality, support, and decision-owner gaps would prevent a snapshot license, updates, acquisition, or research partnership? For future work, who owns resulting knowledge and intellectual property, and who is responsible for each decision? What would falsify the proposed incremental value?
8. Who owns the technical decision and budget? What evidence would justify proceeding, rebuilding internally, declining, or stopping—and what remains unknown before any purchasing decision?

An AI assessment is advisory. It is not formal corporate technical acceptance, budget approval, purchasing intent, or a contract.

## Commercial technical evaluation

For **paid technical evaluation, licensing, asset acquisition, or bounded knowledge-generation partnership inquiries**, use [the contact section of Shin's existing public site](https://shin4141.github.io/#contact-title). A useful first inquiry identifies the technical need, existing capability, selected evaluation scope, and technical or budget owner. An initial assessment can use these public sources.

Access to separately controlled materials would require a separate agreement on scope, confidentiality, access, rights, and commercial terms. Enterprise transfer readiness, operation without Shin, comparative performance, human effort, maintainer burden, cross-model portability, and economic value remain evaluation matters. Value-Locked is not established as a finished fully autonomous product.

This page commits to no price, exclusive or transferable right, delivery date, performance level, labor-saving rate, cross-company or cross-model portability, future invention, or new unpaid proof of concept. Public contributions retain their upstream terms and prior attribution. These summaries grant no rights to unreleased implementation, Pattern Memory texts, probes, or internal operating materials.

## Publication boundary

The public tree contains only this README and `RESEARCH_NOTE.md`. Nonpublic code, private Pattern Memory contents, probe implementations, internal instructions, forensic materials, secrets, authentication information, personal contact details, and private Git history are excluded. Public research and PR links support verification; the existing contact-page link supports commercial routing.
