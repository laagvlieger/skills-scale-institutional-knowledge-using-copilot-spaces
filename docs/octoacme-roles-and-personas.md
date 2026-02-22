# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **Related resources:** [Execution & Tracking](./octoacme-execution-and-tracking.md) | [Project Planning](./octoacme-project-planning.md) | [Risk Management & Communication](./octoacme-risks-and-communication.md)

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interaction with Other Roles
- Works closely with **Technical Lead** on architecture decisions and code quality
- Receives design specifications from **UX Designer** and provides implementation feedback
- Escalates operational issues to **DevOps Engineer**
- Responds to bug reports and edge-case findings surfaced by **Support/Customer Success**

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interaction with Other Roles
- Partners with **Project Manager** to align scope, timelines, and capacity
- Works with **UX Designer** to validate user needs and review prototypes
- Consults **Support/Customer Success** for real-world customer feedback on prioritization
- Coordinates with **Technical Lead** to assess feasibility of proposed features

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interaction with Other Roles
- Works with **Product Manager** to manage scope and prioritization trade-offs
- Relies on **Technical Lead** for technical status, risk identification, and escalation
- Coordinates with **DevOps Engineer** on release schedules and deployment windows
- Escalates customer-impacting issues with input from **Support/Customer Success**

---

## Technical Lead

### Role Summary
The Technical Lead provides technical direction and oversight for the engineering team. They guide architectural decisions, mentor developers, and ensure delivery quality and long-term maintainability of the codebase.

### Responsibilities
- Define and communicate technical architecture and design standards
- Review and approve significant design and code changes
- Identify and manage technical debt and long-term risks
- Mentor developers and facilitate knowledge sharing
- Coordinate technical dependencies across teams
- Participate in planning to assess feasibility and break down complex work

### Goals
- Ensure architectural integrity and code quality across the codebase
- Reduce technical risk and increase engineering velocity
- Build team capability through mentorship and documentation

### Typical Communication
- Architecture decision records (ADRs) and technical design docs
- Code reviews and design review sessions
- Engineering syncs and sprint planning
- Escalation discussions with Project Manager and Product Manager

### Interaction with Other Roles
- Works directly with **Developers** to review code, set standards, and unblock technical issues
- Advises **Product Manager** on feasibility, trade-offs, and technical constraints
- Coordinates with **DevOps Engineer** on infrastructure, CI/CD, and deployment strategy
- Provides technical risk updates to **Project Manager** for the risk register
- Collaborates with **UX Designer** to ensure technical feasibility of proposed experiences

---

## UX Designer

### Role Summary
UX Designers ensure that the product is usable, accessible, and aligned with user needs. They translate product requirements into wireframes, prototypes, and design specifications that guide development.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define and maintain the design system and component library
- Collaborate with Product Manager to validate user requirements
- Work with Developers to ensure accurate implementation of designs
- Provide accessibility guidance throughout the product lifecycle

### Goals
- Deliver intuitive and accessible user experiences
- Reduce user friction and support adoption
- Maintain design consistency across the product

### Typical Communication
- Design reviews and critique sessions
- Prototype walkthroughs with stakeholders and developers
- Annotated design files and component specifications
- Usability test reports and user research findings

### Interaction with Other Roles
- Works closely with **Product Manager** to translate user needs into design requirements
- Collaborates with **Developers** to review implementation against designs and iterate
- Coordinates with **Technical Lead** to validate technical constraints on UX decisions
- Incorporates feedback from **Support/Customer Success** on usability pain points
- Presents designs at stakeholder reviews coordinated by **Project Manager**

---

## Support / Customer Success

### Role Summary
Support and Customer Success roles are the bridge between customers and the product team. They gather real-world feedback, manage customer relationships, and ensure that issues impacting users are triaged and escalated appropriately.

### Responsibilities
- Triage and respond to customer-reported issues and inquiries
- Escalate recurring or high-impact issues to the product and engineering teams
- Document customer feedback and usage patterns for product prioritization
- Maintain customer-facing documentation and self-service resources
- Assist with communication during incidents or releases that affect customers

### Goals
- Maximize customer satisfaction and retention
- Surface actionable insights that improve the product
- Reduce time-to-resolution for customer issues

### Typical Communication
- Support tickets and case notes
- Weekly or monthly customer feedback summaries to Product Manager
- Incident updates and post-incident summaries to affected customers
- Release notes and customer-facing documentation

### Interaction with Other Roles
- Escalates bugs and critical issues to **Developers** and **Technical Lead**
- Provides customer feedback to **Product Manager** to inform prioritization
- Coordinates with **Project Manager** during incidents or high-impact releases
- Works with **UX Designer** to flag usability issues surfaced by customers
- Relies on **DevOps Engineer** for information about infrastructure incidents affecting customers

---

## DevOps Engineer

### Role Summary
DevOps Engineers own the build, deployment, and operations infrastructure. They ensure that systems are reliable, observable, and that the team can deploy software safely and frequently.

### Responsibilities
- Design and maintain CI/CD pipelines and automation tooling
- Manage infrastructure provisioning, configuration, and scaling
- Monitor system health and respond to infrastructure incidents
- Define and enforce security and compliance standards in the pipeline
- Coordinate deployment schedules and release processes with the delivery team
- Drive adoption of observability tooling (logging, metrics, alerting)

### Goals
- Enable reliable, repeatable, and fast deployments
- Maintain high system availability and performance
- Reduce toil through automation and self-service tooling

### Typical Communication
- Deployment run books and infrastructure documentation
- Incident postmortems and on-call reports
- Pipeline status updates and release coordination with Project Manager
- Security and compliance reports

### Interaction with Other Roles
- Collaborates with **Technical Lead** on infrastructure design and deployment architecture
- Partners with **Developers** to optimize build pipelines and local development environments
- Coordinates with **Project Manager** on deployment windows and release scheduling
- Supports **Support/Customer Success** with operational data during customer incidents
- Provides security and compliance input to **Product Manager** and **Technical Lead** for roadmap planning

---

## Cross-Role Collaboration and Handoffs

Effective delivery requires clear handoffs between roles at each stage of the project lifecycle. The table below summarizes key collaboration points:

| From | To | Handoff / Collaboration Point |
|------|-----|-------------------------------|
| Product Manager | UX Designer | Feature requirements → design brief |
| UX Designer | Developer | Design spec → implementation |
| Developer | Technical Lead | PR → code review and approval |
| Technical Lead | DevOps Engineer | Architecture decisions → infrastructure requirements |
| DevOps Engineer | Developer | Pipeline changes → updated CI/CD documentation |
| Support/Customer Success | Product Manager | Customer feedback → backlog input |
| Project Manager | All roles | Risk register updates → team awareness |
| Technical Lead | Project Manager | Technical risk identification → escalation |

> See [Execution & Tracking](./octoacme-execution-and-tracking.md) for escalation paths and review checkpoints.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

