
# GRC102 Week 5 Practical Laboratory
## Simulating and Analysing Security Governance Scenarios

**International Cybersecurity and Digital Forensics Academy (ICDFA)**

A practical security governance simulation exploring how technical weaknesses can become governance failures, how security controls should be implemented and verified, and how security posture should be communicated to executives and the Board.

The scenario incorporates governance lessons from the 2017 Equifax data breach.

> **Security Notice:** This is an authorised, isolated educational simulation. Vulnerable components are included for laboratory purposes only. Do not expose the environment to public networks, use production data, or test systems without explicit authorisation.

---

## Author and Project Details

| Field | Details |
|---|---|
| Institution | International Cybersecurity and Digital Forensics Academy (ICDFA) |
| Course | GRC102 – Information Security Governance |
| Practical | Practical Laboratory 8 / Week 5 Linux Lab |
| Project Title | Simulating and Analysing Security Governance Scenarios |
| Focus | Monitoring, Auditing Controls and Executive Reporting |
| Author | **Kefilwe Matake** |
| Registration Number | C11_26_CGRCE_17575 |
| Assigned Role | Security Governance Analyst |
| Environment | Authorised, isolated Ubuntu/Docker simulation |

---

## 1. Project Overview

This laboratory follows a structured security governance lifecycle, connecting technical controls with risk management, assurance, accountability, and executive oversight.

The project covers:

1. Establishing a simulated technical and governance baseline.
2. Analysing security governance failures using lessons from the Equifax breach.
3. Recording security controls and assessing evidence of implementation.
4. Developing security metrics, trend visualisations, and executive reporting.
5. Identifying assurance limitations and recommending improvements to evidence quality, risk tracking, and reporting consistency.

The central principle is that **the existence of a policy or technical control does not, by itself, prove that risk has been reduced.**

Effective security governance requires accountable control owners, reliable evidence, independent verification, accurate risk status, and reporting that reflects authoritative records.

## 2. Project Objectives

The laboratory aims to:

- Review an isolated Docker environment containing an intentionally vulnerable web application, a database service, and a monitoring service.
- Examine governance records covering policies, controls, risks, incidents, metrics, and audit activities.
- Identify weaknesses involving patch management, security metrics, network segmentation, and database authentication.
- Document control implementation and distinguish implementation records from independent verification evidence.
- Develop security metrics and executive reporting artefacts.
- Reconcile the risk register with dashboard and Board-report claims.
- Provide prioritised, evidence-based recommendations to improve governance assurance.

## 3. Environment Architecture

The supplied Docker Compose configuration describes three services connected through an isolated Docker network.

| Component | Image | Purpose | Governance Relevance |
|---|---|---|---|
| Web Application | `vulhub/struts2:s2-045` | Intentionally vulnerable application service | Demonstrates risks associated with delayed vulnerability remediation |
| Database | `mysql:5.7` | Synthetic customer-data store | Illustrates database authentication and data-layer risks |
| Monitoring | `ubuntu:20.04` | Monitoring and evidence service | Supports the simulated monitoring and evidence workflow |
| Network | `secgov_network` | Isolated laboratory network | Establishes the simulated network boundary |

The web service is configured to expose port `8080` to the laboratory host. The environment must remain isolated and must not contain real customer or production data.

## 4. Project Workflow and Evidence

### Part 1: Setting Up a Simulated Environment

**Purpose:** Establish the baseline environment and governance state.

Key evidence referenced in the associated report includes:

- `docker-compose.yml` — simulated service and network configuration.
- `governance_data.json` — governance tracker state covering policies, controls, risks, metrics, and audit records.
- `governance_tracker.py` — governance tracker logic.
- `initialize_governance.py` — baseline initialisation.
- Vulnerability-scan JSON output, where supplied.

#### Baseline Risk Register

The baseline governance tracker records three open risks.

| Risk ID | Risk Description | Severity | Status | Planned Treatment |
|---|---|---|---|---|
| RISK-001 | Unpatched vulnerabilities | Critical | Open | Automated patch management |
| RISK-002 | Insufficient network segmentation | High | Open | Network segmentation and least privilege |
| RISK-003 | Weak authentication | Medium | Open | Strong authentication and access controls |

These risks provide the starting point for analysing governance weaknesses and evaluating the proposed control improvements.

### Part 2: Analysing Security Governance Failures

