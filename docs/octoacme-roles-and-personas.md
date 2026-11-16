# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Assign these responsibilities based on the needs and size of each project. A person may cover more than one role on a smaller team, provided ownership and review needs remain clear.

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

---

## UX Designer/Researcher

### Role Summary
The UX Designer/Researcher investigates user needs and shapes usable, accessible experiences. This role informs product choices with research and turns agreed needs into design proposals that the team can build and validate.

### Responsibilities
- Plan and conduct user research, and share findings and limitations
- Create user flows, interaction designs, prototypes, and usability guidance
- Identify accessibility and usability considerations early
- Validate designs with users and incorporate feedback

### Decision Boundaries
Owns research methods and design recommendations within the agreed product goals and constraints. The Product Manager owns product priorities and scope; implementation trade-offs are agreed with Developers or the Technical Lead.

### Expected Artifacts
Research plans and findings, user flows or prototypes, design specifications, and usability or accessibility findings.

### Interactions and Handoffs
- Partners with the Product Manager to clarify user needs and translate findings into product requirements and acceptance criteria.
- Works with Developers and QA/Testing to make designs feasible and define testable usability and accessibility expectations.
- Shares research insights and relevant design decisions with the Project Manager and stakeholders so plans, risks, and expectations stay aligned.

---

## Technical Lead/Architect

### Role Summary
The Technical Lead/Architect guides technical direction, architecture, and integration choices so the solution is maintainable and fits project constraints. This role supports the development team and makes technical risks visible; it does not replace the accountability of individual contributors for their implementation work.

### Responsibilities
- Lead technical design and document significant architecture and integration decisions
- Identify technical dependencies, feasibility concerns, and risks
- Support Developers with design reviews, implementation guidance, and technical problem-solving
- Promote reliability, maintainability, and appropriate engineering practices

### Decision Boundaries
Owns or facilitates technical recommendations and decisions within the team's agreed authority. Product scope and priority remain with the Product Manager; schedule and cross-team coordination remain with the Project Manager. Escalate decisions with material product, delivery, or security impact to the relevant owners.

### Expected Artifacts
Technical designs, architecture decision records, integration plans, and technical risks or dependency notes.

### Interactions and Handoffs
- Collaborates with Developers on implementation, code review, estimates, and technical decisions.
- Advises the Product Manager on feasibility, options, and technical trade-offs without taking over prioritization.
- Flags dependencies, estimates, and delivery risks to the Project Manager for planning and escalation.
- Works with QA/Testing on testability and technical quality risks, and communicates material design impacts to stakeholders through the Project Manager or Product Manager.

---

## Security/Privacy Lead

### Role Summary
The Security/Privacy Lead advises the team on security, privacy, and applicable compliance needs, helping incorporate these concerns into delivery from planning through release.

### Responsibilities
- Identify relevant security, privacy, and compliance requirements and risks
- Recommend mitigations and review designs or data handling where appropriate
- Help define security and privacy validation activities
- Escalate material risks through the established incident or project escalation paths

### Decision Boundaries
Provides specialist guidance and identifies risks; the designated security, privacy, or compliance authority retains approval where formal approval is required. The Product Manager owns product scope and prioritization, and Developers own implementation. Unresolved material risks must be escalated rather than silently accepted.

### Expected Artifacts
Security and privacy requirements, risk and mitigation records, review findings, and validation or release recommendations.

### Interactions and Handoffs
- Works with the Product Manager to include relevant requirements in scope and acceptance criteria.
- Partners with Developers on secure implementation and with QA/Testing on security and privacy validation.
- Shares material risks with the Project Manager for the risk register and escalation, and communicates relevant requirements and decisions to stakeholders.

---

## Data/Analytics Lead

### Role Summary
The Data/Analytics Lead helps the team define how success will be measured and ensures that instrumentation, data, and reporting can support reliable decisions.

### Responsibilities
- Translate agreed success metrics into measurement and instrumentation requirements
- Coordinate event definitions, data quality checks, and analytics implementation
- Validate dashboards and analyses, including limitations and assumptions
- Report relevant outcome signals and data quality risks

### Decision Boundaries
Recommends measurement methods and owns the accuracy of analytics work within the team's agreed governance. The Product Manager defines product outcomes and interprets results with context; the Data/Analytics Lead does not independently redefine success metrics or make product prioritization decisions.

### Expected Artifacts
Metric definitions, instrumentation plans, data quality checks, dashboards or analysis, and notes on data limitations.

### Interactions and Handoffs
- Aligns metric definitions and measurement needs with the Product Manager.
- Coordinates instrumentation with Developers and validation with QA/Testing.
- Shares measurement plans, data quality issues, and results with the Project Manager and stakeholders so progress and outcomes can be reported accurately.

---

## Operations/Release Lead

### Role Summary
The Operations/Release Lead coordinates operational readiness and release activities, including deployment checks, monitoring, support handoff, and rollback preparation. This role complements the release and deployment process and may be combined with another role on smaller projects.

### Responsibilities
- Coordinate release readiness, deployment steps, and operational checklists
- Confirm monitoring, alerting, support ownership, and rollback or mitigation plans
- Coordinate post-deployment verification and capture operational feedback
- Identify operational risks and readiness gaps before release

### Decision Boundaries
Coordinates readiness and recommends whether operational conditions are met; production deployment or release approval follows the team's defined authority. The Project Manager coordinates schedule and communications, while the Product Manager owns product scope and release priorities.

### Expected Artifacts
Release and deployment checklist, monitoring and support handoff notes, rollback or mitigation plan, and post-deployment verification results.

### Interactions and Handoffs
- Works with Developers and QA/Testing on release checks, smoke tests, and verification criteria.
- Aligns deployment timing, dependencies, and communications with the Project Manager.
- Shares operational readiness and post-release feedback with the Product Manager and stakeholders, and routes incidents through the established on-call and escalation process.

---

## Role Assignment and Collaboration

- Assign a named owner for each responsibility that is needed on a project, even when one person covers multiple roles.
- The Product Manager remains accountable for product outcomes, priorities, and scope; the Project Manager coordinates delivery, dependencies, risks, and communications.
- Specialist personas provide expertise and defined artifacts. They complement rather than replace the existing Product Manager, Project Manager, Developers, QA/Testing, and Stakeholders.
- Developers implement the solution, QA/Testing validates it against acceptance criteria and quality needs, and stakeholders provide input or approvals according to their responsibilities.
- On smaller projects, roles may be combined where skills and capacity allow. Keep decision ownership explicit, and use independent review or escalation when risk, compliance, or team policy calls for it.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
