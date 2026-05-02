# OctoAcme — Role Responsibility Map Template (RACI)

## Purpose
Provide a lightweight, fill-in RACI chart that maps each project lifecycle phase to the core OctoAcme roles. Use this template at project initiation and revisit it during planning to ensure every phase has clear ownership, accountability, and consultation paths.

## When to create / update
- **Create** during the Initiation phase, alongside the Project One-pager.
- **Revisit** at the start of Planning to confirm role availability and adjust assignments.
- **Review** at each phase transition (e.g., Execution → Release) to confirm hand-offs.

## RACI Key

| Code | Meaning |
|------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome; approves deliverables (only one per row) |
| **C** | Consulted — provides input before or during the work |
| **I** | Informed — kept up-to-date on decisions and progress |

---

## RACI Table

> Replace each cell with R, A, C, I, or leave blank if the role has no involvement in that activity.

| Lifecycle Phase / Activity | PM | PdM | Dev | QA Engineer | UX Designer | Technical Writer | Scrum Master | Stakeholders |
|----------------------------|----|-----|-----|-------------|-------------|-----------------|--------------|--------------|
| **Initiation** | | | | | | | | |
| Define problem statement | C | A | I | I | C | I | I | C |
| Identify stakeholders | A | R | I | I | I | I | I | C |
| Create Project One-pager | R | C | I | I | I | I | C | I |
| Initial risk identification | A | C | C | C | C | I | C | I |
| Populate Role Responsibility Map | A | C | I | I | I | I | R | I |
| **Planning** | | | | | | | | |
| Backlog creation & prioritization | C | A | C | C | C | I | R | C |
| UX research & wireframes | I | C | C | I | A/R | I | I | C |
| Test plan / QA strategy | C | C | C | A/R | I | I | C | I |
| Documentation plan | I | C | I | I | I | A/R | C | I |
| Milestone & release planning | A | C | C | C | C | C | R | I |
| Definition of Done | C | C | C | A/R | C | C | R | I |
| **Execution** | | | | | | | | |
| Feature implementation | I | C | A/R | C | C | I | I | I |
| Design reviews | I | C | C | I | A/R | I | I | I |
| Sprint facilitation & ceremonies | C | C | I | I | I | I | A/R | I |
| Defect triage | C | I | R | A | I | I | C | I |
| Draft documentation | I | C | C | I | I | A/R | I | I |
| Status reporting | A/R | I | I | I | I | I | C | I |
| **Release** | | | | | | | | |
| Release checklist sign-off | A | C | C | C | C | C | C | I |
| Smoke & regression testing | C | I | C | A/R | I | I | I | I |
| Release notes & announcements | C | C | I | I | I | A/R | I | I |
| Stakeholder go-live communication | A/R | C | I | I | I | C | I | I |
| **Retrospective** | | | | | | | | |
| Facilitate retrospective | C | I | I | I | I | I | A/R | I |
| Capture learnings & action items | R | C | C | C | C | C | A | I |
| Update process documentation | C | C | I | I | I | A/R | C | I |
| Communicate improvements | A/R | C | I | I | I | C | C | I |

---

## Required Artifacts by Phase

| Phase | Key Artifacts | Primary Owner |
|-------|--------------|---------------|
| Initiation | Project One-pager, Stakeholder list, Role Responsibility Map | PM |
| Planning | Prioritized backlog, UX wireframes, Test plan, Doc plan, Release timeline, DoD | PM + PdM |
| Execution | Sprint backlog, Defect log, Design specs, Draft docs, Status reports | Dev + QA + UX + TW |
| Release | Release checklist, Test results, Release notes, Go-live sign-off | PM + QA + TW |
| Retrospective | Retro notes, Action items, Updated process docs | Scrum Master + TW |

---

## Instructions for Use

1. **Copy this template** into your project's `docs/` or `.copilot/` folder and rename it to `<project-name>-role-responsibility-map.md`.
2. **Fill in the project name and date** at the top of your copy.
3. **Adjust the RACI cells** to reflect the actual team composition and any project-specific activities.
4. **Review with the team** during the kickoff meeting to validate assignments and resolve any ownership gaps.
5. **Update at each phase transition** to reflect changes in team membership or scope.

> **Tip:** Every row must have exactly one **A** (Accountable). If you find multiple A's in a row, resolve the ownership gap before moving to the next phase.
