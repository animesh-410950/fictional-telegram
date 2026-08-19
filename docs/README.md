# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects using a lightweight, iterative lifecycle that moves work from initiation through planning, execution, release, and retrospection. Initiation focuses on a one‑pager that captures the problem, measurable outcomes, stakeholders, timeline, and risks so teams can validate the business need before planning. Planning turns approved initiatives into shippable increments by producing a prioritized backlog, clear acceptance criteria, estimates, and a Definition of Done. Execution uses a project board to visualize flow and keep work small and reviewable; retrospectives and a continuous‑improvement loop capture learnings and convert them into tracked action items.

## Key workflows and quality assurance
Workflows emphasize repeatable practices for changes and releases. Pull requests should be small when possible, include an issue link and acceptance criteria, and pass automated CI checks (tests, linting, and security scans) before review and merge. Releases follow checklist-driven staging and production deployments with smoke tests, release notes, rollback plans, and post-deploy verification. Quality assurance is layered: unit and integration tests, end-to-end smoke tests for critical flows, CI security scanning, and manual QA when needed; acceptance criteria and test plans are defined during planning to meet the Definition of Done.

## Roles and communication
Roles are explicit so ownership is clear: Product Managers define outcomes and success metrics; Project Managers coordinate delivery, schedule, and risks; Developers implement features, write tests, and support reviews; QA validates acceptance criteria and quality. Communication follows a predictable cadence—daily standups for progress and blockers, weekly delivery syncs for status and risks, demos at milestone ends, and regular stakeholder updates—while core artifacts (project one‑pagers, risk register, release notes, and the docs/ README) act as single sources of truth.

## Documentation index
### Getting started
- [Project Management Overview](./octoacme-project-management-overview.md) — concise introduction to OctoAcme's approach, roles, and key artifacts
- [Roles & Personas](./octoacme-roles-and-personas.md) — definitions and responsibilities for Developers, Product Managers, and Project Managers

### By phase
- [Project Initiation Guide](./octoacme-project-initiation.md) — initial validation, stakeholder alignment, and one‑pager template
- [Project Planning](./octoacme-project-planning.md) — backlog creation, estimates, Definition of Done, and release planning
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team rhythm, PR conventions, CI expectations, and tracking
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — release types, deployment checklist, and rollback procedures
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — retrospective structure and tracking improvements

### Cross-functional topics
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — risk register format, escalation paths, and stakeholder templates
