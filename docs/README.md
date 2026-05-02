# OctoAcme Project Management Docs

This folder contains the end-to-end process documentation for OctoAcme's project management practices. Use this README as your starting point to understand the overall approach and navigate to the relevant detail documents.

## Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**. Work begins when a new idea is ready to be explored, using a short **Project One-pager** to confirm the business need, define measurable success metrics, identify stakeholders, outline a high-level timeline and milestones, and capture initial risks and resourcing needs. A decision gate ensures success criteria and stakeholder alignment are clear before moving into planning, and core artifacts (charter/one-pager, backlog, Definition of Done, risk register, retro notes) are kept current throughout.

Roles are clearly defined to reduce ambiguity and improve ownership. A **Project Manager (PM)** coordinates delivery logistics—plans, schedules, risks, and communication—while a **Product Manager/Product Lead** defines desired outcomes, prioritizes the backlog, and measures success. **Developers** implement features with strong collaboration on design, estimation, testing, and documentation, while **QA/Testing** validates acceptance criteria and quality. Stakeholders contribute inputs and approvals, with a consistent expectation of clear acceptance criteria and a shared Definition of Done to keep scope and delivery aligned.

Execution is organized around a predictable team rhythm and structured workflow. Teams use daily standups for blockers and dependencies, a weekly delivery sync for progress and risk visibility, and demos/reviews at sprint or milestone boundaries. Work is tracked on a project board with standardized states (Backlog → Ready → In Progress → In Review → QA → Done). Communication follows a regular cadence—PM and Product weekly sync, periodic stakeholder updates—plus defined escalation paths for blockers: team triage first, then PM escalation to product/dependent teams, and sponsor escalation for business-impacting issues. Risks are managed via a simple risk register (impact/likelihood/owner/mitigation/status) reviewed routinely.

Quality assurance and release practices are built into the workflow rather than treated as end-stage activities. OctoAcme emphasizes small pull requests, linking PRs to issues and acceptance criteria, and requiring CI checks (tests, linting, security scanning) before review and merge approvals. Testing expectations include unit tests for new logic, integration tests where appropriate, and end-to-end smoke tests for critical flows, plus manual QA when needed for feature acceptance. Releases follow a standard checklist (release notes, rollback/mitigation plan, staging deploy and smoke tests, post-deploy verification, and stakeholder announcements), with an incident/rollback playbook and a strong retrospective practice to convert learnings into tracked, owned improvement actions.

---

## Documentation

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level summary of the full project lifecycle, key principles, and core artifacts |
| [Project Initiation](octoacme-project-initiation.md) | How to kick off a project: one-pager, success criteria, stakeholder alignment, and decision gate |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, Definition of Done, estimation, milestones, and sprint planning |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Team ceremonies, board workflow, progress reporting, and blocker escalation |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register format, communication cadence, escalation paths, and stakeholder updates |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release checklist, staging and smoke tests, post-deploy verification, rollback playbook |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retro format, capturing learnings, and tracking improvement actions |
| [Roles and Personas](octoacme-roles-and-personas.md) | Descriptions of each role (PM, Product Lead, Developer, QA, Stakeholder) and their responsibilities |
