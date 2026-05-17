# 📉 Risk Assessment Methodology

This document outlines the formal methodology and criteria used to evaluate, quantify, and prioritize information security risks within the enterprise email infrastructure.

## 1. Scope
The boundaries of this risk assessment cover the following critical areas:
* **Enterprise Email Infrastructure:** Mail servers, gateways, and endpoint clients.
* **Information Transfer Workflows:** Secure transmission of internal and external communications.
* **User Authentication Mechanisms:** Identity verification and access controls.
* **Security Awareness:** Staff training processes regarding the protection of Personal Identifiable Information (PII) and institutional assets.

## 2. Risk Calculation Criteria
Risks are quantified using a standard qualitative risk analysis formula. This ensures a consistent and objective evaluation across all identified threats.

> **Formula:** `Risk Score = Probability × Impact`

---

## 3. Assessment Scales

### Likelihood Scale (1 - 5)
Determines the probability of a threat successfully exploiting a vulnerability.

* **1 - Rare:** Highly unlikely to occur.
* **2 - Unlikely:** Not expected, but possible under specific circumstances.
* **3 - Possible:** Might occur occasionally.
* **4 - Likely:** Expected to occur frequently.
* **5 - Almost Certain:** Will undoubtedly happen if no controls are applied.

### Impact Scale (1 - 5)
Determines the potential damage to the organization's confidentiality, integrity, or availability.

* **1 - Negligible:** Minimal operational disruption; no data loss.
* **2 - Minor:** Minor financial loss or isolated, non-sensitive data exposure.
* **3 - Moderate:** Significant disruption, potential regulatory scrutiny, or localized PII exposure.
* **4 - Major:** Critical system downtime, large-scale data breach, or heavy financial/reputational damage.
* **5 - Severe:** Catastrophic business failure, massive PII leak, or severe legal penalties.

---

## 4. Risk Matrix & Prioritization (Inherent vs. Residual)

The calculated risk scores (ranging from 1 to 25) are categorized into four tiers to dictate the urgency and type of remediation efforts required.

| Score Range | Risk Level | Required Action & Remediation Priority |
| :---: | :--- | :--- |
| **1 - 5** | 🟢 **Low** | **Acceptable Risk.** Requires periodic monitoring to ensure the risk profile does not change. |
| **6 - 11** | 🟡 **Medium** | **Managed Risk.** Requires planned mitigation. Controls should be implemented within standard budget cycles. |
| **12 - 19** | 🟠 **High** | **Urgent Action.** Requires immediate attention, resource allocation, and rapid control implementation. |
| **20 - 25** | 🔴 **Critical** | **Immediate Escalation.** Requires executive intervention, potential system isolation, and immediate blocking/containment. |
