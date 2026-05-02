# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Engineer

### Role Summary
QA Engineers design and execute test strategies to validate that features meet acceptance criteria and quality standards. They partner closely with Developers and Project Managers to surface defects early and protect release quality.

### Responsibilities
- Develop and maintain test plans, test cases, and automated test suites
- Execute functional, regression, and exploratory testing across sprint increments
- Triage and track defects through to resolution
- Verify acceptance criteria for all user stories before sign-off
- Contribute to the Definition of Done and quality gates

### Goals
- Ensure every release meets agreed quality and acceptance standards
- Reduce production defects through early and continuous testing
- Build shared quality ownership across the entire delivery team

### Typical Communication
- Daily standups to flag blockers and testing progress
- Defect reports and triage sessions with Developers
- Test summary reports to Project Manager and Product Manager before release

### Interaction Model
- **Project Manager**: Provides testing status and risk signals for schedule decisions; escalates blocking defects.
- **Product Manager**: Clarifies acceptance criteria and edge cases; confirms when stories meet the Definition of Done.
- **Developers**: Collaborates on testability, reproduction steps, and defect triage; reviews test coverage during code review.
- **Stakeholders**: Shares release readiness summaries and known issues before go-live.

---

## UX Designer

### Role Summary
UX Designers own user research, interaction design, and experience flows. They ensure that features are useful, usable, and aligned with customer needs before development begins.

### Responsibilities
- Conduct user research, usability studies, and competitive analysis
- Create wireframes, prototypes, and high-fidelity mockups
- Define and maintain the UX style guide and component library
- Collaborate with Product Managers to translate requirements into user flows
- Review implemented features for design fidelity and accessibility

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework by resolving design ambiguity before development starts
- Champion the user perspective across all project phases

### Typical Communication
- Design reviews and prototype walkthroughs with Product Manager and Developers
- Usability test findings shared with the broader team
- Design handoff notes and annotated specs in the project repository

### Interaction Model
- **Project Manager**: Aligns on design milestones and flags scope changes that affect UX timelines.
- **Product Manager**: Partners to translate product goals into user flows and acceptance criteria; validates design against success metrics.
- **Developers**: Provides annotated specs and is available to answer implementation questions; participates in design QA before sign-off.
- **Stakeholders**: Presents design concepts and incorporates feedback through structured review cycles.

---

## Technical Writer

### Role Summary
Technical Writers create and maintain user-facing and internal documentation, ensuring that processes, APIs, and features are clearly communicated to all audiences.

### Responsibilities
- Author and update user guides, release notes, API references, and process docs
- Maintain a consistent documentation style, tone, and structure across the project
- Collaborate with Developers and Product Managers to document new features before release
- Review docs for accuracy after each sprint or release
- Ensure documentation is stored and versioned alongside the product

### Goals
- Make product and process knowledge accessible and discoverable for every team member and end user
- Reduce support burden by ensuring documentation is accurate and up-to-date
- Support onboarding by keeping process and role documentation current

### Typical Communication
- Sprint review participation to capture new feature details
- Documentation review cycles with Developers and Product Managers
- Release checklist sign-off confirming docs are complete

### Interaction Model
- **Project Manager**: Coordinates documentation deadlines as part of the release plan; flags doc debt that could delay release readiness.
- **Product Manager**: Reviews draft documentation against the product vision and feature intent; provides source material from specs and acceptance criteria.
- **Developers**: Obtains technical accuracy reviews; documents code-level details such as API contracts and configuration options.
- **Stakeholders**: Prepares stakeholder-facing content such as release notes and announcement drafts for review and approval.

---

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master / Delivery Facilitator enables the team to work effectively within an Agile framework. They facilitate ceremonies, remove impediments, and continuously improve team processes.

### Responsibilities
- Facilitate sprint ceremonies: planning, daily standup, review, and retrospective
- Identify, track, and escalate impediments that block team progress
- Coach team members on Agile principles and practices
- Shield the team from unplanned interruptions during a sprint
- Track and communicate team velocity, capacity, and sprint health

### Goals
- Maximize team flow and remove friction from the delivery process
- Foster a culture of continuous improvement and psychological safety
- Help the team consistently meet sprint commitments

### Typical Communication
- Daily standups and ceremony facilitation
- Impediment logs and escalation notes shared with Project Manager
- Sprint retrospective summaries and improvement action items

### Interaction Model
- **Project Manager**: Aligns on sprint capacity and escalates blockers that require cross-team intervention or resource decisions.
- **Product Manager**: Coordinates backlog grooming cadence; ensures the backlog is refined and ready for upcoming sprints.
- **Developers**: Coaches on Agile practices, removes process blockers, and facilitates healthy team dynamics.
- **Stakeholders**: Communicates sprint progress and manages expectations around scope and timeline changes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the [Role Responsibility Map Template](octoacme-role-responsibility-map-template.md) to assign RACI ownership across lifecycle phases whenever a new project is initiated.

