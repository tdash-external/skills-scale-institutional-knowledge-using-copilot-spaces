# OctoAcme Project Management Docs

This README is the entry point and index for all project management process documentation at OctoAcme. It provides a summary of our project management practices and links to detailed guides covering each phase of the project lifecycle.

> **Note:** This documentation was improved as part of [issue #3](https://github.com/tdash-external/skills-scale-institutional-knowledge-using-copilot-spaces/issues/3) to address process gaps and enhance clarity across the project lifecycle.

## Project Management Processes Summary

OctoAcme follows a consistent, iterative project management lifecycle grounded in a set of core principles: customer-first prioritization, iterative delivery of small and testable increments, clear ownership with named Project Managers and Product Leads, data-informed decision-making, and a culture of psychological safety that encourages open feedback and continuous learning.

Every project begins with an **Initiation** phase, where the team validates the business need, aligns stakeholders, defines measurable success criteria, and makes a formal go/no-go decision before investing further. The key output is a lightweight Project One-pager capturing the problem statement, goals, stakeholders, timeline, and initial risks. Stakeholders are notified via a standard communication template, and all key decisions are recorded in a Decision Log for auditability.

Once approved, the project moves into **Planning**, where the team holds a structured kickoff meeting (with a documented agenda), breaks work into a prioritized backlog with acceptance criteria, estimates scope, maps milestones and releases, documents a Definition of Done, and confirms stakeholder sign-off before execution begins. Dependencies and risks are captured in a Risk Register from the start.

During **Execution & Tracking**, the delivery team operates in a structured team rhythm: daily standups to surface blockers, weekly delivery syncs to review progress and flagged risks, and sprint demos or milestone reviews. Work flows through a project board (Backlog → Ready → In Progress → In Review → QA → Done), with small pull requests, CI-enforced automated tests and linting, and at least one required approval before merging. Quality assurance is built into the workflow through unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when needed. Velocity and burndown are tracked against the success metrics established at initiation. Blockers are tracked with a resolution template and escalated through clearly defined levels with target resolution timelines.

**Risk Management & Communication** runs continuously throughout the project. The Risk Register captures expanded fields including category, risk score, contingency plan, trigger signals, and residual risk after mitigation. Risks are identified, assessed by impact and likelihood, mitigated through concrete actions, and monitored at weekly syncs. Stakeholder communication is managed via a Stakeholder Communication Matrix that defines who receives what, when, and through which channel. Escalation paths are clearly defined: blockers flow from the team to the PM, then to the Product Lead, and finally to the Sponsor for business-impacting issues, with escalation timelines specified at each level.

When work is ready to ship, the **Release & Deployment** process standardizes how features go to production. Pre-release requirements include all acceptance criteria met, passing CI and security scans, drafted release notes, and a rollback plan. Deployments follow a checklist from staging smoke tests through production deployment and stakeholder announcement. A release communication timeline ensures stakeholders receive advance notice before each deployment. A post-release review checklist confirms the deployment succeeded and monitoring has been verified. A rollback and incident playbook is in place for critical failures.

After each sprint, release, or significant milestone, the team conducts a **Retrospective** to capture what went well, what could be improved, and concrete action items with owners and due dates. For production incidents and significant failures, a dedicated **Post-Mortem** process is followed using the post-mortem template, including a blameless root cause analysis, impact assessment, action items, and distribution checklist. Action items are tracked in the project backlog and reviewed in the weekly PM sync, fostering a culture of continuous, measurable improvement.

### Roles & Personas

OctoAcme projects are delivered by a small set of well-defined roles. **Project Managers (PM)** coordinate delivery, own schedules, manage risks and dependencies, and ensure consistent status reporting and stakeholder communication. **Product Managers (PdM)** define the product vision and outcomes, own the roadmap and backlog prioritization, and validate solutions through user research and metrics. **Developers** design, implement, test, and document software components, participate in code and design reviews, and help identify technical risks. **QA Engineers** validate quality and acceptance criteria, design and maintain test plans, and provide a quality sign-off before each release. **Stakeholders** provide business requirements and approvals at key decision gates and receive regular milestone-based briefings. Persona definitions are documented in detail to support scenario-based exercises and role-specific guidance in Copilot Spaces.

---

## Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level summary of OctoAcme's project management approach, principles, core roles, key artifacts, lifecycle, and communication cadence |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize new work, align stakeholders, and create a lightweight plan — including One-pager template, stakeholder communication template, decision log, and initiation checklist |
| [Project Planning Guide](octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog and plan — kickoff agenda, estimation, Definition of Done, stakeholder alignment steps, and planning checklist with decision gate |
| [Execution & Tracking Guide](octoacme-execution-and-tracking.md) | Day-to-day delivery guidance including team rhythm, PR workflow, quality & testing standards, metrics, and blocker escalation with timelines and resolution template |
| [Risks & Communication Guide](octoacme-risks-and-communication.md) | Expanded risk register format, risk lifecycle, stakeholder communication matrix, status and milestone templates, incident communication, and escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardized release process covering release types, pre-release requirements, deployment checklist, release communication timeline, post-release review checklist, rollback & incident playbook, and release notes template |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Structured retrospective format, facilitation guidance, action item tracking, continuous improvement culture, and post-mortem checklist for incidents |
| [Post-Mortem Template](octoacme-post-mortem-template.md) | Blameless post-mortem document template for production incidents and significant failures, including timeline, root cause analysis, impact assessment, action items, and distribution checklist |
| [Roles & Personas Reference](octoacme-roles-and-personas.md) | Detailed definitions of Developer, Product Manager, Project Manager, QA Engineer, and Stakeholder roles including responsibilities, goals, and communication patterns |
