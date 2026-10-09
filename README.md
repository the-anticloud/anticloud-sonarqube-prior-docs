# SONARQUBE PRIOR DOCS

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-software_development-lightgrey)

> Anticloud-hardened packaging of the upstream project `SONARQUBE_PRIOR_DOCS` in category **SOFTWARE DEVELOPMENT**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SOFTWARE DEVELOPMENT · **Upstream:** https://github.com/SonarSource/sonarqube · **Upstream pin:** `f44f2e2d1774c1fd9cc021474032b0fcbc51a882` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://assets-eu-01.kc-usercontent.com/ef593040-b591-0198-9506-ed88b30bc023/a23fc7ba-23f0-489a-829d-ed88c0748521/Sonar_Logo_Dark%20Backgrounds.svg">
    <img src="https://assets-eu-01.kc-usercontent.com/ef593040-b591-0198-9506-ed88b30bc023/82c13eba-d95c-4bb8-8007-7ce77c14e043/Sonar_Logo_Light%20Backgrounds.svg" alt="Sonar logo" width="400">
  </picture>
</p>

# SonarQube

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://assets-eu-01.kc-usercontent.com/ef593040-b591-0198-9506-ed88b30bc023/19f97554-c5ec-4cf1-87f7-878c02a19702/SQ_Logo_Server_Dark%20Backgrounds.svg">
    <img src="https://assets-eu-01.kc-usercontent.com/ef593040-b591-0198-9506-ed88b30bc023/4a785d22-7141-409d-95a2-695c42595f90/SQ_Logo_Server_Light%20Backgrounds.png" alt="SonarQube Server logo" width="400">
  </picture>
</p>

