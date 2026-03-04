# OctoAcme — Roles & Ceremonies

This document clarifies role involvement across project lifecycle phases and key team ceremonies. It supplements the persona definitions in [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) and aligns with the process guides listed below.

**Related process docs:**
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)

---

## RACI Matrix by Lifecycle Phase

> **R** = Responsible (does the work) | **A** = Accountable (owns the outcome) | **C** = Consulted (provides input) | **I** = Informed (kept up to date)

| Phase | Developer | Product Manager | Project Manager | Stakeholder | Technical Lead | UX/UI Designer | QA Lead | Release Manager |
|---|---|---|---|---|---|---|---|---|
| **Initiation** | I | A | R | C | C | C | I | I |
| **Planning** | C | A | R | I | C | C | C | C |
| **Execution** | R | C | A | I | R | R | R | I |
| **Release** | C | I | C | I | C | I | R | A |
| **Retrospective** | R | C | A | I | C | C | C | C |

---

## Ceremonies

### Kickoff Meeting
- **Leads:** Project Manager
- **Attends:** All roles
- **Accountable:** Project Manager (scheduling, agenda); Product Manager (goals and scope)
- **Purpose:** Align the full team on project goals, scope, roles, and initial plan.
- **Ref:** [Project Initiation](octoacme-project-initiation.md), [Project Planning](octoacme-project-planning.md)

---

### Daily Standup
- **Leads:** Project Manager (or rotating team member)
- **Attends:** Developers, Technical Lead, QA Lead, Project Manager
- **Accountable:** Project Manager (removes blockers)
- **Purpose:** Surface daily progress, blockers, and dependencies. Timebox: 15 minutes.
- **Ref:** [Execution & Tracking](octoacme-execution-and-tracking.md)

---

### Sprint Planning
- **Leads:** Project Manager
- **Attends:** Developers, Product Manager, Technical Lead, QA Lead, UX/UI Designer
- **Accountable:** Product Manager (backlog readiness); Project Manager (capacity and scheduling)
- **Purpose:** Commit to sprint scope, confirm acceptance criteria, and assign work.
- **Ref:** [Project Planning](octoacme-project-planning.md)

---

### Weekly Delivery Sync
- **Leads:** Project Manager
- **Attends:** Product Manager, Technical Lead, QA Lead, Release Manager; Stakeholder (as needed)
- **Accountable:** Project Manager (status accuracy and risk escalation)
- **Purpose:** Review progress against milestones, surface risks, and align on next steps.
- **Ref:** [Execution & Tracking](octoacme-execution-and-tracking.md), [Risk Management & Communication](octoacme-risks-and-communication.md)

---

### Sprint Demo / Review
- **Leads:** Product Manager (or Project Manager)
- **Attends:** All roles; Stakeholder encouraged
- **Accountable:** Product Manager (acceptance of delivered work)
- **Purpose:** Demonstrate completed work, gather feedback, and confirm acceptance criteria are met.
- **Ref:** [Execution & Tracking](octoacme-execution-and-tracking.md)

---

### Release Readiness Review
- **Leads:** Release Manager
- **Attends:** QA Lead, Technical Lead, Project Manager, Product Manager
- **Accountable:** Release Manager (go/no-go decision and rollback plan)
- **Purpose:** Confirm all pre-release criteria are met before deploying to production.
- **Ref:** [Release & Deployment](octoacme-release-and-deployment.md), [Release Readiness Checklist](templates/octoacme-release-readiness-checklist.md)

---

### Post-Release Verification
- **Leads:** Release Manager
- **Attends:** Developers, QA Lead, Technical Lead
- **Accountable:** Release Manager (confirms successful deployment); QA Lead (smoke test sign-off)
- **Purpose:** Validate that the release is functioning correctly in production and that monitoring is active.
- **Ref:** [Release & Deployment](octoacme-release-and-deployment.md)

---

### Retrospective
- **Leads:** Project Manager
- **Attends:** Developers, Product Manager, Technical Lead, QA Lead, UX/UI Designer, Release Manager
- **Accountable:** Project Manager (action item capture and follow-up)
- **Purpose:** Reflect on what went well, what to improve, and commit to actionable follow-ups.
- **Ref:** [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
