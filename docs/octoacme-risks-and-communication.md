# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a table with the following fields:

| Field | Description |
|-------|-------------|
| ID | Unique identifier (e.g., RSK-001) |
| Description | Clear description of the risk |
| Category | Technical / Resource / External / Process / Security |
| Impact | High / Medium / Low — effect if risk materializes |
| Likelihood | High / Medium / Low — probability of occurrence |
| Risk Score | Impact × Likelihood (see matrix below) |

**Risk Score Matrix:**

| | High Impact | Medium Impact | Low Impact |
|-|-------------|---------------|------------|
| **High Likelihood** | High | High | Medium |
| **Medium Likelihood** | High | Medium | Low |
| **Low Likelihood** | Medium | Low | Low |
| Owner | Person responsible for monitoring and mitigating |
| Mitigation Plan | Specific actions to reduce likelihood or impact |
| Contingency Plan | Steps to take if the risk materializes |
| Trigger | Early-warning signals that indicate risk is materializing |
| Residual Risk | Risk level after mitigation is applied |
| Status | Open / Mitigated / Closed / Escalated |
| Last Updated | Date of most recent review |

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

**Stakeholder Communication Matrix:**

| Stakeholder Group | Communication Type | Frequency | Channel | Owner |
|-------------------|--------------------|-----------|---------|-------|
| Executive Sponsor | Status summary + decisions needed | Bi-weekly | Email / Slide deck | PM |
| Product Lead | Detailed status + risks | Weekly | Sync meeting | PM |
| Delivery Team | Blocker triage + sprint goals | Daily | Standup | PM / Tech Lead |
| External Partners | Progress update + dependencies | As needed | Email | PM |
| Support / Sales | Release notes + known issues | Per release | Email / Slack | PM / PdM |

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Milestone Stakeholder Briefing Template:
- Milestone reached:
- What was delivered:
- Impact on timeline / next milestone:
- Outstanding risks:
- Required decisions or approvals:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- Escalation should be triggered when a blocker is unresolved after one business day at the current level
- All escalations should be documented in the project's Decision Log with date, reason, and resolution
