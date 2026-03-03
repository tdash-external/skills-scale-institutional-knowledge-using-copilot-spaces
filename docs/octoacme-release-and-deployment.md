# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] All pre-release requirements verified (acceptance criteria, CI, security scan)
- [ ] Backup or snapshot (if applicable)
- [ ] Stakeholders notified of upcoming deployment (use release communication template below)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Release Communication Timeline
- **T-5 business days:** Notify stakeholders of upcoming release date and scope
- **T-1 business day:** Send final release notes and any preparation actions required from stakeholders
- **Day of release:** Confirm deployment window; send go/no-go confirmation
- **Post-deployment:** Send release announcement with summary of changes and support contacts

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

## Post-Release Review Checklist
- [ ] All success metrics reviewed against pre-release baseline
- [ ] Post-deploy verification steps completed without errors
- [ ] Stakeholder announcement sent
- [ ] Support team briefed on changes and known issues
- [ ] Monitoring dashboards reviewed (errors, latency, usage) for 24–48 hours post-deployment
- [ ] Rollback plan confirmed no longer needed
- [ ] Post-release retrospective scheduled (if significant release)
- [ ] Release artifacts archived (notes, decisions, incident records)
