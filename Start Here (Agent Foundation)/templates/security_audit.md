# Security Audit: [Feature Name]

> **Date:** [YYYY-MM-DD]
> **Auditor:** Security Lead
> **Status:** In Review | Cleared | Blocked

---

## Feature Overview
[Brief description of what is being audited]

---

## Input Validation
- [ ] All user inputs are sanitized (server-side)
- [ ] File uploads validated (type, size, content)
- [ ] No SQL/NoSQL injection vectors
- [ ] No XSS vectors in rendered content
- [ ] URL parameters validated and escaped
- [ ] JSON payloads schema-validated

**Notes:** [Any specific concerns or mitigations]

---

## Authentication & Authorization
- [ ] Auth required for all protected routes
- [ ] Session tokens are HttpOnly and SameSite
- [ ] JWT expiry is reasonable (< 1 hour for sensitive ops)
- [ ] RLS policies enforce user-scoped data access
- [ ] Admin functions require elevated permissions
- [ ] Password reset flow is secure

**Notes:**

---

## Secrets Management
- [ ] No hardcoded API keys or credentials in code
- [ ] All secrets in `.env` file (not committed)
- [ ] `.env.example` contains only placeholder values
- [ ] Secrets rotated if previously exposed
- [ ] No secrets logged to console or error outputs

**Notes:**

---

## Dependencies
- [ ] `npm audit` returns 0 high/critical vulnerabilities
- [ ] No deprecated packages with known CVEs
- [ ] Third-party APIs use HTTPS only
- [ ] External dependencies pinned to specific versions

**Audit Output:**
```
[Paste npm audit output here]
```

---

## Data Protection
- [ ] Sensitive data encrypted at rest (if applicable)
- [ ] PII minimized (collect only what's needed)
- [ ] Logs do not contain passwords, tokens, or PII
- [ ] Data retention policies documented
- [ ] Backup and recovery strategy exists

**Notes:**

---

## STRIDE Threat Model

| Threat | Status | Notes |
|--------|--------|-------|
| **S**poofing | ✅ Mitigated / ⚠️ Accepted / N/A | [Details] |
| **T**ampering | ✅ / ⚠️ / N/A | |
| **R**epudiation | ✅ / ⚠️ / N/A | |
| **I**nfo Disclosure | ✅ / ⚠️ / N/A | |
| **D**enial of Service | ✅ / ⚠️ / N/A | |
| **E**levation of Privilege | ✅ / ⚠️ / N/A | |

---

## Compliance Check
- [ ] GDPR requirements addressed (if applicable)
- [ ] HIPAA requirements addressed (if health data)
- [ ] Consent collection implemented (if required)

---

## Findings

### Blockers (Must Fix)
| ID | Issue | Severity | Recommendation |
|----|-------|----------|----------------|
| | | | |

### Recommendations (Should Fix)
| ID | Issue | Severity | Recommendation |
|----|-------|----------|----------------|
| | | | |

### Accepted Risks
| ID | Issue | Justification | Review Date |
|----|-------|---------------|-------------|
| | | | |

---

## Clearance Decision

- [ ] **CLEARED** - No blockers, approved for deployment
- [ ] **BLOCKED** - Must resolve issues listed above

**Signature:** Security Lead
**Date:** [YYYY-MM-DD]
