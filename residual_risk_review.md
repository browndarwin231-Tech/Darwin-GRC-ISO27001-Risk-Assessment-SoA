# Residual Risk Review

## Purpose

This document evaluates the level of risk that remains after planned security controls and remediation actions are applied.

Residual risk represents the remaining exposure after treatment and helps determine whether additional action or formal risk acceptance is required.

---

## Residual Risk Summary

| Risk ID | Risk Description | Inherent Risk | Treatment | Residual Risk | Decision |
|---|---|---|---|---|---|
| ISO-R-001 | Privileged account compromise | High | MFA and quarterly privileged-access reviews | Medium | Accept with monitoring |
| ISO-R-002 | Former employee retains system access | High | Automated offboarding and inactive-account reviews | Low | Accept |
| ISO-R-003 | Third-party vendor compromise | High | Vendor assessments and recurring reassessments | Medium | Accept with monitoring |
| ISO-R-004 | Delayed vulnerability remediation | High | Severity-based remediation SLAs | Medium | Accept with monitoring |
| ISO-R-005 | Incident response failure | High | Annual tabletop exercises | Medium | Accept with monitoring |
| ISO-R-006 | Backup restoration failure | Medium | Quarterly restoration testing | Low | Accept |
| ISO-R-007 | Incomplete security log retention | Medium | Defined retention requirements | Low | Accept |
| ISO-R-008 | Employee phishing compromise | High | Phishing simulations and targeted training | Medium | Accept with monitoring |
| ISO-R-009 | Excessive user permissions | High | Quarterly access reviews | Medium | Accept with monitoring |
| ISO-R-010 | Business continuity disruption | Medium | Annual BCP and DR exercises | Low | Accept |

---

## Risk Review 1: Privileged Account Compromise

### Inherent Risk

**High – Score 15**

### Treatment Applied

- MFA for privileged accounts
- Quarterly privileged-access reviews
- Removal of unnecessary administrator rights
- Approval evidence retained

### Residual Risk

**Medium – Score 6**

### Residual Risk Rationale

The likelihood of compromise is reduced because privileged accounts are protected by stronger authentication and recurring access review.

However, privileged accounts still present elevated risk due to the level of access they provide.

### Decision

**Accept with Monitoring**

### Monitoring Activities

- Quarterly privileged-access reviews
- MFA enrollment verification
- Privileged account inventory review
- Investigation of unusual administrator activity

---

## Risk Review 2: Former Employee Access

### Inherent Risk

**High – Score 15**

### Treatment Applied

- Automated account disabling
- HR and IT offboarding coordination
- Recurring inactive-account reviews

### Residual Risk

**Low – Score 4**

### Residual Risk Rationale

Automated deprovisioning significantly reduces the likelihood that terminated-user accounts remain active.

### Decision

**Accept**

### Monitoring Activities

- Quarterly inactive-account review
- Sample terminated-user testing
- Review of account-disablement timestamps

---

## Risk Review 3: Third-Party Vendor Compromise

### Inherent Risk

**High – Score 12**

### Treatment Applied

- Vendor security questionnaires
- Vendor risk classification
- Security-document review
- Annual reassessment of high-risk vendors

### Residual Risk

**Medium – Score 6**

### Residual Risk Rationale

Vendor assessments reduce exposure, but third-party risk cannot be fully eliminated because the organization does not directly control vendor environments.

### Decision

**Accept with Monitoring**

### Monitoring Activities

- Annual reassessment
- Vendor security review
- Contract security review
- Tracking vendor remediation findings

---

## Risk Review 4: Delayed Vulnerability Remediation

### Inherent Risk

**High – Score 12**

### Treatment Applied

Severity-based remediation targets:

- Critical: 7 days
- High: 30 days
- Medium: 60 days
- Low: 90 days

Formal risk acceptance is required for approved exceptions.

### Residual Risk

**Medium – Score 6**

### Residual Risk Rationale

Defined remediation timelines reduce exposure, but vulnerabilities may still remain open due to operational constraints or approved exceptions.

### Decision

**Accept with Monitoring**

### Monitoring Activities

- Vulnerability aging reports
- SLA compliance reviews
- Exception tracking
- Risk acceptance review

---

## Risk Review 5: Incident Response Failure

### Inherent Risk

**High – Score 15**

### Treatment Applied

- Annual tabletop exercises
- Lessons-learned documentation
- Corrective-action tracking
- Incident response plan updates

### Residual Risk

**Medium – Score 6**

### Residual Risk Rationale

Regular testing improves readiness and reduces the likelihood of response failure.

Some risk remains because real incidents may differ from tested scenarios.

### Decision

**Accept with Monitoring**

### Monitoring Activities

- Annual exercises
- Corrective-action tracking
- Incident response plan reviews
- Post-incident reviews

---

## Risk Review 6: Backup Restoration Failure

### Inherent Risk

**Medium – Score 10**

### Treatment Applied

- Quarterly restoration testing
- Recovery documentation
- Tracking of failed tests

### Residual Risk

**Low – Score 4**

### Residual Risk Rationale

Regular restoration testing provides stronger assurance that backups are usable during a recovery event.

### Decision

**Accept**

---

## Risk Review 7: Security Log Retention

### Inherent Risk

**Medium – Score 8**

### Treatment Applied

- Formal log-retention requirements
- Increased retention for critical security logs
- Recurring configuration review

### Residual Risk

**Low – Score 3**

### Decision

**Accept**

---

## Risk Review 8: Employee Phishing Compromise

### Inherent Risk

**High – Score 12**

### Treatment Applied

- Security awareness training
- Phishing simulations
- Follow-up training for repeat failures

### Residual Risk

**Medium – Score 6**

### Residual Risk Rationale

Training reduces the likelihood of successful phishing, but human error cannot be completely eliminated.

### Decision

**Accept with Monitoring**

### Monitoring Activities

- Phishing simulation failure rates
- Training completion
- Repeat failure tracking
- Reported phishing events

---

## Risk Acceptance Criteria

Residual risk may be accepted when:

- The remaining risk is within organizational risk tolerance
- Required controls are implemented
- Evidence supports control effectiveness
- The risk owner approves the remaining exposure
- Monitoring activities are defined where necessary

High or Critical residual risks should normally require additional treatment or senior management approval.

---

## Final Assessment

The planned risk treatments reduce all identified High or Medium inherent risks to Medium or Low residual risk levels.

No Critical residual risks remain.

Risks classified as Medium should continue to be monitored through recurring GRC reviews.

Low residual risks may be accepted while maintaining existing controls.

---

## Conclusion

Residual risk review ensures that risk management does not stop after remediation is implemented.

By comparing inherent risk to residual risk, CloudNova Technologies can determine whether its controls reduce exposure to an acceptable level and whether additional treatment or formal risk acceptance is required.
