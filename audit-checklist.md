# ClawAudit Security Checklist

## Pre-Audit Setup
- [ ] Obtain skill source code or ClawHub URL
- [ ] Document skill version and metadata
- [ ] Set up isolated test environment
- [ ] Note all declared permissions

---

## Critical Issues (Auto-Fail)

Any of these = FAIL the audit immediately.

### Prompt Injection
- [ ] Hidden SYSTEM/ASSISTANT role overrides
- [ ] Instruction hijacking patterns ("Ignore previous instructions...")
- [ ] Jailbreak attempts embedded in content
- [ ] Invisible unicode or whitespace attacks
- [ ] Markdown/HTML injection for display manipulation

### Credential Harvesting
- [ ] Requests for API keys, passwords, or tokens
- [ ] Patterns that extract environment variables
- [ ] Attempts to read .env, config files, or secrets
- [ ] OAuth/auth token interception patterns

### Data Exfiltration
- [ ] Outbound HTTP requests to unknown domains
- [ ] Base64 encoding of sensitive data before transmission
- [ ] File content being sent to external endpoints
- [ ] Clipboard or browser data access patterns

### Code Execution
- [ ] Shell command injection vectors
- [ ] eval(), exec(), or dynamic code execution
- [ ] File system write access abuse
- [ ] Process spawning or subprocess calls

### Unauthorized Access
- [ ] File system traversal patterns (../)
- [ ] Access to directories outside declared scope
- [ ] Reading browser history, cookies, or saved passwords
- [ ] Accessing other applications' data

---

## Warnings (Flag for Review)

### Permission Issues
- [ ] Excessive permissions for stated functionality
- [ ] Permissions that don't match documented purpose
- [ ] Write permissions when only read is needed
- [ ] Network access when offline would work

### Data Handling
- [ ] Unclear what data is collected
- [ ] No indication of data retention policy
- [ ] Transmitting more data than necessary
- [ ] Logging sensitive information

### Input Validation
- [ ] Missing sanitization of user inputs
- [ ] No bounds checking on parameters
- [ ] Accepting arbitrary URLs or file paths
- [ ] No validation of external data

### Security Hygiene
- [ ] Hardcoded secrets or API keys in source
- [ ] Using HTTP instead of HTTPS
- [ ] Disabled SSL verification
- [ ] Outdated dependencies with known vulnerabilities

---

## Informational (Best Practices)

### Code Quality
- [ ] Unclear or obfuscated code
- [ ] Lack of error handling
- [ ] Missing input validation messages
- [ ] Poor separation of concerns

### Documentation
- [ ] Missing or inadequate README
- [ ] Undocumented permissions requirements
- [ ] No changelog or version history
- [ ] Missing usage examples

### Maintenance
- [ ] No clear update path
- [ ] Deprecated API usage
- [ ] Abandoned dependencies
- [ ] No contact information for maintainer

---

## Audit Scoring

| Category | Weight | Score (0-10) |
|----------|--------|--------------|
| Critical Issues | 50% | ___ |
| Warnings | 30% | ___ |
| Informational | 20% | ___ |
| **TOTAL** | 100% | ___ |

### Scoring Guide
- **9-10**: Excellent - No issues found
- **7-8**: Good - Minor issues, safe to use
- **5-6**: Acceptable - Some concerns, use with caution
- **3-4**: Poor - Significant issues, not recommended
- **0-2**: Fail - Critical issues found, do not use

---

## Post-Audit Actions

- [ ] Document all findings
- [ ] Generate report from template
- [ ] Assign final PASS/FAIL/CONDITIONAL status
- [ ] If PASS: Generate badge code
- [ ] Email report to customer
- [ ] Post summary to m/skillaudits (with permission)
