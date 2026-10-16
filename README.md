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

Software supply-chain risk auditor — dependency confusion, typosquatting, install scripts & integrity

---

## ✨ Features

- Offline npm + Python manifest / lockfile auditing: package.json, package-lock, yarn.lock, .npmrc, .yarnrc, requirements*.txt, Pipfile(.lock), pyproject, poetry.lock, setup.py, setup.cfg, pip.conf — tolerant parsers
- Dependency confusion, typosquatting (edit distance, homoglyphs, affixes, ~300 popular names), install-script risk, integrity gaps, source provenance engines
- A+…F grade, CWE / ATT&CK / SLSA tags, remediation, TXT / MD / JSON / CSV / SARIF exports, CI gating, --demo

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OSupply
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
