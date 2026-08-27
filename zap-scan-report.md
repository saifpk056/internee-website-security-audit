
---

# FILE 5 — `zap-scan-report.md`

```markdown
# OWASP ZAP Scan Report

## 1. Purpose

OWASP ZAP is used to assist with identifying potential web application security issues.

Automated scanner results are considered preliminary and should be manually verified.

## 2. Tool

OWASP ZAP

## 3. Target

Authorized staging environment or OWASP Juice Shop.

## 4. Scan Areas

The scan may identify:

- Missing security headers
- Cookie configuration issues
- Information disclosure
- Potential injection indicators
- Cross-site scripting indicators
- Other passive security observations

## 5. Scan Procedure

1. Open OWASP ZAP.
2. Configure the authorized target.
3. Browse the application through the proxy.
4. Allow ZAP to observe application traffic.
5. Review passive scan alerts.
6. Perform authorized active scanning where permitted.
7. Review alerts.
8. Manually verify important findings.
9. Export the report.

## 6. Findings

Findings should be recorded after an actual scan.

| ID | Finding | Risk | Status |
|---|---|---|---|
| ZAP-001 | To be determined from scan | TBD | Pending verification |
| ZAP-002 | To be determined from scan | TBD | Pending verification |
| ZAP-003 | To be determined from scan | TBD | Pending verification |

## 7. False Positive Verification

Automated alerts must not automatically be treated as confirmed vulnerabilities.

Each important alert should be manually reviewed.

## 8. Evidence

Screenshots and exported reports can be stored in:

```text
screenshots/
evidence/
