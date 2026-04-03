# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- **Patch**: Hotfixes addressing critical production issues
- **Minor**: Incremental features and improvements
- **Major**: Significant functionality or breaking changes

## Key Participants
- **DevOps/Release Manager**: Leads deployment planning, coordination, and execution
- **Project Manager**: Schedules release window, communicates timeline
- **Tech Lead**: Validates technical readiness, identifies compatibility concerns
- **QA/Testing**: Confirms smoke tests and acceptance criteria validation
- **Developers**: Prepare release artifacts, support troubleshooting
- **Stakeholder/Customer Advocate**: Ensures customer and business readiness, communicates go-live
- **Product Manager**: Validates feature completeness, approves release

## Pre-release requirements
- All acceptance criteria met and PRs merged to release branch
- Passing CI and security scans
- Tech Lead sign-off on code and architecture
- QA confirmation of smoke tests and critical path testing
- Release notes drafted by Product Manager and reviewed by team
- Rollback / mitigation plan documented by DevOps/Release Manager
- Deployment runbook prepared and validated
- Stakeholder readiness confirmed (support, sales, docs, etc.)

## Deployment Checklist
- [ ] DevOps/Release Manager: Deployment window scheduled and communicated
- [ ] Tech Lead: Technical readiness review completed
- [ ] QA/Testing: Smoke tests prepared and validated in staging
- [ ] DevOps: Backup or snapshot taken (if applicable)
- [ ] DevOps: Deploy to staging and run smoke tests
- [ ] QA + Tech Lead: Sign-off on staging validation
- [ ] DevOps: Deploy to production (automated pipeline preferred)
- [ ] DevOps + Tech Lead: Run post-deploy verifications and monitoring
- [ ] DevOps: Confirm system health and performance
- [ ] PM + Stakeholder Advocate: Announce release to customers and stakeholders
- [ ] DevOps: Monitor production for 24-48 hours post-release

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - DevOps/Release Manager triggers incident response and notifies on-call team
  - Tech Lead and Developers support rapid triage
  - Rollback to last known-good release if necessary
  - PM communicates status to stakeholders
  - Post-incident blameless retrospective scheduled with team
  - Action items tracked and prioritized for future releases

## Release Notes Template
- Release name / number:
- Date:
- Summary (for customers):
- Notable changes (new features, improvements, fixes):
- Known issues (with workarounds if available):
- Migration steps (if any):
- Rollback procedure (for ops reference):
- Support contact (for escalations):