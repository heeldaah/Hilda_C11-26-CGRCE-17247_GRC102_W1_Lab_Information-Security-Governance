
# INTERNATIONAL CYBERSECURITY AND DIGITAL FORENSICS ACADEMY (ICDFA)

## Governance, Compliance, and Risk (GCR)

### GRC102 Information Security Governance

# Week 1 Lab: Information Security Governance in Action

**Student:** Hilda Odein Joshua-Jack  
**Registration Number:** C11/26/CGRCE/17247  
**Course Code:** GRC102  
**Course Title:** Information Security Governance  
**Week's Title:** Principles of Information Security Governance  
**Credit Load:** 3 Credits  
**Cohort:** 11  
**Date:** 11th September, 2026  

---

# TABLE OF CONTENTS

1. [Governance Blueprint](#1-governance-blueprint)
   - [1.1 Current-State Governance Gap Assessment](#11-current-state-governance-gap-assessment)
   - [1.2 Proposed Organisational Chart](#12-proposed-organisational-chart)
   - [1.3 RACI Matrix](#13-raci-matrix)
   - [1.4 Governance Rationale](#14-governance-rationale)

2. [Information Security Charter](#2-information-security-charter)
   - [2.1 GHC Information Security Charter](#21-ghc-information-security-charter)
   - [2.2 CFO Justification Memo](#22-cfo-justification-memo)

3. [Board Reporting](#3-board-reporting)
   - [3.1 Board Executive Summary](#31-board-executive-summary)
   - [3.2 Selected Security Metrics](#32-selected-security-metrics)
   - [3.3 Priority Risks and Recommendations](#33-priority-risks-and-recommendations)
   - [3.4 Metric Selection Rationale](#34-metric-selection-rationale)

4. [Security Steering Committee](#4-security-steering-committee)
   - [4.1 Security Steering Committee Terms of Reference](#41-security-steering-committee-terms-of-reference)
   - [4.2 Sample First-Meeting Agenda](#42-sample-first-meeting-agenda)
   - [4.3 CEO Briefing Note](#43-ceo-briefing-note)

5. [Governance Maturity](#5-governance-maturity)
   - [5.1 Maturity Assessment](#51-maturity-assessment)
   - [5.2 12-18 Month Improvement Roadmap](#52-12-18-month-improvement-roadmap)
   - [5.3 Board-Level Executive Summary](#53-board-level-executive-summary)

6. [Conclusion](#6-conclusion)

7. [References](#7-references)

8. [AI Assistance Declaration](#8-ai-assistance-declaration)

---

# 1. GOVERNANCE BLUEPRINT

## 1.1 Current-State Governance Gap Assessment

GHC is a mid-sized health-tech company that has grown quickly, including through two acquisitions. Its use of cloud-based patient-management systems means that information security is important not only from a technical perspective but also from a business, regulatory and reputational perspective.

The current governance structure has several gaps.

| Governance Area | Current-State Gap | Risk/Impact |
|---|---|---|
| Security Ownership | Security is mainly treated as an IT responsibility. | Important security decisions may not receive enough executive attention. |
| Accountability | Roles and responsibilities for security governance are not clearly defined. | Tasks may be duplicated or missed, especially during incidents. |
| Policy Management | Policies may be inconsistent across the organisation and acquired companies. | Different teams may follow different security practices. |
| Risk Management | Security risks are handled mainly when problems occur rather than through a consistent risk-management process. | Emerging risks may not be identified early. |
| Board Reporting | Technical information is not consistently translated into business risks and impacts. | The Board may not have enough information to make informed security decisions. |
| Cross-Functional Coordination | IT, development, compliance, HR and finance do not have a formal structure for making security decisions together. | Security decisions may conflict with business or operational requirements. |
| Acquisition Integration | The two acquired companies may have different systems, policies and security practices. | Existing weaknesses may be introduced into GHC's environment. |

### Overall Assessment

The biggest governance weakness is that information security is being treated mainly as an IT issue. GHC needs a structure that gives security clear executive ownership, defined responsibilities and regular reporting to management and the Board.

---

## 1.2 Proposed Organisational Chart

The proposed structure gives the Board and CEO clear oversight while allowing different business functions to participate in security governance.

```mermaid
flowchart TD
    A["Board of Directors"] --> B["CEO - Sarah Chen"]
    B --> C["Information Security Governance Function"]
    C --> D["Security Steering Committee"]
    D --> E["IT Operations - John Smith"]
    D --> F["Development - Jane Doe"]
    D --> G["Compliance - Mark Johnson"]
    D --> H["HR - Robert Green"]
    D --> I["Finance - Emily White"]
    C --> J["Security Risk & Reporting"]
    C --> K["Policies & Governance"]
    C --> L["Security Metrics & Assurance"]

### Key Reporting Relationships
The Board provides oversight and approves major security priorities.
The CEO provides executive leadership and ensures security supports business objectives.
The Information Security Governance Function coordinates governance, risk, reporting and policy activities.
The Security Steering Committee provides cross-functional oversight and decision-making.
IT, Development, Compliance, HR and Finance contribute their specific responsibilities to security governance.

## 1.3 RACI Matrix

**R = Responsible**  
**A = Accountable**  
**C = Consulted**  
**I = Informed**

| Activity | Board | CEO | Security Governance | IT Manager | Compliance | HR | Development |
|---|---|---|---|---|---|---|---|
| Approve security policy | A | R | C | C | C | I | I |
| Review enterprise security risks | A | A | R | C | C | I | C |
| Incident response planning | I | A | R | R | C | C | C |
| Security awareness | I | A | R | C | C | R | I |
| Access governance | I | A | R | R | C | C | C |
| Regulatory compliance monitoring | I | A | R | C | R | C | I |
| Security metrics and Board reporting | A | A | R | C | C | I | I |
| Security Steering Committee decisions | I | A | R | R | R | C | C |





