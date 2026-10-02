<div align="center">

# Simon Ngoy Mukendi
### Offensive Security Researcher · Windows Internals · EDR/XDR

*"Understanding why a detection fails is the first step to building one that doesn't."*

[![Blog](https://img.shields.io/badge/Blog-mukendi.github.io-1B4F72?style=flat-square&logo=github)](https://mukendi.github.io/blog-security)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Simon_Ngoy-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/simon-ngoy-1a9371103)

</div>

---

## About

Offensive security researcher focused on Windows kernel internals, EDR/XDR research, and adversarial technique analysis. I build and break endpoint security tooling from both sides — offensive PoCs and defensive detection components — and publish my research findings publicly.

- 🔬 **Current focus** : EDR/XDR bypass research, kernel driver engineering, AI security
- 🛠️ **Languages** : C/C++20, Rust, Python, x86/x64 Assembly
- 📍 **Blog** : [mukendi.github.io/blog-security](https://mukendi.github.io/blog-security)

---

## Research & Publications

| | Title | Description |
|---|---|---|
| 📄 | [Module Overloading — Bypassing EDR/XDR via Trust Inheritance](https://mukendi.github.io/blog-security/blog-module-overloading.html) | Full EDR bypass via SEC_IMAGE trust mechanics — zero detections on live Sophos XDR and BitDefender |
| 📄 | [CVE-2021-21551 — Dell Driver BYOVD / LPE](https://mukendi.github.io/blog-security/blog-cve-2021-21551-secretclub.html) | Full exploit chain: static analysis → WinDbg kernel debugging → token-stealing LPE |
| 📄 | [Project Kratos — Anti-Ransomware MiniFilter Driver](https://mukendi.github.io/blog-security/blog-project-kratos.html) | Behavioral ransomware detection at the I/O stack level via Windows kernel minifilter |

---

## Projects

| Project | Description | Tech |
|---|---|---|
| [DetectorOne](https://github.com/mukendi/DetectorOne) | Kernel-mode EDR research agent — BYOVD detection, shellcode analysis via heuristic RWX/RX memory inspection, libyara integration | C++20, WDK |
| [ArgusVisor](https://github.com/mukendi/ArgusVisor) | Research hypervisor monitoring VMX execution and Extended Page Tables (EPT) under Windows x64 | C++, Intel VT-x |
| [Kratos](https://github.com/mukendi/kratosminifilter) | Windows kernel minifilter driver for behavioral ransomware detection at the I/O stack level | C++, KMDF |
| [Virunga](https://github.com/mukendi/Virunga) | BYOVD EDR silencing research PoC — Ring 0/Ring 3 kernel telemetry validation via signed vulnerable driver | C++ |

---

## Core Competencies
