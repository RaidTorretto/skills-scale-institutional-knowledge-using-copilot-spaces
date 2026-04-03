# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles

**Core Delivery Team:**
- **Project Manager (PM)**: Coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success.
- **Developers**: Implement features, collaborate on design and testability.
- **Tech Lead**: Provides technical direction, mentors team, ensures code quality.

**Specialist Roles (as needed):**
- **UX Designer**: Designs user flows and interfaces; collaborates with PM and Developers.
- **QA/Testing**: Validates quality and acceptance criteria.
- **DevOps/Release Manager**: Manages deployment pipelines and release readiness.
- **Scrum Master / Delivery Facilitator**: Facilitates ceremonies, removes blockers, fosters improvement.
- **Stakeholder / Customer Advocate**: Represents user/business needs, validates solutions.

**Supporting Roles:**
- **Stakeholders**: Provide inputs, feedback, and approvals.

_See [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md) for detailed definitions, responsibilities, and cross-functional interactions of each role._

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog with Acceptance Criteria
- Risk Register and Dependency Map
- Definition of Done (DoD)
- Retrospective notes and action items

## Lifecycle (high-level)
1. **Initiation**: Problem statement, stakeholders, high-level timeline.
2. **Planning**: Scope, resources, milestones, dependencies, team composition.
3. **Execution**: Build, test, review, iterate with daily standup rhythm.
4. **Release**: Deploy, verify, announce, monitor.
5. **Close & Retrospective**: Capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM + Tech Lead
- Twice-weekly standups for delivery team (or as agreed)
- Sprint planning and retrospectives (Scrum Master leads)
- Monthly stakeholder updates (PM + Stakeholder Advocate)
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Reference `octoacme-roles-and-personas.md` to clarify who is involved at each phase.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.