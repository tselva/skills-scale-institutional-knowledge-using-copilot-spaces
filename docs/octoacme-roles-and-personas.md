# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## QA Leads

### Role Summary
QA Leads define and enforce the quality strategy across the project lifecycle. They ensure quality gates are clear, test coverage is appropriate, and release readiness criteria are met.

### Responsibilities
- Define test strategy across unit, integration, end-to-end, and regression layers
- Translate acceptance criteria into test scenarios and quality gates
- Coordinate manual and automated testing activities across teams
- Track and triage defects with clear severity and ownership
- Confirm release readiness with evidence from test execution and risk assessment

### Goals
- Prevent critical defects from reaching production
- Improve confidence in release quality and stability
- Shorten feedback loops for quality issues

### Typical Communication
- Daily defect triage and execution updates with Developers
- Quality gate sign-off with Project Managers before release
- Acceptance validation reviews with Product Managers

### Interactions With Existing Roles
- Developers: co-design testability, validate fixes, and maintain automated coverage
- Product Managers: align expected behavior and acceptance evidence
- Project Managers: escalate quality risks and adjust timeline expectations when needed

---

## DevOps Engineers

### Role Summary
DevOps Engineers own delivery reliability across build, deployment, and runtime operations. They provide the automation and observability needed for safe, repeatable releases.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Define environment standards for development, staging, and production
- Implement monitoring, alerting, and deployment health checks
- Partner on incident response, rollback, and post-incident follow-up
- Improve deployment frequency and reduce mean time to recovery

### Goals
- Increase release reliability and deployment velocity
- Reduce manual deployment risk and operational toil
- Improve service observability and incident readiness

### Typical Communication
- Pipeline and release readiness updates in weekly delivery syncs
- Incident and rollback coordination with Project Managers and on-call teams
- Automation planning with Developers during sprint work

### Interactions With Existing Roles
- Developers: define build/test/deploy standards and operational handoffs
- Project Managers: align deployment windows, risks, and incident communication
- Product Managers: support launch sequencing and rollout strategy

---

## UX Designers

### Role Summary
UX Designers ensure that delivered solutions are usable, intuitive, and aligned to customer needs. They bridge discovery and delivery by turning requirements into validated user experiences.

### Responsibilities
- Create user journeys, wireframes, and interaction prototypes
- Run or support usability testing and synthesize findings
- Define interaction and accessibility requirements for implementation
- Partner with Product Managers to refine requirements and scope
- Support Developers during implementation with design clarifications

### Goals
- Improve usability and adoption of delivered features
- Reduce rework caused by unclear interaction requirements
- Ensure accessibility and consistency across user flows

### Typical Communication
- Discovery and requirements workshops with Product Managers
- Design handoff sessions and implementation reviews with Developers
- Milestone demos with stakeholders for experience validation

### Interactions With Existing Roles
- Product Managers: align user outcomes, scope, and success signals
- Developers: resolve UI/UX trade-offs and implementation constraints
- Project Managers: surface design dependencies and schedule implications

---

## Business Analysts / Stakeholders

### Role Summary
Business Analysts and key Stakeholders represent business context, constraints, and outcome expectations. They help convert business needs into actionable requirements and ensure value realization.

### Responsibilities
- Gather and clarify business requirements and operational constraints
- Validate feature scope against expected business outcomes
- Participate in milestone reviews and decision checkpoints
- Support prioritization with impact, risk, and dependency insights
- Confirm delivered capabilities meet business needs

### Goals
- Keep delivery aligned with strategic and operational objectives
- Reduce requirement ambiguity and late-stage churn
- Improve decision quality through stronger business context

### Typical Communication
- Requirement reviews and milestone checkpoints with Product Managers
- Decision and escalation discussions with Project Managers
- Feedback loops during demos and release readiness reviews

### Interactions With Existing Roles
- Product Managers: shape backlog priorities and measurable outcomes
- Project Managers: align delivery constraints and stakeholder decisions
- Developers and QA Leads: clarify business rules and acceptance expectations

---

## Role Interaction and Handoff Checklist (Template)

Use this checklist during planning, sprint kickoff, and release readiness to reduce ownership gaps.

- [ ] Role owner is named for each major workstream (Product, Delivery, Engineering, QA, UX, Operations)
- [ ] Acceptance criteria include product, UX, and QA perspectives
- [ ] CI/CD and environment requirements are defined with DevOps support
- [ ] Dependencies and handoff points are documented in the project board
- [ ] Risk owners are assigned for product, delivery, technical, and operational risks
- [ ] Release readiness includes QA sign-off and rollback ownership
- [ ] Business validation checkpoints are scheduled with analysts/stakeholders
- [ ] Incident escalation path and communication owner are confirmed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

