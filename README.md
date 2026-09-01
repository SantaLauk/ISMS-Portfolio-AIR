# AIR ISMS Portfolio

### ISO/IEC 27001:2022 — Information Security Management System

> **Aetheria Infrastructure Research (AIR)** is a fictional European research organisation created for portfolio purposes. All organisations, systems, personnel, data, risks and findings described in this repository are simulated.

---

## Overview

This repository contains an ISO/IEC 27001:2022-aligned ISMS portfolio developed for a fictional research organisation.

The project covers the main stages of an ISMS, including organisational context, asset management, risk assessment, security policies, incident response, internal audit and continual improvement.

AIR is a 145-person research organisation with offices in Madrid, Brussels and Riga. It works on critical infrastructure research, AI-powered resilience modelling and government-commissioned research programmes. The organisation handles sensitive research data and operates a combination of cloud and on-premises systems.

The portfolio was developed over April and May 2026. A simulated certification pathway runs from June 2026 to March 2027, with external certification targeted for Q1 2027.

**Standard coverage:** ISO/IEC 27001:2022 Clauses 4–10 and all 93 Annex A controls assessed.

---

## Repository Structure

    ISMS-Portfolio-AIR/
    │
    ├── README.md
    ├── 00-Summary/
    ├── 01-Context-and-Scope/
    ├── 02-Asset-Management/
    ├── 03-Risk-Management/
    ├── 04-Policies/
    ├── 05-Operations/
    ├── 06-Compliance/
    └── 07-Improvement/

---

## Document Index

| # | Document ID | Title | Format | ISO 27001:2022 Clause |
|---|---|---|---|---|
| — | — | [Executive Summary](00-Summary/AIR-ISMS_Portfolio-Executive-Summary.pdf) | PDF | — |
| 1 | AIR-ISMS-ORG-001 | [Organisation Profile](01-Context-and-Scope/AIR-ISMS-ORG-001_Organisation-Profile_v1.0.pdf) | PDF | Clauses 4.1, 4.2 |
| 2 | AIR-ISMS-SCO-001 | [ISMS Scope Statement](01-Context-and-Scope/AIR-ISMS-SCO-001_ISMS-Scope-Statement_v1.0.pdf) | PDF | Clause 4.3 |
| 3 | AIR-ISMS-AST-001 | [Information Asset Inventory](02-Asset-Management/AIR-ISMS-AST-001_Asset-Inventory_v1.0.xlsx) | Excel | Clause 8.1, Annex A 5.9 |
| 4 | AIR-ISMS-RSK-001 | [Risk Assessment Methodology](03-Risk-Management/AIR-ISMS-RSK-001_Risk-Assessment-Methodology_v1.0.pdf) | PDF | Clause 6.1.2 |
| 5 | AIR-ISMS-RSK-002 | [Risk Register](03-Risk-Management/AIR-ISMS-RSK-002_Risk-Register_v1.0.xlsx) | Excel | Clauses 6.1.2, 6.1.3 |
| 6 | AIR-ISMS-POL-001 | [Information Security Policy](04-Policies/AIR-ISMS-POL-001_Information-Security-Policy_v1.0.pdf) | PDF | Clause 5.2, Annex A 5.1 |
| 7 | AIR-ISMS-POL-002 | [Access Control Policy](04-Policies/AIR-ISMS-POL-002_Access-Control-Policy_v1.0.pdf) | PDF | Annex A 5.15–5.18, 8.2–8.5 |
| 8 | AIR-ISMS-POL-003 | [Incident Response Policy](04-Policies/AIR-ISMS-POL-003_Incident-Response-Policy_v1.0.pdf) | PDF | Annex A 5.24–5.28 |
| 9 | AIR-ISMS-EXR-001 | [IR Tabletop Exercise — Operation Stale Key](05-Operations/AIR-ISMS-EXR-001_IR-Scenario-Tabletop_v1.0.pdf) | PDF | Annex A 5.24–5.28 |
| 10 | AIR-ISMS-SOA-001 | [Statement of Applicability](06-Compliance/AIR-ISMS-SOA-001_Statement-of-Applicability_v1.0.xlsx) | Excel | Clause 6.1.3 |
| 11 | AIR-ISMS-AUD-001 | [Internal Audit Report](06-Compliance/AIR-ISMS-AUD-001_Internal-Audit-Report_v1.0.pdf) | PDF | Clause 9.2 |
|  | AIR-ISMS-AUD-001 | [Findings Log](06-Compliance/AIR-ISMS-AUD-001_Findings-Log_v1.0.xlsx) | Excel | Clause 9.2 |
| 12 | AIR-ISMS-RMP-001 | [Security Improvement Roadmap](07-Improvement/AIR-ISMS-RMP-001_Security-Improvement-Roadmap_v1.0.xlsx) | Excel | Clauses 10.1, 10.2 |

---

## What Each Section Covers

### 01 — Context and Scope

The Organisation Profile defines AIR's internal and external context, including its governance structure, objectives, regulatory obligations and threat landscape.

The Scope Statement defines the ISMS boundary across three locations, 145 personnel and 12 systems, including documented exclusions and interface controls.

### 02 — Asset Management

The Asset Inventory covers 11 primary information assets and 12 supporting technical assets. Assets are assigned owners, classification levels, CIA impact ratings and related risks.

### 03 — Risk Management

The Risk Assessment Methodology defines a 5×5 likelihood and impact matrix, risk appetite and available treatment options.

The Risk Register contains 13 identified risks covering areas including identity and access management, data protection, AI infrastructure and legal compliance. Ten risks were rated High.

### 04 — Policies

Three policies form the main policy set in the portfolio:

- **Information Security Policy** — management commitment, security objectives, information classification and policy hierarchy.
- **Access Control Policy** — account lifecycle, MFA, privileged access and contractor access.
- **Incident Response Policy** — incident severity, response procedures, notification requirements and evidence handling.

### 05 — Operations

The tabletop exercise, **Operation Stale Key**, simulates the exploitation of a stale contractor account and access to Restricted research data. The exercise tests detection, classification, containment, legal notification and evidence handling.

### 06 — Compliance

The Statement of Applicability assesses all 93 ISO/IEC 27001:2022 Annex A controls.

- 9 controls are fully implemented.
- 63 are partially implemented.
- 21 are not yet implemented.

The simulated internal audit identified 2 major non-conformities, 5 minor non-conformities, 5 observations and 8 conformities.

### 07 — Improvement

The Security Improvement Roadmap contains 48 initiatives across 9 workstreams, covering remediation of audit findings and risk treatment actions.

---

---

## Technologies and Frameworks Referenced

`ISO/IEC 27001:2022` `GDPR` `NIS2 Directive` `EU AI Act` `Microsoft Azure` `Microsoft Entra ID` `Microsoft 365` `Microsoft Intune` `Microsoft Defender for Endpoint` `GitHub Enterprise` `Azure Key Vault` `Privileged Identity Management (PIM)`

---

## Notes

- All document IDs follow the convention `AIR-ISMS-[CATEGORY]-[NUMBER]`.
- Documents are version 1.0.
- Document classification levels used are Restricted, Confidential, Internal and Public.
- AIR and all associated data, systems and findings are fictional and were created for portfolio purposes.
