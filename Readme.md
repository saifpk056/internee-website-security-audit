# Security Audit of Internee.pk's Website

## Project Overview

This project focuses on performing a structured security audit of a web application and identifying common security weaknesses.

The assessment covers important web application areas including authentication, user profiles, APIs, input validation, session management, access control, and security configuration.

OWASP ZAP and Burp Suite are used as security testing tools. OWASP Juice Shop is used as the primary intentionally vulnerable application for practical testing and demonstrations.

## Objective

The main objective of this project is to:

- Identify potential web application vulnerabilities.
- Understand common OWASP Top 10 security risks.
- Perform controlled security testing.
- Document security findings.
- Assess the risk associated with findings.
- Recommend appropriate security controls and remediation measures.

## Scope

The security assessment focuses on:

- Login and authentication
- User profiles
- API endpoints
- Input validation
- SQL Injection
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Session security
- Access control
- Security headers
- Information disclosure
- OWASP Top 10 vulnerabilities

## Tools

The following tools are used:

- OWASP ZAP
- Burp Suite
- OWASP Juice Shop
- Web Browser
- Git
- GitHub

## Testing Methodology

The assessment follows these stages:

1. Define scope.
2. Confirm authorization.
3. Perform passive reconnaissance.
4. Identify application attack surfaces.
5. Map application functionality.
6. Perform automated scanning.
7. Perform controlled manual testing.
8. Record observations.
9. Assess risk.
10. Recommend remediation.
11. Prepare the final security report.

## Authorized Testing

Testing of a production website must only be performed with explicit authorization.

For practical vulnerability demonstrations, OWASP Juice Shop is used because it is deliberately vulnerable and designed for security education.

## Security Areas

### Authentication

Testing focuses on:

- Login security
- Password handling
- Session management
- Authentication controls

### Input Validation

Testing focuses on whether user-controlled input is safely processed.

Examples include:

- SQL Injection
- XSS
- Malicious input handling

### API Security

Testing focuses on:

- Authentication
- Authorization
- Input validation
- Error handling
- Information exposure

### CSRF Protection

The assessment checks whether sensitive state-changing requests have appropriate anti-CSRF protections.

## Expected Outcomes

The project demonstrates knowledge of:

- Web application security
- OWASP Top 10
- Vulnerability assessment
- Security testing tools
- Risk assessment
- Security documentation
- Remediation planning

## Ethical Considerations

Security testing must only be performed against systems where permission has been obtained.

The following activities are excluded:

- Unauthorized access
- Destructive testing
- Denial-of-service attacks
- Credential theft
- Accessing private user information
- Data destruction

## Repository Structure

```text
internee-website-security-audit/
│
├── README.md
├── security-audit-report.md
├── methodology.md
├── vulnerability-assessment.md
├── zap-scan-report.md
├── burp-suite-testing.md
├── owasp-top-10-mapping.md
├── remediation-plan.md
├── test-cases.md
├── findings-summary.md
├── screenshots/
│   └── README.md
├── evidence/
│   └── README.md
└── .gitignore
