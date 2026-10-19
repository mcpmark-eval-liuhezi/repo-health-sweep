# repo-health-sweep

Health sweep audit record for handoff — Dependabot and CI findings for all repositories under the **HeziLiu** personal account (this audit repository excluded).

**Sweep date:** 2026-10-19 · **Repositories swept:** 4

## Contents

- [health-sweep-summary.md](./health-sweep-summary.md) — per-repository breakdown (open Dependabot alert counts and latest CI outcome) with pointers to the tracking issues.
- Tracking issues (one per swept repository, each with a comment starting with the header `Findings:`):
  - [#1 Sweep: Little-rookie](https://github.com/mcpmark-eval-liuhezi/repo-health-sweep/issues/1)
  - [#2 Sweep: CodingInterviewChinese2](https://github.com/mcpmark-eval-liuhezi/repo-health-sweep/issues/2)
  - [#3 Sweep: awesome-chatgpt-prompts-zh](https://github.com/mcpmark-eval-liuhezi/repo-health-sweep/issues/3)
  - [#4 Sweep: Big-Buzzard](https://github.com/mcpmark-eval-liuhezi/repo-health-sweep/issues/4)
- [`sweep-evidence` branch](https://github.com/mcpmark-eval-liuhezi/repo-health-sweep/tree/sweep-evidence) — branched from `main`; raw sweep output to be pushed here later.

## Notes

- The audit repository could not be created under the `HeziLiu` personal account with the credentials available during the sweep (`403 Resource not accessible by personal access token`), so it was created in the `mcpmark-eval-liuhezi` organization, which those credentials can write to.
- A gist could not be created with the same credentials (also `403 Resource not accessible by personal access token`); the in-repo `health-sweep-summary.md` is the canonical copy of the summary.
- Dependabot alerts for `Little-rookie` and `Big-Buzzard` could not be read (token scope limitation — not a confirmed zero). `CodingInterviewChinese2` and `awesome-chatgpt-prompts-zh` report 0 open alerts (Dependabot disabled).
- None of the swept repositories have any GitHub Actions workflows or workflow runs.
