# 🛡️ ISO/IEC 27001:2022 Email Security Risk Assessment

![ISO 27001:2022](https://img.shields.io/badge/Framework-ISO_27001:2022-0284c7?style=flat-square)
![GRC](https://img.shields.io/badge/Domain-Governance,_Risk_%26_Compliance-0f172a?style=flat-square)
![Risk Management](https://img.shields.io/badge/Skill-Risk_Assessment-166534?style=flat-square)

> A comprehensive Risk Assessment focusing on social engineering threats, vulnerability identification, and mitigation strategies for the protection of personal and corporate data within enterprise email systems.

## 1. Project Overview
This project demonstrates the ability to bridge the gap between human-centric vulnerabilities and technical defense mechanisms within corporate communications. It quantifies associated risks and applies international governance standards (**ISO/IEC 27001:2022**) to design auditable, actionable mitigation strategies.

## 2. Business Scenario
The assessment simulates a large academic institution managing sensitive **Personal Identifiable Information (PII)**, critical academic records, and intellectual property. 

**The Threat Landscape:** The institution faces highly targeted social engineering campaigns (such as Spear-Phishing and Business Email Compromise) aiming to:
* Compromise administrative and executive credentials.
* Bypass perimeter network defenses.
* Inadvertently or maliciously exfiltrate critical data.

## 3. Methodology Summary
Risks are calculated using a standard **5x5 Risk Matrix (Likelihood × Impact)**. The evaluation provides a clear comparative analysis between:
* **Inherent Risk:** The baseline threat level prior to control implementation.
* **Residual Risk:** The estimated, acceptable risk level after applying targeted Annex A controls.

## 4. Key ISO 27001:2022 Controls Mapped
To ensure regulatory compliance and operational security, the following Annex A controls have been evaluated and integrated as mitigation strategies:
* **A.5.14** Information transfer
* **A.5.18** Use of secret authentication information *(Enforcing MFA)*
* **A.6.3** Information security awareness, education, and training
* **A.8.7** Protection against malware
* **A.8.12** Data leakage prevention *(DLP implementation)*
* **A.8.20** Networks security *(SPF, DKIM, DMARC enforcement)*

## 5. Skills Demonstrated
### Governance & Compliance
* **IT Governance & Risk Management:** Structured risk identification and treatment.
* **Standard Implementation:** Translating ISO/IEC 27001:2022 clauses into operational reality.
* **Data Privacy:** Protecting PII and ensuring data lifecycle integrity.

### Technical Security (Blue Team Operations)
* **Threat Mitigation:** Designing defenses against advanced social engineering tactics.
* **Security Architecture Alignment:** Mapping normative mitigation controls to technical deployments, such as mapping log collection to SIEM platforms and deploying EDR agents across virtualized endpoints (e.g., VMware environments).

---

## 📂 Repository Structure
```text
├── docs/
│   └── methodology.md             # Detailed breakdown of Probability/Impact scales
├── deliverables/
│   └── Risk_Register_v1.0.xlsx    # The core Risk Assessment matrix (Excel)
└── README.md                      # Project overview and executive summary
