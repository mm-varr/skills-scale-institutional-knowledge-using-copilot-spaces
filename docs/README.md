# OctoAcme Project Management Documentation

Welcome to the central guide to how OctoAcme initiates, plans, delivers, and improves projects. Use the links below to find detailed processes, checklists, and role guidance.

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md) — Principles, roles, key artifacts, lifecycle, and an introduction to using these process docs.
- [Project Initiation](./octoacme-project-initiation.md) — Validate a proposal, align stakeholders, define success measures, and decide whether to proceed to planning.
- [Project Planning](./octoacme-project-planning.md) — Turn approved work into a prioritized backlog, delivery plan, milestones, and quality approach.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Coordinate day-to-day work, track progress, apply the PR workflow, and validate quality.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Maintain and escalate risks and dependencies, and keep stakeholders informed.
- [Release & Deployment](./octoacme-release-and-deployment.md) — Prepare, deploy, verify, and, when needed, roll back a release.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Turn learnings from sprints, releases, milestones, and incidents into owned improvements.
- [Roles & Personas](./octoacme-roles-and-personas.md) — Responsibilities, goals, and typical communication for developers, product managers, and project managers.

## Executive Summary

OctoAcme uses a structured, collaborative lifecycle to move work from a validated need through delivery and continuous improvement. The approach is **customer-first**, prioritizing value and usability; **iterative**, delivering small, testable increments; and grounded in **clear ownership**, with named project and product leads. Teams use measurable outcomes and evidence to make **data-informed decisions**, while **psychological safety** encourages candid feedback and learning.

Projects begin by confirming the problem, stakeholders, success measures, and decision to proceed. Planning translates approved work into a prioritized backlog, clear acceptance criteria, realistic capacity, dependencies, and a release plan. During execution, the team tracks work on a shared project board, reviews small pull requests, tests changes, and monitors risks and outcome metrics. Releases use readiness checks and post-deployment verification; retrospectives capture lessons and track improvements with owners.

The Project Manager coordinates delivery, schedules, risks, and communications. The Product Manager defines outcomes, prioritizes work, and measures success. Developers build and test; QA/Testing validates quality and acceptance criteria; stakeholders provide input and approvals. Shared artifacts—including the project one-pager, backlog, release plan, risk register, and retrospective actions—keep ownership and decisions visible.

## Quick Reference

### Lifecycle

1. **Initiation** — Define the problem, stakeholders, success criteria, and high-level timeline; agree whether to proceed.
2. **Planning** — Prioritize and estimate work, define acceptance criteria and Definition of Done, and map dependencies and milestones.
3. **Execution** — Build, test, review, demonstrate, and iterate while tracking delivery and risks.
4. **Release** — Confirm readiness, deploy, verify, communicate, and roll back if needed.
5. **Close and improve** — Retrospect, record learnings, and assign follow-up actions.

### Communication cadence

- **Daily:** 15-minute delivery-team standups for progress, blockers, and dependencies.
- **Weekly:** PM–Product Manager alignment and delivery sync; review the risk register and update stakeholders as needed.
- **Each sprint or milestone:** Demo/review; hold a retrospective after each sprint, release, or important milestone.
- **Monthly:** Stakeholder updates.
- **As needed:** Escalate blockers through team triage → PM → Product Lead → Sponsor; use the security incident runbook and notify Security on-call for security incidents.

## How to Use These Docs

- **New to OctoAcme:** Start with the [Project Management Overview](./octoacme-project-management-overview.md), then check [Roles & Personas](./octoacme-roles-and-personas.md).
- **Project Manager:** Use [Initiation](./octoacme-project-initiation.md) and [Planning](./octoacme-project-planning.md) to establish the work; use [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md) during delivery.
- **Product Manager or stakeholder:** Refer to [Initiation](./octoacme-project-initiation.md) for goals and decision gates, [Planning](./octoacme-project-planning.md) for priorities and acceptance criteria, and [Risk Management & Communication](./octoacme-risks-and-communication.md) for updates and decisions.
- **Developer or QA/Testing:** Use [Planning](./octoacme-project-planning.md) for backlog items and Definition of Done, then [Execution & Tracking](./octoacme-execution-and-tracking.md) for board, PR, and test practices.
- **Preparing a release:** Follow the readiness and deployment checklists in [Release & Deployment](./octoacme-release-and-deployment.md).
- **Finishing a sprint, release, or milestone:** Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to turn feedback into actionable improvements.

## Quality Assurance

Quality is built into planning and delivery: define acceptance criteria and a Definition of Done; write unit tests for new logic and integration tests where applicable; run automated tests, linting, and security scans in CI; request at least one review approval; and perform manual QA when needed. Before release, verify acceptance criteria and passing checks, prepare smoke tests and a rollback plan, test in staging, and confirm production behavior after deployment.

## Contributing

Found a gap or have an improvement to suggest? Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template. Describe the proposed change and why it is needed; include suggested content and stakeholder review context when applicable.
