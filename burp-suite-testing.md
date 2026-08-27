
---

# FILE 6 — `burp-suite-testing.md`

```markdown
# Burp Suite Testing

## 1. Introduction

Burp Suite can be used to inspect and analyze HTTP requests and responses during authorized web application security testing.

## 2. Main Components

Useful Burp Suite components include:

- Proxy
- Repeater
- HTTP history
- Decoder
- Intruder where explicitly authorized

## 3. Testing Areas

### Authentication

Review:

- Login requests
- Session cookies
- Authentication responses
- Logout behavior

### Authorization

Review whether server-side authorization is enforced when accessing protected resources.

### Input Validation

Review user-controlled parameters and how the server processes them.

### API Security

Review:

- API requests
- Authentication
- Authorization
- Response data
- Error handling

## 4. Safe Testing Workflow

1. Configure the browser to use the authorized Burp proxy.
2. Browse the application.
3. Review HTTP history.
4. Identify important requests.
5. Send selected requests to Repeater.
6. Modify requests within the approved testing scope.
7. Compare responses.
8. Document observations.

## 5. Evidence

For each finding, record:

- Request
- Response
- Affected endpoint
- Security impact
- Screenshot if required
- Remediation recommendation

## 6. Reporting Template

```text
Finding ID:
Title:
Endpoint:
Severity:
Description:
Evidence:
Impact:
Recommendation:
Verification Status:
