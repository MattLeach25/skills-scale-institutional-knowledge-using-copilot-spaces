# OctoAcme Project Management Docs

This directory is the canonical location for OctoAcme project management process documentation. It provides guidance, templates, and standards that help every team member — from new joiners to experienced contributors — understand how OctoAcme plans, executes, and continuously improves its projects.

## Project Management Overview

OctoAcme follows a lightweight, iterative project management approach centred on customer-first value delivery and data-informed decisions. Projects move through a defined lifecycle, with clear roles, regular communication cadences, and built-in quality gates at every stage.

### Lifecycle

| Phase | Description |
|---|---|
| **Initiation** | Validate the business need, define success metrics, align stakeholders, and produce a Project One-pager / Charter. |
| **Planning** | Break work into shippable increments, define the Definition of Done (DoD), build the Risk Register, and agree on a release timeline. |
| **Execution & Tracking** | Build, test, and iterate in sprints using the project board (Backlog → Ready → In Progress → In Review → QA → Done). Track velocity, escalate blockers, and keep the Risk Register current. |
| **Release & Deployment** | Meet pre-release requirements (CI green, security scans, release notes, rollback plan), run smoke tests, deploy, and announce to stakeholders. |
| **Close & Retrospective** | Capture what went well and what to improve, convert learnings into backlog action items, and measure impact over time. |

### Personas / Roles

- **Project Manager (PM)** — Coordinates delivery, schedules, risk management, and stakeholder communication.
- **Product Manager / Product Lead (PdM)** — Defines outcomes, prioritizes the backlog, and measures success.
- **Developers** — Implement features, write tests, participate in design and code reviews.
- **QA / Testing** — Validate quality and acceptance criteria across unit, integration, and end-to-end layers.
- **Stakeholders** — Provide inputs, approvals, and receive regular status updates.

### Communication Strategy

- **Weekly PM + PdM sync** — Align on priorities, risks, and decisions.
- **Twice-weekly delivery standups** — 15-minute check-ins on progress and blockers.
- **Monthly stakeholder updates** — Milestone-based status reports.
- **Single source of truth** — The project README or release doc holds current status.
- **Weekly Status Template** — Progress · Next steps · Risks & blockers · Ask / decisions needed.
- **Escalation path** — Team → PM → Product Lead → Sponsor (security incidents follow the security incident runbook).

### Quality Assurance

- **Definition of Done (DoD)** — Defined during Planning; all items must meet DoD before merging.
- **Testing layers** — Unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release.
- **CI checks** — Automated tests, linting, and security scanning run on every pull request.
- **Release checklist** — Acceptance criteria met, CI green, release notes drafted, rollback plan documented.
- **Rollback / Incident** — Trigger incident response, rollback to last known-good release if needed, triage root cause, and schedule a blameless retrospective.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle summary. |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work, One-pager template, and initiation checklist. |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, DoD, risk & dependency management, and planning checklist. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Team rhythm, PR workflow, quality standards, metrics, and blocker escalation. |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk Register format, lifecycle, stakeholder communication, and escalation paths. |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release types, deployment checklist, rollback playbook, and release notes template. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, facilitation tips, and continuous improvement tracking. |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for each role. |
