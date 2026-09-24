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

## Executive Summary

TechGlobal is a global organisation with approximately 2,500 employees across five offices. Its current security governance model is largely IT-centric, with significant security decisions concentrated around the IT Director. Business units also make security-related decisions inconsistently, while visibility at CEO and Board level remains limited.

The assessment identified that the core issue is not simply technical security capability. The organisation requires clearer governance structures, decision rights, accountability, escalation mechanisms, and segregation of duties.

As the Lead Security Governance Consultant, the proposed governance model establishes clear separation between:

* **Board oversight**
* **CEO executive accountability**
* **CISO-led security governance**
* **CRO/Risk challenge and enterprise risk oversight**
* **Executive and security governance committees**
* **IT operational implementation**
* **Business Unit risk ownership**

The proposed model is aligned with the principles of **ISO/IEC 27014**, **NIST Cybersecurity Framework (CSF) 2.0**, **COBIT 2019**, and the **IIA Three Lines Model**.

---

# 1. Governance Architecture and Stakeholder Map

## 1.1 Current-State Governance Gap Assessment

The assessment identified the following governance weaknesses:

| Governance Gap             | Current Condition                                                          | Governance Impact                                                |
| -------------------------- | -------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| Concentration of authority | Security authority is heavily concentrated with the IT Director            | Creates key-person dependency and weakens independent challenge  |
| Committee structure        | No formal security governance committee                                    | Security decisions may be inconsistent or undocumented           |
| Accountability             | Ownership, risk acceptance and implementation responsibilities are unclear | Creates accountability gaps                                      |
| Business-unit governance   | Business units make security decisions inconsistently                      | Creates uneven security practices across the organisation        |
| Board visibility           | Limited reporting to the Board                                             | Strategic security risks may not receive appropriate oversight   |
| Escalation                 | No clearly defined escalation path                                         | Material risks may not reach the appropriate authority           |
| Decision records           | No formal decision-recording mechanism                                     | Difficult to demonstrate why decisions were made                 |
| Segregation of duties      | Some security activities are concentrated within the same functions        | Creates potential conflicts of interest and assurance weaknesses |

---

## 1.2 Key Stakeholders

The proposed governance model involves the following stakeholders:

| Stakeholder           | Primary Governance Role                                                                |
| --------------------- | -------------------------------------------------------------------------------------- |
| Board                 | Provides oversight and challenges management on material security risks                |
| CEO                   | Holds executive accountability for organisational security governance                  |
| CISO                  | Leads information security governance and provides security direction                  |
| CRO / Risk            | Provides independent enterprise risk challenge and oversight                           |
| Legal / Compliance    | Provides regulatory, legal and compliance advice                                       |
| Finance               | Provides financial oversight and challenge for security investments                    |
| HR                    | Supports people-related security responsibilities                                      |
| IT / Technology       | Implements and operates technical security controls                                    |
| Business Unit Leaders | Own business risks and ensure security requirements are implemented within their areas |

---

## 1.3 Proposed Governance Architecture

```text
                         BOARD
                           │
                    Oversight & Challenge
                           │
                          CEO
                           │
              Executive Accountability
                           │
        ┌──────────────────┴──────────────────┐
        │                                     │
       CISO                              CRO / RISK
        │                                     │
 Security Governance                  Risk Challenge
        │                                     │
        └──────────────┬──────────────────────┘
                       │
          Security Governance Committee
                       │
        ┌──────────────┼──────────────┐
        │              │              │
       IT             BU Leaders      Legal/
   Technology         / Security      Compliance
                       Champions
        │
 Technical Implementation
```

---

## 1.4 Governance Model Justification

The proposed structure separates **accountability, ownership, implementation and assurance**.

The Board provides oversight rather than managing day-to-day security activities.

The CEO provides executive accountability and ensures that security is treated as an organisational risk rather than solely an IT issue.

The CISO provides security governance leadership, while the CRO/Risk function provides independent risk challenge.

IT remains responsible for technical implementation, but it should not automatically own all security risks or approve its own exceptions without appropriate challenge.

Business Unit Leaders retain ownership of risks arising from their business activities.

This structure creates clearer decision rights and reduces the concentration of authority within a single function.

---

# 2. Governance Responsibility and Authority Matrix

## 2.1 Responsibility Profiles

### Board

* Provide oversight of material information security risks.
* Challenge management on security performance.
* Review significant security incidents and risk exposures.
* Ensure security receives appropriate strategic attention.

### CEO

* Hold executive accountability for security governance.
* Ensure security responsibilities are clearly assigned.
* Chair the Executive Security Council.
* Ensure material security risks are escalated appropriately.

### CISO

* Lead the information security governance programme.
* Develop and maintain the security strategy.
* Coordinate security policies, standards and governance processes.
* Report security risks and performance to executive management.
* Coordinate security governance committees.

