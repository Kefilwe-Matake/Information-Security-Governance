# GRC102 – Information Security Governance

## Week 2 Practical Laboratory: Developing Security Policies and Procedures

**International Cybersecurity and Digital Forensics Academy (ICDFA)**

> **NexusTech Solutions – Policy Overhaul Simulation**

|                      |                              |
| -------------------- | ---------------------------- |
| **Role**             | Information Security Manager |
| **Student**          | Kefilwe Matake               |
| **Registration No.** | C11_26_CGRCE_17575           |
| **Submission Date**  | 18 September 2026            |
| **Assessment**       | Week 2 Practical Laboratory  |
| **Evidence Bundles** | 1–5                          |

---

## 📌 Project Overview

NexusTech Solutions has grown from a small software company into a **250-person organisation serving financial and healthcare clients**. Its existing five-year-old **"IT Rules"** document combines management requirements, technical configurations, operational procedures and informal recommendations.

This creates several governance challenges:

* Unclear distinction between mandatory requirements and recommendations
* Inconsistent security practices
* Unclear ownership and accountability
* Difficulty maintaining and updating security requirements
* Limited auditability of operational processes
* Increased risk as the organisation's technology and business environment evolves

### Project Objective

The objective of this laboratory was to redesign the security documentation structure and develop practical governance artefacts that are:

* **Clear**
* **Implementable**
* **Measurable**
* **Auditable**
* **Maintainable**
* **Aligned with security governance principles**

The work demonstrates how governance objectives can be translated into **policies, standards, procedures and guidelines**, supported by defined ownership, communication, training, review and continuous improvement processes.

---

# 📑 Contents

