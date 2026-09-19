<div align="center">

<img src="assets/banner.svg" alt="Chumaniac — capture, compile, verify. Local-first tooling for the agent skill supply chain." width="100%">
<img src="assets/hud.svg" alt="Pipeline active. Stack: rust, typescript, bwrap, sandbox-exec. Policy: fail-closed, offline, no keys." width="100%">

</div>

```console
$ whoami --verbose
  capture → compile → verify · the boring layer of the agent supply chain
  a skill you can't replay in a box and explain in a diff is just folklore

$ ls ~/projects
  skilltape   rust        capture a command → reviewable Skill → sandboxed replay → Receipt
  skillsync   typescript  offline provenance / compatibility / drift · never executes the skill
```

[![SkillTape](https://img.shields.io/badge/SkillTape-v0.1.0-DEA584?style=flat-square&logo=rust&logoColor=1a1206)](https://github.com/Chumaniac/skilltape)
[![CI](https://img.shields.io/github/actions/workflow/status/Chumaniac/skilltape/ci.yml?style=flat-square&label=CI&logo=githubactions&logoColor=white)](https://github.com/Chumaniac/skilltape/actions/workflows/ci.yml)
[![10 crates](https://img.shields.io/badge/crates-10-0b1220?style=flat-square)](https://github.com/Chumaniac/skilltape/tree/main/crates)
[![SkillSync](https://img.shields.io/npm/v/%40chumanic%2Fskillsync?style=flat-square&label=SkillSync%40npm&color=3178c6)](https://github.com/Chumaniac/skillsync)
[![LoopX](https://img.shields.io/badge/upstream-LoopX_--_4659_%C2%B7_4657_merged-5eead4?style=flat-square)](https://github.com/huangruiteng/loopx/pulls?q=is%3Apr+author%3AChumaniac)

```console
$ telemetry --public
  repos 4 · PRs 15 opened / 15 merged · commits 275 · releases v0.1.0 + v0.1.2
  targets linux-gnu · darwin x86_64/aarch64 · windows-msvc · gates CodeQL + Dependabot
```

<img src="assets/lang.svg" alt="Language distribution by bytes: TypeScript 51.9%, Rust 42.3%, Python 2.7%, CSS 1.2%, Shell 0.8%, PowerShell 0.7%, other 0.3%." width="100%">
