# 🦉 OSupply

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OSupply** — Software Supply-Chain Risk Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OSupply is an offline software supply-chain risk auditor for npm and Python projects that parses manifests and lockfiles with tolerant stdlib parsers. It detects dependency confusion, typosquatting (edit distance, homoglyphs, affixes against ~300 popular names), risky install scripts, integrity gaps and source-provenance problems. Findings are graded A+ to F with CWE/ATT&CK/SLSA tags and exported as TXT, Markdown, JSON, CSV or SARIF for CI gating.

---

## ✨ Features


- Parses package.json, lockfiles, .npmrc/.yarnrc, requirements*.txt, Pipfile, pyproject, poetry.lock, setup.py and pip.conf
- Dependency-confusion and typosquatting detection (edit distance, homoglyphs, affixes, ~300 popular names)
- Install-script risk, integrity-gap and source-provenance engines
- A+..F grade with CWE / MITRE ATT&CK / SLSA tags and remediation guidance
- Configurable internal scopes/prefixes and trusted registries to reduce false positives
- Export TXT/MD/JSON/CSV/SARIF with --fail-on and --min-grade CI gating and a --check-name quick mode

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OSupply -p ./project -e auto -f sarif -o supply.sarif
./OSupply -p ./package-lock.json --internal-scope @acme --fail-on high
./OSupply --check-name reqeusts,expres,lodahs
./OSupply --demo
./OSupply --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
