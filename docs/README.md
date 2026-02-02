# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This guide provides a comprehensive entry point to understanding how OctoAcme runs projects, from initial conception through delivery, release, and continuous improvement.

## Overview

OctoAcme follows a structured, iterative approach to project management that emphasizes customer value, clear ownership, and data-informed decisions. Our process guides projects through five key lifecycle phases: **Initiation** (problem statement, stakeholders, high-level timeline), **Planning** (scope, resources, milestones, dependencies), **Execution** (build, test, review, iterate), **Release and Deployment** (deploy, verify, announce), and **Close & Retrospective** (capture learnings and next steps). Each phase is designed to deliver small, testable increments while maintaining transparency and alignment across all stakeholders.

The OctoAcme project management framework brings together multiple personas working in concert. The **Project Manager (PM)** coordinates delivery activities, schedules, risks, and communications, ensuring the team delivers on commitments efficiently. The **Product Manager (PdM)** defines what should be built to deliver customer and business value, prioritizing the roadmap and measuring outcomes. **Developers** design, build, test, and deliver software components while collaborating on design and testability. **QA/Testing** validates quality and acceptance criteria to ensure features meet standards before release. Finally, **Stakeholders** provide inputs, approvals, and ongoing engagement throughout the project lifecycle. Each role has clear responsibilities and communication patterns that enable effective collaboration.

Communication and collaboration are central to OctoAcme's project success. The team maintains a consistent cadence with twice-weekly standups for delivery teams (or as agreed), weekly syncs between PM and PdM, weekly delivery syncs to show progress and flag risks, demos/reviews at the end of each sprint or milestone, and monthly stakeholder updates. Teams use a standardized weekly status template that covers progress, next steps, risks & blockers, and asks/decisions needed. When issues arise, they follow a clear escalation path from team-level triage to PM to Product Lead to Sponsor, with special protocols for security incidents.

Quality assurance is woven throughout the OctoAcme process, not treated as an afterthought. Pull requests follow best practices: small PRs (≤400 lines when possible), include issue links and acceptance criteria, run automated tests and linting in CI before requesting review, and require at least one approval before merging. The CI pipeline enforces tests, lint checks, and security scans before any code reaches production. Testing occurs at multiple levels including unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. Every release includes pre-deployment smoke tests on staging, post-deployment verifications in production, and a documented rollback/mitigation plan to ensure teams can respond quickly if issues arise.

## Process Documents

The following documents provide detailed guidance for each phase of the OctoAcme project management lifecycle:

- [**OctoAcme Project Management Overview**](./octoacme-project-management-overview.md) — A concise introduction to OctoAcme's approach, principles, core roles, key artifacts, and communication cadence.

- [**Project Initiation Guide**](./octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan with a Project One-pager.

- [**Project Planning**](./octoacme-project-planning.md) — Turn approved initiatives into actionable plans with prioritized backlogs, acceptance criteria, release plans, and risk management.

- [**Execution & Tracking**](./octoacme-execution-and-tracking.md) — Day-to-day execution guidance including team rhythm, project board workflows, PR conventions, quality & testing, and blocker escalation.

- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks using the Risk Register, stakeholder communication templates, and escalation paths.

- [**Release & Deployment Guide**](./octoacme-release-and-deployment.md) — Standardized release process covering release types, pre-release requirements, deployment checklists, and rollback procedures.

- [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings after sprints, releases, or milestones and convert them into actionable improvements.

- [**Roles & Personas**](./octoacme-roles-and-personas.md) — Detailed definitions of Developers, Product Managers, Project Managers, and how these personas are used in OctoAcme processes.
