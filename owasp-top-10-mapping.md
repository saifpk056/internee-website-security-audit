
---

# FILE 7 — `owasp-top-10-mapping.md`

```markdown
# OWASP Top 10 Mapping

## Overview

This document maps the security assessment to major OWASP Top 10 categories.

## A01 — Broken Access Control

Assessment areas:

- User profiles
- Protected resources
- API authorization
- Role-based access

Controls:

- Server-side authorization
- Least privilege
- Deny by default

## A02 — Cryptographic Failures

Assessment areas:

- HTTPS
- Sensitive data transmission
- Password protection
- Sensitive information storage

Controls:

- Strong encryption
- HTTPS
- Secure password hashing

## A03 — Injection

Assessment areas:

- SQL Injection
- Command injection indicators
- Unsafe input processing

Controls:

- Parameterized queries
- Input validation
- Safe APIs

## A04 — Insecure Design

Assessment areas:

- Authentication design
- Authorization design
- Security requirements

Controls:

- Threat modeling
- Secure design principles
- Security requirements

## A05 — Security Misconfiguration

Assessment areas:

- Security headers
- Error messages
- Debug settings
- Default configurations

Controls:

- Secure configuration
- Disable unnecessary features
- Regular configuration reviews

## A06 — Vulnerable and Outdated Components

Assessment areas:

- Dependencies
- Libraries
- Framework versions

Controls:

- Dependency management
- Security updates
- Software inventory

## A07 — Identification and Authentication Failures

Assessment areas:

- Login
- Sessions
- Password recovery
- MFA

Controls:

- Strong authentication
- Secure session management
- MFA

## A08 — Software and Data Integrity Failures

Assessment areas:

- Software dependencies
- Update mechanisms
- CI/CD processes

Controls:

- Integrity verification
- Trusted dependencies
- Secure development pipelines

## A09 — Security Logging and Monitoring Failures

Assessment areas:

- Authentication events
- Security events
- Error logging

Controls:

- Centralized logging
- Monitoring
- Alerting

## A10 — Server-Side Request Forgery

Assessment areas:

- Server-side URL fetching
- External resource requests
- Internal resource access controls

Controls:

- URL allowlists
- Network restrictions
- Input validation

## Conclusion

OWASP Top 10 provides a useful framework for organizing web application security testing and remediation.
