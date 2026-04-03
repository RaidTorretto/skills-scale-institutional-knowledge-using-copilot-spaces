# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- **Daily standups (15 min)**: Focus on progress, blockers, dependencies. Scrum Master facilitates.
- **Weekly delivery sync**: Show progress, updates, and flagged risks. PM and Tech Lead lead.
- **Sprint review/Demo**: Product Manager, Developers, Designer, Stakeholder Advocate, and stakeholders participate.
- **Sprint retrospective**: Scrum Master facilitates; all core team members participate.

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require Tech Lead + at least one peer approval before merging (or team-defined policy)
- Design review workflow (for UI/UX work):
  - Designer presents design; seeks feedback from PM, Tech Lead, and lead Developers
  - Incorporate feedback and finalize before implementation

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- Design reviews before implementation to ensure alignment
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed (coordinate with QA/Testing role)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)
- Share metrics with Stakeholder Advocate for stakeholder communication

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup. Scrum Master helps identify resolution.
- **Level 2**: PM escalates to Tech Lead, Product Lead, and dependent teams.
- **Level 3**: Sponsor-level escalation for business-impacting issues (PM + Stakeholder Advocate).

## Role-Specific Responsibilities During Execution
- **Scrum Master**: Facilitates ceremonies, unblocks team, tracks action items from retrospectives.
- **Tech Lead**: Reviews code/design, mentors team, escalates technical risks to PM.
- **UX Designer**: Supports implementation via design refinement and QA feedback.
- **DevOps/Release Manager**: Monitors deployment readiness, manages infrastructure blockers.
- **Stakeholder/Customer Advocate**: Provides feedback at demos, flags business/user concerns.

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests, lint, and security scanning
- [ ] Design reviews include PM, Tech Lead, and UX Designer
- [ ] Daily standups scheduled and Scrum Master assigned
- [ ] Sprint retrospectives captured with action items tracked
- [ ] Regular demos scheduled with Stakeholder Advocate participation
- [ ] Risk register updated weekly and reviewed in team syncs
- [ ] Code review standards enforced (Tech Lead + peer sign-off)
- [ ] QA acceptance criteria validated before marking Done