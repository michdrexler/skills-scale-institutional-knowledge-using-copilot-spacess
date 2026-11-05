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

## UX/UI Designer or User Researcher

### Role Summary
UX/UI Designers and User Researchers translate customer needs into intuitive experiences and clear product flows. They help ensure that the solution is usable, understandable, and aligned with user expectations before and during delivery.

### Responsibilities
- Conduct user interviews, usability testing, and research synthesis
- Define user journeys, wireframes, interaction patterns, and design requirements
- Validate that product decisions meet customer needs and accessibility standards
- Partner with Product Managers to refine problem statements and acceptance criteria
- Work with Developers to ensure designs are feasible, testable, and consistent with implementation constraints

### Goals
- Improve usability, accessibility, and user confidence
- Reduce rework caused by unclear requirements or poor experience design
- Align product decisions with real user needs and business outcomes

### Typical Communication
- Discovery sessions and design reviews
- User research summaries and prototype feedback loops
- Cross-functional discussions during planning and validation

### Interaction with Existing Roles
- Product Managers: Helps refine user problems, success criteria, and prioritization with evidence from research and user feedback.
- Project Managers: Contributes to milestone planning, risk identification related to scope or usability, and dependency tracking across design/validation work.
- Developers: Collaborates on feasibility, implementation details, and testing to ensure the final experience matches intended behavior.

---

## Tech Lead or Solution Architect

### Role Summary
Tech Leads or Solution Architects guide technical direction, design quality, and engineering trade-offs. They help teams make sound architecture decisions while balancing speed, reliability, and maintainability.

### Responsibilities
- Define technical approach, architecture patterns, and integration decisions
- Review design trade-offs for scalability, performance, resilience, and maintainability
- Support estimates, sequencing, and dependency planning with Product and Project Managers
- Guide code quality, technical standards, and decisions during implementation
- Help resolve technical blockers and identify risk early

### Goals
- Deliver a robust technical foundation for the product
- Reduce avoidable complexity and integration risk
- Support predictable delivery with clear technical ownership

### Typical Communication
- Architecture reviews and technical design discussions
- Engineering planning and dependency reviews
- Escalation paths for major technical risks or blockers

### Interaction with Existing Roles
- Product Managers: Aligns technical feasibility with roadmap expectations, trade-offs, and delivery timelines.
- Project Managers: Helps sequence work, identify blockers, and communicate technical dependencies that affect milestones.
- Developers: Provides technical leadership, mentorship, and decision-making support during implementation and review.

---

## QA/Test Engineer

### Role Summary
QA/Test Engineers validate that features meet acceptance criteria, function reliably, and are ready for release. They help balance delivery speed with confidence in quality.

### Responsibilities
- Define and execute test strategies across unit, integration, UI, and regression coverage
- Validate acceptance criteria and identify gaps in feature behavior or edge cases
- Coordinate test planning with Developers and Product Managers
- Support release readiness and defect triage for critical issues
- Capture evidence of quality through test results and validation notes

### Goals
- Reduce production defects and release risk
- Improve confidence in feature quality before deployment
- Ensure customer-facing behavior matches agreed requirements

### Typical Communication
- Test plans, release validation, and defect triage discussions
- Acceptance reviews with Product Managers and stakeholders
- Coordination with Developers during implementation and pre-release checks

### Interaction with Existing Roles
- Product Managers: Confirms acceptance criteria are testable and feature behavior matches expected outcomes.
- Project Managers: Helps shape release readiness, risk tracking, and communication of quality concerns.
- Developers: Works closely on defect reproduction, root-cause analysis, and regression prevention.

---

## Security/Privacy Lead

### Role Summary
Security and Privacy Leads ensure the team addresses security, compliance, and data handling requirements throughout the project lifecycle. They reduce risk and help create trust in the solution.

### Responsibilities
- Identify security, privacy, compliance, and data-handling risks
- Review architecture, workflows, and third-party dependencies for gaps
- Define controls, mitigations, and escalation paths for sensitive scenarios
- Partner with Product and Engineering on requirements, approvals, and release readiness
- Support incident response planning and risk communication for impacted projects

### Goals
- Reduce legal, privacy, and security exposure
- Build safeguards into delivery rather than treating them as an afterthought
- Support safe release decisions and stakeholder confidence

