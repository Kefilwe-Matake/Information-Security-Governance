# Week 3 Practical Laboratory: Roles, Responsibilities and Accountability in Security Governance

**International Cybersecurity and Digital Forensics Academy (ICDFA)**

> **TechGlobal – Governance Transformation Simulation**

|                      |                                     |
| -------------------- | ----------------------------------- |
| **Role**             | Lead Security Governance Consultant |
| **Student**          | Kefilwe Matake                      |
| **Registration No.** | C11_26_CGRCE_17575                  |
| **Submission Date**  | 25 September 2026                   |
| **Assessment**       | Week 3 Practical Laboratory         |

---

## 📋 Table of Contents

* [Executive Summary](#executive-summary)
* [1. Governance Architecture and Stakeholder Map](#1-governance-architecture-and-stakeholder-map)

  * [1.1 Current-State Governance Gap Assessment](#11-current-state-governance-gap-assessment)
  * [1.2 Stakeholder Map](#12-stakeholder-map)
  * [1.3 Proposed Security Governance Architecture](#13-proposed-security-governance-architecture)
  * [1.4 Governance Model Justification](#14-governance-model-justification)
* [2. Governance Responsibility and Authority Matrix](#2-governance-responsibility-and-authority-matrix)

  * [2.1 Responsibility Profiles](#21-responsibility-profiles)
  * [2.2 Authority Principles](#22-authority-principles)
  * [2.3 Overlapping Authority and Conflict Resolution](#23-overlapping-authority-and-conflict-resolution)
* [3. Security Governance Committee Ecosystem](#3-security-governance-committee-ecosystem)

  * [3.1 Committee Structure](#31-committee-structure)
  * [3.2 Governance Information Flow](#32-governance-information-flow)
  * [3.3 Terms of Reference](#33-terms-of-reference)
  * [3.4 Business Unit Participation](#34-business-unit-participation)
  * [3.5 Sample Committee Agenda](#35-sample-committee-agenda)
  * [3.6 Sample Decision Log](#36-sample-decision-log)
  * [3.7 Twelve-Month Governance Calendar](#37-twelve-month-governance-calendar)
* [4. RACI Accountability Matrix](#4-raci-accountability-matrix)

  * [4.1 Problematic RACI Assignments Corrected](#41-problematic-raci-assignments-corrected)
  * [4.2 RACI Implementation Guide](#42-raci-implementation-guide)
* [5. Cyber-Risk Escalation, Segregation of Duties and Assurance](#5-cyber-risk-escalation-segregation-of-duties-and-assurance)

  * [5.1 Major Cyber-Risk Escalation Workflow](#51-major-cyber-risk-escalation-workflow)
  * [5.2 Escalation Thresholds](#52-escalation-thresholds)
  * [5.3 Segregation-of-Duties Weakness Register](#53-segregation-of-duties-weakness-register)
  * [5.4 Decision Recording and Assurance](#54-decision-recording-and-assurance)
* [6. Overall Consultant Recommendation](#6-overall-consultant-recommendation)
* [7. References](#7-references)
* [AI Assistance Declaration](#ai-assistance-declaration)

---

# Executive Summary

TechGlobal is a fast-growing technology organisation with approximately **2,500 employees across five global offices**.

The current governance model is characterised by:

* Security decisions being concentrated around the IT Director
* Inconsistent security decisions across business units
* Limited executive and Board visibility into cyber risk
* Unclear separation between security ownership, risk acceptance and implementation
* No formal security governance committee
* Limited formal escalation mechanisms
* Unclear accountability for governance activities
* Limited evidence of formal security decision-making

These weaknesses represent a **security governance and accountability problem**, rather than solely a technical control problem.

This report proposes a structured governance model that separates:

> **Board Oversight → Executive Accountability → Security Governance → Enterprise Risk Challenge → Operational Implementation → Business Ownership**

The proposed model introduces:

* Board oversight of material cyber risk and risk appetite
* CEO-level executive accountability
* CISO-led security governance
* CRO/Risk challenge and enterprise risk integration
* Cross-functional security governance committees
* Defined business-unit security ownership
* RACI-based accountability
* Formal cyber-risk escalation thresholds
* Segregation-of-duties controls
* Formal security decision records
* Independent assurance through Internal Audit

The objective is to transition TechGlobal from **informal security decision-making to structured, accountable and auditable security governance**.

---

# 1. Governance Architecture and Stakeholder Map

## 1.1 Current-State Governance Gap Assessment

TechGlobal's current model can be described as **security by informal decision**.

The IT Director is effectively acting as security owner, risk approver and operational decision-maker, while business units make local security decisions without a consistent enterprise governance mechanism.

| # | Current Weakness                                                        | Business / Risk Consequence                                                                  |
| - | ----------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| 1 | Security authority is concentrated with the IT Director                 | Excessive dependence on one role and potential conflicts of interest                         |
| 2 | No formal security governance committee                                 | Cross-functional decisions may occur without Risk, Legal, Finance, HR or business-unit input |
| 3 | Ownership, risk acceptance and implementation are not clearly separated | Weak independent challenge and potential self-approval                                       |
| 4 | Business units make inconsistent security decisions                     | Uneven security exposure across offices and business areas                                   |
| 5 | Limited Board visibility into cyber risk                                | Reduced ability to exercise effective oversight                                              |
| 6 | No reliable escalation pathway                                          | Material risks may remain at operational level for too long                                  |
| 7 | Governance accountability is unclear                                    | Decisions may be delayed or disputed                                                         |
| 8 | Lack of formal decision records                                         | Difficulty demonstrating who approved significant decisions and why                          |

---

## 1.2 Stakeholder Map

| Stakeholder               | Authority / Influence      | Primary Interest                                                       | Governance Contribution                            |
| ------------------------- | -------------------------- | ---------------------------------------------------------------------- | -------------------------------------------------- |
| **Board of Directors**    | Very High                  | Risk appetite, material cyber risk, regulatory exposure and reputation | Oversight, risk appetite and strategic challenge   |
| **CEO**                   | Very High                  | Business performance and strategic alignment                           | Executive accountability and decision-making       |
| **CISO**                  | High                       | Security strategy, policy and programme effectiveness                  | Security governance leadership                     |
| **CRO / Risk**            | High                       | Enterprise risk integration                                            | Risk methodology, challenge and aggregation        |
| **Legal / Compliance**    | High                       | Regulatory and contractual obligations                                 | Legal advice and regulatory assessment             |
| **Finance**               | Medium–High                | Budget, loss exposure and investment priorities                        | Financial governance and resource decisions        |
| **HR**                    | Medium                     | People-related security risks                                          | People governance and awareness                    |
| **IT / Technology**       | High                       | Availability, implementation and continuity                            | Technical implementation and control operation     |
| **Business Unit Leaders** | High within business units | Operational performance and local risk                                 | Business risk ownership and control implementation |

---

## 1.3 Proposed Security Governance Architecture

The proposed architecture separates **oversight, executive direction, security governance, enterprise-risk challenge and operational implementation**.

```text
                         BOARD OF DIRECTORS
                                  │
                    Oversight & Risk Appetite
                                  │
                                 CEO
                                  │
                     Executive Accountability
                                  │
              ┌───────────────────┴───────────────────┐
              │                                       │
             CISO                               CRO / RISK
              │                                       │
    Security Governance                    Enterprise Risk Challenge
              │
    Security Governance Committee
              │
     ┌────────┼────────┬──────────┐
     │        │        │          │
    IT      Legal      HR     Business Units
     │
Technical Implementation
```

### Governance Design

The model establishes:

* **Board:** Oversight of material cyber risk and risk appetite
* **CEO:** Executive accountability
* **CISO:** Enterprise security governance leadership
* **CRO/Risk:** Risk methodology and independent challenge
* **IT:** Technical implementation and operations
* **Business Units:** Ownership of operational risks
* **Internal Audit:** Independent assurance

---

## 1.4 Governance Model Justification

A 2,500-employee organisation operating across five global offices requires a governance model that can scale without creating unnecessary bureaucracy.

A fully centralised security model would maintain TechGlobal's current dependency on IT. Conversely, allowing every business unit to make independent security decisions would increase inconsistency and enterprise risk.

The proposed model therefore combines:

> **Central Governance + Distributed Business Ownership + Independent Challenge + Executive Oversight**

---

# 2. Governance Responsibility and Authority Matrix

## 2.1 Responsibility Profiles

| Role                      | Purpose                              | Core Responsibilities                                   | Decision Authority                          |
| ------------------------- | ------------------------------------ | ------------------------------------------------------- | ------------------------------------------- |
| **Board**                 | Provide oversight and accountability | Risk appetite, material cyber risk, assurance           | Risk appetite and material-risk decisions   |
| **CEO**                   | Hold executive accountability        | Strategy, priorities and resources                      | Executive security and investment decisions |
| **CISO**                  | Lead enterprise security governance  | Security strategy, policy, risk oversight and reporting | Security governance and standards           |
| **CRO / Risk**            | Integrate cyber risk into ERM        | Risk methodology, challenge and aggregation             | Risk methodology and challenge              |
| **Legal / Compliance**    | Provide regulatory oversight         | Privacy, contracts and regulatory advice                | Regulatory advice                           |
| **Finance**               | Ensure financial governance          | Budgeting and investment prioritisation                 | Budget allocation within authority          |
| **HR**                    | Manage people governance             | Joiner/mover/leaver controls, training and conduct      | HR process decisions                        |
| **IT / Technology**       | Implement and operate controls       | Architecture, secure operations and continuity          | Technical implementation                    |
| **Business Unit Leaders** | Own business risk                    | Business risks and control implementation               | Business risk decisions within authority    |

---

## 2.2 Authority Principles

The governance model applies five core authority principles:

1. **One clear accountable owner** should be identified for major governance decisions.
2. **Risk acceptance** should not automatically belong to the person or team implementing the control.
3. **Business owners** remain responsible for business risks arising from their operations.
4. **Legal and Compliance** provide advice and challenge but do not automatically own business decisions.
5. **Internal Audit** remains separate from management decision-making to preserve independent assurance.

---

## 2.3 Overlapping Authority and Conflict Resolution

| Conflict Area             | Governance Issue                                                | Resolution Principle                                                                   |
| ------------------------- | --------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| **CISO vs IT**            | CISO defines security requirements while IT implements controls | CISO owns governance; IT owns technical implementation                                 |
| **CISO vs CRO/Risk**      | Both functions may assess security risks                        | CISO owns security analysis; CRO/Risk owns enterprise methodology and challenge        |
| **Business Unit vs CISO** | Business unit may want to accept security risk                  | Risk acceptance follows delegated authority and defined thresholds                     |
| **Legal vs Business**     | Regulatory obligations may affect commercial decisions          | Legal provides authoritative advice; authorised business leadership makes the decision |

---

# 3. Security Governance Committee Ecosystem

## 3.1 Committee Structure

### Executive Security Council

**Chair:** CEO

**Core Members:**

* CEO
* CISO
* CRO/Risk
* CFO/Finance
* Legal/Compliance
* HR
* CIO/IT
* Selected business executives

**Responsibilities:**

* Review enterprise cyber-risk exposure
* Approve strategic security priorities
* Resolve major conflicts
* Review security investments
* Determine Board escalations

---

### Security Governance / Steering Committee

**Chair:** CISO

**Core Members:**

* CISO
* CRO/Risk
* IT
* Legal/Compliance
* Finance
* HR
* Business-unit representatives
* Relevant security specialists

**Responsibilities:**

* Review policies
* Monitor risks
* Track control performance
* Monitor remediation
* Review third-party risks
* Review security architecture decisions
* Track programme progress

---

### Third-Party Security Working Group

**Purpose:** Focused supplier and third-party risk review.

**Core Participants:**

* Security
* IT
* Procurement
* Legal
* Risk
* Business owner

**Responsibilities:**

* Assess supplier security requirements
* Review high-risk suppliers
* Track remediation
* Review contractual security requirements
* Escalate unacceptable risk

---

## 3.2 Governance Information Flow

```text
Business Units / IT / Security Operations
                  │
                  ▼
        Security Governance Committee
                  │
          Risk & Decision Review
                  │
                  ▼
         Executive Security Council
                  │
       Material Risk / Escalation
                  │
                  ▼
             Board / Committee
```

---

## 3.3 Terms of Reference

| Element                | Definition                                                                                                 |
| ---------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Purpose**            | Cross-functional forum for security risk, policy, investment, compliance and technology decisions          |
| **Scope**              | Security policies, risks, remediation, third-party risk, incidents, architecture and compliance            |
| **Chair**              | CISO                                                                                                       |
| **Membership**         | CRO/Risk, IT, Legal/Compliance, Finance, HR, business units and relevant specialists                       |
| **Cadence**            | Monthly for the first six months; quarterly once governance stabilises                                     |
| **Decision Authority** | Endorse standards, approve operational approaches within delegated authority and assign remediation owners |
| **Reporting**          | Minutes, decision logs, action trackers and escalation notes                                               |

---

## 3.4 Business Unit Participation

Business units should not create independent security governance silos.

Each major business unit should nominate a:

> **Security Champion / Business Information Security Officer (BISO)**

The BISO acts as a bridge between central security governance and business operations.

---

## 3.5 Sample Committee Agenda

1. Opening and approval of previous minutes
2. Outstanding actions and overdue decisions
3. Cyber-risk dashboard and trend review
4. High-risk vulnerabilities and remediation
5. Major incidents and near-misses
6. Third-party security risks
7. Security policy changes and exceptions
8. Security architecture decisions
9. Compliance and regulatory matters
10. Security programme progress
11. Executive or Board escalations
12. New actions, owners and due dates

---

## 3.6 Sample Decision Log

| Date       | Decision / Issue                                                 | Decision Owner                | Rationale                                  | Action                             | Review               |
| ---------- | ---------------------------------------------------------------- | ----------------------------- | ------------------------------------------ | ---------------------------------- | -------------------- |
| 22/09/2026 | High-risk supplier requires remediation before production access | CISO                          | Critical security gaps identified          | Procurement & IT track remediation | 30/09/2026           |
| 22/09/2026 | Enterprise MFA requirement approved                              | Security Governance Committee | Consistent authentication control required | IT prepares implementation plan    | 30/11/2026           |
| 22/09/2026 | Critical vulnerability escalated                                 | CISO                          | Exposure affects business-critical service | IT remediation tracked weekly      | Weekly until closure |

---

## 3.7 Twelve-Month Governance Calendar

| Month  | Major Governance Activity                                         |
| ------ | ----------------------------------------------------------------- |
| **1**  | Governance model launch and role confirmation                     |
| **2**  | Enterprise cyber-risk assessment                                  |
| **3**  | Policy and standards review                                       |
| **4**  | Third-party security review                                       |
| **5**  | Security awareness review                                         |
| **6**  | Mid-year governance effectiveness review                          |
| **7**  | Business continuity / recovery governance review                  |
| **8**  | Security architecture review                                      |
| **9**  | Access governance review                                          |
| **10** | Incident response governance exercise                             |
| **11** | Annual security strategy and budget planning                      |
| **12** | Annual Board cyber-risk review and governance maturity assessment |

---

# 4. RACI Accountability Matrix

**R = Responsible | A = Accountable | C = Consulted | I = Informed**

| Activity                                  | Board | CEO | CISO | CRO/Risk | Legal | Finance | HR | IT | BU |
| ----------------------------------------- | ----- | --- | ---- | -------- | ----- | ------- | -- | -- | -- |
| Cybersecurity strategy approval           | A     | R   | R    | C        | C     | C       | I  | C  | C  |
| Security policy approval                  | I     | A   | R    | C        | C     | I       | C  | C  | C  |
| Enterprise cyber-risk assessment          | I     | I   | R    | A        | C     | I       | C  | C  | C  |
| Risk acceptance                           | I     | C   | C    | R/C      | C     | C       | I  | I  | A* |
| Security budget approval                  | I     | A   | R    | C        | I     | R       | I  | C  | C  |
| Security architecture approval            | I     | I   | A    | C        | C     | I       | I  | R  | C  |
| Third-party security review               | I     | I   | A    | C        | C     | C       | I  | R  | R  |
| Access governance                         | I     | I   | A    | C        | C     | I       | R  | R  | R  |
| Incident response governance              | I     | A   | R    | C        | C     | I       | C  | R  | C  |
| Material incident escalation              | I**   | A   | R    | C        | C     | I       | I  | R  | C  |
| Regulatory notification decision          | I     | A   | C    | C        | R     | I       | I  | C  | I  |
| Security awareness programme              | I     | I   | A    | C        | C     | I       | R  | C  | R  |
| Vulnerability remediation oversight       | I     | I   | A    | C        | I     | C       | I  | R  | R  |
| Business continuity / recovery governance | I     | A   | C    | C        | C     | C       | C  | R  | R  |
| Board cyber-risk reporting                | I     | A   | R    | C        | C     | I       | I  | C  | I  |

> ***** Risk acceptance above delegated authority escalates to the CEO or Board according to the applicable threshold.
>
> ****** The Board becomes accountable when a material Board-level decision or risk-appetite matter is required.

---

## 4.1 Problematic RACI Assignments Corrected

| Problem                                           | Governance Risk                | Correction                                              |
| ------------------------------------------------- | ------------------------------ | ------------------------------------------------------- |
| Multiple accountable parties                      | Ambiguous accountability       | Board owns oversight; CEO owns executive implementation |
| IT accountable for enterprise security governance | Recreates the IT-centric model | CISO owns security governance; IT owns implementation   |
| Business units excluded from risk activities      | Weak business ownership        | Business units remain accountable for operational risk  |

---

## 4.2 RACI Implementation Guide

### Planning

Confirm the Responsible and Accountable roles before work begins.

### Approvals

Verify that the person approving a decision has the appropriate authority.

### Incidents

Use the RACI to identify decision-makers quickly during an active incident.

### Review

Review the RACI whenever there is a significant organisational, regulatory or technology change.

---

# 5. Cyber-Risk Escalation, Segregation of Duties and Assurance

## 5.1 Major Cyber-Risk Escalation Workflow

```text
Cyber Risk / Security Issue Identified
                 │
                 ▼
       Assess Business Impact
                 │
                 ▼
        Determine Risk Level
                 │
        ┌────────┼────────┐
        │        │        │
        ▼        ▼        ▼
     Level 1  Level 2  Level 3
     Operational Executive Material
        │        │        │
        ▼        ▼        ▼
   Operational   CEO /    CEO + Board
   Management   Council
                 │
                 ▼
          Decision Recorded
                 │
                 ▼
        Action & Remediation
                 │
                 ▼
        Review and Closure
```

---

## 5.2 Escalation Thresholds

| Level                          | Example Trigger                                                                        | Decision Authority                     | Response                         |
| ------------------------------ | -------------------------------------------------------------------------------------- | -------------------------------------- | -------------------------------- |
| **Level 1 – Operational**      | Limited business impact or routine control issue                                       | Operational owner / IT / CISO delegate | Immediate operational handling   |
| **Level 2 – Executive**        | Significant disruption, major control failure or substantial customer/financial impact | CEO / Executive Security Council       | Formal incident or risk response |
| **Level 3 – Material / Board** | Material financial, reputational or regulatory impact                                  | CEO + Board / appropriate committee    | Executive and Board-led response |

---

## 5.3 Segregation-of-Duties Weakness Register

| ID | Weakness                                                             | Risk Created                          | Recommended Control                                           | Residual Risk |
| -- | -------------------------------------------------------------------- | ------------------------------------- | ------------------------------------------------------------- | ------------- |
| 1  | IT Director acts as security owner, risk approver and implementer    | Self-approval                         | Separate CISO governance, CRO challenge and IT implementation | Medium        |
| 2  | Same person could request and approve privileged access              | Privilege escalation                  | Manager approval + security validation + IT provisioning      | Low–Medium    |
| 3  | IT could approve its own security architecture exceptions            | Security requirements may be bypassed | CISO approval for security exceptions                         | Low           |
| 4  | Business unit could accept risk without enterprise visibility        | Unmanaged enterprise risk             | Formal thresholds + central risk register                     | Medium        |
| 5  | Incident responders could close incidents without independent review | Control failures may be missed        | Post-incident review                                          | Low           |
| 6  | Security budget decisions lack financial challenge                   | Poor prioritisation                   | Joint CISO/Finance business case                              | Low           |
| 7  | Security team could design and assure its own controls               | Reduced objectivity                   | Independent Internal Audit assurance                          | Low           |

---

## 5.4 Decision Recording and Assurance

Every significant governance decision should have a documented record.

### Minimum Decision Record

```text
Date
Decision Owner
Issue / Risk Statement
Decision Made
Decision Authority
Evidence Considered
Risk Assessment
Alternatives Considered
Conditions / Exceptions
Residual Risk
Actions and Owners
Target Completion Date
Review Date
Closure Status
```

Decision records provide an auditable trail demonstrating:

* What decision was made
* Who made the decision
* Whether they had the appropriate authority
* What evidence was considered
* What actions were agreed
* Whether those actions were completed

Internal Audit should remain independent from management decision-making and may periodically assess whether the governance and decision-recording processes are operating effectively.

---

# 6. Overall Consultant Recommendation

TechGlobal should transition from its current **IT-centric informal governance model** to a structured governance model based on:

> **Clear Accountability + Distributed Ownership + Independent Challenge + Formal Escalation + Continuous Oversight**

### Priority Actions

1. Confirm Board and CEO oversight responsibilities.
2. Establish the CISO as security governance leader.
3. Establish the Security Governance Committee.
4. Define CRO/Risk challenge responsibilities.
5. Formalise business-unit security ownership.
6. Implement the RACI matrix.
7. Introduce cyber-risk escalation thresholds.
8. Establish a formal decision log.
9. Implement segregation-of-duties controls.
10. Introduce ongoing governance effectiveness reviews.

### Target Governance State

```text
CURRENT STATE
────────────────────────────────────────
IT-Centric Governance
        ↓
Unclear Accountability
        ↓
Inconsistent Decisions
        ↓
Limited Risk Visibility


TARGET STATE
────────────────────────────────────────
Defined Governance
        ↓
Clear Decision Rights
        ↓
Distributed Business Ownership
        ↓
Independent Risk Challenge
        ↓
Structured Escalation
        ↓
Auditable Decisions
        ↓
Continuous Oversight
```

The proposed model is intended to make security governance **visible, accountable, consistent and auditable**, while avoiding unnecessary bureaucracy.

---

# 7. References

1. International Cybersecurity and Digital Forensics Academy. (2026a). *GRC102 Week 3 Practical Laboratory: Roles, Responsibilities and Accountability in Security Governance.*

2. International Cybersecurity and Digital Forensics Academy. (2026b). *Roles and Responsibilities in Security Governance.*

3. International Organization for Standardization. (2020). *ISO/IEC 27014:2020 – Information security, cybersecurity and privacy protection — Governance of information security.*

4. ISACA. (2019). *COBIT 2019 Framework: Governance and Management Objectives.*

5. National Institute of Standards and Technology. (2024). *The NIST Cybersecurity Framework (CSF) 2.0.*

6. The Institute of Internal Auditors. (2020). *The IIA's Three Lines Model: An Update of the Three Lines of Defense.*

---

# 🤖 AI Assistance Declaration

AI tools were used to support **research, content refinement, report structure, and the formatting and professional alignment of diagrams and tables**.

The final submission was reviewed and adapted by the student, who remains responsible for **factual accuracy, framework interpretation and originality**.

Forensics Academy

---

> **Portfolio Disclaimer**
>
> This project is an academic governance simulation developed for the GRC102 practical laboratory. **TechGlobal is a simulated organisation** used for the purposes of the exercise.