[![Build](https://github.com/SonarSource/sonarqube/actions/workflows/build.yml/badge.svg)](https://github.com/SonarSource/sonarqube/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=sonarqube&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=sonarqube)
[![AI Code Assurance](https://next.sonarqube.com/sonarqube/api/project_badges/ai_code_assurance?project=org.sonarsource.sonarqube%3Asonarqube-private&token=sqb_c0e2fa9ac4ef89f9a8403c6ba235e108ceb1dce1)](https://next.sonarqube.com/sonarqube/dashboard?id=sonarqube)
[![Release](https://img.shields.io/github/v/release/SonarSource/sonarqube)](https://github.com/SonarSource/sonarqube/releases)
[![Docker pulls](https://img.shields.io/docker/pulls/library/sonarqube)](https://hub.docker.com/_/sonarqube)
[![License](https://img.shields.io/badge/license-LGPL%20v3-blue)](#license)
[![Community](https://img.shields.io/badge/community-forum-blue)](https://community.sonarsource.com/c/sq/10)

SonarQube is the algorithmic verification platform for code quality and security. Its static analysis applies techniques such as symbolic execution and data and control flow analysis to inspect your code, find bugs, vulnerabilities, and structural problems, and tell you exactly what to fix and why, in your IDE, your pull requests, and your CI pipeline.

This project holds the source of the **SonarQube Community Build**, the free, open-source edition of the SonarQube platform. It shares the same analysis used across the SonarQube product line.

Trusted by more than 7 million developers and 22,000 organizations, SonarQube analyzes over 750 billion lines of code every day.

## Built for the AI era

AI writes code faster than teams can review it, creating verification debt: code reaching production before anyone has confirmed what it does. SonarQube applies the same consistent, explainable analysis to every line, whether a developer or an agent wrote it. Vibe, then verify: generate fast, then verify what reaches production. It is the verification stage of the Agent Centric Development Cycle, running in the outer CI verification loop to verify code before it merges.

## What SonarQube finds

- **Bugs and reliability issues** that break behavior at runtime.
- **Security vulnerabilities and security hotspots**, with clear guidance on the risk and the fix.
- **Maintainability and structural issues** that make code harder to change over time.
- **Coverage on new code**, so quality improves with every commit instead of stalling behind a backlog.

It analyzes 40+ programming languages and frameworks. Analysis is repeatable, auditable, and explainable: the same code always produces the same findings, every finding is traceable, and each one tells you what the problem is and why it matters.

## Commercial editions

SonarQube Server and SonarQube Cloud include everything in the Community Build and add:

**Detect more**

- More bugs, vulnerabilities, code quality issues, and architecture issues, through broader coverage and deeper analysis.
- More languages and frameworks than the Community Build.
- Software composition analysis (SCA) for vulnerable and risky open-source dependencies.
- Advanced security with deep taint analysis (SAST) that traces vulnerabilities across data flows.
- Secrets detection for leaked credentials, tokens, and keys.
- Infrastructure as code (IaC) analysis for Terraform, Kubernetes, Docker, and CloudFormation.
- Architecture management to define architectural constraints and catch structural violations.

**Analyze your whole workflow**

- Branch analysis and pull request decoration, so every change is verified before it merges.

**Govern, report, and see across teams**

- Portfolios and applications that roll up quality and security across many projects.
- Executive dashboards and trend reporting.
- Security and compliance reports, including OWASP Top 10, CWE, and PCI DSS.
- Enterprise governance: enforce Quality Gates and permissions across teams, with full audit trails.

**Fix**

- SonarQube Remediation Agent to reduce technical debt by fixing SonarQube issues for you, opening verified fix pull requests you can review and merge.

Some capabilities are part of the SonarQube Advanced Security add-on. See the [product line](#the-sonarqube-product-line) for details.

## Quality gates

A Quality Gate is a pass-or-fail check on your new code. Set the standard once, and SonarQube enforces it automatically in every pull request and pipeline, so issues are caught before they merge rather than found in production.

## The SonarQube product line

The Community Build is free and open source. The wider SonarQube line applies the same analysis across your workflow:

- **[SonarQube Server](https://www.sonarsource.com/products/sonarqube/server/)**, self-managed, with more languages, deeper security analysis, and branch and pull request analysis.
- **[SonarQube Cloud](https://www.sonarsource.com/products/sonarqube/cloud/)**, hosted, with the same capabilities as a managed service.
- **[SonarQub

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Java / Gradle** (manifests: build.gradle; scanned in UPSTREAM_CLONE)
- Top-level source layout: `buildSrc/`, `gradle/`, `plugins/`, `scripts/`, `server/`, `sonar-application/`, `sonar-core/`, `sonar-duplications/`, `sonar-markdown/`, `sonar-plugin-api-impl/`, `sonar-sarif/`, `sonar-shutdowner/`
- Snapshot size: **8409 files**, **915898 lines of code** (measured; see Benchmarks)
- Primary languages: `.java` (7525), `.json` (384), `.xml` (189), `.txt` (59), `.gradle` (50), `.proto` (49)
- Upstream commit pinned for this packaging: `f44f2e2d1774c1fd9cc021474032b0fcbc51a882`

---

## Installation

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=sonarqube&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=sonarqube)
[![AI Code Assurance](https://next.sonarqube.com/sonarqube/api/project_badges/ai_code_assurance?project=org.sonarsource.sonarqube%3Asonarqube-private&token=sqb_c0e2fa9ac4ef89f9a8403c6ba235e108ceb1dce1)](https://next.sonarqube.com/sonarqube/dashboard?id=sonarqube)
[![Release](https://img.shields.io/github/v/release/SonarSource/sonarqube)](https://github.com/SonarSource/sonarqube/releases)
[![Docker pulls](https://img.shields.io/docker/pulls/library/sonarqube)](https://hub.docker.com/_/sonarqube)
[![License](https://img.shields.io/badge/license-LGPL%20v3-blue)](#license)
[![Community](https://img.shields.io/badge/community-forum-blue)](https://community.sonarsource.com/c/sq/10)

SonarQube is the algorithmic verification platform for code quality and security. Its static analysis applies techniques such as symbolic execution and data and control flow analysis to inspect your code, find bugs, vulnerabilities, and structural problems, and tell you exactly what to fix and why, in your IDE, your pull requests, and your CI pipeline.

This project holds the source of the **SonarQube Community Build**, the free, open-source edition of the SonarQube platform. It shares the same analysis used across the SonarQube product line.

Trusted by more than 7 million developers and 22,000 organizations, SonarQube analyzes over 750 billion lines of code every day.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

./gradlew ide

Then open the root file `build.gradle` as a project in IntelliJ or Eclipse.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

[![AI Code Assurance](https://next.sonarqube.com/sonarqube/api/project_badges/ai_code_assurance?project=org.sonarsource.sonarqube%3Asonarqube-private&token=sqb_c0e2fa9ac4ef89f9a8403c6ba235e108ceb1dce1)](https://next.sonarqube.com/sonarqube/dashboard?id=sonarqube)
[![Release](https://img.shields.io/github/v/release/SonarSource/sonarqube)](https://github.com/SonarSource/sonarqube/releases)
[![Docker pulls](https://img.shields.io/docker/pulls/library/sonarqube)](https://hub.docker.com/_/sonarqube)
[![License](https://img.shields.io/badge/license-LGPL%20v3-blue)](#license)
[![Community](https://img.shields.io/badge/community-forum-blue)](https://community.sonarsource.com/c/sq/10)

SonarQube is the algorithmic verification platform for code quality and security. Its static analysis applies techniques such as symbolic execution and data and control flow analysis to inspect your code, find bugs, vulnerabilities, and structural problems, and tell you exactly what to fix and why, in your IDE, your pull requests, and your CI pipeline.

This project holds the source of the **SonarQube Community Build**, the free, open-source edition of the SonarQube platform. It shares the same analysis used across the SonarQube product line.

Trusted by more than 7 million developers and 22,000 organizations, SonarQube analyzes over 750 billion lines of code every day.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Java / Gradle |
| Manifests detected | build.gradle |
| Files in snapshot | 8409 |
| Lines of code | 915898 |
| Dependency references | 0 |
| Upstream license | LGPL-3.0 |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

Here is an example of how to do it:

```bash
cd /path/to/sonarqube-webapp/server/sonar-web

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `SONARQUBE_PRIOR_DOCS` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: LGPL-3.0** (evidence: `LICENSE.txt` in the upstream snapshot).

License file excerpt:

```text
                   GNU LESSER GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

 Copyright (C) 2007 Free Software Foundation, Inc. <http://fsf.org/>
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.

  This version of the GNU Lesser General Public License incorporates
the terms and conditions of version 3 of the GNU General Public
License, supplemented by the additional permissions listed below.

  0. Additional Definitions.

  As used herein, "this License" refers to version 3 of the GNU Lesser
General Public License, and the "GNU GPL" refers to version 3 of the GNU
General Public License.

  "The Library" refers to a covered work governed by this License,
other than an Application or a Combined Work as defined below.
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original LGPL-3.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `LGPL-3.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `SONARQUBE_PRIOR_DOCS` (category: SOFTWARE DEVELOPMENT)
- **Upstream URL:** https://github.com/SonarSource/sonarqube
- **Pinned commit (SHA):** `f44f2e2d1774c1fd9cc021474032b0fcbc51a882`
- **Branch:** master
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`f4c5b53232ec39eaaa2c4e1935274cb54ffeb1de5c6a3caf80f96ea2ea038156`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

