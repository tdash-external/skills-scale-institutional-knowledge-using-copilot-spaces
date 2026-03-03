# OctoAcme — Post-Mortem Template

## Purpose
Provide a structured, blameless post-mortem record for production incidents, significant quality failures, or missed milestones. This document should be completed within 3 business days of the event and stored in the project's docs/ folder.

---

## Incident Overview

| Field | Value |
|-------|-------|
| Incident / Issue Title | |
| Date & Time of Occurrence | YYYY-MM-DD HH:MM (timezone) |
| Date & Time Resolved | YYYY-MM-DD HH:MM (timezone) |
| Severity | Critical / High / Medium / Low |
| Affected Users / Systems | |
| Reported By | |
| Incident Commander | |
| Post-Mortem Author | |
| Post-Mortem Date | |

---

## Timeline

List key events in chronological order.

| Time | Event |
|------|-------|
| HH:MM | Description of event or action |
| HH:MM | |
| HH:MM | |

---

## Impact Assessment

- **Users impacted:** (number or percentage)
- **Systems affected:** 
- **Duration:** 
- **Business impact:** (e.g., revenue, SLA breach, customer trust)
- **Data impact:** (any data loss, corruption, or exposure)

---

## Root Cause Analysis

### Immediate Cause
What directly triggered the incident?

### Root Cause(s)
Use the "5 Whys" or fishbone technique to trace back to underlying causes.

1. Why did [immediate cause] happen?
2. Why did [answer to #1] happen?
3. Why did [answer to #2] happen?
4. Why did [answer to #3] happen?
5. Why did [answer to #4] happen?

**Root cause conclusion:**

### Contributing Factors
List any factors that made the incident more likely or harder to resolve (process gaps, missing monitoring, communication delays, etc.):

- 
- 
- 

---

## What Went Well

(Even during incidents, capture things that worked — quick detection, good team communication, etc.)

-
-

## What Could Be Improved

-
-

---

## Action Items

| # | Action | Owner | Due Date | Status |
|---|--------|-------|----------|--------|
| 1 | | | YYYY-MM-DD | Open |
| 2 | | | YYYY-MM-DD | Open |
| 3 | | | YYYY-MM-DD | Open |

---

## Lessons Learned

Summarize key takeaways that should inform future practices, documentation updates, or tooling improvements.

---

## Distribution

- [ ] Post-mortem shared with delivery team
- [ ] Post-mortem shared with relevant stakeholders
- [ ] Action items added to project backlog
- [ ] Relevant process documentation updated
- [ ] Learnings added to team knowledge base