### CRO / Risk

* Provide independent risk challenge.
* Ensure security risks are integrated into enterprise risk management.
* Challenge risk assessments and risk acceptance decisions.
* Support escalation of material risks.

### Legal / Compliance

* Provide regulatory and legal guidance.
* Advise on contractual and compliance obligations.
* Challenge decisions where legal or regulatory exposure exists.

### IT / Technology

* Implement approved technical controls.
* Operate security technologies and infrastructure.
* Remediate technical security weaknesses.
* Maintain technical documentation.

### Business Unit Leaders

* Own risks arising from their business activities.
* Ensure security requirements are implemented within their areas.
* Participate in risk acceptance decisions.
* Escalate security concerns appropriately.

---

## 2.2 Authority Principles

The following principles should guide governance decisions:

1. **Every significant security decision should have one clearly accountable owner.**
2. **Risk acceptance should not automatically sit with the person responsible for implementing the control.**
3. **Business owners should own business risks.**
4. **Legal and Compliance should provide advice and challenge where appropriate.**
5. **Internal Audit should remain independent from operational management and control ownership.**
6. **Material decisions should be documented and traceable.**
7. **Conflicts of interest should be identified and managed through segregation of duties.**

---

## 2.3 Conflict Resolution

### CISO vs IT

Where the CISO and IT disagree on a security control or technical implementation decision, the matter should first be discussed through the Security Governance Committee.

If unresolved and the matter presents material risk, it should be escalated to the CEO and CRO/Risk.

### CISO vs CRO/Risk

Where security and enterprise risk functions disagree on risk treatment, the issue should be documented and escalated through the appropriate executive governance forum.

### Business Unit vs CISO

Business Unit Leaders may challenge security requirements where they affect business operations. However, material security risks should not be accepted without appropriate authority and documentation.

### Legal / Compliance vs Business

Where legal or regulatory requirements conflict with business preferences, Legal/Compliance should document the regulatory obligation and escalate unresolved issues through governance channels.

---

# 3. Security Governance Committee Ecosystem

## 3.1 Executive Security Council

**Chair:** CEO

**Purpose:** Provide executive oversight of significant security risks, priorities and decisions.

### Key Responsibilities

* Review material security risks.
* Review significant incidents.
* Review security strategy and priorities.
* Approve major security initiatives.
* Resolve escalated governance issues.
* Provide direction on risk treatment.

---

## 3.2 Security Governance / Steering Committee

**Chair:** CISO

**Purpose:** Provide cross-functional security governance and coordinate security-related decisions.

### Core Membership

* CISO
* CRO / Risk
* IT / Technology
* Legal / Compliance
* Finance
* HR
* Business Unit representatives
* Other subject matter experts as required

### Key Responsibilities

* Review security policies and standards.
* Review security risks and remediation activities.
* Review third-party security risks.
* Review significant control weaknesses.
* Monitor security governance performance.
* Prepare matters requiring executive escalation.

### Meeting Frequency

The committee should meet **monthly during the first six months** of implementation and then move to a **quarterly schedule** once governance processes are established and operating effectively.

---

## 3.3 Third-Party Security Working Group

**Purpose:** Coordinate security governance for suppliers, vendors and other third parties.

### Key Responsibilities

* Review third-party security risks.
* Coordinate due diligence requirements.
* Review security clauses in contracts.
* Track third-party remediation actions.
* Escalate high-risk supplier issues.
* Monitor supplier security obligations.

---

## 3.4 Governance Information Flow

```text
Business Units
      │
      ▼
Security Champions / BISO
      │
      ▼
Security Governance Committee
      │
      ├──────────────► CRO / Risk
      │
      ├──────────────► Legal / Compliance
      │
      └──────────────► CISO
                          │
                          ▼
                  Executive Security Council
                          │
                          ▼
                         CEO
                          │
                          ▼
                        Board
```

---

## 3.5 Terms of Reference

### Purpose

The Security Governance Committee provides a formal cross-functional forum for reviewing, challenging and coordinating information security governance matters.

### Scope

The committee should cover:

* Security policies and standards
* Security risks
* Risk treatment and remediation
* Security incidents
* Third-party security
* Security architecture
* Compliance obligations
* Security performance
* Security awareness
* Governance issues requiring escalation

### Decision Authority

The committee should:

* Review and challenge security decisions.
* Recommend decisions to executive management where required.
* Escalate material risks.
* Track agreed actions.
* Maintain decision records.

---

## 3.6 Business Unit Security Champions

Each Business Unit should designate a **Security Champion or Business Information Security Officer (BISO)**.

### Responsibilities

* Act as the connection between the Business Unit and security governance.
* Promote security awareness.
* Identify business-specific security risks.
* Support risk assessments.
* Track remediation activities.
* Escalate security issues.

