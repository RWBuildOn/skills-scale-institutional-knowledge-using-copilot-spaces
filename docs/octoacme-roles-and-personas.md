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

## Stakeholder (Non-Executive Sponsor)

### Role Summary
Stakeholders provide business context, champion project importance within the organization, and review milestone outcomes. They are not day-to-day participants but are engaged at key decision points and reviews.

### Responsibilities
- Approve major scope, priority, or budget decisions
- Provide business context and strategic direction
- Offer feedback on milestone deliverables
- Escalate support or resources when blockers exceed the PM's reach
- Represent the project to senior leadership as needed

### Goals
- Ensure the project delivers measurable business value
- Maintain organizational alignment and buy-in
- Remove executive-level blockers quickly

### Typical Communication
- Milestone review presentations and written summaries
- Escalation messages from PM when decisions are required
- Release announcements and post-launch results

### Interactions
- Works with **Project Managers** on escalations and decision approvals
- Receives milestone briefings from **Product Managers**
- Reviews outputs from **Developers** through demos and release notes

---

## Technical Lead

### Role Summary
The Technical Lead oversees technical architecture and standards, guiding the team toward sound, scalable design decisions.

### Responsibilities
- Define and enforce technical architecture and coding standards
- Guide design decisions and ADRs (Architecture Decision Records)
- Review and approve significant technical changes
- Identify and communicate technical risks and dependencies
- Mentor Developers and support code quality practices

### Goals
- Maintain a healthy, maintainable codebase
- Reduce technical debt and systemic risk
- Ensure technical decisions align with product goals

### Typical Communication
- Design reviews, RFC documents, and architecture diagrams
- PR reviews and inline code comments
- Technical risk updates in weekly delivery syncs

### Interactions
- Works closely with **Developers** on architecture, code quality, and mentoring
- Coordinates with **QA Lead** on test strategy and defect triage
- Partners with **Project Managers** to surface technical risks and inform scheduling

---

## UX/UI Designer

### Role Summary
The UX/UI Designer ensures that the user experience and interface standards are met, delivering designs that are usable, accessible, and aligned with product goals.

### Responsibilities
- Deliver wireframes, prototypes, and final design assets
- Conduct or facilitate usability reviews
- Maintain and evolve the design system and style guide
- Collaborate on design handoffs and developer implementation guidance
- Advocate for the user throughout the product lifecycle

### Goals
- Maximize usability and accessibility of product features
- Reduce rework caused by unclear or late design input
- Ensure design consistency across the product

### Typical Communication
- Design reviews and critiques during sprint planning and refinement
- Annotated design files shared with Developers via design tooling
- Feedback loops with Product Managers during discovery

### Interactions
- Works with **Product Managers** during feature discovery and acceptance criteria definition
- Partners with **Developers** during feature refinement, handoff, and implementation review
- Coordinates with **QA Lead** on usability acceptance testing

---

## QA Lead

### Role Summary
The QA Lead owns the quality assurance strategy and orchestrates both manual and automated testing to ensure releases meet acceptance criteria and quality standards.

### Responsibilities
- Define and maintain the test plan and QA strategy
- Coordinate acceptance testing with the team and stakeholders
- Track defect discovery, triage, and resolution
- Ensure test coverage for critical flows before each release
- Champion quality practices (test automation, standards, tooling)

### Goals
- Prevent regressions and critical defects from reaching production
- Improve test automation coverage over time
- Provide clear, timely signal on release readiness

### Typical Communication
- Test status reports and defect summaries shared with PM and Technical Lead
- QA sign-off notes in release readiness reviews
- Defect triage discussions in daily standups or ad-hoc syncs

### Interactions
- Works with **Developers** on defect reproduction, root cause, and automated test support
- Partners with **Project Managers** on test timelines and release readiness gates
- Coordinates with **Technical Lead** on test strategy and tooling decisions
- Collaborates with **UX/UI Designer** on usability and acceptance testing

---

## Release Manager

### Role Summary
The Release Manager coordinates release scheduling and deployment processes, ensuring that all pre-release requirements are met and that releases proceed with minimal risk.

### Responsibilities
- Maintain the release calendar and deployment schedule
- Confirm all pre-release criteria are met (tests, reviews, comms)
- Communicate release timelines and status to stakeholders
- Maintain and verify rollback plans
- Coordinate post-release verification and incident response triggers

### Goals
- Deliver releases on schedule with predictable, low-risk deployments
- Ensure stakeholders are informed and prepared before and after each release
- Reduce time-to-recovery when incidents occur

### Typical Communication
- Release readiness briefings with QA Lead, Technical Lead, and PM
- Pre-release announcements to stakeholders and support teams
- Post-release verification summaries

### Interactions
- Coordinates with **QA Lead** on test sign-off and release readiness criteria
- Works with **Technical Lead** on deployment approach and rollback strategy
- Partners with **Project Managers** on scheduling and stakeholder communication
- Engages **Developers** for last-mile fixes and deployment support

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For role involvement across project phases and ceremonies, see [`octoacme-roles-and-ceremonies.md`](octoacme-roles-and-ceremonies.md).

