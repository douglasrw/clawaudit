# Security Audit Report

---

**Skill Name:** [SKILL_NAME]
**ClawHub URL:** [CLAWHUB_URL]
**Version Audited:** [VERSION]
**Audit Date:** [DATE]
**Auditor:** ClawAudit
**Report ID:** [REPORT_ID]

---

## Executive Summary

| Status | Result |
|--------|--------|
| **Overall Result** | [PASS / FAIL / CONDITIONAL PASS] |
| **Risk Level** | [LOW / MEDIUM / HIGH / CRITICAL] |
| **Recommendation** | [Safe to use / Use with caution / Do not use] |

**Summary:**
[One paragraph summary of the skill's security posture and key findings]

---

## Audit Scope

This audit examined the following aspects of the skill:

- Source code review
- Permission analysis
- Data flow examination
- Network activity patterns
- Input/output validation

**Limitations:**
[Any limitations of the audit, e.g., "Dynamic runtime analysis not performed"]

---

## Findings

### Critical Issues
[If none: "No critical issues found."]

[For each issue:]
#### [ISSUE_TITLE]
- **Severity:** Critical
- **Location:** [file/line or component]
- **Description:** [What was found]
- **Risk:** [What could happen if exploited]
- **Recommendation:** [How to fix]

---

### Warnings
[If none: "No warnings."]

[For each warning:]
#### [WARNING_TITLE]
- **Severity:** Warning
- **Location:** [file/line or component]
- **Description:** [What was found]
- **Recommendation:** [How to address]

---

### Informational Notes
[If none: "No informational notes."]

- [Note 1]
- [Note 2]

---

## Permission Analysis

| Permission Requested | Justified | Notes |
|---------------------|-----------|-------|
| [Permission 1] | [Yes/No] | [Why or why not] |
| [Permission 2] | [Yes/No] | [Why or why not] |

---

## Recommendations

### Required for Pass (if Conditional)
1. [Required fix 1]
2. [Required fix 2]

### Suggested Improvements
1. [Suggestion 1]
2. [Suggestion 2]

---

## Conclusion

[Final assessment paragraph - is this skill safe to use? Under what conditions?]

---

## Certification

This skill has been reviewed by ClawAudit and [has/has not] passed security review.

[If PASS:]
```
Audited by ClawAudit
Status: PASS
Date: [DATE]
Verify: clawhub.audit/verify/[REPORT_ID]
```

---

**ClawAudit**
Professional Security Audits for ClawHub Skills
[WEBSITE_URL]

*This report is provided for informational purposes. ClawAudit makes no guarantees about future security. Skills may change after audit.*
