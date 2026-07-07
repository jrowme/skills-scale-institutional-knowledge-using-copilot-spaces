# OctoAcme Project Management Process Docs

Welcome to the OctoAcme project management knowledge hub. This folder contains the definitive guides for how we run projects at OctoAcme—from initial conception through retrospective and continuous improvement.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, clear ownership, and data-informed decision-making. Our five-phase lifecycle—**Initiation, Planning, Execution, Release, and Close & Retrospective**—ensures disciplined planning while maintaining team agility.

**Communication and risk management** are woven into our DNA through a structured cadence (daily standups, weekly syncs, monthly stakeholder updates) and a transparent three-level escalation model (team triage → PM escalation → sponsor-level escalation). We maintain a Risk Register to actively track and mitigate blockers, and use a single source of truth—the project repository—to keep all stakeholders informed and reduce miscommunication.

**Quality assurance is embedded throughout execution and release**. We mandate unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI/CD pipelines. Pull requests follow strict conventions (≤400 lines, include issue links and acceptance criteria, require at least one approval), and all code must pass automated tests before review. Before any release, we verify acceptance criteria, run CI/CD pipelines, document rollback plans, and confirm staging smoke tests—reducing production risk and enabling confident deployments.

**Continuous learning drives improvement**. Structured retrospectives held after each sprint, release, or milestone capture learnings and generate actionable items with clear owners and due dates. By measuring impact and celebrating incremental improvements, we foster psychological safety and a culture where feedback drives sustainable process enhancements. This holistic approach—combining disciplined planning, clear communication, quality-first execution, and reflective learning—positions OctoAcme to scale projects consistently while maintaining team agility and stakeholder confidence.

## Quick Start

If you're new to OctoAcme's processes, start here:

1. Read the **[Project Management Overview](./octoacme-project-management-overview.md)** for a high-level introduction to our approach, core roles, and artifacts.
2. Pick the phase relevant to your work:
   - **Starting a new project?** → [Project Initiation Guide](./octoacme-project-initiation.md)
   - **Planning delivery?** → [Project Planning](./octoacme-project-planning.md)
   - **Executing and tracking?** → [Execution & Tracking](./octoacme-execution-and-tracking.md)
   - **Preparing to release?** → [Release & Deployment Guide](./octoacme-release-and-deployment.md)
   - **Learning from outcomes?** → [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Lifecycle

1. **Initiation** – Define the problem, goals, success metrics, and get stakeholder buy-in
2. **Planning** – Break work into shippable increments, estimate, and identify risks and dependencies
3. **Execution** – Build, test, review, and iterate with consistent communication
4. **Release** – Deploy to production following our release checklist and processes
5. **Close & Retrospective** – Capture learnings and convert them into continuous improvements

## All Process Documents

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Concise introduction to our approach, roles, and artifacts |
| [Project Initiation Guide](./octoacme-project-initiation.md) | How to validate and authorize work, align stakeholders, and create a lightweight plan |
| [Project Planning](./octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Manage day-to-day execution, track progress, and handle blockers |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Identify, manage, and communicate risks, dependencies, and stakeholder updates |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize releases and deployments to reduce risk |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Definitions of typical roles and responsibilities |

## Key Roles

- **Project Manager (PM)** – Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)** – Defines outcomes, prioritizes backlog, and measures success
- **Developers** – Implement features, collaborate on design and testability
- **QA/Testing** – Validate quality and acceptance criteria
- **Stakeholders** – Provide inputs and approvals

## How to Use These Docs

- **Keep the Project Charter updated** in your project repo
- **Add process-specific docs** to `.copilot/` if you want Copilot Spaces to use them as context
- **Reference checklists** at each phase to ensure no steps are missed
- **Link to specific sections** in pull requests, issues, and communications for quick guidance

## Questions?

If you have questions about OctoAcme processes or want to propose improvements, create an issue using our [Add/Update Process Docs template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
