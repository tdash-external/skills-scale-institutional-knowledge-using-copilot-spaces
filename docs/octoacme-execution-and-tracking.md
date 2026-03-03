# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (resolve within 1 business day)
- Level 2: PM escalates to Product Lead and dependent teams (unresolved after 1 business day; target resolution within 2 business days from escalation)
- Level 3: Sponsor-level escalation for business-impacting or unresolved blockers (target 24-hour executive response)

**Blocker Resolution Template:**

| Field | Value |
|-------|-------|
| Blocker ID | BLK-### |
| Description | What is blocked and why |
| Impact | Which deliverables or milestones are at risk |
| Raised by | Name / date |
| Escalation level | 1 / 2 / 3 |
| Owner | Who is resolving it |
| Target resolution date | YYYY-MM-DD |
| Resolution notes | How it was resolved |

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Blocker escalation path communicated to team
- [ ] Dashboard or metrics tracking set up for project success metrics