1. [Introduction](#1-introduction)
2. [Evidence Bundle 1 – Security Policy Hierarchy](#2-evidence-bundle-1--security-policy-hierarchy-and-categorisation)
3. [Evidence Bundle 2 – Acceptable Use Policy](#3-evidence-bundle-2--acceptable-use-policy)
4. [Evidence Bundle 3 – User Access Request Procedure](#4-evidence-bundle-3--user-access-request-procedure)
5. [Evidence Bundle 4 – Communication & Training Plan](#5-evidence-bundle-4--communication--training-plan)
6. [Evidence Bundle 5 – Policy Review & Maintenance](#6-evidence-bundle-5--policy-review--maintenance)
7. [Key Governance Outcomes](#7-key-governance-outcomes)
8. [References](#8-references)
9. [AI Assistance Declaration](#9-ai-assistance-declaration)

---

# 1. Introduction

The laboratory applies the Week 2 distinction between four levels of security documentation:

| Document Type | Purpose                                                               | Authority           | Requirement                |
| ------------- | --------------------------------------------------------------------- | ------------------- | -------------------------- |
| **Policy**    | Defines management intent, objectives and organisational expectations | Senior management   | Mandatory                  |
| **Standard**  | Defines specific minimum security requirements                        | Derived from policy | Mandatory                  |
| **Procedure** | Defines how approved activities are performed                         | Operational         | Mandatory where applicable |
| **Guideline** | Provides recommended implementation practices                         | Advisory            | Recommended                |

This hierarchy separates **what the organisation requires** from **how those requirements are implemented**.

### Governance Model

```text
                    GOVERNANCE
          Business objectives • Risk • Direction
                           │
                           ▼
                       POLICY
                  What & Why?
                           │
             ┌─────────────┴─────────────┐
             ▼                           ▼
         STANDARD                    GUIDELINE
     Mandatory minimums          Recommended practices
             │
             ▼
         PROCEDURE
           How?
```

### Example

An **Access Control Policy** may establish the requirement for secure authentication.

That requirement can then be translated into:

* **Standard:** MFA is required for defined access scenarios.
* **Procedure:** Helpdesk instructions for enrolling or resetting MFA.
* **Guideline:** Recommended practices for protecting authentication information.

This structure improves governance clarity while allowing technical standards and operational procedures to evolve without unnecessarily rewriting the overarching policy.

---

# 2. Evidence Bundle 1 – Security Policy Hierarchy and Categorisation

## 2.1 Policy Hierarchy

The hierarchy was used to replace the mixed and outdated **"IT Rules"** document with a structured security documentation architecture.

### Key Governance Principle

> High-level policies should remain relatively stable, while standards and procedures can evolve as technology, threats and operational processes change.

---

## 2.2 Classification of Draft Security Statements

|  # | Draft Statement                                                                                           | Classification | Rationale                                                    |
| -: | --------------------------------------------------------------------------------------------------------- | -------------- | ------------------------------------------------------------ |
|  1 | Employees must use MFA when accessing the corporate network remotely.                                     | **Standard**   | Defines a specific, measurable authentication requirement.   |
|  2 | Configure MFA by downloading the Authenticator app, scanning the QR code and entering the six-digit code. | **Procedure**  | Provides sequential instructions for completing an activity. |
|  3 | Developers are recommended to use parameterised queries to reduce SQL injection risk.                     | **Guideline**  | Provides recommended secure development practice.            |
|  4 | NexusTech is committed to protecting confidentiality, integrity and availability of client data.          | **Policy**     | Expresses high-level management intent.                      |
|  5 | Corporate laptops must use full-disk encryption with BitLocker or FileVault.                              | **Standard**   | Defines a mandatory and technically verifiable control.      |
|  6 | Employees should avoid public, unsecured Wi-Fi when travelling.                                           | **Guideline**  | Provides recommended user behaviour.                         |
|  7 | A suspected security breach must be reported immediately to the IT Helpdesk at extension 5555.            | **Procedure**  | Defines the operational response and reporting route.        |
|  8 | Passwords must be at least 14 characters and include uppercase, lowercase, number and special character.  | **Standard**   | Defines measurable password requirements.                    |

### Governance Observation

The exercise demonstrates why a generic **"Password Policy"** can create confusion when it combines different types of requirements.

A better structure is:

```text
Access / Authentication Policy
            │
            ├── Password Standard
            ├── MFA Standard
            │
            └── Password Reset Procedure
```

---

# 3. Evidence Bundle 2 – Acceptable Use Policy

## NexusTech Solutions – Acceptable Use Policy

| Field                  | Details                      |
| ---------------------- | ---------------------------- |
| **Document ID**        | NTS-ISP-001                  |
| **Version**            | 1.0                          |
| **Status**             | Pending Management Review    |
| **Policy Owner**       | Information Security Manager |
| **Approval Authority** | CEO                          |
| **Effective Date**     | Upon Approval                |
| **Review Cycle**       | At least annually            |
| **Classification**     | Internal                     |

### 3.1 Purpose

The policy establishes requirements for the responsible and secure use of NexusTech information systems, corporate devices, networks and information resources.

Its objective is to reduce:

* Cybersecurity risk
* Operational risk
* Legal and compliance risk
* Information-handling risk
* Unauthorised access
* Misuse of corporate resources

while supporting legitimate business activities.

---

## 3.2 Scope

The policy applies to:

* Employees
* Contractors
* Consultants
* Temporary staff
* Other authorised users

It covers access to NexusTech:

* Information systems
* Networks
* Applications
* Devices
* Corporate information
* Authorised devices used to access company resources

---

## 3.3 Acceptable Use Requirements

Users must:

* Use NexusTech systems primarily for authorised business purposes.
* Protect credentials and authentication information.
* Secure devices when unattended.
* Use authorised software, applications and storage services.
* Protect confidential company and client information.
* Promptly report suspected security incidents and phishing attempts.
* Report lost devices or suspected unauthorised access.
* Follow applicable security policies, standards and procedures.
* Comply with applicable legal, contractual and organisational requirements.

---

## 3.4 Prohibited Activities

Users must not:

* Install unauthorised software.
* Disable or bypass security controls.
* Share passwords, authentication tokens or accounts.
* Access systems or information without authorisation.
* Use corporate systems for unlawful, fraudulent or malicious activities.
* Store confidential company or client information in unauthorised personal cloud storage.
* Transfer sensitive information through unauthorised personal email or file-sharing services.
* Knowingly introduce malware.
* Create unacceptable security, legal, operational or reputational risk.

---

## 3.5 Reasonable Personal Use

Limited personal use may be permitted where it:

* Does not interfere with work responsibilities.
* Does not create unacceptable security or compliance risk.
* Does not consume excessive organisational resources.
* Does not involve prohibited activities.
* Does not involve unauthorised handling of company or client information.

NexusTech may restrict or withdraw personal-use privileges where misuse creates unacceptable risk.

---

## 3.6 Roles and Responsibilities

| Role                          | Responsibility                                                                   |
| ----------------------------- | -------------------------------------------------------------------------------- |
| **Employees / Users**         | Comply with the AUP, protect information and credentials, and report incidents.  |
| **Managers**                  | Reinforce requirements and escalate repeated or serious violations.              |
| **IT & Information Security** | Implement supporting controls, provide guidance and investigate security events. |
| **Human Resources**           | Support onboarding, acknowledgement and disciplinary processes.                  |

---

## 3.7 Compliance and Enforcement

Users must acknowledge the policy and complete required awareness training.

Where appropriate, NexusTech may monitor use of its information resources in accordance with applicable organisational and legal requirements.

Violations may result in:

* Corrective action
* Access restriction
* Disciplinary action
* Contractual consequences
* Legal action

depending on the nature and severity of the violation.

---

## 3.8 Exceptions

Exceptions must be:

1. Formally documented
2. Supported by a legitimate business justification
3. Assessed for security and compliance risk
4. Approved by the appropriate authority
5. Time-limited where practical
6. Supported by compensating controls where required

Emergency exceptions must be documented and reviewed after the event.

---

# 4. Evidence Bundle 3 – User Access Request Procedure

## NexusTech Solutions – User Access Request Procedure

| Field               | Details                                    |
| ------------------- | ------------------------------------------ |
| **Document ID**     | NTS-PR-001                                 |
| **Version**         | 1.0                                        |
| **Status**          | Pending Management Review                  |
| **Procedure Owner** | Information Security Manager               |
| **Applies To**      | Helpdesk, IT, Managers, System/Data Owners |
| **Effective Date**  | Upon Approval                              |
| **Review Cycle**    | At least annually                          |

### 4.1 Objective

The procedure establishes a repeatable process for:

**Request → Approval → Provisioning → Validation → Evidence → Closure**

It supports:

* Least privilege
* Role-based access
* Authorised approval
* Accountability
* Auditability

---

## 4.2 Required Approvals

| Requirement                | Expectation                                                         |
| -------------------------- | ------------------------------------------------------------------- |
| Approved workflow          | Requests must enter through the approved ticketing/workflow system. |
| Manager approval           | Manager confirms legitimate business need.                          |
| System/Data Owner approval | Required for sensitive systems or information where applicable.     |
| Provisioning authority     | Only designated IT/Helpdesk personnel may provision access.         |
| Required resources         | Approved ticketing, identity/access tools and role definitions.     |

---

## 4.3 Access Provisioning Workflow

```text
Receive Request
      ↓
Validate Request
      ↓
Verify Approvals
      ↓
Determine Appropriate Access
      ↓
Create / Modify Account
      ↓
Apply Security Controls
      ↓
Validate Access
      ↓
Notify User & Manager
      ↓
Capture Evidence
      ↓
Close Request
```

### Detailed Process

1. **Receive the request** through the approved ticketing system.
2. **Validate the request** for user, role, system, access level, business justification and start date.
3. **Verify required approvals** before proceeding.
4. **Determine appropriate access** using role definitions and least privilege.
5. **Create or modify the account** using approved identity-management processes.
6. **Apply required security controls**, including MFA where applicable.
7. **Validate the result** and confirm unnecessary permissions were not assigned.
8. **Notify the user and manager** that provisioning is complete.
9. **Capture evidence** including request, approvals, access granted and technician details.
10. **Close the ticket** only after all required evidence and validations are complete.

---

## 4.4 Emergency Access

Emergency access must be:

* Justified
* Authorised
* Limited to the minimum required access
* Time-limited where possible
* Documented
* Reviewed retrospectively

Emergency access must not automatically become permanent access.

---

## 4.5 Audit Trail

The access record should demonstrate:

```text
WHO requested?
      ↓
WHO approved?
      ↓
WHAT access was granted?
      ↓
WHEN was it granted?
      ↓
WHO provisioned it?
```

This creates an auditable chain of accountability.

---

# 5. Evidence Bundle 4 – Communication & Training Plan

The rollout approach focuses on ensuring employees **understand, acknowledge and apply** the Acceptable Use Policy.

## 5.1 Stakeholder Communication Plan

| Audience          | Key Message                                                                | Channel                                                       | Owner                | Timing | Success Measure                                       |
| ----------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------- | -------------------- | ------ | ----------------------------------------------------- |
| **All Employees** | Acceptable use, prohibited activities, personal use and incident reporting | CEO announcement, all-hands, email, intranet, learning module | Information Security | Week 1 | ≥95% training & acknowledgement; ≥85% knowledge score |
| **IT / Helpdesk** | AUP requirements must be supported through technical controls              | Technical briefing & targeted training                        | InfoSec / IT Manager | Week 1 | 100% completion                                       |
| **Managers**      | Reinforce expectations and escalate violations                             | Management briefing                                           | InfoSec / HR         | Week 1 | 100% acknowledgement                                  |
| **HR**            | Align AUP with onboarding and disciplinary processes                       | HR workshop                                                   | InfoSec + HR         | Week 1 | Processes updated                                     |

---

## 5.2 Rollout Timeline

```text
DAY 1
CEO Announcement
      ↓
DAYS 2–3
Policy Publication + Training
      ↓
DAY 4
Awareness + Targeted Briefings
      ↓
DAY 5
Knowledge Check + Attestation
      ↓
WEEK 2
Reminders + Clarification
      ↓
30 DAYS
Completion & Incident Trend Review
      ↓
90 DAYS
Post-Implementation Review
```

---

## 5.3 Effectiveness Measures

| Metric                      | Target |
| --------------------------- | -----: |
| Training completion         |   ≥95% |
| Policy acknowledgement      |   ≥95% |
| Knowledge-check performance |   ≥85% |
| IT/Helpdesk completion      |   100% |
| Management acknowledgement  |   100% |

Missed deadlines trigger reminders and escalation to management and HR.

Repeated misunderstanding should result in **targeted retraining**, while serious or repeated violations should follow established security, management and HR processes.

---

# 6. Evidence Bundle 5 – Policy Review & Maintenance

## Policy Review & Maintenance Memo

**To:** Information Security Steering Committee
**From:** Information Security Manager
**Date:** 18 September 2027
**Subject:** Review of Acceptable Use Policy Following Cloud Migration and Security Incident

### 6.1 Review Triggers

An early review of the Acceptable Use Policy was initiated because of two material changes:

**1. AWS Cloud Migration**

NexusTech migrated it

