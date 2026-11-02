# OctoAcme Project Management Docs

This README is an entry point to OctoAcme's project management guidance. The documents below describe the project lifecycle, the people and practices involved, and the supporting workflows.

## Project management process

OctoAcme projects move through initiation, planning, execution and tracking, release, and retrospective. Initiation validates the business need, identifies stakeholders, defines measurable outcomes, and captures an initial timeline, risks, and resource needs in a project one-pager. After approval, planning turns the initiative into a prioritized, estimated backlog with acceptance criteria, a Definition of Done, assigned responsibilities, dependency tracking, and agreed milestones and release plans.

During execution, teams track work on a project board and deliver in small increments. The Project Manager (PM) coordinates schedules, risks, dependencies, and communications; the Product Manager/Product Lead defines outcomes, prioritizes work, and measures success; developers implement and test changes; QA/testing validates quality and acceptance criteria; and stakeholders provide input and approvals. Teams coordinate through standups, delivery syncs, sprint or milestone demos, and regular PM–Product alignment, with stakeholder updates on an agreed cadence. Risks and blockers are reviewed regularly and escalated from the team to the PM, Product Lead, and sponsor as appropriate; security incidents follow the security incident runbook and notify Security on-call.

Quality assurance is part of delivery from planning through release. Teams define acceptance criteria and a Definition of Done, write unit tests for new logic, add integration and end-to-end smoke tests where applicable, and run tests, linting, and security scans in CI. Manual QA is used when needed. Before release, the team confirms acceptance criteria and CI results, prepares release notes and a rollback or mitigation plan, tests in staging, deploys, and performs post-deployment verification. Retrospectives after sprints, releases, milestones, or incidents capture learnings and turn them into a small set of owned, time-bound improvement actions.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
