<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8A2BE2,100:00599C&height=225&section=header&text=TsyVM&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Reverse%20Engineer%20%C2%B7%20Binary%20Intelligence%20%C2%B7%20Native%20Systems%20Tooling&descAlignY=55&descSize=18"/>

<a href="https://github.com/TsyVM">
<img src="https://readme-typing-svg.demolab.com/?lines=A+laptop%2C+a+cat%2C+and+a+smoke.;Reverse+the+Binary.+Reconstruct+the+Architecture.;No+offset+ships+unless+it%27s+proven.&font=Fira%20Code&center=true&width=650&height=45&color=8A2BE2&vCenter=true&size=22&pause=1800"/>
</a>

<br/>

[![GitHub followers](https://img.shields.io/github/followers/TsyVM?label=Follow&style=for-the-badge&color=8A2BE2&logo=github)](https://github.com/TsyVM)
[![Team](https://img.shields.io/badge/Team-TeamVanilla-8A2BE2?style=for-the-badge)](https://www.teamvanilla.org/)
[![Location](https://img.shields.io/badge/Location-Florida%2C%20USA-00599C?style=for-the-badge)](#)
[![Profile Views](https://komarev.com/ghpvc/?username=TsyVM&style=for-the-badge&color=blueviolet)](https://github.com/TsyVM)

<br/>

[![C++23](https://img.shields.io/badge/C%2B%2B-23-00599C?style=flat-square&logo=cplusplus&logoColor=white)](https://en.cppreference.com/w/cpp/23)
[![C++20](https://img.shields.io/badge/C%2B%2B-20-00599C?style=flat-square&logo=cplusplus&logoColor=white)](https://en.cppreference.com/w/cpp/20)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=flat-square&logo=python&logoColor=white)](#)
[![PHP](https://img.shields.io/badge/PHP-Platform%20Engineering-777BB4?style=flat-square&logo=php&logoColor=white)](#)
[![DirectX9](https://img.shields.io/badge/DirectX-9%20%7C%20Shader%20Pipelines-107C10?style=flat-square)](#)
[![Windows](https://img.shields.io/badge/Windows-x86%20%7C%20x64-0078D6?style=flat-square&logo=windows&logoColor=white)](#)
[![Linux](https://img.shields.io/badge/Linux-supported-FCC624?style=flat-square&logo=linux&logoColor=black)](#)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](#)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 👋 About

I build tools that pull the truth out of compiled binaries. My work centers on **native reverse engineering and architecture recovery** — reconstructing class layouts, RTTI, vtables, and function addresses directly from Windows executables, then shipping that knowledge as verified SDKs, analysis platforms, encyclopedic references, and runtime tooling.

I'm part of **[TeamVanilla](https://www.github.com/TeamVanillaRND)** & [@TeamVanilla](https://www.x.com/@HomeOfVanilla), where I build both general-purpose reverse-engineering infrastructure and deep, engine-specific modding ecosystems for classic PC games — plus the graphics/shader research and hardened web platform work that supports them.

> **My rule:** nothing ships unless it's proven. Every offset, class, or address is either read straight from compiler-emitted metadata or corroborated against disassembled machine code. Unknowns get bounded, not guessed.

```yaml
🔍 Currently building: NiTools Suite — automated architecture recovery for compiled binaries
🧩 Also maintaining:    DonutsSDK, VanHooks, and modding tooling for two classic PC games
📚 Also writing:        engine-internals encyclopedias and a DX9/HLSL rendering reference series
💬 Ask me about:        RTTI recovery, VTable hooking, PE internals, mod loader architecture
🐈 Status:              I do not like GitHub. (...but here we are)
```

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=cpp,py,php,cmake,windows,linux,git,github&theme=dark" />

</div>

<br/>

| Area | Skills |
|---|---|
| **Reverse Engineering** | PE binary parsing · MSVC RTTI/COL recovery · vtable & member-offset recovery · disassembly-based verification · pattern & string-xref anchoring · packer & entropy diagnostics |
| **Binary Formats** | Chunk/container models · archive & VFS layouts · string hashing · compression codecs · audio/video containers · UI-layout & script vocabularies · save/config formats · byte-level toolcraft |
| **Systems Programming** | Runtime hooking (trampoline, IAT/PLT, VTable, mid-function) · DLL injection & proxying · RAII memory patching · process rebasing · non-destructive interception |
| **SDK Design** | Two-pillar (data vs. runtime) architecture · three-tier API surfaces · `Result<T>`/`std::expected` error models · header-only runtime · generated-from-data class DBs · `static_assert` invariants |
| **Diagnostic Tooling** | Static + dynamic analysis hosts · injected read-only inspection · drift detection against shipped catalogues · live-object scanning · no-toolchain reference implementations |
| **Modding Systems** | Loader architecture (ASI-style) · loose-file shadowing · menu/UI extension · engine-limit taxonomy · memory-pool mechanics · content pipelines |
| **Graphics / DirectX9** | Present hooks & overlays · device-reset handling · shader injection & HLSL authoring · deferred & forward+ rendering · render-target capture · post-processing pipelines |
| **Web Platforms** | PHP platform architecture · auth/OAuth · async jobs & scheduled tasks · REST API design · security hardening |
| **Engineering Style** | Exception-free, RAII-first C++ · zero-dependency & header-only libraries · plugin architectures · reproducible, provenance-tagged research |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🚀 Flagship Product

<div align="center">

### 🧠 [NiSuite (NiTools Suite)](https://github.com/TsyVM/NiSuite)
**Browser-based binary intelligence & architecture recovery platform**

[![Version](https://img.shields.io/badge/version-V2-8A2BE2?style=for-the-badge)](#)
[![Stars](https://img.shields.io/github/stars/TsyVM/NiSuite?style=for-the-badge&color=yellow)](https://github.com/TsyVM/NiSuite/stargazers)
[![TeamVanilla](https://img.shields.io/badge/by-TeamVanilla-8A2BE2?style=for-the-badge)](https://www.teamvanilla.org/)

*"Reverse the Binary. Reconstruct the Architecture."*

</div>

Most analysis tools stop at instructions, symbols, and control flow. NiSuite goes further — recovering the **higher-level architecture** compiled out of a binary (class hierarchies, RTTI, vtables, subsystem boundaries) and surfacing it as structured, actionable knowledge, so less time goes into rebuilding context and more into generating insight.

Built to sit alongside **Ghidra, IDA Pro, Binary Ninja, PE-bear, and Detect It Easy** — not a disassembler replacement, but the layer that turns their output into architecture.

<table>
<tr><td valign="top">

**📦 PE Structure**
- Header/section walk (DOS, COFF, optional)
- Rich header & compiler fingerprint
- Resources, debug directory, overlay data
- TLS callbacks, relocations, SEH tables

</td><td valign="top">

**🏛️ Reconstruction ★**
- Architecture & class-hierarchy recovery
- VTable analysis + slot mapping
- Struct/type/ctor-dtor recovery
- XRefs, per-finding confidence scoring

</td><td valign="top">

**🔬 Recovery eXtensions**
- MSVC/GCC demangling, name propagation
- Thunk, switch-table, lambda detection
- RTTI v2/CLI, `.pdata` unwind parsing
- Function fingerprints, offset verification

</td><td valign="top">

**⚙️ Code Analysis**
- Capstone disasm (x86/x64/ARM/MIPS, WASM)
- Pseudo-C decompiler, interactive CFG
- Signatures, stack frames, string xrefs
- In-browser script console

</td></tr>
<tr><td valign="top">

**🔎 Advanced RE**
- IAT rebuild, dynamic import discovery
- Full-binary call graph (Cytoscape/dagre)
- Anti-analysis & syscall-table detection
- Binary-level patch diffing, entropy analysis

</td><td valign="top">

**🛡️ Security**
- Consolidated risk scoring & capability summary
- YARA rule generation
- IOC extraction (network, registry, file paths)
- Packer identification & unpacking hints

</td><td valign="top">

**📊 Visualization**
- Byte-pair digram heatmap
- Hilbert-curve entropy map
- Function heatmaps & density views

</td><td valign="top">

**💾 Export & Utilities**
- JSON / YAML / SDB export
- Header/SDK, Frida hook, Ghidra export
- Runtime verification harness
- Cross-build diffing

</td></tr>
</table>

**Analyst Query** — a context-aware Q&A panel scoped to the loaded binary: once a file is analyzed, the full static-analysis result is embedded as context, so questions resolve against actual findings rather than generic reference material. Supports multi-turn follow-ups, quick prompts, and exportable sessions.

Ships with a **modular plugin architecture** — custom engine signatures, RTTI databases, class definitions, string intelligence, and security heuristics — for reverse engineers, malware analysts, security researchers, game modders, engine researchers, software archaeologists, and digital forensics analysts.

<div align="center">

**[➡️ Explore NiSuite](https://github.com/TsyVM/NiSuite)**

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🧩 Foundational Libraries

### 🪝 [VanHooks](https://github.com/TsyVM/VanHooks)
**Modern C++23 cross-platform function hooking library**

[![Stars](https://img.shields.io/github/stars/TsyVM/VanHooks?style=flat-square&color=yellow)](https://github.com/TsyVM/VanHooks/stargazers)
[![Release](https://img.shields.io/badge/release-v1.0.0-blue?style=flat-square)](https://github.com/TsyVM/VanHooks/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://github.com/TsyVM/VanHooks/blob/main/LICENSE)
![C++23](https://img.shields.io/badge/C%2B%2B-23-00599C?style=flat-square)
![Windows](https://img.shields.io/badge/Windows-x86%20%7C%20x64-0078D6?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-x64%20%7C%20ARM64-FCC624?style=flat-square)
![macOS](https://img.shields.io/badge/macOS-x64%20%7C%20ARM64-000000?style=flat-square)

The hooking engine that powers every mod loader in this portfolio — production-grade, `std::expected`-based, and genuinely competitive with (or ahead of) established libraries:

| | VanHooks | MinHook |
|---|:---:|:---:|
| **Platforms** | 🟢 Win/Linux/macOS | Win |
| **ARM64** | 🟢 ✓ | ✗ |
| **Hook types** | 🟢 Trampoline+IAT+PLT+VTable+Mid | Trampoline |
| **Error model** | 🟢 `std::expected` | C enum |
| **RAII lifetime** | 🟢 ✓ | ✗ |
| **Batch groups** | 🟢 ✓ | ✗ |

**➡️ [Explore VanHooks](https://github.com/TsyVM/VanHooks)**

### 🔎 [GameFunctionsRecoveryTools](https://github.com/TsyVM/GameFunctionsRecoveryTools)
**Universal struct/offset verifier — GUI desktop app**

[![Stars](https://img.shields.io/github/stars/TsyVM/GameFunctionsRecoveryTools?style=flat-square&color=yellow)](https://github.com/TsyVM/GameFunctionsRecoveryTools/stargazers)
![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=flat-square&logo=python&logoColor=white)
![Capstone](https://img.shields.io/badge/Disasm-Capstone-orange?style=flat-square)

Cross-checks claimed C++ struct layouts against a real compiled binary using a self-contained PE parser + RTTI recovery + disassembly corroboration. Verdicts sorted into `CONFIRMED` / `CONFLICT` / `NO_ANCHOR` / `ERROR` tiers, with entropy-based packer diagnostics and JSON/CSV/`.inl` export. Re-derives its own ground truth on every run and reports drift against previously shipped catalogues.

**➡️ [Explore GameFunctionsRecoveryTools](https://github.com/TsyVM/GameFunctionsRecoveryTools)**

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🎮 Game Reverse-Engineering Ecosystems

<details open>
<summary><h3 style="display:inline">🍩 The Simpsons: Hit & Run <i>(2003 · Radical/Pure3D Engine)</i></h3></summary>

The most complete ecosystem in the portfolio — analysis, SDK, encyclopedia, and end-user tooling working together end-to-end.

<table>
<tr>
<td width="50%" valign="top">

**📦 [DonutsSDK](https://github.com/TsyVM/DonutsSDK)**
[![Stars](https://img.shields.io/github/stars/TsyVM/DonutsSDK?style=flat-square&color=yellow)](https://github.com/TsyVM/DonutsSDK/stargazers)
![C++20](https://img.shields.io/badge/C%2B%2B-20-00599C?style=flat-square)
![MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)

Verified C++20 modding SDK.

![Classes](https://img.shields.io/badge/classes-1%2C207-blueviolet?style=flat-square)
![Relations](https://img.shields.io/badge/relations-3%2C924-blueviolet?style=flat-square)
![VTables](https://img.shields.io/badge/vtables-965%20verified-brightgreen?style=flat-square)
![Offsets](https://img.shields.io/badge/offsets-1%2C917-brightgreen?style=flat-square)

Every entry `static_assert`-enforced against RTTI extracted from the retail `shar.exe`. Three-tier API + native VanHooks integration.

</td>
<td width="50%" valign="top">

**🩻 [SAHRDiag](https://github.com/TsyVM/SAHRDiag)**
[![Stars](https://img.shields.io/github/stars/TsyVM/SAHRDiag?style=flat-square&color=yellow)](https://github.com/TsyVM/SAHRDiag/stargazers)
![C++](https://img.shields.io/badge/C%2B%2B-x86-00599C?style=flat-square)

Static + dynamic RTTI/COL analysis tool — no IDA, x64dbg, or Ghidra required.

Live heap scanning via DLL injection, with a no-compiler Python fallback for the static pass. Produced the ground-truth data behind DonutsSDK's 965 verified vtables.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🧰 [sahr-modloader](https://github.com/TsyVM/sahr-modloader)** *(+ legacy `old-sahr-modloader`)*
[![Stars](https://img.shields.io/github/stars/TsyVM/sahr-modloader?style=flat-square&color=yellow)](https://github.com/TsyVM/sahr-modloader/stargazers)
![CMake](https://img.shields.io/badge/build-CMake-064F8C?style=flat-square)

File-system hook-based mod loader built on VanHooks — numbered load priority, Safe Mode, crash-dump logging.

</td>
<td width="50%" valign="top">

**📚 [HnREncyclopedia](https://github.com/TsyVM/HnREncyclopedia)**

Reference documentation cataloguing recovered Hit & Run engine internals — the human-readable companion to DonutsSDK, organized as a hub with focused deep-dive chapters and confidence markers on every non-obvious claim.

</td>
</tr>
</table>

</details>

<details open>
<summary><h3 style="display:inline">🏁 Need for Speed: Most Wanted <i>(2005 · EA Black Box Engine)</i></h3></summary>

<table>
<tr>
<td width="50%" valign="top">

**🛠️ [nfsmw-modloader](https://github.com/TsyVM/nfsmw-modloader)**
[![Stars](https://img.shields.io/github/stars/TsyVM/nfsmw-modloader?style=flat-square&color=yellow)](https://github.com/TsyVM/nfsmw-modloader/stargazers)

Non-destructive runtime mod loader for `speed.exe` (US v1.3). Hooks texture uploads + `CreateFileA` to substitute textures and whole files entirely in memory — nothing on disk is touched.

</td>
<td width="50%" valign="top">

**🗺️ [nfsmw-rockport-editor](https://github.com/TsyVM/nfsmw-rockport-editor)**

World/level editor for the Rockport City open world.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📦 [MWSDK](https://github.com/TsyVM/MWSDK)**

Modding SDK for *Most Wanted*, applying the same RTTI-verification methodology as DonutsSDK to the Black Box engine.

</td>
<td width="50%" valign="top">

**📚 [MWEncyclopedia](https://github.com/TsyVM/MWEncyclopedia)**

Reference documentation of *Most Wanted* engine internals, alongside an in-progress DX9/HLSL rendering-architecture reference covering the engine's shader and deferred-lighting pipeline.

</td>
</tr>
</table>

</details>

> ℹ️ **"MW" = Need for Speed: Most Wanted** (2005), not The Elder Scrolls III: Morrowind.

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🧭 Design Philosophy

The methodology behind every project in this portfolio, distilled into a few rules I actually hold myself to:

- 🔬 **Evidence over assumption** — every claim is RTTI-derived or disassembly-corroborated. A value with no traceable source doesn't ship; it gets marked `Open` instead of guessed.
- ⚖️ **Two independent evidence bases** — on-disk data (parsed bytes, asset structure) and compiled code (RTTI, disassembly) are proven separately and cross-checked against each other. Agreement between the two is what makes a claim trustworthy.
- 📒 **An honest ledger** — every non-trivial deliverable tracks what's `Verified` ✅, what's `Reasoned` 🟡, and what's still `Open` ⏳, reported alongside the work instead of buried in it.
- 📏 **Measure before you change** — no blind tuning. Read the live state, classify what kind of limit or value you're looking at, then use the lever that actually matches it.
- 🔁 **If it isn't reproducible, it isn't done** — every finding ships as a tool or script that regenerates the same numbers on a fresh copy of the target, with a no-toolchain fallback where possible.
- 🔒 **Non-destructive by default** — analysis tooling is strictly read-only; mod loaders redirect assets in memory rather than touching the install.
- 🤝 **Responsible scope** — single-player/offline use only, no affiliation with original studios, no multiplayer-cheat intent, interoperability framing throughout.
- 🧑‍🔧 **Accessible builds** — every project ships a compiled/CMake path *and* a no-toolchain fallback, so results are reproducible even without the exact original tooling.

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 📈 GitHub Stats

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=TsyVM&theme=radical&hide_border=true&background=0D1117&ring=8A2BE2&fire=00599C&currStreakLabel=8A2BE2"/>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 📊 Repository Index

<div align="center">

| Project | Ecosystem | Type | Link |
|---|---|---|---|
| **NiSuite** | Generic | 🧠 Binary intelligence platform | [repo](https://github.com/TsyVM/NiSuite) |
| **VanHooks** | Generic | 🪝 Function hooking library | [repo](https://github.com/TsyVM/VanHooks) |
| **GameFunctionsRecoveryTools** | Generic | 🔎 Offset verification tool | [repo](https://github.com/TsyVM/GameFunctionsRecoveryTools) |
| **DonutsSDK** | Simpsons: Hit & Run | 📦 Modding SDK | [repo](https://github.com/TsyVM/DonutsSDK) |
| **SAHRDiag** | Simpsons: Hit & Run | 🩻 Binary analysis tool | [repo](https://github.com/TsyVM/SAHRDiag) |
| **sahr-modloader** | Simpsons: Hit & Run | 🧰 Mod loader | [repo](https://github.com/TsyVM/sahr-modloader) |
| **old-sahr-modloader** | Simpsons: Hit & Run | 🧰 Mod loader (legacy) | [repo](https://github.com/TsyVM/old-sahr-modloader) |
| **HnREncyclopedia** | Simpsons: Hit & Run | 📚 Reference docs | [repo](https://github.com/TsyVM/HnREncyclopedia) |
| **nfsmw-modloader** | NFS: Most Wanted | 🧰 Mod loader | [repo](https://github.com/TsyVM/nfsmw-modloader) |
| **nfsmw-rockport-editor** | NFS: Most Wanted | 🗺️ World/level editor | [repo](https://github.com/TsyVM/nfsmw-rockport-editor) |
| **MWSDK** | NFS: Most Wanted | 📦 Modding SDK | [repo](https://github.com/TsyVM/MWSDK) |
| **MWEncyclopedia** | NFS: Most Wanted | 📚 Reference docs | [repo](https://github.com/TsyVM/MWEncyclopedia) |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

</div>
<div align="center">

## 🍩 TeamVanilla

<a href="https://www.teamvanilla.org/">
<img src="https://img.shields.io/badge/TeamVanilla-Visit%20Website-8A2BE2?style=for-the-badge" alt="TeamVanilla"/>
</a>

**NiSuite** and the wider reverse-engineering methodology behind this portfolio are built and maintained under **TeamVanilla** — building tools for people who want to understand how software really works.

*"Reverse the Binary. Reconstruct the Architecture."*

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

<div align="center">

### 📫 Find me

[![GitHub](https://img.shields.io/badge/GitHub-TsyVM-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TsyVM)
[![TeamVanilla](https://img.shields.io/badge/TeamVanilla-Website-8A2BE2?style=for-the-badge)](https://www.teamvanilla.org/)

<sub>💭 "I do not like Github."</sub>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00599C,100:8A2BE2&height=100&section=footer"/>

</div>