### Typical Communication
- Security review checkpoints and risk assessments
- Dependencies with compliance or legal stakeholders
- Release-risk discussions and incident escalation planning

### Interaction with Existing Roles
- Product Managers: Helps define acceptable risks, requirements, and release trade-offs.
- Project Managers: Tracks remediation plans, dependency impacts, and decision timelines.
- Developers: Reviews implementation patterns, validates security controls, and supports remediation work.

---

## Data/Analytics Lead

### Role Summary
Data and Analytics Leads help teams define what to measure and how to interpret outcomes. They connect delivery work to business and product value through instrumentation and reporting.

### Responsibilities
- Define analytics requirements, events, and reporting needs for product features
- Align metrics with product goals, user outcomes, and stakeholder expectations
- Collaborate with Developers to instrument reliable tracking and reporting
- Review success metrics after release and recommend iteration based on evidence
- Identify gaps in measurement that could affect product decisions

### Goals
- Make product value measurable and actionable
- Improve learning from adoption, usage, and quality signals
- Support data-informed prioritization and release evaluation

### Typical Communication
- Metric definitions and dashboard reviews
- Product impact analysis and KPI discussions
- Feedback loops during planning, release, and retrospective stages

### Interaction with Existing Roles
- Product Managers: Aligns metrics to desired outcomes and helps interpret whether the feature is succeeding.
- Project Managers: Helps estimate reporting work, dependencies, and readiness for measurement during rollout.
- Developers: Works with implementation teams to ensure telemetry is accurate, useful, and maintainable.

---

## Operations/SRE or Release Manager

### Role Summary
Operations, SRE, or Release Managers ensure that systems are ready for deployment, observable in production, and recoverable when issues occur. They help delivery teams manage operational risk around release and support.

### Responsibilities
- Coordinate deployment windows, rollback plans, and release readiness checks
- Support monitoring, alerting, and operational health during and after release
- Partner with Developers and QA to validate smoke tests and stability requirements
- Prepare support handoff and communication for customers or internal teams
- Help document incident response and mitigation steps for critical failures

### Goals
- Reduce deployment risk and service disruption
- Improve operational observability and recovery speed
- Maintain production stability while enabling regular delivery

### Typical Communication
- Release planning and deployment reviews
- Post-deploy checks and incident coordination
- Operational readiness and support handoff discussions

### Interaction with Existing Roles
- Product Managers: Helps align release timing and customer communication needs with business priorities.
- Project Managers: Coordinates schedules, dependencies, and communication during release windows.
- Developers: Works together on deployment readiness, observability, and rollback decisions.
- QA/Test Engineers: Confirms readiness criteria and validates the release against predefined quality gates.

---

## Customer Support/Success Representative

### Role Summary
Customer Support and Success Representatives bring real customer issues, adoption patterns, and support readiness needs into the product and delivery process. They help teams build solutions that are easier to use and easier to support.

### Responsibilities
- Surface recurring customer feedback, support trends, and product pain points
- Help define support expectations, documentation needs, and user guidance
- Validate readiness for launch, adoption, and support coverage
- Partner with Product Managers on gaps in user experience or service quality
- Feed operational insights back into backlog prioritization and release planning

### Goals
- Improve customer satisfaction and support efficiency
- Reduce friction for users after launch
- Connect delivery work to real operational feedback and customer impact

### Typical Communication
- Customer issue reviews and support escalation updates
- Launch readiness and communications planning
- Feedback loops with Product and Project leads

### Interaction with Existing Roles
- Product Managers: Provides market and customer context to shape prioritization and problem framing.
- Project Managers: Contributes to milestone planning, risk awareness, and stakeholder communication needs.
- Developers: Identifies product issues that need fix, clarification, or better supportability in implementation.

---

## Role Clarity and Team Adaptation

These personas help teams define ownership more clearly across planning, delivery, validation, and release. On smaller teams, multiple responsibilities may be combined into a single person, but accountability should still be explicit. The goal is not to add bureaucracy, but to make handoffs, decision rights, and collaboration patterns visible so project outcomes are more predictable and less dependent on informal knowledge.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Teams can choose which roles are needed based on project size, complexity, and risk profile.

