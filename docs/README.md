# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. This folder contains comprehensive guidance for managing projects from initiation through retrospective and continuous improvement.

## Overview

OctoAcme operates on a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. Our processes are designed to ensure that every project has explicit goals, measurable outcomes, and stakeholder alignment before development begins, and maintains transparency and quality throughout execution.

### Core Principles
- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

### Key Roles
- **Project Manager (PM):** Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes the backlog, and measures success
- **Developers:** Implement features, collaborate on design and testability
- **QA/Testing:** Validates quality and acceptance criteria
- **Stakeholders:** Provide inputs and approvals

## Project Lifecycle

OctoAcme projects follow a five-phase lifecycle:

### 1. Initiation
Validate business needs, identify stakeholders, and create a lightweight plan. Deliverables include a Project One-pager with problem statement, success metrics, stakeholders, and initial timeline.

→ [Read the Project Initiation Guide](./octoacme-project-initiation.md)

### 2. Planning
Turn approved initiatives into actionable plans and backlogs for delivery. Define shippable increments, identify dependencies and risks, and align timelines and responsibilities.

→ [Read the Project Planning Guide](./octoacme-project-planning.md)

### 3. Execution & Tracking
Manage day-to-day execution and track progress toward milestones. Use structured team rhythms (daily standups, weekly syncs, demos) and maintain quality through testing, code review, and CI/CD.

→ [Read the Execution & Tracking Guide](./octoacme-execution-and-tracking.md)

### 4. Release & Deployment
Standardize how features are released to production to reduce risk and improve observability. Follow pre-release requirements, deployment checklists, and rollback procedures.

→ [Read the Release & Deployment Guide](./octoacme-release-and-deployment.md)

### 5. Retrospective & Continuous Improvement
Capture learnings and convert them into actionable improvements. Conduct timeboxed retrospectives after each sprint, release, or milestone to reflect and drive incremental progress.

→ [Read the Retrospective & Continuous Improvement Guide](./octoacme-retrospective-and-continuous-improvement.md)

## Key Workflows & Practices

### Team Rhythm
- **Daily standups** (15 min) — focus on progress, blockers, and dependencies
- **Weekly delivery sync** — review progress, updates, and flagged risks
- **Demo/Review** — at the end of each sprint or milestone
- **Monthly stakeholder updates** — keep sponsors and stakeholders informed

### Pull Request Workflow
- Small PRs (≤ 400 lines when possible)
- Include issue link and acceptance criteria in PR description
- Run automated tests and linting in CI before requesting review
- Require at least one approval before merging (or team-defined policy)

### Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Risk Management & Communication
Maintain a Risk Register tracking each risk's description, impact, likelihood, owner, and mitigation plan. Review risks weekly during syncs. Escalate blockers through clear pathways: team-level triage → PM escalation to Product Lead → sponsor-level involvement for business-impacting issues.

→ [Read the Risk Management & Communication Guide](./octoacme-risks-and-communication.md)

## Core Documents

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate, authorize, and plan new work
- **[Project Planning Guide](./octoacme-project-planning.md)** — Turn approved initiatives into actionable plans and backlogs
- **[Execution & Tracking Guide](./octoacme-execution-and-tracking.md)** — Manage day-to-day execution and track progress
- **[Risk Management & Communication Guide](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize how features are released to production
- **[Retrospective & Continuous Improvement Guide](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of typical roles and responsibilities

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction.
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate and plan your work.
- **In execution?** Use the [Execution & Tracking Guide](./octoacme-execution-and-tracking.md) and [Risk Management & Communication Guide](./octoacme-risks-and-communication.md) to stay aligned.
- **Preparing a release?** Consult the [Release & Deployment Guide](./octoacme-release-and-deployment.md).
- **Completing a phase?** Conduct a retrospective using the [Retrospective & Continuous Improvement Guide](./octoacme-retrospective-and-continuous-improvement.md).

Keep the Project Charter updated in your project repo. Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
