<div align="center">

<img src="nisuite-logo.png" alt="NiTools Suite" width="440">

[![Version](https://img.shields.io/badge/version-V2-8A2BE2?style=for-the-badge)](#)
[![Platform](https://img.shields.io/badge/platform-browser--based-8A2BE2?style=for-the-badge)](#what-is-nitools-suite)
[![Architecture](https://img.shields.io/badge/architecture-plugin--based-00599C?style=for-the-badge)](#plugin-architecture)
[![TeamVanilla](https://img.shields.io/badge/by-TeamVanilla-8A2BE2?style=for-the-badge)](https://www.teamvanilla.org/)

<br/>

[![PE Parsing](https://img.shields.io/badge/PE-parsing%20%2B%20intelligence-brightgreen?style=flat-square)](#pe-structure)
[![RTTI](https://img.shields.io/badge/RTTI-v2%20%2F%20CLI%20recovery-blueviolet?style=flat-square)](#reconstruction)
[![VTables](https://img.shields.io/badge/vtables-recovery%20engine-brightgreen?style=flat-square)](#reconstruction)
[![Disasm](https://img.shields.io/badge/disasm-Capstone%20x86%2Fx64%2FARM%2FMIPS-orange?style=flat-square)](#code-analysis)
[![Security](https://img.shields.io/badge/security-MITRE%20ATT%26CK%20mapped-red?style=flat-square)](#security)
[![Export](https://img.shields.io/badge/export-JSON%20%7C%20YAML%20%7C%20SDB-3776AB?style=flat-square)](#export--utilities)
[![Ecosystem](https://img.shields.io/badge/ecosystem-Ghidra%20%7C%20IDA%20%7C%20Binja-00599C?style=flat-square)](#how-nitools-fits-into-the-ecosystem)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 📖 What is NiTools Suite?

**NiTools Suite** is a browser-based reverse engineering and binary analysis platform designed to recover meaningful information from compiled software.

Most analysis tools stop at presenting instructions, symbols, and control flow. **NiTools focuses on discovering the higher-level architecture hidden within a binary** — and surfacing it as structured, actionable knowledge.

> **The philosophy:** reverse engineers should spend less time rebuilding context and more time generating insight.

**V2** significantly expands the platform with a second reconstruction tier (Recovery eXtensions), an integrated Capstone WASM disassembly engine with x86/x64/ARM/MIPS support, an Analyst Query panel for contextual binary interrogation, and a broad set of new analysis modules across every section of the tool.

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🧭 Module Groups

NiTools V2 organizes its capabilities into nine module groups accessible from the sidebar.

---

### 🎯 Core Analysis

Entry-point modules, available the moment a binary is loaded.

| Module | Description |
|---|---|
| Overview | Binary summary dashboard — stats, threat level, compiler, key findings |
| File Information | SHA hashes, timestamps, size, entropy overview, VirusTotal pivot links |
| Hex Viewer | Raw byte-level view of the loaded binary |
| Analyst Notes | Persistent per-session markdown notes attached to the current binary |

---

### 🏛️ Reconstruction ★

The primary architecture recovery tier. Reconstructs the high-level structure compiled out of the binary.

| Module | Description |
|---|---|
| Architecture Recovery | Full structural recovery — subsystems, class relationships, ownership patterns |
| Class Hierarchy | Inheritance tree reconstruction from binary evidence |
| VTable Analysis | Virtual dispatch table recovery and slot mapping |
| Structure Recovery | Struct and class memory layout reconstruction |
| Type Recovery | Compiler type information recovery |
| Ctor/Dtor Recovery | Object lifecycle function identification |
| Serialization Recovery | Detection and recovery of serialization patterns |
| Cross-References | XRef resolution across the full binary |
| RE Toolkit | Integrated reverse engineering utilities — header gen, SDK output, Frida hook gen, Ghidra export |
| Game Model | Game engine subsystem and entity model recovery |
| Provenance & Confidence | Per-finding confidence scoring and source attribution |

---

### 🔬 Recovery eXtensions

A second reconstruction tier added in V2, targeting finer-grained binary artifacts.

| Module | Description |
|---|---|
| Symbol Demangler | MSVC and GCC/Clang name demangling |
| Name Propagator | Propagate recovered names across the binary |
| Getter/Setter Map | Accessor pattern detection and mapping |
| Thunk Resolver | Identify and resolve thunk trampolines |
| Stack Strings | Recover strings assembled at runtime on the stack |
| Switch Tables | Detect and recover jump table structures |
| Lambda Detector | Identify compiler-generated lambda and closure objects |
| Class Size Estimator | Infer class sizes from allocation and constructor evidence |
| Function Heatmap | Cross-reference density and call frequency heatmap |
| Middleware Hub | Detect embedded middleware, libraries, and SDKs |
| COMDAT Folding | Identify folded identical functions (ICF) |
| Function Fingerprints | Structural function signatures for matching across builds |
| RTTI v2 / CLI | Extended RTTI reconstruction with CLI output |
| Offset Verifier | Validate recovered struct offsets against binary evidence |
| .pdata Unwind | Parse x64 exception unwind records |
| Engine Dictionary | Known engine pattern and symbol reference library |

---

### ⚙️ Code Analysis

Static analysis of code structure and behaviour.

| Module | Description |
|---|---|
| Strings | String extraction with categorization and pattern tagging |
| Import Table | Full import resolution with API categorization |
| Export Table | Export enumeration and symbol mapping |
| Disassembly | Capstone-powered disassembly engine — x86/x64/ARM/MIPS (WASM, Defcon 2026) |
| Decompiler | Pseudo-C output for recovered functions |
| Control Flow Graph | Interactive CFG visualization per function |
| Function Map | Full function inventory with role classification |
| Signatures | Byte-pattern signature matching across the binary |
| Stack Frames | Stack layout recovery per function |
| String X-Refs | Cross-reference strings back to owning code |
| Script Console | In-browser scripting against the live analysis state |

---

### 📦 PE Structure

Deep inspection of the Portable Executable format.

| Module | Description |
|---|---|
| Headers & Sections | Full PE header walk — DOS, COFF, optional, section table |
| Rich Header | Compiler and toolchain fingerprint recovery |
| Resources | Embedded resource enumeration and extraction |
| Debug Directory | PDB paths, CodeView records, debug metadata |
| Overlay Data | Data appended past the PE image boundary |
| TLS Callbacks | Pre-`main` execution hook detection |
| Relocations | Base-relocation record analysis |
| Exception Handlers | SEH and x64 exception handler table recovery |

---

### 🔎 Advanced RE

Behavioural analysis and deeper reverse engineering modules.

| Module | Description |
|---|---|
| Dynamic Imports | Runtime-resolved import discovery |
| IAT Rebuild | Import Address Table reconstruction |
| Protocol Analysis | Embedded protocol and data format detection |
| Call Graph | Interactive full-binary call graph (Cytoscape/dagre) |
| Loop Detection | Loop structure identification and classification |
| Syscall Table | Direct syscall enumeration and mapping |
| Anti-Analysis | Anti-debug, anti-sandbox, and evasion detection |
| Patch Differ | Binary-level diff between two builds |
| Entropy Analyzer | Per-section entropy histogram with Chart.js |

---

### 🛡️ Security

Threat assessment, detection engineering, and IOC production.

| Module | Description |
|---|---|
| Security Hub | Consolidated threat findings, risk scoring, and capability summary |
| YARA Generator | Auto-generate YARA rules from binary features |
| IOC Extractor | Surface network indicators, registry keys, file paths, and hashes |
| Unpacker Hints | Packer identification and unpacking guidance |

---

### 📊 Visualization

Binary structure rendered as visual maps.

| Module | Description |
|---|---|
| Byte-Pair Digram | 256×256 byte transition heatmap |
| Hilbert Entropy Map | Space-filling entropy visualization of the full binary |

---

### 💾 Export & Utilities

Analysis output and round-trip tooling.

| Module | Description |
|---|---|
| Export Analysis | Export the current analysis state as JSON |
| Multi-Format Export | Export to JSON, YAML, and SDB simultaneously |
| Runtime Harness | Dynamic verification harness for recovered offsets and structures |
| Build Diff | Compare analysis results across builds |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🖥️ Analyst Query

V2 includes an integrated **Analyst Query** panel that accepts natural-language questions about the currently loaded binary. The panel is context-aware — when a binary is loaded, the full static analysis result is embedded in the query context, allowing questions to be answered against real findings rather than general knowledge.

The panel supports multi-turn conversation, one-click quick prompts, per-message copy, and chat export. When no binary is loaded, it operates as a general reverse engineering reference.

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## ⚙️ Technical Stack

| Component | Library |
|---|---|
| CFG / Call Graph / Class Hierarchy | D3 v7.9 |
| Entropy histogram, byte-pair digram | Chart.js 4.4 |
| Overlay / section decompress | fflate 0.8 |
| Syntax-highlighted disasm / decompiler | Prism 1.29 |
| Analyst Notes markdown | Marked 12 + DOMPurify 3.2 |
| Keyboard shortcuts | hotkeys-js 3.13 |
| Drag-reorder plugin packs | Sortable 1.15 |
| Call graph layout engine | Cytoscape 3.30 |
| Utilities | lodash 4.17 |
| Disassembly engine (x86/x64/ARM/MIPS) | Capstone.js 5.0.9 (WASM) |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## ⚖️ How NiTools Fits Into The Ecosystem

NiTools isn't a replacement for your disassembler — it's the layer that turns its output into architecture.

| Tool | Their strength | Where NiTools complements |
|---|---|---|
| **Ghidra** | Interactive disassembly, decompilation, scripting | Automated architecture recovery, RTTI discovery, VTable analysis, class relationship reconstruction, subsystem discovery |
| **IDA Pro** | Deep manual analysis, industry standard | Automated knowledge extraction, architecture reconstruction, rapid binary triage |
| **Binary Ninja** | Intermediate-language workflows | Structural recovery, system identification, runtime architecture discovery, class hierarchy reconstruction |
| **PE-bear** | PE inspection | Architecture recovery, RTTI discovery, subsystem analysis, binary intelligence |
| **Detect It Easy (DIE)** | Packer ID, compiler detection, fingerprinting | Architecture recovery, security intelligence, class reconstruction, engine research |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🧩 Plugin Architecture

NiTools includes a modular plugin architecture allowing custom:

- 🔧 Engine Signatures
- 🏛️ RTTI Databases
- 📦 Class Definitions
- 🔤 String Intelligence
- 🛡️ Security Heuristics
- 🎯 Pattern Recognition Rules
- 🧪 Research Workflows

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🎯 Designed For

<div align="center">

| | | |
|:--:|:--:|:--:|
| 🔍 Reverse Engineers | 🦠 Malware Analysts | 🛡️ Security Researchers |
| 🎮 Game Modders | ⚙️ Engine Researchers | 🏺 Software Archaeologists |
| 💻 Systems Developers | 🔬 Digital Forensics Analysts | |

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🌱 Philosophy

**Recover Knowledge** — software contains architecture; the challenge is extracting it.

**Explain Structure** — names, ownership, inheritance, and subsystem boundaries matter.

**Accelerate Research** — researchers should spend less time rebuilding context and more time generating insight.

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🔭 Vision

To build one of the most capable architecture recovery and binary intelligence platforms available.

Not simply a disassembler. Not simply a PE parser. Not simply another static analysis engine.

**A platform for recovering and understanding software architecture.**

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

<div align="center">

## ☕ TeamVanilla

<a href="https://www.teamvanilla.org/">
<img src="https://img.shields.io/badge/TeamVanilla-Visit%20Website-8A2BE2?style=for-the-badge" alt="TeamVanilla"/>
</a>

Created and maintained by **TeamVanilla** — building tools for people who want to understand how software really works.

*"Reverse the Binary. Reconstruct the Architecture."*

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00599C,100:8A2BE2&height=100&section=footer"/>
