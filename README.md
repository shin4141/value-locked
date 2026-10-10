# Value-Locked

Value-Locked is an operational approach for carrying distinctions learned from past failures into later AI-assisted investigation, repair, and verification.

This repository presents public evidence, a research summary, and questions for commercial technical evaluation. Implementation assets and working records remain separately controlled. This is a documentation repository, not a release of the core implementation.

Maintained by **Shin ([shin4141](https://github.com/shin4141))**.

## Principle

A failure can expose a distinction that a later AI execution should preserve: for example, an operation returning a response versus the requested state actually being established.

Value-Locked's proposed distinctive capability is the operational connection between a lesson from an earlier failure and what a later AI execution investigates or verifies. It is a claim about how knowledge is carried into work, not a claim that a new model, memory architecture, or fully autonomous product has been built.

In owner-operated work, this includes:

- Recording the distinction exposed by a failure, its relevant conditions, and the limits of the evidence.
- Supplying that knowledge as context for later AI-assisted work.
- Checking outcomes against the required behavior rather than relying on a completion message alone.
- Preserving enough verification and progress information for another AI session to resume within a human-defined scope.

These are operating characteristics observed in the owner's workflow. Their portability and incremental benefit in another organization remain unproven.

## Public repair evidence

The following contributions by `shin4141` were merged upstream. The links provide the public change, review, and acceptance history.

| Public contribution | What the accepted change addresses | Scope of the evidence |
| --- | --- | --- |
| [Apple Swift OpenAPI Generator PR #939](https://github.com/apple/swift-openapi-generator/pull/939) | Reports duplicate generated schema names before a dictionary-construction crash. | An accepted contribution continuing prior repair work and review direction. It does not establish original discovery or sole authorship. |
| [Microsoft Power Platform Terraform Provider PR #1254](https://github.com/microsoft/terraform-provider-power-platform/pull/1254) | Rechecks requested remote state after HTTP 409 and uses bounded retries when state has not converged. | A repair to the specified managed-environment and enterprise-policy paths. |
| [Toyota Connected emb_cli PR #240](https://github.com/toyota-connected/emb_cli/pull/240) | Batches `chmod` calls while preserving repeated-destination order, argument bounds, and failure propagation. | Fewer process invocations in the tested cases; no measured end-to-end wall-clock speedup is claimed. |

Upstream acceptance demonstrates acceptance of these particular code changes. It does not establish an endorsement, employment relationship, partnership, commercial purchase, or a causal performance advantage attributable to Value-Locked. The original reports, prior contributors, and upstream licenses remain relevant.

## Research context

An existing contributor study used a pinned version of the public [AIDev-7.6M dataset](https://huggingface.co/datasets/hao-li/AIDev-7.6M/tree/37bbe1533e26cc1e1374917dba1186d1c8a4dc81), containing **7,685,281 pull requests**.

Under fixed qualification rules and an initial 52-day comparison window, the existing analysis reported a **provisional top-ten range for breadth across qualifying external organizations**. Shin was compared separately, using a provisional activity window after the dataset's collection cutoff.

This is a conditional organization-breadth result. It is **not a repair-speed ranking, a worldwide skill ranking, or a coding-agent benchmark**. Actual start dates and some qualification decisions remain unresolved. It also does not measure the commercial value of the assets.

[Research definitions, dates, and limitations](RESEARCH_NOTE.md) distinguish the dataset size, eligible comparison units, provisional window, and unresolved qualifications. This repository publishes a summary of the existing extraction; the complete underlying audit has not been released here or independently reproduced.

## Learning and restart evidence

Owner-maintained records describe **22 failure-pattern records**, a limited improvement to a probe for a **known failure**, and instances of another AI session resuming work from saved records.

The known-failure improvement was not a blind test on an unknown target. It does not establish a general discovery-rate improvement or an advantage over ordinary coding-agent investigation. The underlying pattern texts, probes, instructions, and forensic records are not published in this repository.

## What remains unproven

The available evidence does not establish:

- Superior performance to standard Codex or other coding-agent workflows.
- A finished product that operates fully autonomously.
- A quantified reduction in labor cost, intervention count, or total delivery time.
- Independent operation in another company's environment without Shin.
- General improvement from the failure-pattern records across unknown tasks.
- Enterprise deployment, integration effort, support requirements, or transfer readiness.
- A proven acquisition value, purchase probability, or buyer willingness to pay.

Accepted repairs, owner-observed reuse, controlled comparative performance, independent deployment, and commercial demand are different kinds of evidence.

## Questions for a technical team or its AI reviewer

Use the public material without assuming that Value-Locked is superior, unique in the market, or worth purchasing.

1. Which, if any, of the demonstrated repair behaviors matter to your actual engineering work? What relevant needs are not represented by these examples?
2. Which behaviors are already covered by your products, agent harnesses, project memory, tests, CI, or review practices? What evidence would establish an incremental difference?
3. Could public documentation, existing open-source tools, or internal engineering close the same gap? How would the time, uncertainty, and maintenance costs compare with evaluating or acquiring external assets?
4. Which technical claims can be checked from the public PRs, and which rely on the owner's account? What missing evidence or counterexample would change your assessment?
5. What would a fair comparison require: tasks, baseline, environment, success criteria, human involvement, costs, and failure cases? Would a narrower evaluation be enough?
6. What economic value, if any, could an incremental capability have after accounting for evaluation, integration, human review, maintenance, and licensing costs? Could the net benefit be zero or negative?
7. Which rights, confidentiality boundaries, and support obligations would matter for a non-exclusive license, a limited exclusive license, or an asset acquisition?
8. Who would own a technical evaluation and its budget? What evidence would justify progressing, declining, or stopping?

An AI review is advisory. It is not a company's formal technical acceptance, budget approval, purchasing intent, or contract.

## Commercial technical evaluation

For **commercial evaluation, licensing, or technical partnership inquiries**, use [the contact section of Shin's existing public site](https://shin4141.github.io/#contact-title). Please identify Value-Locked and the technical need or evaluation scope you have in mind.

Any review of separately controlled materials would require a separately agreed scope, confidentiality, access, rights, and commercial terms. This page does not commit to a price, an exclusive or transferable right, a delivery date, a performance level, or new unpaid proof-of-concept work.

Public OSS contributions remain governed by their upstream terms. Publishing these summaries does not grant rights to the unreleased implementation, pattern texts, private probes, or internal operating materials.

## Publication boundary

This repository contains only the README and a research-summary note. It excludes nonpublic code, pattern-record contents, private probes, internal instructions, forensic files, secrets, and personal contact details. Public source links and the commercial contact-page link are provided for verification and routing.
