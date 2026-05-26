# AIR ISMS Portfolio
### ISO/IEC 27001:2022 — Information Security Management System

> **Aetheria Infrastructure Research (AIR)** is a fictional European research organisation created for portfolio purposes. All documents, data, risks, and findings in this repository are simulated. The organisation, its systems, personnel, and government partnerships do not exist.

---

## Overview

This repository contains a complete, end-to-end Information Security Management System (ISMS) portfolio built to the requirements of **ISO/IEC 27001:2022**. It was developed to demonstrate practical knowledge of the standard, from organisational context and risk assessment through policy development, control evaluation, internal audit, and improvement planning.

The fictional organisation (AIR) is a 145-person critical infrastructure research firm operating across three EU locations (Madrid, Brussels, Riga), handling sensitive research and infrastructure-related data, and developing proprietary AI models. The scenario was chosen to reflect a complex, realistic information security environment (multiple jurisdictions, sensitive data classifications, contractor access risks, and a mix of cloud and on-premises infrastructure).

**Certification target (simulated):** ISO/IEC 27001:2022 — Q1 2027
**Standard clause coverage:** All mandatory clauses (4–10) and all 93 Annex A controls assessed

---

## Repository Structure

```
AIR-ISMS-Portfolio/
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
```

---

## Document Index

| # | Document ID | Title | Format | ISO 27001:2022 Clause |
|---|---|---|---|---|
| — | — | [Executive Summary](00-Summary/) | Word | — |
| 1 | AIR-ISMS-ORG-001 | [Organisation Profile](01-Context-and-Scope/) | Word | Clause 4.1, 4.2 |
| 2 | AIR-ISMS-SCO-001 | [ISMS Scope Statement](01-Context-and-Scope/) | Word | Clause 4.3 |
| 3 | AIR-ISMS-AST-001 | [Information Asset Inventory](02-Asset-Management/) | Excel | Clause 8.1, Annex A 5.9 |
| 4 | AIR-ISMS-RSK-001 | [Risk Assessment Methodology](03-Risk-Management/) | Word | Clause 6.1.2 |
| 5 | AIR-ISMS-RSK-002 | [Risk Register](03-Risk-Management/) | Excel | Clause 6.1.2, 6.1.3 |
| 6 | AIR-ISMS-POL-001 | [Information Security Policy](04-Policies/) | Word | Clause 5.2, Annex A 5.1 |
| 7 | AIR-ISMS-POL-002 | [Access Control Policy](04-Policies/) | Word | Annex A 5.15–5.18, 8.2–8.5 |
| 8 | AIR-ISMS-POL-003 | [Incident Response Policy](04-Policies/) | Word | Annex A 5.24–5.28 |
| 9 | AIR-ISMS-EXR-001 | [IR Tabletop Exercise — Operation Stale Key](05-Operations/) | Word | Annex A 5.24–5.28 |
| 10 | AIR-ISMS-SOA-001 | [Statement of Applicability](06-Compliance/) | Excel | Clause 6.1.3 |
| 11 | AIR-ISMS-AUD-001 | [Internal Audit Report](06-Compliance/) | Word | Clause 9.2 |
| 12 | AIR-ISMS-AUD-001 | [Findings Log](07-Improvement/) | Excel | Clause 9.2 |
| 13 | AIR-ISMS-RMP-001 | [Security Improvement Roadmap](07-Improvement/) | Excel | Clause 10.1, 10.2 |

---

## What Each Section Covers

### 01 — Context and Scope
The foundation of the ISMS. The **Organisation Profile** documents AIR's internal and external context: governance structure, strategic objectives, regulatory obligations (GDPR, NIS2, EU AI Act), and the threat landscape specific to a critical infrastructure research organisation. The **Scope Statement** formally defines the ISMS boundary across all three locations, 145 personnel, and 12 systems, with justified exclusions and documented interface controls.

### 02 — Asset Management
The **Asset Inventory** catalogues 11 primary information assets (from government-classified research data to AI model weights) and 12 supporting technical assets. Each asset carries an owner, a classification level (Restricted through Public), a CIA impact rating, and links to the risks that apply to it.