**Purpose:** Identify weaknesses in governance, implementation, and accountability.

The analysis identifies four primary governance concerns:

1. **Policy implementation:** A patch-management policy exists, but critical vulnerabilities remain recorded as unresolved.
2. **Metrics and measurement:** Security metrics are not consistently demonstrated to drive timely remediation.
3. **Security architecture:** Insufficient network segmentation may increase the risk of lateral movement.
4. **Authentication and access control:** Weak database authentication may expose sensitive information to unauthorised access.

Key evidence referenced:

- `analyze_governance_failures.py`
- `governance_failure_report_20261007_195441.json`
- `equifax_comparison.md`
- `simulate_attack.py`

**Evidence limitation:** The attack-simulation script is referenced, but the resulting `attack_log.json` was not supplied in the reviewed evidence package. Therefore, successful execution of the simulated attack cannot be claimed as verified.

### Part 3: Implementing Security Governance Controls

**Purpose:** Record proposed or simulated control improvements and assess the supporting evidence.

| Control ID | Control | Intended Objective | Verification Status |
|---|---|---|---|
| CTL-004 | Automated patch management | Identify, test, and remediate critical vulnerabilities promptly | Partially verified |
| CTL-005 | Network segmentation | Reduce unnecessary lateral connectivity | Partially verified |
| CTL-006 | Database security | Strengthen database authentication and access controls | Verified at simulation-state level |
| CTL-007 | Real-time security monitoring | Detect suspicious activity and generate alerts | Partially verified |
| CTL-008 | Executive security oversight | Formalise executive and Board oversight | Verified as governance design |

Related evidence:

- `implement_governance_controls.py`
- `governance_controls_report.md`
- `patch_management.py`
- `patch_status.json`
- `governance_oversight.md`
- `governance_data.json`

The evidence does not support treating every control as independently verified.

For example, `patch_status.json` records `mysql_secured=true`. However, this status alone does not establish that Apache Struts patching or network segmentation has been independently verified.

The report recommends maintaining complete, timestamped control status records and performing independent retesting before closing associated risks.

### Part 4: Developing Security Governance Metrics and Reporting

**Purpose:** Translate security control information into operational, executive, and Board-level reporting.

Key artefacts referenced:

- `governance_metrics.py`
- `governance_metrics_framework.md`
- `executive_dashboard.html`
- `board_report.md`
- `dashboard_user_guide.md`
- Five simulation-generated trend charts

#### Security Metrics Categories

| Category | Example Measures |
|---|---|
| Implementation | Patch compliance, monitoring coverage, and policy compliance |
| Effectiveness | Remediation time, incident trends, and control effectiveness |
| Efficiency | Security costs, staffing, and automation |
| Impact | Incident costs, business disruption, and customer impact |

Useful metric definitions should specify the metric name, description, formula, target, data source, reporting frequency, owner, and intended audience.

Metrics must also use appropriate evaluation logic. For example, lower remediation times may indicate improvement, whereas higher patch-compliance percentages generally indicate improvement.

## 5. Key Assurance Findings

The most important outcome is the distinction between recording a control as implemented and possessing sufficient evidence to demonstrate that the control is effective.

| Finding | Why It Matters | Recommended Action |
|---|---|---|
| Critical and High risks remain open in the authoritative tracker | Dashboard and Board-report claims may not reflect actual residual risk | Reconcile reports with `governance_data.json`; close risks only after retesting and approval |
| Attack log was not supplied | The script alone does not prove that the simulation executed successfully | Preserve runtime logs and timestamped results when the authorised test is executed |
| Patch-status evidence is incomplete | Available status information does not verify all patching and segmentation claims | Persist complete control states and independently verify each control |
| Monitoring artefacts were not supplied separately | Implementation records do not prove that monitoring operated effectively | Retain monitoring configurations, alerts, and test results |
| Trend history is synthetic | Simulated charts must not be interpreted as measured production history | Label synthetic data clearly or use recorded simulation events |
| Metric status logic may be directionally incorrect | Measures where lower values are better require different evaluation logic | Define metric-specific pass/fail rules and validate them |
| Dashboard and risk-register data are inconsistent | Decision-makers may receive an inaccurate picture of residual risk | Generate dashboard and Board-report values from one authoritative source |

### Overall Assessment

The simulation demonstrates a structured understanding of security governance and the relationship between technical control weaknesses, accountability, risk treatment, and executive oversight.

