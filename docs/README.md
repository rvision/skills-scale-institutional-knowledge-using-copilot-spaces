# OctoAcme Project Management Docs

OctoAcme follows a structured, lifecycle-based approach to project management organized into five phases: **Initiation, Planning, Execution, Release, and Retrospective**. Every project begins with a lightweight one-pager capturing the problem statement, SMART objectives, success metrics, stakeholders, and initial risks. Projects only advance to planning once success metrics are clear, stakeholder alignment is confirmed, and team availability is locked in. This gate-based initiation ensures that only well-defined, prioritized work enters the delivery pipeline, reducing wasted effort and misaligned expectations.

The **planning and execution phases** emphasize iterative delivery, clear ownership, and disciplined tracking. Work is broken into shippable increments with a prioritized backlog, a Definition of Done, and a release milestone map. During execution, the team maintains a consistent rhythm — daily standups, weekly delivery syncs, and end-of-sprint demos — supported by a GitHub Projects board with columns spanning Backlog through Done. Pull requests are kept small (≤ 400 lines when possible), linked to issues with acceptance criteria, and require at least one approval after passing CI checks (tests, linting, and security scans). Blockers are escalated through a clear three-level path: team triage → PM/Product Lead → Sponsor.

OctoAcme defines three core **personas** that shape how work is structured and communicated. *Developers* own implementation, testing, and code review while contributing to design and risk identification. *Product Managers* define outcomes, own the backlog, and measure success through data-driven decisions. *Project Managers* coordinate delivery, manage schedules, risks, and cross-team dependencies, and maintain consistent status reporting. This separation of concerns ensures each dimension of project health — what to build, how to build it, and when to deliver it — has a named owner.

**Risk management, communication, and quality assurance** are woven throughout every phase. Risks are tracked in a living Risk Register (with ID, impact, likelihood, owner, and mitigation) and reviewed weekly. Stakeholder communication follows a predictable cadence — weekly status updates, monthly stakeholder briefings, and ad-hoc escalations — anchored to a single source of truth. On the quality side, the process mandates unit, integration, and end-to-end smoke tests, with security scanning in CI and manual QA for feature acceptance. Every release requires a rollback plan, staging smoke tests, and release notes before production deployment. After each sprint, release, or incident, a timeboxed retrospective captures what went well, what to improve, and 2–3 prioritized action items — closing the loop on continuous improvement.

## Process Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
