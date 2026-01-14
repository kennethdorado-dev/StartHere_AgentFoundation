# Agent Foundation: Multi-Agent Governance System

Welcome to the **Agent Foundation**, a comprehensive "Golden Image" governance system designed to orchestrate multi-agent AI teams. This repository serves as a starter kit for establishing robust, expert-level operational protocols across any software project.

## 🚀 Overview

This system provides a structured framework for AI agents to collaborate effectively. It defines specific roles, responsibilities, communication protocols, and decision-making hierarchies to ensure projects move from chaotic "vibes-based" coding to professional, scalable engineering.

## 📂 Repository Structure

The core of this system lives in the `.agent` directory, containing specialized profile instructions for each role in the multi-agent team.

```
.
├── .agent/
│   ├── governance/          # Detailed role definitions and protocols
│   │   ├── team_lead.md     # Master Orchestrator & Single Point of Entry
│   │   ├── strategic_lead.md# Product strategy & RICE prioritization
│   │   ├── architect.md     # Technical decisions & ADRs
│   │   ├── security_lead.md # Threat modeling & security audits
│   │   ├── systems_catalyst.md # Process optimization & retrospectives
│   │   ├── data_architect.md # Data strategy & schema design
│   │   ├── ui_ux_specialist.md # Design systems & accessibility
│   │   ├── backend_engineer.md # API implementation & logic
│   │   └── qa_specialist.md # Testing strategies & quality gates
│   └── REVERSE_ONBOARDING_PROMPT.md # Prompt for initializing existing projects
├── docs/
│   └── CORE_CONTEXT.md      # The Single Source of Truth for project context
├── templates/               # Reusable governance templates (ADRs, Briefs, etc.)
├── CHANGELOG.md             # Version history of the governance system itself
└── IMPROVEMENTS.md          # Backlog for cross-project governance enhancements
```

## 🛠 Roles & Responsibilities

Each agent has a highly specific "Persona" and set of "Operating Protocols":

- **Team Lead**: The conductor. Managing the flow of work, assigning tasks, and ensuring no agent is blocked.
- **Strategic Lead**: The visionary. Defines *what* to build and *why*, using RICE scoring to prioritize features.
- **Architect**: The builder. Makes high-level technical decisions and ensures code manageability.
- **Security Lead**: The guardian. Proactively identifies risks and enforces security best practices.
- **Systems Catalyst**: The improver. Optimizes the workflow and identifies bottlenecks in the agentic process.
- **Data Architect**: The structured thinker. Owens the data model, database schema, and data governance.
- **UI/UX Specialist**: The designer. Ensures a premium, accessible, and user-centric frontend experience.
- **Backend Engineer**: The implementer. scalable business logic and API integration.
- **QA Specialist**: The validator. Prevents regressions and ensures high-quality releases.

## 🏁 Getting Started

To use this foundation for a new or existing project:

1.  **Copy the System**: Copy the entire `.agent` directory, `docs` folder, and `templates` folder into your project root.
2.  **Initialize Context**: 
    - Open `docs/CORE_CONTEXT.md` and fill in your project's Identity, Tech Stack, and Goals.
    - *Tip*: If you have an existing codebase, run the `REVERSE_ONBOARDING_PROMPT.md` with an AI model to auto-generate this context.
3.  **Activate Roles**: When interacting with the AI, explicitly invoke the relevant role or let the **Team Lead** route your request.

## 🔄 Workflow

The system uses a **Phase-Gate Process** to ensure quality:

1.  **Strategy Phase**: Feature is defined and scored (Strategic Lead).
2.  **Design & Architecture Phase**: Tech stack and UI verified (Architect & UI/UX).
3.  **Implementation Phase**: Code is written (Backend/Frontend).
4.  **Verification Phase**: Code is tested and security-audited (QA & Security).
5.  **Review Phase**: Lessons learned are logged (Systems Catalyst).

## 🤝 Contributing

We believe in continuous improvement.
- Check `IMPROVEMENTS.md` to see the backlog of governance enhancements.
- Log new reusable patterns or suggestions in `IMPROVEMENTS.md` under "Pending Review".
- Semantic Versioning is used for this governance system (see `CHANGELOG.md`).

---

*This system helps you build not just code, but a self-improving engineering organization.*
