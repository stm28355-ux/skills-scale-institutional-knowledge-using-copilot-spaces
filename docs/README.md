# OctoAcme Project Management Documentation

## Overview

OctoAcme uses a structured, phase-based approach to project management that emphasizes customer value, iterative delivery, clear ownership, data-informed decisions, and psychological safety.

### Core Philosophy

OctoAcme's project management approach is built around a clear lifecycle that starts with initiation, moves through planning and execution, and ends with release and retrospective. The process emphasizes validating the business need early, confirming stakeholders and measurable outcomes, and creating a lightweight project charter or one-pager before committing to broader planning. Once approved, teams break the work into prioritized backlog items with acceptance criteria, estimates, dependencies, and a shared definition of done. This creates a repeatable structure for turning ideas into shippable increments while keeping scope, milestones, and responsibilities visible.

The operating model relies on distinct but connected roles. Developers are responsible for building and testing features, maintaining documentation, and helping identify technical risks; Product Managers define the customer problem and prioritize the roadmap based on value and measurable outcomes; Project Managers oversee schedules, dependencies, risk tracking, and stakeholder communication; and QA/testing contributors validate acceptance criteria and release readiness. These persona definitions are intended to make delivery more predictable by clarifying ownership and enabling better collaboration across product, engineering, and stakeholder groups.

Communication is treated as a core project control, not an afterthought. OctoAcme recommends daily standups for rapid issue triage, weekly delivery syncs or PM/PdM reviews, milestone demos, and regular stakeholder updates. Risk and dependency management is integrated into the same rhythm: identify issues early, assess impact and likelihood, assign an owner, and escalate through defined paths when blockers affect delivery, security, or business impact.

Quality assurance is embedded throughout the lifecycle rather than happening only at the end. The process calls for unit, integration, and end-to-end smoke testing where appropriate, along with CI checks, security scanning, and manual QA when product acceptance needs human validation. Release processes require passing tests, security validation, smoke checks, release notes, and rollback planning before production deployment. After each sprint or milestone, the team is expected to run a retrospective to capture what went well, what needs improvement, and which action items should be tracked back into the backlog.

## Documentation Index

### Getting Started
- [Project Management Overview](octoacme-project-management-overview.md) — Start here for an introduction to our approach, core roles, and key artifacts

### Project Lifecycle Phases

**1. Initiation** — Validate and authorize new work
- [Project Initiation Guide](octoacme-project-initiation.md)

**2. Planning** — Turn approved initiatives into actionable plans
- [Project Planning](octoacme-project-planning.md)

**3. Execution** — Manage day-to-day delivery and track progress
- [Execution & Tracking](octoacme-execution-and-tracking.md)

**4. Release** — Standardize deployment to production
- [Release & Deployment Guide](octoacme-release-and-deployment.md)

**5. Close & Improve** — Capture learnings and drive continuous improvement
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

### Cross-cutting Topics
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Apply throughout all phases
- [Roles and Personas](octoacme-roles-and-personas.md) — Understand core responsibilities and typical interactions

## Quick Start by Role

- **New Project Manager?** Start with [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md)
- **Developer joining a project?** Review [Execution & Tracking](octoacme-execution-and-tracking.md) and your project's Definition of Done
- **New Product Manager?** Read [Project Management Overview](octoacme-project-management-overview.md) and [Project Planning](octoacme-project-planning.md)
- **QA or Testing contributor?** See [Execution & Tracking](octoacme-execution-and-tracking.md) for quality standards and [Release & Deployment Guide](octoacme-release-and-deployment.md) for release validation

## Key Templates & Checklists

Quick reference to standard templates and artifacts used across OctoAcme projects:

- **Project One-pager** — See [Project Initiation Guide](octoacme-project-initiation.md)
- **Backlog Item Template** — See [Project Planning](octoacme-project-planning.md)
- **Definition of Done Checklist** — See [Project Planning](octoacme-project-planning.md)
- **Risk Register** — See [Risk Management & Communication](octoacme-risks-and-communication.md)
- **Release Notes Template** — See [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Retrospective Action Items** — See [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- **Weekly Status Template** — See [Risk Management & Communication](octoacme-risks-and-communication.md)

## Communication & Escalation

- **Daily standups** — 15 minute team sync to discuss progress, blockers, and dependencies
- **Weekly PM/PdM sync** — Alignment on priorities, risks, and upcoming work
- **Twice-weekly delivery standups** — Team-level execution status (or as agreed)
- **Monthly stakeholder updates** — High-level progress, milestones, and business impact
- **Escalation paths** — Team-level → PM → Product Lead → Sponsor (see [Risk Management & Communication](octoacme-risks-and-communication.md))

## How to Use These Docs

1. Start with the [Project Management Overview](octoacme-project-management-overview.md) for onboarding.
2. Use the phase-specific guide that matches the current project stage.
3. Reference the templates and checklists for recurring planning, tracking, and release activities.
4. If a gap is identified, use the issue template in [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates.

---

Maintained for OctoAcme project teams and collaborators.
