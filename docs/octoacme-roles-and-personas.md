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

## Product Lead

### Role Summary
Product Leads provide strategic oversight and serve as the primary escalation point and decision authority for product initiatives. They align stakeholder and sponsor expectations with engineering capacity and priorities.

### Responsibilities
- Approve project charters and validate business alignment
- Escalate blockers and risks to executive sponsors
- Align on roadmap prioritization with Product Managers
- Validate business outcomes and measure impact post-launch
- Make strategic trade-off decisions on scope, timeline, and quality

### Goals
- Ensure all projects deliver measurable business value
- Maintain stakeholder and sponsor confidence and alignment
- Enable fast, informed decision-making during execution

### Typical Communication
- Weekly alignment syncs with PM and engineering leads
- Monthly stakeholder updates on portfolio progress
- Escalation calls for high-risk or blocked items

### Interactions with Existing Roles
- **With Product Managers:** Aligns on prioritization and validates that backlog reflects business strategy
- **With Project Managers:** Escalation point for scope, timeline, and resource conflicts; approves major trade-off decisions
- **With Developers:** Provides business context and validates technical feasibility trade-offs with Product Manager

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality strategy, test planning, and acceptance validation. They partner with developers and product teams to define robust testing approaches that verify features meet acceptance criteria.

### Responsibilities
- Define comprehensive test plans and QA strategy aligned with project scope
- Validate acceptance criteria with Product Manager and developers before sprint
- Execute testing phases: unit, integration, end-to-end, and smoke tests
- Identify and escalate quality risks that could impact release readiness
- Report quality metrics, defect status, and test coverage
- Collaborate with developers on testability and design-for-quality

### Goals
- Ensure all features meet acceptance criteria before release
- Minimize production defects and post-release issues
- Maintain consistent product reliability and performance standards

### Typical Communication
- Sprint planning and daily standups
- QA sign-off on acceptance criteria
- Defect triage and escalation reviews
- Pre-release quality gates and readiness validation

### Interactions with Existing Roles
- **With Product Managers:** Clarifies and validates acceptance criteria; reports on feature quality metrics
- **With Developers:** Collaborates on test design and identifies testability gaps; escalates critical defects
- **With Project Managers:** Provides quality status updates; flags quality risks that could delay release

---

## Tech Lead / Architecture Owner

### Role Summary
Tech Leads provide technical guidance, review system design, and help teams navigate architectural decisions and technical risks. They mentor developers and advise Product Managers on technical feasibility and capacity constraints.

### Responsibilities
- Define or validate technical architecture for features and systems
- Review technical designs and code to ensure quality standards
- Identify technical risks and propose mitigation strategies
- Advise Product Manager on technical feasibility and effort trade-offs
- Mentor developers on implementation approaches and best practices
- Coordinate technical dependencies across teams and systems

### Goals
- Maintain system quality, scalability, and long-term maintainability
- Reduce technical debt and minimize rework
- Enable sustainable, predictable development pace
- Share technical knowledge and build team capabilities

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and technical feedback
- Capacity planning and estimation support
- Technical spike investigations and proof-of-concept work

### Interactions with Existing Roles
- **With Developers:** Mentors on implementation; reviews designs and code; advises on technical feasibility
- **With Product Managers:** Advises on technical feasibility and trade-offs; informs effort estimates
- **With Project Managers:** Supports capacity planning and identifies technical dependencies that impact timeline

---

## Release Manager

### Role Summary
Release Managers coordinate deployment activities, ensure pre-release readiness, manage rollout execution, and communicate release status to stakeholders. They own the deployment checklist and rollback procedures.

### Responsibilities
- Coordinate deployment windows and schedule across all teams
- Verify pre-release checklist: tests passing, documentation ready, rollback plan documented
- Execute or coordinate production deployments with ops teams
- Manage and execute rollback procedures if critical issues arise
- Communicate release status to stakeholders and support teams
- Document release notes, known issues, and migration steps

### Goals
- Reduce deployment risk and minimize incident frequency
- Minimize release-related downtime and customer impact
- Ensure clear, proactive communication during deployments
- Enable fast, reliable releases to production

### Typical Communication
- Pre-release coordination with developers and ops
- Deployment window announcements to stakeholders
- Stakeholder release notifications and documentation
- Post-deployment verification and incident response

### Interactions with Existing Roles
- **With Developers:** Coordinates merge readiness and coordinates final testing before deployment
- **With QA/Testing Lead:** Verifies quality gate approval; coordinates smoke testing during deployment
- **With Project Managers:** Provides release status updates; escalates deployment issues that impact timeline

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests and strategic priorities. They define business objectives, approve funding and resource allocation, and make major trade-off decisions on project scope and timeline.

### Responsibilities
- Define business objectives and success criteria for initiatives
- Approve project funding, scope, and resource allocation
- Make strategic trade-off decisions: scope, timeline, quality, resources
- Receive regular project status updates and escalations
- Validate that delivered features meet business needs and objectives
- Communicate project value and progress to broader organization

### Goals
- Ensure all projects align with business strategy
- Protect business investments in product development
- Enable quick, informed decision-making on priorities and trade-offs
- Maintain confidence and alignment across executive leadership

### Typical Communication
- Monthly or milestone-based status updates
- Project approval gates (initiation, planning, release)
- High-priority escalation and blocker resolution
- Post-release outcome validation and impact measurement

### Interactions with Existing Roles
- **With Product Lead:** Receives escalations and approves major business decisions; aligns on strategic priorities
- **With Project Managers:** Receives status updates; makes decisions on scope and timeline trade-offs
- **With Product Managers:** Validates that delivered features meet business objectives; measures business impact

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
