# OctoAcme Project Management Docs

This directory contains OctoAcme’s project management guidance. Use this README as a starting point to understand the lifecycle and find the process details you need.

## How OctoAcme manages projects

OctoAcme’s project lifecycle runs from initiation and planning through execution, release, and continuous improvement. During **initiation**, the team validates the business need, defines a measurable goal and success criteria, identifies stakeholders and resources, and records initial risks. The Product Lead and stakeholders review the one-pager and decide whether the work is ready to move into planning.

In **planning**, the team turns approved work into a prioritized, estimated backlog with clear acceptance criteria and a Definition of Done. It agrees milestones and a release plan, identifies dependencies, and records risks with owners and mitigation plans. During **execution**, the team delivers iterative increments and tracks work on a project board. The Project Manager coordinates delivery, schedules, risks, and communications; the Product Manager owns outcomes and priorities; developers implement and test; QA validates acceptance; and stakeholders provide input and approvals.

Communication and quality checks are part of day-to-day delivery. Teams use standups, a weekly delivery or PM–Product sync, demos or reviews, and regular stakeholder updates; the exact cadence can be agreed by the team. Progress, blockers, decisions, risks, and dependencies are made visible through the project board, risk register, and a shared status source. Quality practices include unit tests for new logic, integration tests where applicable, smoke tests for critical flows, and CI checks for tests, linting, and security scanning. Pull requests should be small where possible, linked to issues and acceptance criteria, and reviewed according to the team’s approval policy.

Before **release**, the team confirms acceptance criteria, passing CI and security scans, release notes, smoke tests, and a rollback or mitigation plan. It deploys to staging for verification, deploys to production, and performs post-deployment checks and stakeholder communications. After each sprint, release, milestone, or incident, a **retrospective** captures learnings and assigns a small number of actionable improvements with owners, due dates, and success criteria.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md) — principles, roles, lifecycle, key artifacts, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — validate and authorize new work, align stakeholders, and prepare the one-pager.
- [Project Planning](octoacme-project-planning.md) — scope and prioritize delivery work, estimate it, and manage milestones, risks, and dependencies.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — day-to-day delivery rhythm, project board workflow, quality practices, metrics, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — maintain the risk register, communicate status, and escalate issues.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release readiness, deployment checks, rollback, incident response, and release notes.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — run retrospectives and track improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — responsibilities, goals, and communication patterns for developers, Product Managers, and Project Managers.
