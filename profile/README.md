<p align="center">
  <img src="https://raw.githubusercontent.com/OrganisationServiceManagement/.github/refs/heads/main/assets/ZOAK%2BOSMBanner-2026.svg" alt="ZOAK Solutions" width="100%">
</p>

<h1 align="center">ZOAK Solutions</h1>

<p align="center">
  <em>Delivering secure, scalable, and resilient solutions for mission-critical services</em>
</p>
---****

## 🛍️ Overview

**ZOAK Pty Ltd** (trading as **ZOAK Solutions**) is an Australian company that has operated since 2013, delivering secure, scalable, and resilient solutions to mission-critical sectors. We serve Australian Government departments and agencies, internet regulators, ASX-listed firms, and global technology vendors. Our primary focus is designing, building, operating, and securing internet-facing and cloud-native systems, with a deep specialisation in Information Security Management and compliance engineering.

Our GitHub Enterprise supports the secure and collaborative development of ZOAK intellectual property, client deliverables, and open-source tooling across internal tooling / research, infrastructure-as-code, cybersecurity automation, and Organisational Service Management (OSM) schema and tooling.

---

## 📜 Philosophy

ZOAK is **hands-on**, **partner-focused**, and **long-term oriented**. We believe in:

- Reducing operational overheads through automation and reusable frameworks
- Bridging strategic objectives with operational execution
- Security-first design, not security-as-an-afterthought
- Supporting clients through every phase: design → build → secure → operate

---

## 🛠️ GitHub Usage at ZOAK

- **Host and manage internal tools and shared frameworks** such as:
  - `schema.osm.dev`: modular JSON-based schemas for managing organisational policies, risks, assets, objectives, third parties, and treatments
  - `OSMPowerKits`: PowerShell tooling for secure and auditable AWS resource enumeration
  - `Numbering-System`: tooling and documentation for the administration and operation of Australia’s numbering services registry platform [thenumberingsystem.com.au]{https://thenumberingsystem.com.au)

- **Version-control documentation, automation, templates** including:
  - ISMS artefacts and compliance automation tooling
  - AWS, M365/Azure, Atlassian automation code
  - CI/CD pipelines for monitoring/deployments/job automation and other business processes
  - **Automate security and compliance assessments**, using scripts to:
    - Verify control implementation against Essential Eight and ISO/IEC 27001:2022
    - Generate Statements of Applicability (SoAs)
    - Conduct gap analysis for third-party risk assessments
    - Integrate control evidence across Atlassian, M365, and GitHub

- **Enable secure DevSecOps pipelines**, where:
  - All repositories are required to have branch protection and signed commits
  - CodeQL and dependency scanning are enforced
  - Infrastructure changes are peer-reviewed and auditable
  - Secrets scanning and GitHub Actions hardening are mandatory

---

## 🧹 Key Themes and Domains

### ✅ Compliance & Security Engineering
- ISO/IEC 27001:2022, ISO/IEC 22301, ASD ISM, SOC 2, OSCAL, 
- Secure logging, incident response, auditing automation
- Control evidence tracking and auto-updating SoA

### 📦 Organisation+Operations-as-Code
- Terraform for AWS multi-account environments
- PowerShell/Python automation for M365, Entra ID
- Ansible roles for hardened Linux baseline deployments

### 🧠 Organisational Service Management (OSM)
- Machine-readable definitions of:
  - Assets, Risks, Treatments, Controls, Policies
  - Objectives, Third-Parties, Owners, Audits
- Graph-based navigation and validation

---

## 🧪 Research, Prototypes & Experiments

This environment is also home to:
- Prototypes exploring narrative linking and AI orchestration (e.g., JIMIS — Just-In-time ISMS Insight System)
- Experimental language models for parsing ISMS documents
- Federated search across JIRA, Confluence, and GitHub content
- Validation endpoints for ISMS schemas using Pydantic + AWS Lambda

---

## 🔐 Access and Usage Policy

- All contributions must follow [ZOAK Secure Coding Standards]
- Repository access is assigned on a least-privilege model
- GitHub Actions must be approved and reviewed by InfoSec
- Code merges to `main` are gated by review, CI, and security checks
- Audit logs are ingested into our centralised monitoring solution

---

## 🛍️ Future Direction

ZOAK's future development efforts are focused on:
- Consolidating all GRC activities within the `GRCosm` framework
- Extending OSM Schema support to external validators and control libraries
- Publishing select internal tooling under open-source licenses
- Deepening GitHub Actions integration with ISMS observability and reporting pipelines
- Using GitHub as a backend for AI-guided control recommendation engines and compliance agents

---

## 📂 Contact and Governance

**Organisation**: ZOAK Pty Ltd  
**ABN/ACN**: 68 161 531 880  
**Website**: [zoak.solutions](https://zoak.solutions)  | [osm.dev](https://osm.dev)
**Email**: [admin@zoak.solutions](mailto:admin@solutions).

---
