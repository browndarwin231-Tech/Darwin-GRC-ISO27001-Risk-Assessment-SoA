# ISO 27001 Control Justifications

## Purpose

This document explains why selected ISO 27001 controls are applicable to CloudNova Technologies and how each control supports the treatment of identified information security risks.

The justifications support the organization's Statement of Applicability and demonstrate how controls are selected based on business needs, information assets, and identified risks.

---

## A.5.15 Access Control

### Applicability

**Applicable**

### Justification

CloudNova Technologies uses cloud systems, Microsoft 365, Azure, SaaS applications, and internal business systems that require controlled access.

Access controls are necessary to ensure that only authorized users can access systems and information.

### Risks Addressed

- Unauthorized access
- Excessive permissions
- Former employee access
- Account compromise

### Expected Evidence

- Access control policy
- User access lists
- Access review reports
- Account provisioning records

---

## A.5.16 Identity Management

### Applicability

**Applicable**

### Justification

The organization must manage user identities throughout the employee lifecycle, including account creation, modification, and termination.

Identity management reduces the risk that inactive or unauthorized accounts remain enabled.

### Risks Addressed

- Former employee access
- Unauthorized accounts
- Orphaned accounts

### Expected Evidence

- User provisioning records
- Termination records
- Account disablement logs
- Identity management procedures

---

## A.5.18 Access Rights

### Applicability

**Applicable**

### Justification

User permissions may change as job responsibilities change.

Recurring access reviews help verify that users only retain the access necessary for their current responsibilities.

### Risks Addressed

- Excessive permissions
- Unauthorized access
- Privilege accumulation

### Expected Evidence

- Quarterly access review reports
- Reviewer approvals
- Removed-access records
- Access exceptions

---

## A.8.2 Privileged Access Rights

### Applicability

**Applicable**

### Justification

Administrator accounts have elevated access to critical systems and present a higher security risk than standard user accounts.

Privileged access should be limited, approved, and periodically reviewed.

### Risks Addressed

- Privileged account compromise
- Insider misuse
- Unauthorized administrative changes

### Expected Evidence

- Privileged account inventory
- Access approvals
- Quarterly privileged-access reviews
- Removed privilege records

---

## A.8.5 Secure Authentication

### Applicability

**Applicable**

### Justification

CloudNova Technologies relies on remote access and cloud-based systems.

Strong authentication, including MFA, reduces the risk of unauthorized access caused by stolen credentials.

### Risks Addressed

- Credential compromise
- Account takeover
- Unauthorized remote access

### Expected Evidence

- MFA configuration screenshots
- Authentication policy
- MFA enrollment reports
- Approved exceptions

---

## A.8.8 Management of Technical Vulnerabilities

### Applicability

**Applicable**

### Justification

Systems may contain vulnerabilities that could be exploited if they are not identified and remediated.

A vulnerability management process is required to detect, prioritize, and remediate technical weaknesses.

### Risks Addressed

- Exploitation of known vulnerabilities
- Delayed remediation
- System compromise

### Expected Evidence

- Vulnerability scan reports
- Remediation tickets
- Severity-based remediation SLAs
- Risk acceptance records

---

## A.8.13 Information Backup

### Applicability

**Applicable**

### Justification

Backups are required to recover systems and information after ransomware, hardware failure, accidental deletion, or other disruptive events.

### Risks Addressed

- Data loss
- Backup restoration failure
- Business disruption

### Expected Evidence

- Backup logs
- Backup policy
- Restoration test reports
- Recovery documentation

---

## A.8.15 Logging

### Applicability

**Applicable**

### Justification

Security logging is required to support monitoring, incident investigation, accountability, and forensic analysis.

### Risks Addressed

- Undetected malicious activity
- Incomplete investigations
- Insufficient audit evidence

### Expected Evidence

- SIEM screenshots
- Log source inventory
- Log retention settings
- Security event records

