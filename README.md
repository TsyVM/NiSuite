<div align="center">

<img src="nitools-logo.png" alt="NiTools Suite" width="440">

[![Capabilities](https://img.shields.io/badge/capabilities-5%20cores-8A2BE2?style=for-the-badge)](#-core-capabilities)
[![Platform](https://img.shields.io/badge/platform-browser--based-8A2BE2?style=for-the-badge)](#what-is-nitools-suite)
[![Plugins](https://img.shields.io/badge/architecture-plugin--based-00599C?style=for-the-badge)](#plugin-architecture)
[![TeamVanilla](https://img.shields.io/badge/by-TeamVanilla-8A2BE2?style=for-the-badge)](https://www.teamvanilla.org/)

<br/>

[![PE Parsing](https://img.shields.io/badge/PE-parsing%20%2B%20intelligence-brightgreen?style=flat-square)](#binary-analysis)
[![RTTI](https://img.shields.io/badge/RTTI-class%20recovery-blueviolet?style=flat-square)](#architecture-recovery)
[![VTables](https://img.shields.io/badge/vtables-recovery%20engine-brightgreen?style=flat-square)](#reverse-engineering)
[![Security](https://img.shields.io/badge/security-MITRE%20ATT%26CK%20mapped-red?style=flat-square)](#security-analysis)
[![SDKGen](https://img.shields.io/badge/output-headers%20%2B%20SDKs-3776AB?style=flat-square)](#research-tooling)
[![Ecosystem](https://img.shields.io/badge/ecosystem-Ghidra%20%7C%20IDA%20%7C%20Binja-00599C?style=flat-square)](#how-nitools-fits-into-the-ecosystem)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 📖 What is NiTools Suite?

**NiTools Suite** is a browser-based reverse engineering and binary analysis platform designed to recover meaningful information from compiled software.

Most analysis tools stop at presenting instructions, symbols, and control flow. **NiTools focuses on discovering the higher-level architecture hidden within a binary.**

> **The philosophy:** reverse engineers should spend less time rebuilding context and more time generating insight.

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00599C&height=3&section=header"/>

## 🧭 Core Capabilities

> Five pillars, each deep enough to stand on its own — together they turn a binary into an architecture report.

### 🧩 Binary Analysis

| Feature | Description |
|---|---|
| PE Parsing | Full Portable Executable structural walk |
| Import / Export Analysis | Resolve dependencies and surface exposed symbols |
| Resource Inspection | Enumerate and extract embedded resources |
| Relocation Analysis | Map base-relocation records |
| TLS Callback Detection | Surface pre-`main` execution hooks |
| Rich Header Analysis | Recover compiler/toolchain fingerprints |
| Overlay Detection | Find data appended past the PE image |
| Section Intelligence | Characterize sections by entropy, permissions, and role |
| Compiler Fingerprinting | Identify the toolchain that produced the binary |

### 🏛️ Architecture Recovery

| Feature | Description |
|---|---|
| Class Hierarchies | Reconstruct inheritance from binary evidence |
| RTTI Structures | Parse compiler-emitted type information |
| VTables | Recover virtual dispatch tables |
| Constructors / Destructors | Identify object lifecycle functions |
| Object Relationships | Map ownership and composition |
| Engine Subsystems | Identify functional subsystem boundaries |
| Runtime Ownership Patterns | Trace who owns what, and when |
| Cross-Module Relationships | Follow architecture across module boundaries |

### 🔍 Reverse Engineering

| Feature | Description |
|---|---|
| VTable Recovery | Virtual table reconstruction |
| RTTI Reconstruction | Rebuild type descriptors from raw bytes |
| Class Recovery | Full class definition reconstruction |
| Function Classification | Categorize functions by role and behavior |
| Structure Recovery | Recover struct/class memory layouts |
| String Intelligence | Correlate strings with owning code |
| Cross-Reference Analysis | Trace usage across the binary |
| Call Graph Exploration | Visualize and navigate call relationships |
| Engine Pattern Recognition | Detect known engine architectures automatically |

### 🛡️ Security Analysis

| Feature | Description |
|---|---|
| Entropy Analysis | Flag packed or encrypted regions |
| Packer Detection | Identify known packers and protectors |
| Capability Detection | Surface what a binary is capable of doing |
| Threat API Discovery | Flag suspicious API usage |
| MITRE ATT&CK Mapping | Map behaviors to the ATT&CK framework |
| Suspicious Behavior Detection | Heuristic flagging of risky patterns |
| Timestamp Forensics | Analyze compile-time and header timestamps |
| Network Indicator Discovery | Surface embedded network artifacts |
| Heuristic Risk Assessment | Score overall binary risk |
| YARA Rule Generation | Auto-generate detection rules |

### 🧪 Research Tooling

| Feature | Description |
|---|---|
| C++ Header Generation | Emit usable headers from recovered classes |
| SDK Generation | Produce ready-to-use SDKs |
| Ghidra Export Support | Round-trip findings into Ghidra |
| Frida Hook Generation | Auto-generate instrumentation hooks |
| Architecture Reports | Human-readable summaries of recovered structure |
| Plugin Packs | Bundle and share research |
| Custom Signatures | Define your own detection patterns |
| Pattern Libraries | Reusable signature collections |
| Research Notes | Attach knowledge directly to findings |

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
