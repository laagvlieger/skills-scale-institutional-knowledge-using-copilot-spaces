# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

> **Related resources:** [Roles & Personas](./octoacme-roles-and-personas.md) | [Execution & Tracking](./octoacme-execution-and-tracking.md) | [Project Planning](./octoacme-project-planning.md)

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths

Escalation follows a defined path depending on the nature and severity of the issue:

- **Team-level → Project Manager:** Raised in daily standup or async. Project Manager owns tracking and facilitates resolution.
  - *Example:* A sprint story is blocked on a third-party integration; developer raises in standup, PM coordinates with partner team.
- **Project Manager → Product Lead:** When the issue affects scope, timeline, or resource allocation that exceeds team authority.
  - *Example:* A key dependency is delayed by two weeks; PM escalates to Product Lead to decide whether to scope down the release.
- **Product Lead → Sponsor:** For business-critical issues requiring executive input or resources beyond the team.
  - *Example:* A regulatory compliance gap is discovered; Product Lead escalates to Sponsor who engages Legal.
- **Security incidents:** DevOps Engineer and Technical Lead immediately notify Security on-call. Project Manager coordinates status communication to affected stakeholders. Follow the security incident runbook.
  - *Example:* A critical vulnerability is reported in a dependency; DevOps Engineer triggers the security runbook, Technical Lead coordinates a hotfix, Project Manager sends an internal incident update.
- **Customer-impacting incidents:** Support/Customer Success triggers escalation to DevOps Engineer and Project Manager. Product Manager is notified for prioritization decisions.
  - *Example:* A major customer reports data unavailability; Support escalates to DevOps Engineer who investigates and restores service while PM coordinates customer communication.

## Review Checkpoints

The following reviews must occur at defined points in the delivery cycle:

| Checkpoint | Timing | Facilitator | Required Attendees |
|---|---|---|---|
| Risk register review | Weekly delivery sync | Project Manager | Technical Lead, DevOps Engineer |
| Stakeholder status update | Weekly or milestone-based | Project Manager | Product Manager, key stakeholders |
| Technical design review | Before major feature work begins | Technical Lead | Developers, DevOps Engineer |
| Release readiness review | Before production deployment | DevOps Engineer | Technical Lead, Project Manager, Product Manager |
| Post-incident retrospective | Within 48h of resolution | Project Manager | Affected team members |
