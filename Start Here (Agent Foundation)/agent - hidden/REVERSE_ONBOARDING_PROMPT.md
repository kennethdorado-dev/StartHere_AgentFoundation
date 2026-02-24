# Reverse Onboarding: Master Prompt

Copy and paste this entire prompt when you're ready to onboard the governance system to your existing project.

---

## Onboarding Command

```
You are the Team Lead from `.agent/governance/team_lead.md`. This is a REVERSE ONBOARDING—the governance system is being added to an existing, in-flight project.

Your mission: Perform a rapid project assessment and populate the core governance files so the specialist agents can operate effectively.

---

### Phase 1: Initial Discovery (5 minutes)

1. **Read your profile**: `.agent/governance/team_lead.md`
2. **Read the constitution**: `.agent/governance/GOVERNANCE.md`
3. **Scan the project structure**: Use `list_dir` and `find_by_name` to understand:
   - Tech stack (look for package.json, requirements.txt, go.mod, etc.)
   - Directory structure (src/, components/, services/, etc.)
   - Existing documentation (README, docs/)

4. **Identify the project type**:
   - Is this a Web App, Mobile, API, Library, or CLI?
   - What's the primary language/framework?
   - Is there a database? If so, which one?

---

### Phase 2: Create Core Context (10 minutes)

Populate `docs/CORE_CONTEXT.md` with this structure:

```markdown
# Project Context

## Project Identity
- **Name:** [Extract from package.json or README]
- **Type:** [Web App / API / Mobile / etc.]
- **Primary Goal:** [Best guess from README or code]
- **Tech Stack:** [Framework, Language, DB, Hosting]

## Current State
- **Phase:** [Discovery / MVP / Production / Maintenance]
- **Estimated Completion:** [If determinable from code maturity]

## Architecture Summary
- **Frontend:** [Framework + key libs]
- **Backend:** [Framework + key libs]
- **Database:** [Type + ORM if any]
- **Auth:** [Method if implemented]
- **Deployment:** [Platform if configured]

## Existing Features (Implemented)
- [Feature 1 - Brief description]
- [Feature 2 - Brief description]
- [...]

## In Progress (Based on uncommitted changes or TODOs)
- [Feature/Task 1]
- [...]

## Known Issues
- [Issue 1 - if found in code comments or GitHub issues]
- [...]

## Next Priorities (Best Guess)
- [Priority 1]
- [Priority 2]
- [Priority 3]
```

---

### Phase 3: Identify Governance Debt (5 minutes)

Create `docs/GOVERNANCE_DEBT.md`:

```markdown
# Governance Debt Assessment

## Missing Documentation
- [ ] [Item 1 - e.g., "No API documentation"]
- [ ] [Item 2]

## Security Concerns
- [ ] [Concern 1 - e.g., "RLS policies not defined"]
- [ ] [Concern 2]

## Code Quality Issues
- [ ] [Issue 1 - e.g., "Inconsistent naming conventions"]
- [ ] [Issue 2]

## Testing Gaps
- [ ] [Gap 1 - e.g., "No E2E tests"]
- [ ] [Gap 2]

## Technical Debt
- [Item 1 - e.g., "Hardcoded values in components"]
- [Item 2]
```

---

### Phase 4: Specialist Activation Recommendations

Based on your discovery, recommend which specialists to onboard first:

```markdown
# Recommended Onboarding Sequence

## Immediate (Week 1)
1. **[Role]** - Rationale: [Why this role is critical now]
2. **[Role]** - Rationale: [...]

## Near-term (Week 2-3)
3. **[Role]** - Rationale: [...]
4. **[Role]** - Rationale: [...]

## Future
- [Remaining roles when bandwidth allows]
```

---

### Deliverable Summary

After completing the above, provide me with:

1. **Project Identity Card** (1 paragraph summary)
2. **Top 3 Governance Gaps** (What's missing most critically)
3. **Recommended First Specialist** (Which role should we onboard first and why)
4. **Quick Wins** (2-3 immediate improvements you can make without specialist involvement)

---

### Constraints

- Complete this in < 20 minutes of analysis time
- Prioritize breadth over depth (we can deep-dive later)
- Use compressed protocols; don't load full specialist profiles unless absolutely necessary
- If you need clarification on something that can't be inferred, list it as a question at the end
```

---

## How to Use This Prompt

1. **Copy the entire "Onboarding Command" section above** (everything in the code block).
2. **Paste it into a new conversation** with your AI agent.
3. **Wait for the Team Lead to complete the assessment** (~15-20 minutes of processing).
4. **Review the deliverables** and answer any clarification questions.
5. **Begin onboarding specialists** in the recommended sequence.

---

## Expected Output

You will receive:
- A fully populated `docs/CORE_CONTEXT.md`
- A `docs/GOVERNANCE_DEBT.md` file
- A recommended onboarding sequence
- A 1-paragraph project summary
- 2-3 quick wins you can implement immediately

This gives your entire agent team a shared understanding of the project state in under 30 minutes total.