---

## A.8.16 Monitoring Activities

### Applicability

**Applicable**

### Justification

The organization needs continuous monitoring to identify suspicious activity and potential security incidents.

### Risks Addressed

- Undetected attacks
- Delayed incident response
- Unauthorized activity

### Expected Evidence

- Monitoring dashboards
- Security alerts
- Investigation tickets
- Escalation records

---

## A.5.19 Supplier Relationships

### Applicability

**Applicable**

### Justification

CloudNova Technologies relies on external vendors and service providers that may process company data or access company systems.

Vendor security controls should be evaluated before and during the relationship.

### Risks Addressed

- Third-party compromise
- Data exposure
- Supply-chain risk

### Expected Evidence

- Vendor security questionnaires
- Risk assessments
- Vendor classifications
- Due-diligence records

---

## A.5.20 Supplier Agreements

### Applicability

**Applicable**

### Justification

Security expectations should be documented in supplier contracts and agreements.

This helps define responsibility for data protection, incident notification, access control, and other security requirements.

### Risks Addressed

- Unclear security responsibilities
- Inadequate vendor controls
- Compliance failures

### Expected Evidence

- Signed supplier agreements
- Security clauses
- Data protection requirements
- Incident notification requirements

---

## A.5.22 Monitoring of Supplier Services

### Applicability

**Applicable**

### Justification

Vendor risk may change over time.

Recurring supplier reviews help confirm that high-risk vendors continue to meet required security expectations.

### Risks Addressed

- Vendor control degradation
- New vendor vulnerabilities
- Third-party security incidents

### Expected Evidence

- Annual reassessment reports
- Updated vendor questionnaires
- Risk review records
- Remediation tracking

---

## A.5.24 Information Security Incident Management Planning

### Applicability

**Applicable**

### Justification

A documented incident response process is necessary to coordinate actions during cybersecurity incidents.

### Risks Addressed

- Delayed response
- Poor incident coordination
- Increased business impact

### Expected Evidence

- Incident response plan
- Escalation procedures
- Contact lists
- Response playbooks

---

## A.5.26 Response to Information Security Incidents

### Applicability

**Applicable**

### Justification

Incident response procedures should be tested so the organization can identify weaknesses before a real incident occurs.

### Risks Addressed

- Incident response failure
- Delayed containment
- Ineffective communication

### Expected Evidence

- Tabletop exercise reports
- Lessons learned
- Corrective action records
- Updated response procedures

---

## A.6.3 Information Security Awareness

### Applicability

**Applicable**

### Justification

Employees are frequent targets of phishing and social engineering.

Security awareness training reduces human-related security risk.

### Risks Addressed

- Phishing compromise
- Social engineering
- Credential theft

### Expected Evidence

- Training completion records
- Phishing simulation reports
- Awareness materials
- Follow-up training records

---

## A.5.29 Information Security During Disruption

### Applicability

**Applicable**

### Justification

Security controls must continue to operate during outages, disasters, or other disruptive events.

### Risks Addressed

- Business disruption
- Loss of security controls
- Unauthorized access during emergencies

### Expected Evidence

- Business continuity plan
- Disaster recovery procedures
- Exercise reports
- Continuity test results

---

## A.5.30 ICT Readiness for Business Continuity

### Applicability

**Applicable**

### Justification

Technology recovery capabilities should be tested to confirm that critical systems can be restored within acceptable timeframes.

### Risks Addressed

- Extended system outage
- Failed disaster recovery
- Loss of critical services

### Expected Evidence

- Disaster recovery test reports
- Recovery time results
- Restoration logs
- Corrective actions

---

## Conclusion

The selected ISO 27001 controls are applicable because they directly support the treatment of identified risks and protect the confidentiality, integrity, and availability of CloudNova Technologies' information assets.

Control implementation and supporting evidence should be reviewed periodically to confirm that the controls remain effective and appropriate.
