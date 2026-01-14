# Changelog

All notable changes to this governance system will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Added
- 

### Changed
- 

### Deprecated
- 

### Removed
- 

### Fixed
- 

---

## [1.3.0] - 2026-01-12

### Added
- **Team Lead** (`team_lead.md`): Master Orchestrator agent that serves as the single entry point for all requests.
- **Request Classification Engine**: Decision tree for routing requests to appropriate domains.
- **Compressed Role Protocols**: Token-efficient summaries of each specialist's core behaviors.
- **Blended Execution Pattern**: Multi-domain task handling without context switches.
- **Loyalty Hierarchy**: Decision-making priority placing project success over individual role protocols.
- **Synergy Patterns**: High-efficiency pairings between complementary roles.

### Changed
- **GOVERNANCE.md**: Added Team Lead to Role Summary table.

## [1.2.0] - 2026-01-12

### Added
- **Profile Activation Guidelines** (Section 11 of `GOVERNANCE.md`): Comprehensive baseline configurations derived from industry best practices.
- **Global Operational Defaults**: Autonomy, documentation, communication, and risk tolerance settings.
- **Role-Specific Baselines**: Recommended starting values for each agent's [USER] section.
- **Project-Type Tuning Matrix**: Quick-configure presets for Hackathon, Enterprise, R&D, and Open Source projects.
- **Hard Constraints**: Non-negotiable "Never Do" list across all agents.
- **Communication Presets**: Concise, Explanatory, Formal, and Collaborative tone options.

## [1.1.0] - 2026-01-08

### Added
- **Data Architect** (`data_architect.md`): New role dedicated to bridging frontend-first development and database implementation. Owns 9 facets of data strategy.
- **Workflow Integration**: Inserted Data Architect into the Phase Gate workflow between UI/UX and Backend implementation.
- **Data Governance**: Added protocols for Data Discovery, Modeling, Sensitivity Classification, and canonical Data Dictionary management.

### Changed
- **GOVERNANCE.md**: Updated hierarchy diagram, communication matrix, and decision authority to include Data Architect.

---

## [1.0.0] - 2026-01-08

### Added

#### Agent Profiles
- **Strategic Lead** (`strategic_lead.md`): RICE scoring framework, Strategy Brief template, Phase Gate system, escalation protocols
- **Security Lead** (`security_lead.md`): STRIDE threat model, OWASP Top 10 reference, RLS policy templates, Incident Response protocol
- **Systems Catalyst** (`systems_catalyst.md`): Orchestration metrics, 5 Whys analysis, Retrospective templates, Friction audit protocol
- **Architect** (`architect.md`): ADR template, Dependency justification protocol, Tech debt tracking, Code review standards
- **UI/UX Specialist** (`ui_ux_specialist.md`): Complete design token system (HSL colors, typography, spacing, shadows), A11y checklist, Animation library
- **Backend Engineer** (`backend_engineer.md`): Schema design checklist, API contract templates, Service layer patterns, Migration protocol
- **QA Specialist** (`qa_specialist.md`): Test strategy matrix, Bug triage protocol, E2E test patterns, Deployment clearance checklist

#### Governance
- **GOVERNANCE.md**: Team hierarchy diagram, Inter-agent communication matrix, Phase Gate workflow, Decision authority levels, Escalation template, Conflict resolution protocol, Onboarding sequence

#### Templates
- `templates/strategy_brief.md`: Feature justification with RICE scoring
- `templates/adr.md`: Architectural Decision Record format
- `templates/security_audit.md`: Per-feature security checklist
- `templates/bug_report.md`: Structured bug documentation
- `templates/chronicles_entry.md`: Lessons learned format

#### Operational Assets
- `docs/CORE_CONTEXT.md`: Single Source of Truth placeholder
- `brain/CHRONICLES.md`: Lessons learned log placeholder
- `IMPROVEMENTS.md`: Continuous improvement backlog

---

## Version Guidelines

### When to Increment

| Change Type | Version Bump | Example |
|-------------|--------------|---------|
| Bug fix in existing protocol | PATCH (1.0.X) | Fix typo in checklist |
| New template or minor addition | MINOR (1.X.0) | Add new E2E test pattern |
| Breaking structure change | MAJOR (X.0.0) | Reorganize agent hierarchy |

### Release Process

1. Move items from `[Unreleased]` to new version section
2. Update version number and date
3. Commit with message: `chore: release vX.Y.Z`
4. Tag the commit: `git tag -a vX.Y.Z -m "Release description"`
5. Push with tags: `git push --tags`

---

## Glossary

- **ADR**: Architectural Decision Record
- **RLS**: Row Level Security (Supabase/PostgreSQL)
- **RICE**: Reach, Impact, Confidence, Effort (prioritization)
- **STRIDE**: Spoofing, Tampering, Repudiation, Info Disclosure, DoS, Elevation (threat model)
- **A11y**: Accessibility
- **SSOT**: Single Source of Truth
