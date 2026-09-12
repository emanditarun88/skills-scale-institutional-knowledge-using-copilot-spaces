# OctoAcme Project Management Documentation

## Overview

The OctoAcme Project Management framework provides a comprehensive approach to running cross-functional projects. Our processes emphasize customer value delivery, iterative development, clear ownership, and data-driven decision-making across five lifecycle phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**.

OctoAcme follows a structured, lifecycle-based approach that begins with validating business need and aligning stakeholders through a lightweight Project One-pager capturing problem statements, success metrics, and resource needs. Once stakeholders approve an initiative, the planning phase breaks work into shippable increments, establishes acceptance criteria, estimates scope, and creates a prioritized backlog with a clear Definition of Done. Execution and tracking form the operational heartbeat through daily standups (15 minutes), weekly delivery syncs, and end-of-sprint demos, with work flowing through a GitHub Projects board. Quality is embedded throughout via unit and integration tests in CI, mandatory security scanning, and manual QA for feature acceptance. The organization defines clear role boundaries—Developers implement features and tests, Product Managers own vision and prioritize the backlog, and Project Managers coordinate schedules and manage risks. Communication is intentional through weekly PM/PdM syncs, monthly stakeholder updates, and standardized risk registers updated weekly. Finally, retrospectives after each sprint capture learnings and convert 2–3 top action items into tangible process improvements, embedding continuous learning into the team's culture.

## Key Principles

- **Customer-First**: Prioritize customer value and usability
- **Iterative Delivery**: Deliver small, testable increments
- **Clear Ownership**: Named Project Manager and Product Lead for every project
- **Data-Informed**: Measure impact and iterate based on evidence
- **Psychological Safety**: Encourage feedback and continuous learning

## Documentation Structure

### Project Lifecycle

1. **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, and decide go/no-go for planning
2. **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, establish acceptance criteria, and create actionable backlog
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day execution, track progress toward milestones, and maintain quality standards
4. **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize release processes and reduce deployment risk with checklists and rollback plans
5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive iterative improvements after sprints and releases

### Cross-Cutting Guidance

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to core roles, key artifacts, lifecycle phases, and communication cadence
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Manage risks, dependencies, and stakeholder communication with escalation paths and templates
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of key roles (PM, Product Manager, Developers, QA) and responsibilities in project execution

## Quick Start for New Team Members

1. **Start here**: Read [Project Management Overview](./octoacme-project-management-overview.md) for a concise 5-minute introduction to how OctoAcme runs projects
2. **Know your role**: Review your responsibilities in [Roles & Personas](./octoacme-roles-and-personas.md)
3. **Follow the lifecycle**: Navigate to the documentation for the phase your project is currently in:
   - Starting a new project? → [Project Initiation Guide](./octoacme-project-initiation.md)
   - Planning work? → [Project Planning](./octoacme-project-planning.md)
   - Executing and tracking? → [Execution & Tracking](./octoacme-execution-and-tracking.md)
   - Preparing for release? → [Release & Deployment Guide](./octoacme-release-and-deployment.md)
   - Wrapping up? → [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
4. **Throughout execution**: Reference [Risk Management & Communication](./octoacme-risks-and-communication.md) for handling risks, dependencies, and stakeholder updates

## Key Workflows & Practices

### Execution & Quality
- Daily standups (15 min) focused on progress, blockers, and dependencies
- Weekly delivery syncs and end-of-sprint demos
- GitHub Projects board with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Small PRs (≤ 400 lines) with issue links and acceptance criteria
- Unit tests, integration tests, and security scanning in CI
- Manual QA for feature acceptance when needed

### Communication & Risk Management
- Weekly PM + Product Manager sync for strategic alignment
- Monthly stakeholder updates and milestone-based reporting
- Risk register updated weekly with ID, description, impact, likelihood, owner, and mitigation
- Formal escalation paths: Team-level → PM → Product Lead → Sponsor
- Incident communication with blameless retrospectives

### Continuous Improvement
- Retrospectives after each sprint, release, or milestone (45–75 minutes)
- 2–3 prioritized action items with clear owners and due dates
- Action item tracking in project backlog or GitHub issues
- Review of outstanding actions in weekly PM syncs

## How to Use These Docs

- **Keep the Project Charter updated** in your project repository
- **Reference the appropriate lifecycle doc** based on your current project phase
- **Use templates and checklists** to standardize your team's execution
- **Feed improvements back** into these docs after retrospectives and learnings
- **Add this README** to your project repository to guide new team members

---

For questions or improvements to these processes, open an issue with the [Process Doc Update](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
