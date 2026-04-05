# 🌾 OHarvest

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-ORec%20%2F%20OSINT-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-requests%20beautifulsoup4-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OHarvest** is a comprehensive email and subdomain OSINT harvester. It collects emails and subdomains for a target domain using Certificate Transparency (crt.sh), web crawling, common email patterns, DNS TXT/SPF analysis, and DNS probing of common subdomains.

**Fast threaded harvesting with TXT, JSON, and CSV export.**

---

## 📌 Overview

OHarvest combines multiple passive OSINT sources to discover email addresses and subdomains associated with a target domain. It runs sources in parallel and presents clean, categorized results with statistics.

Excellent for initial reconnaissance and expanding the digital footprint of a target.

---

## 🖥️ Modules

| # | Module                  | Description |
|---|-------------------------|-------------|
| **[1]** | **Harvest**             | Full multi-source email & subdomain collection |
| **[2]** | **Quick Extract**       | Extract emails from a single URL |
| **[3]** | **Subdomain Probe**     | DNS-resolve 55+ common subdomains |

---

## 📊 Key Features

- **5 Powerful Sources**:
  - crt.sh (Certificate Transparency logs)
  - Web Crawl (homepage, contact, about pages)
  - Common Patterns (info@, admin@, sales@ …)
  - DNS TXT (SPF/DMARC record parsing)
  - DNS Probe (common subdomain wordlist resolution)
- **Parallel Execution** — Threaded harvesting for speed
- **Smart Extraction** — Regex-based email and subdomain detection
- **Live Progress** — Real-time results from each source
- **Multiple Export Formats** — TXT, JSON, CSV
- **Clean Terminal UI** — Colored output with summary statistics

---

## ⚙️ Requirements

- **requests**
- **beautifulsoup4**
  ```bash
  pip install requests beautifulsoup4
  pip install dnspython
  chmod +x OHarvest
  ./OHarvest


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.
AUTHORISED OSINT AND SECURITY RESEARCH ONLY
