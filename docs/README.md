# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear accountability. The process spans five core phases: **Initiation**, where business needs and success metrics are validated with stakeholders; **Planning**, where work is broken into shippable increments with acceptance criteria and risk assessment; **Execution**, managed through daily standups and a project board with defined workflow columns; **Release**, which requires pre-release verification including CI/security scans and smoke tests; and **Close & Retrospective**, where learnings are captured and converted into actionable improvements.

The organization defines clear, overlapping roles to maintain accountability and enable collaboration. **Project Managers** coordinate schedules, risks, and stakeholder communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; **Developers** implement features, write tests, and participate in design and code reviews; and **QA/Testing** teams validate quality against acceptance criteria. Each project has a named PM and Product Lead, supported by weekly syncs between PM and Product Manager, twice-weekly delivery standups, and monthly stakeholder updates.

Quality and risk management are embedded at every stage. OctoAcme requires unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI. A simple **Risk Register** (tracking ID, description, impact, likelihood, owner, and mitigation) is maintained and reviewed at weekly syncs, with escalation paths defined at three levels: team triage, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues.

Finally, OctoAcme institutionalizes learning through structured retrospectives held after each sprint, release, or milestone. Teams reflect on what went well, what could improve, and identify 2–3 prioritized action items with clear owners and due dates. These improvements feed back into the backlog and are tracked in the weekly PM sync, creating a culture of psychological safety and continuous refinement.

---

## Project Management Process Documents

All core process documentation is organized in this folder:

- **[OctoAcme Project Management Overview](./octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, core roles, key artifacts, and the five-phase lifecycle.

- **[OctoAcme Project Initiation Guide](./octoacme-project-initiation.md)** — Define initial steps to validate business need, align stakeholders, and create a lightweight plan using the Project One-pager template.

- **[OctoAcme Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog, including sprint planning, dependencies, and the Definition of Done.

- **[OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution, team rhythm (standups, syncs, demos), and blocker escalation.

- **[OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md)** — Explain how to identify, assess, monitor, and communicate risks and dependencies using the Risk Register and escalation paths.

- **[OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production, including pre-release requirements, deployment checklists, and rollback procedures.

- **[OctoAcme Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements through structured retrospectives and action item tracking.

- **[OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)** — Define typical roles (Developers, Product Managers, Project Managers) and their responsibilities, goals, and communication patterns.

---

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction.

2. **Starting a new project?** Follow the lifecycle:
   - [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Execution](./octoacme-execution-and-tracking.md) → [Release](./octoacme-release-and-deployment.md) → [Retrospective](./octoacme-retrospective-and-continuous-improvement.md)

3. **Managing risks or communications?** Refer to [Risk Management & Communication](./octoacme-risks-and-communication.md).

4. **Role clarity needed?** See [Roles and Personas](./octoacme-roles-and-personas.md) to understand responsibilities and typical workflows.

5. **Contributing to process docs?** Use the issue template [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates or clarifications.

---

## Keeping Docs Updated

These documents are living artifacts. As processes evolve:
- Capture feedback in project retrospectives
- Propose improvements using the process doc update issue template
- Keep cross-references and examples current
- Version key artifacts in the project repository

For questions or suggestions, reach out to your Project Manager or Product Lead.