The governance design and reporting package are developed, but the evidence-validation trail requires improvement before the dashboard can be relied upon as proof of full control effectiveness.

**Implementation claims must not be treated as verified outcomes unless supported by reproducible evidence and appropriate independent retesting.**

## 6. Priority Recommendations

The following actions are recommended to improve the governance and assurance process.

1. **Improve evidence-state persistence:** Store patch and control states together with timestamps, control identifiers, and supporting evidence.
2. **Complete independent retesting:** Retest patching, network segmentation, database access, and monitoring before closing risks.
3. **Reconcile executive reporting:** Generate Board and dashboard risk totals from the same authoritative risk data.
4. **Retain runtime evidence:** Preserve vulnerability-scan results, attack logs, monitoring alerts, and post-control scan results.
5. **Correct metric evaluation logic:** Use direction-aware status rules for measures where lower values indicate better performance.
6. **Label synthetic data:** Clearly distinguish generated trends from observed test results and production measurements.
7. **Strengthen assurance independence:** Where practical, separate control implementation responsibilities from assurance approval.
8. **Document residual risk:** Record risk owners, treatment plans, target dates, exceptions, and formal acceptance decisions.

## 7. Repository Evidence Index

The following files are referenced in the associated report. Their inclusion in this index does not confirm that every file was supplied or exists in the repository.

| Evidence File | Purpose |
|---|---|
| `docker-compose.yml` | Simulated Docker environment definition |
| `governance_data.json` | Governance tracker state |
| `governance_tracker.py` | Governance tracker logic |
| `initialize_governance.py` | Baseline initialisation |
| `analyze_governance_failures.py` | Governance failure analysis logic |
| `governance_failure_report_20261007_195441.json` | Generated governance failure findings |
| `simulate_attack.py` | Authorised attack-simulation logic |
| `attack_log.json` | Expected simulation output; not supplied in the reviewed evidence package |
| `equifax_comparison.md` | Comparison with governance lessons from Equifax |
| `implement_governance_controls.py` | Control implementation and verification logic |
| `governance_controls_report.md` | Control implementation narrative |
| `patch_management.py` | Simulated patch-management actions |
| `patch_status.json` | Retained simulated patch status |
| `governance_oversight.md` | Executive and Board oversight design |
| `governance_metrics.py` | Metric generation, charts, dashboard, and reporting logic |
| `governance_metrics_framework.md` | Metric definitions and reporting framework |
| `executive_dashboard.html` | Executive dashboard output |
| `board_report.md` | Board-level reporting output |
| `dashboard_user_guide.md` | Dashboard interpretation guide |
| Assessment brief and embedded charts | Five submitted trend visualisations, as referenced in the report |

**Repository note:** Before publishing, verify that each referenced artefact exists in the repository. Clearly identify missing files and distinguish expected outputs from generated evidence.

## 8. References

1. U.S. Government Accountability Office. (2018). *Data Protection: Actions Taken by Equifax and Federal Agencies in Response to the 2017 Breach* (GAO-18-559).  
   https://www.gao.gov/products/gao-18-559

2. U.S. House Committee on Oversight and Government Reform. (2018). *The Equifax Data Breach*.  
   https://oversight.house.gov/wp-content/uploads/2018/12/Equifax-Report.pdf

3. National Institute of Standards and Technology, National Vulnerability Database. *CVE-2017-5638: Apache Struts Remote Code Execution Vulnerability*.  
   https://nvd.nist.gov/vuln/detail/CVE-2017-5638

4. International Cybersecurity and Digital Forensics Academy (ICDFA). *GRC102 Practical Laboratory Instructions and Assessment Brief*. Course materials.

5. Student-generated scripts, configuration files, and output artefacts referenced in the evidence index.

## 9. AI Assistance Declaration

AI assistance was used to support report structuring, language refinement, evidence reconciliation, and professional presentation.

The laboratory evidence, scripts, configuration files, and generated outputs referenced in the associated report were supplied as student evidence. Missing runtime output has not been represented as verified evidence.

The author remains responsible for understanding, reviewing, and validating the technical and governance conclusions presented in this project.

---

**Author:** Kefilwe Matake  
**Course:** GRC102 – Information Security Governance  
**Institution:** International Cybersecurity and Digital Forensics Academy (ICDFA)  
**Project:** Week 5 Practical Laboratory – Simulating and Analysing Security Governance Scenarios