---

## 3.7 Sample Committee Agenda

1. Opening and confirmation of previous minutes
2. Review of outstanding actions
3. Current security risk profile
4. New and emerging risks
5. Security incidents
6. Vulnerability and remediation status
7. Third-party security risks
8. Policy and compliance updates
9. Security projects and investments
10. Decisions requiring approval
11. Escalations to Executive Security Council
12. Any other business
13. Closing and confirmation of actions

---

## 3.8 Sample Decision Log

| Decision ID | Date       | Decision                     | Owner | Risk   | Approval Authority            | Status      |
| ----------- | ---------- | ---------------------------- | ----- | ------ | ----------------------------- | ----------- |
| SEC-001     | 2026-09-25 | Example security exception   | CISO  | High   | Executive Security Council    | Open        |
| SEC-002     | 2026-09-25 | Example remediation priority | IT    | Medium | Security Governance Committee | In Progress |

The decision log should provide traceability for significant governance decisions.

---

## 3.9 12-Month Governance Calendar

| Month    | Key Governance Activity                              |
| -------- | ---------------------------------------------------- |
| Month 1  | Establish governance structure and confirm roles     |
| Month 2  | Approve committee Terms of Reference                 |
| Month 3  | Establish risk and decision registers                |
| Month 4  | Conduct governance maturity review                   |
| Month 5  | Review security policies and accountability          |
| Month 6  | Conduct first formal governance effectiveness review |
| Month 7  | Review third-party security governance               |
| Month 8  | Review security metrics and reporting                |
| Month 9  | Review segregation of duties                         |
| Month 10 | Conduct risk escalation exercise                     |
| Month 11 | Review Board reporting                               |
| Month 12 | Annual governance effectiveness assessment           |

---

# 4. RACI Accountability Matrix

## 4.1 RACI Definitions

| RACI                | Meaning                                 |
| ------------------- | --------------------------------------- |
| **R – Responsible** | Performs the activity                   |
| **A – Accountable** | Owns the final outcome and decision     |
| **C – Consulted**   | Provides input before the decision      |
| **I – Informed**    | Receives information about the decision |

---

## 4.2 Governance RACI Matrix

| Activity                         | Board | CEO | CISO | CRO/Risk | Legal/Compliance | IT  | BU |
| -------------------------------- | ----- | --- | ---- | -------- | ---------------- | --- | -- |
| Approve security strategy        | C     | A   | R    | C        | C                | C   | C  |
| Security policy governance       | I     | A   | R    | C        | C                | C   | C  |
| Security risk assessment         | I     | A   | R    | C        | C                | C   | R  |
| Risk acceptance                  | I     | A   | C    | C        | C                | I   | R  |
| Technical control implementation | I     | I   | C    | I        | I                | A/R | C  |
| Security incident management     | I     | A   | R    | C        | C                | R   | C  |
| Third-party security             | I     | A   | R    | C        | C                | R   | C  |
| Security reporting               | I     | A   | R    | C        | C                | C   | C  |
| Material risk escalation         | C     | A   | R    | R        | C                | C   | C  |
| Security assurance               | I     | A   | C    | C        | C                | C   | C  |

---

## 4.3 Problematic Assignments Corrected

The following governance issues should be corrected:

### IT approving its own security exceptions

Where IT both implements a control and approves an exception to that control, independence may be weakened.

**Improvement:** Require CISO and/or appropriate risk authority review depending on the level of risk.

### Business Unit accepting material risks without visibility

Business units may understand their operational risks, but material security risks should be visible to the appropriate governance authority.

**Improvement:** Establish defined risk acceptance thresholds and escalation requirements.

### Security team performing its own independent assurance

A team should not be considered independent assurance when it is assessing controls that it owns or operates.

**Improvement:** Maintain an independent Internal Audit or assurance function.

---

## 4.4 RACI Implementation Principles

The RACI should be implemented using the following principles:

* Each activity should have **one Accountable owner**.
* Multiple people may be **Responsible** where appropriate.
* Consulted stakeholders should provide meaningful input.
* Informed stakeholders should receive appropriate updates.
* RACI assignments should be reviewed whenever organisational responsibilities change.

---

# 5. Cyber-Risk Escalation, Segregation of Duties and Assurance

## 5.1 Cyber-Risk Escalation Workflow

```text
Risk Identified
      │
      ▼
Business / IT Assessment
      │
      ▼
Security Governance Review
      │
      ▼
Risk Rating
      │
      ├── Low ─────► Operational Management
      │
      ├── Medium ──► Security Governance Committee
      │
      └── High / Material
                    │
                    ▼
            Executive Security Council
                    │
                    ▼
                   CEO
                    │
                    ▼
                  Board
```

