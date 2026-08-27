# Evidence

This directory stores supporting evidence for security findings.

Possible evidence includes:

- Sanitized HTTP requests
- Sanitized HTTP responses
- ZAP scan results
- Burp Suite observations
- Screenshots
- Remediation verification

## Evidence Requirements

Evidence should:

1. Be collected only from authorized testing.
2. Avoid personal or confidential information.
3. Be sufficient to support the reported finding.
4. Be clearly associated with a finding ID.

Example:

```text
F-001/
    screenshot.png
    request.txt
    response.txt
