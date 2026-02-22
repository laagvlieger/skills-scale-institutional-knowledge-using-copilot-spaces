# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

> **Related resources:** [Roles & Personas](./octoacme-roles-and-personas.md) | [Project Planning](./octoacme-project-planning.md) | [Risk Management & Communication](./octoacme-risks-and-communication.md)

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

## Role Responsibilities in Execution

| Activity | Primary Owner | Supporting Roles |
|---|---|---|
| Daily standup facilitation | Project Manager | All team members |
| PR review and merge approval | Technical Lead / Developer | Developer |
| QA and acceptance validation | Developer | Product Manager |
| CI/CD pipeline maintenance | DevOps Engineer | Technical Lead |
| Risk register updates | Project Manager | Technical Lead |
| Sprint demo facilitation | Project Manager | Product Manager |
| Design review sign-off | UX Designer | Product Manager, Developer |
| Customer-impacting issue triage | Support/Customer Success | Project Manager, DevOps Engineer |

## Blocker Escalation

Escalate blockers promptly at the appropriate level:

- **Level 1 — Team triage:** Raise in daily standup. The team self-organizes to resolve.
  - *Example:* A developer is blocked on a dependency from another developer on the same team.
- **Level 2 — Cross-team or PM escalation:** Project Manager escalates to Product Lead and dependent teams. Technical Lead supports with technical context.
  - *Example:* An external API is unavailable; PM coordinates with the partner team and adjusts the sprint scope.
- **Level 3 — Sponsor-level escalation:** For business-impacting or unresolvable issues. Project Manager or Product Manager escalates to the project sponsor.
  - *Example:* A critical security vulnerability is discovered days before a release; sponsor and security team are notified immediately.
- **Security incidents:** Follow the security incident runbook. Notify Security on-call and loop in DevOps Engineer and Technical Lead.

## Stakeholder and Technical Review Checkpoints

Formal reviews must be scheduled at the following points:

- **Sprint/milestone demo:** At the end of each sprint or milestone. Product Manager and key stakeholders attend.
- **Technical design review:** Before starting any major new feature or architectural change. Technical Lead convenes. Required attendees: Technical Lead, Developers working on the feature, DevOps Engineer.
- **Release readiness review:** Before any production deployment. DevOps Engineer leads. Required attendees: Technical Lead, Project Manager, Product Manager.
- **Risk review:** Weekly, as part of the delivery sync. Project Manager facilitates with input from Technical Lead and DevOps Engineer.

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Role owners assigned for all active work items
- [ ] Stakeholder review checkpoints added to project calendar
- [ ] Technical design review completed for major features
- [ ] Release readiness review scheduled before each deployment
- [ ] Security scanning enabled in CI pipeline
- [ ] On-call and incident response runbooks up to date
