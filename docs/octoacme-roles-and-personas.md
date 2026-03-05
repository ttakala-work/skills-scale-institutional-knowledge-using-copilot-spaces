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

## Engineering Leads / Tech Leads

### Role Summary
Engineering Leads (or Tech Leads) provide technical direction for the project, ensure architectural coherence, and support Developers in making high-quality implementation decisions.

### Responsibilities
- Define and communicate technical approach and architecture for the project.
- Review and approve key technical decisions and trade-offs.
- Pair with Developers on complex or risky changes.
- Ensure non-functional requirements (performance, security, reliability, observability) are considered.
- Partner with Product Managers and Project Managers on feasibility and technical risk assessment.

### Goals
- Maintain a coherent, scalable technical architecture.
- Reduce technical risk and unplanned rework.
- Mentor and unblock Developers throughout the delivery cycle.

### Typical Communication
- Technical design reviews and architecture decision records (ADRs).
- PR reviews and pairing sessions with Developers.
- Feasibility and risk input in planning meetings and weekly syncs.

### Interaction with Existing Roles
- **With Developers:** provide guidance, review designs and PRs, and help unblock implementation challenges.
- **With Product Managers:** translate product goals and constraints into technical plans and milestones.
- **With Project Managers:** surface technical risks, dependencies, and capacity constraints to feed into plans and status updates.

---

## Designers / UX

### Role Summary
Designers/UX partners ensure that solutions are usable, accessible, and aligned with customer needs and product vision.

### Responsibilities
- Shape user flows, interaction patterns, and visual design for features.
- Collaborate with Product Managers to validate problem/solution fit via prototypes or user feedback.
- Provide design specifications and assets for Developers.
- Participate in reviews to ensure the implemented experience matches the intended design.

### Goals
- Deliver intuitive, accessible, and on-brand user experiences.
- Reduce redesign cycles by providing clear specifications early.
- Advocate for the end user throughout the project lifecycle.

### Typical Communication
- Design reviews and prototype walkthroughs.
- Design spec handoffs and asset delivery to Developers.
- Participation in sprint reviews to evaluate UX quality of implemented features.

### Interaction with Existing Roles
- **With Product Managers:** co-create problem definitions, solution concepts, and acceptance criteria that reflect user needs.
- **With Developers:** clarify design details, provide assets, and review builds for UX quality.
- **With Project Managers:** align on design timelines, review cycles, and dependencies that may affect the project plan.

---

## QA / Testing

### Role Summary
QA/Testing ensures that changes meet quality standards and acceptance criteria before and after release.

### Responsibilities
- Collaborate on test strategy (unit, integration, end-to-end, exploratory).
- Design and execute test cases for new functionality and regressions.
- Validate acceptance criteria, edge cases, and critical user paths.
- Partner with Developers to improve test coverage and automation.
- Log and prioritize defects in alignment with Product Managers.

### Goals
- Prevent regressions and quality issues from reaching production.
- Build a sustainable test automation suite that keeps pace with delivery velocity.
- Provide clear go/no-go input ahead of releases.

### Typical Communication
- Test plans and test reports shared before and after releases.
- Defect reports and triage discussions with Developers and Product Managers.
- Go/no-go assessments for release readiness.

### Interaction with Existing Roles
- **With Developers:** coordinate on test coverage, environments, and defect triage.
- **With Product Managers:** confirm that features meet the agreed acceptance criteria and quality bar before release.
- **With Project Managers:** provide test status, risk assessments, and go/no-go input ahead of releases.

---

## Customer Support / Success

### Role Summary
Customer Support/Success represents the customer's voice during and after delivery. They help ensure that releases are supportable, that known issues are communicated, and that feedback is routed back into the roadmap.

### Responsibilities
- Prepare for upcoming releases (e.g., FAQs, known issues, support workflows).
- Surface recurring customer pain points and feature requests to Product Managers.
- Participate in incident communications and post-incident reviews as needed.
- Help track customer impact of major changes or incidents.

### Goals
- Ensure every release is supportable and well-communicated to customers.
- Close the feedback loop between customers and the product team.
- Minimize customer disruption from changes or incidents.

### Typical Communication
- Pre-release readiness reviews with Project Managers and Product Managers.
- Release announcements and customer-facing communications.
- Post-incident retrospectives and customer impact summaries.

### Interaction with Existing Roles
- **With Product Managers:** share insights from customers and help validate whether changes are solving real problems.
- **With Project Managers:** coordinate on stakeholder communications for releases and incidents.
- **With Developers:** provide concrete examples of customer issues to aid debugging and prioritization.

---

## Stakeholders / Sponsors

### Role Summary
Stakeholders and Sponsors provide strategic direction, approve major decisions, and help remove organizational blockers. They champion the project and are accountable for its business outcomes.

### Responsibilities
- Align project goals with business strategy and priorities.
- Approve major scope or timeline changes.
- Help resolve cross-team or organizational escalations.
- Champion the project and communicate outcomes to broader audiences.

### Goals
- Ensure the project delivers measurable business value.
- Protect the team from organizational friction and competing priorities.
- Maintain visibility into project health and key risks.

### Typical Communication
- Monthly (or milestone-based) status updates from Project Managers.
- Escalation discussions for high-impact risks and blockers.
- Go/no-go reviews for major releases or scope changes.

### Interaction with Existing Roles
- **With Product Managers:** align on business outcomes, metrics, and prioritization.
- **With Project Managers:** receive regular status updates and support escalation paths for critical risks.
- **With Developers and other delivery roles:** set context and expectations, but delegate day-to-day execution to the project team.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For lifecycle participation of each persona (initiation, planning, execution, release, retrospectives), see the relevant process docs in `docs/`.

---

## Changelog

### March 2026 — Expanded Roles Coverage
Added five new personas to reflect how projects actually run at OctoAcme:
- **Engineering Leads / Tech Leads** — technical direction, architecture, and feasibility.
- **Designers / UX** — user experience, design specs, and prototype validation.
- **QA / Testing** — test strategy, defect triage, and release go/no-go.
- **Customer Support / Success** — release readiness, customer feedback, and incident communications.
- **Stakeholders / Sponsors** — expanded with Goals, Typical Communication, and interaction patterns.

Each new persona includes a Role Summary, Responsibilities, Goals, Typical Communication, and Interaction with Existing Roles section, matching the format of the original three personas. Cross-functional checklists in other process docs have also been updated to explicitly reference these roles. See `docs/octoacme-project-management-overview.md` for a summary of all core roles.

