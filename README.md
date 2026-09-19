<div align="center">

<img src="assets/banner.svg" alt="Chumaniac — capture, compile, verify. Local-first tooling for the agent skill supply chain." width="100%">

<br>

[![Rust](https://img.shields.io/badge/rust-10_crates-DEA584?style=flat-square&logo=rust&logoColor=1a1206)](https://github.com/Chumaniac/skilltape/tree/main/crates)
[![TypeScript](https://img.shields.io/badge/typescript-strict-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/Chumaniac/skillsync)
[![Fail closed](https://img.shields.io/badge/fallback-fail--closed-0b1220?style=flat-square&labelColor=4c1d24&color=f2616b)](https://github.com/Chumaniac/skilltape#what-works-today)

</div>

## ▘ `whoami`

```text
chumaniac@local ~$ whoami --verbose
```

I build the boring, load-bearing layer of the agent ecosystem: **capture, provenance,
sandboxed replay, verification receipts**. A skill that can't be replayed in a box and
explained in a diff is just folklore.

- **Reviewable artifacts over vibes** — every run leaves a Receipt someone can read.
- **Fail closed** — no restricted executor, no claim: Replay and Verify refuse to pretend.
- **Local-first** — no account, no API key, no model provider in front of the first result.

## ▛ Projects

| | | |
|---|---|---|
| [**SkillTape**](https://github.com/Chumaniac/skilltape) | Rust · Beta | Capture a command you already run → compile a reviewable Agent Skill → replay it in an isolated sandbox → get a Receipt. `bwrap` / `sandbox-exec`, 10 crates, checksummed release assets. |
| [**SkillSync**](https://github.com/Chumaniac/skillsync) | TypeScript · MIT | Offline verification for a local Skill: provenance, target compatibility, drift — `verify · scan · compat · diff · fix · report`. Never executes the Skill, never reads credentials. |

[![SkillTape release](https://img.shields.io/github/v/release/Chumaniac/skilltape?style=flat-square&label=skilltape&color=dea584)](https://github.com/Chumaniac/skilltape/releases/tag/v0.1.0)
[![SkillTape CI](https://img.shields.io/github/actions/workflow/status/Chumaniac/skilltape/ci.yml?style=flat-square&label=CI&logo=githubactions&logoColor=white)](https://github.com/Chumaniac/skilltape/actions/workflows/ci.yml)
[![SkillSync on npm](https://img.shields.io/npm/v/%40chumanic%2Fskillsync?style=flat-square&label=%40chumanic%2Fskillsync&color=3178c6)](https://www.npmjs.com/package/@chumanic/skillsync)

## ▜ Upstream

[**huangruiteng/LoopX**](https://github.com/huangruiteng/loopx) — long-horizon agent control
plane (~5.9k stars), with an itemized contributor task board, so each change starts from a
claimed `[Task]` issue.

| PR | Scope | Merged |
|---|---|---|
| [#4659](https://github.com/huangruiteng/loopx/pull/4659) | `refactor(cli)`: move the `update` command into its own module — `support_control.py` 898 → 772 lines | 2026-09-17 |
| [#4657](https://github.com/huangruiteng/loopx/pull/4657) | `docs(catalog)`: IP-035 — *install ownership is not an update permission* | 2026-09-17 |

## ▞ Instrument panel

Snapshot as of **2026-09-19**, from the GitHub API — public repos only.

```text
repos (public) ......... 4        commits (default branch) ... 275
PRs opened ............. 15       PRs merged ................. 15  (100%)
releases ............... SkillTape v0.1.0 · SkillSync v0.1.2
targets shipped ........ linux-gnu · apple-darwin (x86_64 + aarch64) · windows-msvc
gates in CI ............ CI · Release · skill-verify · CodeQL · Dependabot · Docker runner
```

<img src="assets/lang.svg" alt="Language distribution across public repositories by bytes: TypeScript 51.9%, Rust 42.3%, Python 2.7%, CSS 1.2%, Shell 0.8%, PowerShell 0.7%, other 0.3%." width="100%">

<div align="center">

*exit 0 — no credentials, no model calls, no network required to reproduce the receipts.*

</div>
