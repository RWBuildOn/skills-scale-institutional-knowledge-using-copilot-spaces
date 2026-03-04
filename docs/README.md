# OctoAcme Project Management Docs

This README is the entry point for OctoAcme's project management documentation. It summarizes our core processes and links to each detailed process doc below.

---

## Overview

OctoAcme manages projects through a structured lifecycle: **Initiation → Planning → Execution → Release → Close/Retrospective**. Each phase has defined activities, artifacts, and owners to ensure work is well-scoped, delivered iteratively, and continuously improved. New projects begin with a lightweight one-pager that captures the problem, goal, success metrics, and key stakeholders, followed by a planning phase where scope is broken into shippable increments with clear acceptance criteria and a Definition of Done.

Key roles span the full delivery team. **Project Managers (PM)** coordinate delivery, schedules, risks, and communications. **Product Managers (PdM)** own the product vision, backlog prioritization, and outcome measurement. **Developers** implement features, write tests, and collaborate on design and code reviews. **QA/Testing** validates quality and acceptance criteria. **Stakeholders** provide inputs, approvals, and receive regular updates throughout the project.

Communication is intentional and cadenced. Weekly syncs between PM and PdM keep priorities aligned, while twice-weekly team standups surface blockers early. Stakeholders receive monthly milestone-based updates, and ad-hoc escalations follow a defined path from team lead to engineering manager to VP as needed. Status updates, risk registers, and escalation templates ensure consistent, transparent communication across all audiences.

Quality assurance is built into every phase. Pull requests are kept small (≤ 400 lines when possible), include issue links and acceptance criteria, and require at least one approval after passing automated CI checks (linting, unit tests, security scanning). Integration and end-to-end smoke tests validate critical flows before each release. Every release goes through a deployment checklist covering staging verification, rollback planning, and post-deploy announcements, with a blameless retrospective closing the loop on learnings and action items.

---

## Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | Purpose, principles, core roles, key artifacts, and lifecycle at a glance |
| [Project Initiation](./octoacme-project-initiation.md) | How to validate and authorize new work, align stakeholders, and create a lightweight plan |
| [Project Planning](./octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog, release plan, and milestones |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day team rhythm, PR workflow, quality practices, and blocker escalation |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk register, risk lifecycle, stakeholder communication templates, and escalation paths |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Release types, pre-release checklist, deployment steps, rollback playbook, and release notes |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | How to run retrospectives, capture action items, and drive ongoing process improvement |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed role summaries, responsibilities, goals, and communication patterns for each persona |
