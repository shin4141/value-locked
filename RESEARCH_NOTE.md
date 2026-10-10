# Contributor research note

**Evidence snapshot: 2026-10-10.**

This note summarizes an existing evidence extraction. It is not a new experiment or an independent reproduction of the contributor audit. It documents the conditions attached to the research statement in the [README](README.md).

## Dataset and comparison units

| Item | Definition or value from the existing extraction |
| --- | --- |
| Public source | [hao-li/AIDev-7.6M, pinned revision](https://huggingface.co/datasets/hao-li/AIDev-7.6M/tree/37bbe1533e26cc1e1374917dba1186d1c8a4dc81) |
| Revision | `37bbe1533e26cc1e1374917dba1186d1c8a4dc81` |
| Dataset size | 7,685,281 pull requests; this is a PR count, not a contributor count |
| PR creation dates in the extraction | 2024-12-24 through 2026-03-31 UTC |
| Fixed 12-month comparison window | [2025-04-01, 2026-04-01) UTC |
| Units eligible for the 12-month comparison | 399,314 developer units |
| Units with a complete initial 52-day window | 268,990 developer units |
| Initial-window definition | Day 0 through Day 51, using the UTC date of the first observed AI-related PR as Day 0 |
| Shin's provisional separate window | [2026-08-14, 2026-10-05) UTC |
| Shin's actual AI-assisted activity start | Unknown |

Developer units were based on stable GitHub author identities, with confirmed alternate accounts combined. The study excluded known bots and shared accounts, self-controlled projects, forks, and other ineligible cases under its fixed rules. Employment, affiliation, and control relationships were not exhaustively resolved.

Not every PR in the dataset belongs to the fixed 12-month window. The two developer-unit counts describe different eligible comparison sets and should not be substituted for the total PR count.

## What organization breadth means

A qualifying contribution required a substantive code change merged directly into external, non-fork OSS, public human-maintainer acceptance, and a fixed organization-category qualification. Documentation-only, dependency-only, and formatting-only changes were outside that definition. A distinct organization was counted once using its stable GitHub organization identity.

The extraction reported **nine qualifying organizations confirmed** for Shin and **14 additional organizations unresolved**. Its conditional result supports the conservative outward description used in the README: a **provisional top-ten range for qualifying organization breadth under the specified 52-day rules**.

The qualification uncertainty is not a statistical confidence interval. A population-wide percentile is unknown. Shin's activity window is provisional and occurs after the dataset cutoff, so this is a separate-period comparison, not a simultaneous global leaderboard.

## What the result does not measure

The result does not measure:

- Time spent investigating or repairing a task.
- Time from the actual start of work to a merge.
- Equivalent repair difficulty or review depth.
- Global engineering skill or coding-agent performance.
- The incremental effect of Value-Locked versus a baseline.
- Commercial demand, revenue, labor savings, or a transfer price.

Unobserved or nonpublic PRs, unidentified accounts, organization changes, unresolved affiliation/control, and the actual start date limit the comparison.

## Verification boundary

The public dataset reference identifies the source and revision. The linked upstream PRs in the README identify particular accepted contributions.

The complete qualification audit and its implementation are not published here. The dataset link alone therefore does not independently reproduce the reported qualification result. A prospective evaluator should distinguish the public source, the owner's reported analysis, and any later independent verification.

No claim of peer review, an independent certification, or a repair-speed world rank is made.
