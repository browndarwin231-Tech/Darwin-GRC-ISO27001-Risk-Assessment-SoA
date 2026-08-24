# Darwin-GRC-ISO27001-Risk-Assessment-SoA

Hands-on GRC project simulating an ISO 27001 risk assessment, control selection, Statement of Applicability, treatment planning, and residual risk review.

# ISO 27001 Risk Assessment & Statement of Applicability Project

## Project Overview

This project simulates an ISO 27001 risk assessment and Statement of Applicability process for a fictional SaaS company called **CloudNova Technologies**.

The goal is to identify information security risks, evaluate likelihood and impact, select appropriate ISO 27001 controls, document control applicability, plan risk treatment, and review residual risk.

This project demonstrates practical GRC skills including:

- ISO 27001 risk assessment
- Risk identification
- Risk scoring
- Statement of Applicability
- Control selection
- Control justification
- Risk treatment planning
- Residual risk analysis
- Compliance documentation
- Information security governance

## Business Scenario

CloudNova Technologies is preparing to strengthen its information security management system and align with ISO 27001 requirements.

The organization uses:

- Microsoft 365
- Microsoft Azure
- Cloud-based SaaS applications
- Remote employees
- Third-party vendors
- Centralized logging
- Endpoint protection
- Multi-Factor Authentication
- Backup systems

The assessment focuses on identifying risks that may affect the confidentiality, integrity, and availability of information assets.

## Assessment Scope

The risk assessment covers:

- Identity and Access Management
- Privileged Access
- Third-Party Risk
- Incident Response
- Vulnerability Management
- Logging and Monitoring
- Backup and Recovery
- Security Awareness
- Data Protection
- Business Continuity

## Risk Assessment Method

Risk is calculated using:

Risk Score = Likelihood × Impact

### Likelihood Scale

- 1 = Rare
- 2 = Unlikely
- 3 = Possible
- 4 = Likely
- 5 = Almost Certain

### Impact Scale

- 1 = Insignificant
- 2 = Minor
- 3 = Moderate
- 4 = Major
- 5 = Severe

### Risk Ratings

- 1–4 = Low
- 5–10 = Medium
- 11–15 = High
- 16–25 = Critical

## Key Risks Identified

| Risk | Likelihood | Impact | Score | Rating |
|---|---:|---:|---:|---|
| Privileged account compromise | 3 | 5 | 15 | High |
| Former employee retains access | 3 | 5 | 15 | High |
| Third-party vendor compromise | 3 | 4 | 12 | High |
| Delayed vulnerability remediation | 3 | 4 | 12 | High |
| Incident response failure | 3 | 5 | 15 | High |
| Backup restoration failure | 2 | 5 | 10 | Medium |
| Incomplete security log retention | 2 | 4 | 8 | Medium |
| Employee phishing compromise | 3 | 4 | 12 | High |

## Statement of Applicability

The Statement of Applicability identifies which ISO 27001 controls are applicable to the organization and explains why they were selected or excluded.

Example control areas include:

- Access Control
- Identity Management
- Privileged Access
- Logging
- Vulnerability Management
- Supplier Security
- Incident Management
- Backup
- Business Continuity
- Security Awareness

## Example Control Decisions

| Control Area | Applicable | Implementation Status | Justification |
|---|---|---|---|
| Identity Management | Yes | Implemented | Required to control access to organizational systems |
| Privileged Access Management | Yes | Partial | Administrator access requires stronger recurring review |
| Security Logging | Yes | Implemented | Required for threat detection and investigation |
| Supplier Security | Yes | Partial | Vendors may access systems or sensitive data |
| Backup | Yes | Partial | Backups exist but restoration testing needs improvement |
| Security Awareness | Yes | Implemented | Employees require recurring security training |

## Risk Treatment Options

Each identified risk may be handled through:

- Mitigate
- Accept
- Avoid
- Transfer

High-risk findings are primarily addressed through mitigation.

## Example Risk Treatment

### Privileged Account Compromise

**Treatment:** Mitigate

**Actions:**
- Enforce MFA
- Perform quarterly privileged-access reviews
- Remove unnecessary administrator rights
- Retain approval evidence

### Third-Party Vendor Compromise

**Treatment:** Mitigate

**Actions:**
- Perform vendor risk assessments
- Require security questionnaires
- Review vendor security documentation
- Reassess high-risk vendors annually

### Backup Restoration Failure

**Treatment:** Mitigate

**Actions:**
- Conduct quarterly restoration testing
- Document recovery results
- Track failed restoration attempts
- Retest after corrective action

## Residual Risk

Residual risk is the amount of risk that remains after controls and remediation actions are implemented.

Example:

Initial Risk Score = 15 High

After MFA and quarterly privileged-access reviews:

Residual Risk Score = 6 Medium

Residual risk should be reviewed and formally accepted when appropriate.

## Repository Structure

Darwin-GRC-ISO27001-Risk-Assessment-SoA/
│
├── README.md
├── iso27001_risk_register.csv
├── statement_of_applicability.csv
├── risk_treatment_plan.csv
├── control_justifications.md
├── residual_risk_review.md
└── evidence/

## Skills Demonstrated

- ISO 27001
- Governance, Risk, and Compliance
- Risk Assessment
- Risk Registers
- Statement of Applicability
- Control Selection
- Risk Treatment
- Residual Risk
- Information Security Governance
- Third-Party Risk Management
- Identity and Access Management
- Compliance Documentation

## Project Goal

The goal of this project is to demonstrate practical ISO 27001 GRC work by identifying information security risks, selecting appropriate controls, documenting applicability, planning risk treatment, and evaluating residual risk.
