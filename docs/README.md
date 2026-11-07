# OctoAcme Project Management Docs

This directory contains OctoAcme's project management guidance. OctoAcme takes a customer-first, iterative, and data-informed approach, with clear ownership and a culture that encourages feedback and learning.

## Project management process at a glance

OctoAcme's project lifecycle moves from **initiation** to **planning**, **execution**, **release**, and **retrospective**. During initiation, the team validates the business need, defines measurable outcomes, aligns stakeholders, identifies initial risks and resources, and makes a go/no-go decision. Planning turns approved work into a prioritized backlog with acceptance criteria and estimates, defines the Definition of Done, and maps milestones, dependencies, and risks.

During execution, teams track work on a project board and deliver small increments through reviewed pull requests. Developers implement and test the work, QA validates acceptance criteria, Product Managers prioritize outcomes, and Project Managers coordinate delivery, risks, schedules, and communications. Regular standups, weekly delivery and PM/PdM syncs, sprint or milestone demos, and stakeholder updates keep progress visible. Risks are reviewed regularly and escalated from the team to the PM, Product Lead, and sponsor as appropriate.

Quality is built into delivery with unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI. Automated tests and linting should pass before review, and a pull request should receive at least one approval or follow the team's defined policy. Before release, the team verifies acceptance criteria, CI and security checks, release notes, smoke tests, and rollback or mitigation plans. After deployment, the team performs post-release checks, communicates the release, and uses retrospectives to record and follow up on improvement actions.

## Process documents

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) — principles, lifecycle, roles, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — validating and authorizing a project, stakeholder alignment, and initial deliverables.
- [Project Planning](octoacme-project-planning.md) — backlog creation, estimation, Definition of Done, milestones, risks, and dependencies.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — day-to-day delivery, project board workflow, quality practices, metrics, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — risk lifecycle, stakeholder updates, incident communication, and escalation paths.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release readiness, deployment checks, rollback, and release notes.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — capturing learnings and tracking improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — responsibilities, goals, and typical communication for key project roles.