---

## 5.2 Escalation Levels

### Level 1 – Operational

Used for routine risks that can be managed within operational teams.

Examples:

* Low-risk vulnerabilities
* Routine access issues
* Minor control deficiencies

### Level 2 – Executive

Used for risks requiring management attention.

Examples:

* Significant control weaknesses
* Repeated security incidents
* High-risk third-party findings
* Significant policy exceptions

### Level 3 – Material / Board

Used for risks that could materially affect the organisation.

Examples:

* Major security incidents
* Significant regulatory exposure
* Material business disruption
* Major unresolved cyber risks
* Significant risk acceptance decisions

---

# 5.3 Segregation of Duties Weakness Register

| ID     | Weakness                                                                         | Risk                                 | Recommended Control                               |
| ------ | -------------------------------------------------------------------------------- | ------------------------------------ | ------------------------------------------------- |
| SOD-01 | IT Director has excessive security decision authority                            | Concentration of authority           | Establish CISO and governance committee oversight |
| SOD-02 | Privileged access request and approval may be performed within the same function | Unauthorised or inappropriate access | Separate request, approval and provisioning       |
| SOD-03 | IT may approve its own architecture exceptions                                   | Conflict of interest                 | Require independent security/risk review          |
| SOD-04 | Business Units may accept risks without appropriate visibility                   | Uncontrolled risk exposure           | Define risk acceptance thresholds                 |
| SOD-05 | Incident closure may occur without governance review                             | Inadequate lessons learned           | Require appropriate post-incident review          |
| SOD-06 | Security budget decisions may lack independent financial challenge               | Poor investment decisions            | Include Finance in governance                     |
| SOD-07 | Security teams may perform self-assurance                                        | Reduced independence                 | Use independent assurance mechanisms              |

---

# 5.4 Security Decision Records

Significant security decisions should be documented using a standard decision-record format.

### Minimum Fields

* Decision ID
* Date
* Decision owner
* Issue or risk
* Options considered
* Recommended decision
* Business impact
* Security impact
* Regulatory impact
* Risk rating
* Risk owner
* Approval authority
* Decision outcome
* Actions required
* Due date
* Review date

This creates a clear audit trail and improves accountability.

---

# 5.5 Assurance Approach

The governance model should distinguish between:

**Management responsibility**

Management owns security risks and controls.

**Risk challenge**

CRO/Risk provides independent challenge and oversight.

**Operational implementation**

IT and Business Units implement and operate controls.

**Independent assurance**

Internal Audit or another appropriately independent assurance function evaluates governance and control effectiveness.

This separation supports stronger governance and reduces conflicts of interest.

---

# 6. Overall Consultant Recommendation

TechGlobal should transition from its current IT-centric and informal security governance model toward a structured governance framework with clearly defined accountability, authority and escalation.

The implementation should prioritise the following:

1. Establish clear **Board and CEO security oversight**.
2. Formalise the **CISO's security governance leadership role**.
3. Establish the **Security Governance Committee**.
4. Introduce **CRO/Risk challenge** into security risk decisions.
5. Assign clear **Business Unit security ownership**.
6. Implement a formal **RACI accountability framework**.
7. Establish defined **cyber-risk escalation thresholds**.
8. Introduce a formal **security decision log**.
9. Strengthen **segregation of duties**.
10. Maintain **independent assurance** over security governance and controls.

The objective is not to create additional bureaucracy. The objective is to ensure that the right people make the right security decisions, with clear accountability, appropriate challenge and documented authority.

---

# 7. References

1. International Cybersecurity and Digital Forensics Academy (ICDFA). **GRC102 – Information Security Governance, Week 3 Practical Laboratory: Roles, Responsibilities and Accountability in Security Governance.**
2. International Cybersecurity and Digital Forensics Academy (ICDFA). **Roles and Responsibilities in Security Governance – Module 3 Learning Materials.**
3. ISO/IEC 27014:2020. **Information security, cybersecurity and privacy protection — Governance of information security.**
4. ISACA. **COBIT 2019 Framework: Governance and Management Objectives.**
5. National Institute of Standards and Technology (NIST). **Cybersecurity Framework (CSF) 2.0.**
6. Institute of Internal Auditors (IIA). **The IIA's Three Lines Model.**

---

# AI Assistance Declaration

AI tools were used to support **research, structure, analysis, content refinement, and the formatting of diagrams and tables** within this report.

The final submission was reviewed and adapted by the student. The student remains responsible for the accuracy of the content, interpretation of the referenced governance frameworks, and originality of the submitted work.


---

> **Portfolio Disclaimer:**
> This report was developed as part of an academic governance simulation and is intended to demonstrate practical application of information security governance concepts. TechGlobal is a simulated organisation created for the purposes of the practical laboratory.
