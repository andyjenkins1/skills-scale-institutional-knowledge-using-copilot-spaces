# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management documentation! This guide serves as your entry point to understanding how we run projects, collaborate across teams, and deliver value to our customers. Whether you're a new team member, a stakeholder, or a contributor looking to understand our processes, you'll find everything you need to get started here.

## Overview

OctoAcme follows a structured yet flexible project management approach that emphasizes iterative delivery, clear ownership, and continuous improvement. Our methodology is built on customer-first principles and data-informed decision-making. Every project follows a defined lifecycle from initiation through retrospective, with consistent practices for communication, risk management, and quality assurance. We maintain psychological safety and encourage feedback at every stage, ensuring that teams can collaborate effectively and deliver high-quality outcomes.

Our project delivery framework is designed to support cross-functional teams working on product features, services, and integrations. Each project has a named Project Manager (PM) who coordinates delivery, schedules, and communications, as well as a Product Manager (PdM) or Product Lead who defines outcomes, prioritizes the backlog, and measures success. Developers implement features with a focus on testability and maintainability, while QA/Testing validates quality against acceptance criteria. Stakeholders provide essential inputs, approvals, and feedback throughout the project lifecycle.

The team operates on a regular rhythm to maintain momentum and transparency. Daily standups (15 minutes) keep everyone aligned on progress, blockers, and dependencies. Weekly delivery syncs provide opportunities to review progress, update stakeholders, and address flagged risks. At the end of each sprint or milestone, the team conducts demos and reviews to showcase completed work and gather feedback. This cadence ensures that everyone stays informed, issues are surfaced early, and the team can adapt quickly to changing requirements or obstacles.

Our project board—typically implemented using GitHub Projects—provides a visual representation of work in progress. Items move through six columns: Backlog (prioritized work waiting to be started), Ready (fully defined work ready for implementation), In Progress (active development), In Review (code review and technical validation), QA (quality assurance and acceptance testing), and Done (completed and merged). This workflow ensures transparency, helps identify bottlenecks, and keeps the team focused on delivering small, testable increments.

Pull requests follow clear guidelines to maintain code quality and velocity: keep them small (≤ 400 lines when possible), include links to the related issue and acceptance criteria in the description, ensure CI runs tests, linting, and security scans, and obtain at least one approval before merging. This approach enables faster reviews, reduces merge conflicts, and improves code quality through focused feedback.

When blockers or risks arise, the team follows a clear escalation path to ensure timely resolution: team-level triage in daily standups for immediate issues, PM escalation to the Product Lead and dependent teams for cross-team blockers, and sponsor-level escalation for business-impacting issues that require executive decision-making or additional resources.

## Process Documents

For detailed guidance on each phase of the project lifecycle and specific processes, please refer to the following documents:

- [**OctoAcme Project Management Overview**](./octoacme-project-management-overview.md) — High-level introduction to our principles, roles, artifacts, and lifecycle
- [**Project Initiation**](./octoacme-project-initiation.md) — How to validate ideas, align stakeholders, and create a project one-pager
- [**Project Planning**](./octoacme-project-planning.md) — Breaking work into actionable backlogs, estimating scope, and defining success criteria
- [**Execution and Tracking**](./octoacme-execution-and-tracking.md) — Day-to-day workflows, team rhythm, PR conventions, and quality practices
- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — Identifying and mitigating risks, stakeholder updates, and escalation paths
- [**Release and Deployment**](./octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment checklists, and rollback procedures
- [**Retrospective and Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and turning them into actionable improvements
- [**Roles and Personas**](./octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities for all team members

## Getting Started

If you're new to OctoAcme or joining a project team, we recommend starting with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our core principles and lifecycle. Then, review the [Roles and Personas](./octoacme-roles-and-personas.md) document to understand your role and how you'll collaborate with others. As your project progresses through each phase, reference the appropriate process document for detailed guidance and templates.

For questions, clarifications, or suggestions on improving these processes, reach out to your Project Manager or Product Lead. We continuously iterate on our practices based on team feedback and lessons learned from retrospectives.
