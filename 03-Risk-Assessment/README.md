# CareHome GRC & ISMS Portfolio – Risk Management

## 1. Project Overview

This project demonstrates how Governance, Risk and Compliance (GRC) principles can be applied to identify, assess, prioritise and treat information security risks within a fictional UK care-home organisation.

The risk register focuses on protecting sensitive care information, maintaining secure access to systems, improving security monitoring and supporting business continuity.

This work forms part of my wider CareHome GRC & ISMS Portfolio and builds on the Asset Register by connecting identified assets and business processes to potential information security risks.

## 2. Project Objectives

- Identify information security risks affecting critical assets and business processes.
- Document threats, vulnerabilities and potential business impacts.
- Assess risk likelihood and impact using a consistent scoring approach.
- Assign risk ratings and responsible owners.
- Recommend proportionate risk treatment actions.
- Record target completion times and estimated residual risk scores.
- Support risk-based decision-making and continuous improvement.
- Demonstrate practical risk management skills relevant to an ISO 27001-aligned ISMS.

## 3. Workbook Structure

The Excel workbook contains two worksheets:

| Worksheet | Purpose |
|---|---|
| Risk Register | Records identified risks, affected assets or processes, threats, vulnerabilities, impacts, likelihood, scores, ratings, existing controls, treatments, owners, targets and residual scores. |
| Scoring | Provides the risk rating and treatment guidance used in the workbook. |

## 4. Risk Register Fields

The Risk Register worksheet contains the following fields:

- **Risk ID:** Unique identifier assigned to each risk.
- **Risk Statement:** Description of what could go wrong.
- **Asset / Process:** Asset or business process affected.
- **Threat:** Potential cause of the risk.
- **Vulnerability:** Weakness that could allow the threat to cause harm.
- **Impact:** Assessed consequence if the risk occurs.
- **Likelihood:** Estimated chance of the risk occurring.
- **Score:** Calculated or recorded risk score.
- **Rating:** Risk priority, such as High or Critical.
- **Existing Controls:** Controls currently identified in the scenario.
- **Treatment:** Proposed action to reduce or manage the risk.
- **Owner:** Role responsible for managing the risk.
- **Target:** Intended treatment completion timeframe.
- **Residual Score:** Estimated remaining risk after the proposed treatment.

## 5. Identified Information Security Risks

The workbook contains 10 illustrative risks:

| Risk ID | Risk Description | Rating |
|---|---|---|
| R-001 | Identifiable resident information could be entered into an unapproved public AI service. | Critical |
| R-002 | Compromised credentials could provide unauthorised access to care records. | High |
| R-003 | Excessive permissions could expose resident information beyond job requirements. | High |
| R-004 | Delayed patching could allow exploitation of known vulnerabilities. | High |
| R-005 | Phishing could compromise staff accounts. | High |
| R-006 | Weak network segmentation could increase the impact of endpoint compromise. | High |
| R-007 | Untested backups may fail during ransomware or an outage. | High |
| R-008 | Supplier accounts could remain active after support ends. | High |
| R-009 | Insufficient logging could delay investigation. | High |
| R-010 | Incomplete incident response could delay containment. | High |

These ratings represent the initial assessment recorded in the portfolio workbook. They should be reviewed as additional evidence becomes available.

## 6. Risk Assessment Methodology

The register uses a qualitative risk assessment approach supported by numerical likelihood and impact values.

**Initial risk score:**

Risk Score = Impact × Likelihood

The workbook records likelihood and impact values on a numerical scale and uses the resulting score to support risk prioritisation.

The Scoring worksheet provides the following guidance:

| Score | Rating | Treatment Guidance |
|---|---|---|
| 1 | Low | Monitor |
| 6 | Medium | Planned treatment |
| 12 | High | Prioritise |
| 20 | Critical | Immediate action |

These are the score points explicitly listed in the workbook, rather than complete score ranges. The scoring thresholds should be clarified and consistently applied before using the register operationally.

## 7. Risk Treatment Examples

### R-001: Unapproved Use of Public AI

**Risk:** Identifiable resident information could be entered into an unapproved public AI service.

**Proposed treatment:**
- Prohibit entering identifiable resident information into unapproved AI services.
- Assess any suspected disclosure through the appropriate incident process.
- Provide staff training on safe and approved AI use.
- Establish an approved AI-use process.

**Suggested owner:** Information Governance / GRC.

### R-002: Unauthorised Access to Care Records

**Risk:** Compromised credentials could allow unauthorised access to sensitive care information.

**Proposed treatment:**
- Enforce multi-factor authentication (MFA).
- Review and remove unjustified MFA exceptions.
- Review user permissions.
- Monitor access to sensitive systems.

**Suggested owner:** Identity and Access Management (IAM).

### R-007: Backup and Recovery Failure

**Risk:** Backups may not be recoverable during ransomware or a service outage.

**Proposed treatment:**
- Conduct regular backup restoration tests.
- Document test results and remediation actions.
- Review backup protection and access restrictions.
- Align recovery arrangements with business continuity requirements.

**Suggested owner:** IT / Business Continuity.

## 8. Risk Ownership and Governance

Each risk is assigned a responsible role to support accountability and follow-up.

Examples include:

- **Information Governance / GRC:** AI governance and incident response.
- **Identity and Access Management:** Authentication and access controls.
- **IT:** Patching, network security and monitoring.
- **IT / Business Continuity:** Backup and recovery.
- **Procurement / IT:** Supplier access management.
- **IT / HR:** Staff security awareness.

Risk owners should review progress against target dates, retain supporting evidence and escalate overdue or unacceptable risks through the appropriate governance process.

## 9. Residual Risk

Residual risk represents the risk expected to remain after treatment measures have been implemented.

The workbook includes a Residual Score field to support this assessment. These values should be treated as estimates until the proposed controls have been implemented and their effectiveness verified.

A complete risk review should document:
- The control implemented.
- Evidence of implementation.
- The reassessed likelihood and impact.
- The revised risk score and rating.
- Risk acceptance or further treatment decisions, where applicable.

## 10. GRC and ISO 27001 Relevance

This project demonstrates risk management practices that support an Information Security Management System (ISMS) aligned with ISO/IEC 27001:2022 principles.

The register can support:
- Information security risk assessment and treatment.
- Asset-based risk identification.
- Access control and identity management.
- Vulnerability and patch management.
- Incident management and monitoring.
- Supplier risk management.
- Business continuity and backup planning.
- Management oversight and internal audit preparation.

The register is a portfolio demonstration and does not, by itself, establish ISO 27001 compliance or certification.

## 11. Tools Used

- Microsoft Excel
- Information security risk assessment concepts
- Risk scoring and prioritisation
- ISO/IEC 27001:2022-aligned ISMS principles

## 12. Project Outcome

This project demonstrates a structured approach to documenting and prioritising information security risks, assigning ownership and proposing treatment actions.

It provides a foundation for further portfolio activities, including the Statement of Applicability, Risk Treatment Plan, ISO 27001 Gap Assessment, access review, internal audit and GRC dashboard.

## Disclaimer

This is a fictional educational portfolio project created to demonstrate GRC knowledge and practical skills. All organisational scenarios and risk descriptions are illustrative. The workbook is not an assessment of a real care-home organisation, and the identified controls and residual scores have not been independently verified.
