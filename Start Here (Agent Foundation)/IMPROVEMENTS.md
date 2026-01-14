# 🔄 Governance Improvement Backlog

> **Purpose:** Central hub for collecting, evaluating, and integrating improvements to the governance system.
> **Owner:** Systems Catalyst (or USER for cross-project patterns)
> **Review Cadence:** Monthly or after every 3 projects

---

## How to Use This File

### Submitting Improvements
When any project discovers a better pattern:
1. Systems Catalyst logs it in that project's `CHRONICLES.md`
2. If the pattern is **reusable across projects**, add it to "Pending Review" below
3. Include the source project, description, and evidence

### Evaluation Criteria
Improvements are accepted if they:
- ✅ Apply to most/all project types (not project-specific)
- ✅ Reduce friction, increase quality, or improve security
- ✅ Don't add unnecessary complexity
- ✅ Have been validated in at least one real project

---

## Pending Review

| ID | Source Project | Category | Suggestion | Evidence | Submitted |
|----|----------------|----------|------------|----------|-----------|
| IMP-001 | [Example] | QA | Add API contract testing pattern | Caught 3 bugs in handoff | YYYY-MM-DD |
| | | | | | |

---

## Accepted (Queued for Next Release)

| ID | Category | Change Description | Target File(s) | Priority |
|----|----------|-------------------|----------------|----------|
| | | | | |

### Implementation Notes
<!-- When implementing accepted improvements, document any considerations here -->

---

## Integrated (Released)

| ID | Version | Change Description | Files Modified |
|----|---------|-------------------|----------------|
| IMP-000 | v1.1 | Added Data Architect Role | `data_architect.md`, `GOVERNANCE.md`, `CHANGELOG.md` |
| — | v1.0 | Initial governance system release | All |

---

## Rejected / Deferred

| ID | Suggestion | Reason | Revisit Date |
|----|------------|--------|--------------|
| | | | |

---

## Improvement Categories

Use these categories when submitting:

| Category | Scope |
|----------|-------|
| **Strategic** | Roadmap, prioritization, feature gating |
| **Security** | Threat models, audits, compliance |
| **Orchestration** | Team chemistry, handoffs, communication |
| **Architecture** | Tech patterns, ADRs, dependencies |
| **UI/UX** | Design tokens, accessibility, components |
| **Backend** | Schemas, APIs, performance |
| **QA** | Testing patterns, coverage, automation |
| **Templates** | Reusable document templates |
| **Governance** | Team structure, escalation, onboarding |

---

## Metrics (Optional)

Track governance effectiveness over time:

| Metric | Baseline | Current | Trend |
|--------|----------|---------|-------|
| Avg. feature cycle time | — | — | — |
| Rework rate | — | — | — |
| Security incidents | — | — | — |
| Handoff friction reports | — | — | — |

---

## Quick Add Template

Copy and paste to add a new improvement:

```markdown
| IMP-XXX | [Project Name] | [Category] | [Brief description] | [What evidence supports this?] | YYYY-MM-DD |
```
