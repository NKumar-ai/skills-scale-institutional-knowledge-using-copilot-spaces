# OctoAcme Project Management Docs

This README provides an overview of the project management practices and process documentation for OctoAcme teams. It summarizes our approach and links to detailed guides on project initiation, planning, execution, risk management, release, and continuous improvement.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project delivery that emphasizes customer value, iterative execution, and clear ownership. The methodology is organized around five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, projects begin with a lightweight One-pager that articulates the problem statement, success metrics, stakeholder alignment, and initial timeline—establishing a clear decision gate before committing resources. Once approved, teams move into detailed planning, where work is broken into shippable increments with defined acceptance criteria, estimates are assigned, dependencies are mapped, and a Definition of Done is established.

The execution phase is anchored by a consistent team rhythm and governance structure. Daily standups (15 minutes) focus on progress and blockers, while weekly delivery syncs provide visibility into risks and progress. The team uses GitHub Projects with a standardized workflow (Backlog → Ready → In Progress → In Review → QA → Done), enforces small, well-documented PRs (≤400 lines), and requires automated testing, linting, and at least one approval before merge. Quality is embedded throughout: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI.

OctoAcme's organizational structure is built on clear role definition and collaboration between three core personas: **Developers** (implement features, maintain tests and docs, estimate scope), **Product Managers** (define success metrics, prioritize backlog, validate solutions), and **Project Managers** (manage timelines, risks, and communications). A weekly sync between PM and Product Manager keeps delivery and product goals synchronized, while monthly stakeholder updates and ad-hoc escalations ensure transparency. Communication uses templates for weekly status reports and incident notifications to standardize information flow.

The journey concludes with release management and continuous improvement. Before production deployment, all acceptance criteria must be met, CI and security scans must pass, release notes must be drafted, and a rollback plan must be documented. Finally, after each sprint, release, or significant milestone, OctoAcme conducts a retrospective to capture what went well, what could improve, and to convert findings into tracked action items. This blameless, iterative reflection cycle reinforces a culture of psychological safety and continuous improvement.

## Core Phases and Process Guides

OctoAcme employs an iterative, customer-centric approach with clear ownership, data-driven decision making, and psychological safety. Core phases include:

- **Initiation:** Define problem, align stakeholders, and set success metrics ([Project Initiation Guide](./octoacme-project-initiation.md))
- **Planning:** Break down work, estimate, and map milestones ([Project Planning](./octoacme-project-planning.md))
- **Execution & Tracking:** Use consistent workflows, quality practices, and reporting to drive delivery ([Execution & Tracking](./octoacme-execution-and-tracking.md))
- **Risk & Communication:** Identify, document, and escalate risks; maintain clear stakeholder communication ([Risks & Communication](./octoacme-risks-and-communication.md))
- **Release & Deployment:** Standardize how features flow to production with pre-release and rollout checks ([Release & Deployment Guide](./octoacme-release-and-deployment.md))
- **Retrospective & Improvement:** Run regular retros to learn and improve ([Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md))

## Key Artifacts & Roles

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, principles, and key roles
- [Roles and Personas](./octoacme-roles-and-personas.md) — Definitions of Developers, Product Managers, and Project Managers
- [Project Initiation Guide](./octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning](./octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward project milestones
- [Risks and Communication](./octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies
- [Release and Deployment](./octoacme-release-and-deployment.md) — Standardize how OctoAcme releases features to production to reduce risk and improve observability
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements

## How to Use These Docs

- **New team members:** Start with [Project Management Overview](./octoacme-project-management-overview.md) and [Roles and Personas](./octoacme-roles-and-personas.md) to understand the framework and your role.
- **Project kickoff:** Reference [Project Initiation Guide](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md) to establish your project charter and backlog.
- **During execution:** Use [Execution & Tracking](./octoacme-execution-and-tracking.md) for daily workflows and [Risks and Communication](./octoacme-risks-and-communication.md) to manage risks and stakeholder updates.
- **Before release:** Follow the pre-release checklist in [Release and Deployment](./octoacme-release-and-deployment.md).
- **After each milestone:** Run a retrospective using guidance from [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

## Quick Links

| Role | Key Resources |
|------|---|
| **Product Manager** | [Project Management Overview](./octoacme-project-management-overview.md), [Project Initiation Guide](./octoacme-project-initiation.md), [Roles and Personas](./octoacme-roles-and-personas.md) |
| **Project Manager** | [Project Planning](./octoacme-project-planning.md), [Execution & Tracking](./octoacme-execution-and-tracking.md), [Risks and Communication](./octoacme-risks-and-communication.md) |
| **Developer** | [Execution & Tracking](./octoacme-execution-and-tracking.md), [Roles and Personas](./octoacme-roles-and-personas.md), [Release and Deployment](./octoacme-release-and-deployment.md) |
| **All Roles** | [Project Management Overview](./octoacme-project-management-overview.md), [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) |