### 03 — Risk Management
The **Risk Assessment Methodology** defines a 5×5 likelihood-impact matrix, risk appetite thresholds, and the four treatment options available to asset owners. The **Risk Register** applies this methodology to 13 identified risks across identity and access, data protection, AI infrastructure, and legal compliance domains.

### 04 — Policies
Three topic-specific policies exist beneath the top-level Information Security Policy:
- **Information Security Policy** — management mandate, five measurable security objectives, information classification scheme, and the policy hierarchy
- **Access Control Policy** — full access lifecycle with defined timeframes, MFA requirements, Privileged Identity Management, and a contractor access framework
- **Incident Response Policy** — P1–P4 severity classification, six-phase response lifecycle, GDPR 72-hour notification obligations, and evidence handling procedures

### 05 — Operations
A fully scripted **tabletop exercise** (Operation Stale Key) simulating the exploitation of a stale contractor account to access 4.1 GB of Restricted research data. Six timed injects test the team's detection, classification, containment, legal notification, and media handling capability, with facilitator notes, expected responses, and a structured debrief framework.

### 06 — Compliance
The **Statement of Applicability** assesses all 93 ISO/IEC 27001:2022 Annex A controls, none are excluded. 9 are fully implemented, 63 are partially implemented, and 21 are not yet implemented, each with an evidence reference and recommended action. The **Internal Audit Report** documents a simulated first audit: 2 major non-conformities, 5 minor non-conformities, 5 observations, and 8 conformities, with a full findings log tracking corrective actions and target dates.

### 07 — Improvement
A **10-month Security Improvement Roadmap** across 9 workstreams, covering 48 prioritised initiatives. Includes a 15-gate pre-certification checklist mapping every condition AIR must satisfy before submitting for Stage 1 external audit.

---

## Simulated Certification Pathway

| Phase | Period | Focus |
|---|---|---|
| **Treatment** | Jun – Sep 2026 | Close 2 major NCRs and 5 minor NCRs. Complete ROPA, DPIAs, supplier assessments, MFA migration, automated offboarding, staff training. |
| **Pre-Certification** | Oct – Nov 2026 | Follow-up internal audit. Verify NCR closure. Complete all policies. Conduct management review. External penetration test. |
| **Stage 1 Audit** | Dec 2026 | External certification body documentation review. Identify Stage 2 readiness gaps. |
| **Stage 2 Audit** | Feb – Mar 2027 | On-site audit. ISO/IEC 27001:2022 certificate issued. |

---

## Key Numbers

| Metric | Value |
|---|---|
| Documents produced | 12 |
| ISO 27001:2022 clauses addressed | 4–10 (all mandatory) |
| Annex A controls assessed | 93 of 93 |
| Annex A controls implemented | 9 (10%) |
| Annex A controls partially implemented | 63 (68%) |
| Annex A controls not yet implemented | 21 (22%) |
| Information assets inventoried | 23 (11 primary, 12 supporting) |
| Risks identified and rated | 13 |
| Audit findings | 12 (2 major NCR, 5 minor NCR, 5 observations, 8 conformities) |
| Roadmap initiatives | 48 across 9 workstreams |
| Personnel in scope | 145 (120 employees, 25 contractors) |
| Locations in scope | 3 (Madrid, Brussels, Riga) |

---

## Technologies and Frameworks Referenced

`ISO/IEC 27001:2022` `GDPR` `NIS2 Directive` `EU AI Act` `Microsoft Azure` `Microsoft Entra ID` `Microsoft 365` `Microsoft Intune` `Microsoft Defender for Endpoint` `GitHub Enterprise` `Azure Key Vault` `Privileged Identity Management (PIM)`

---

## Notes

- All document IDs follow the convention `AIR-ISMS-[CATEGORY]-[NUMBER]`
- All documents are at version 1.0, dated May 2026
- Document classification levels used: Restricted, Confidential, Internal, Public
- The organisation and all associated data are entirely fictional and created for portfolio demonstration purposes only
