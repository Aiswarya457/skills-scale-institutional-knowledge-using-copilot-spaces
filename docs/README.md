# OctoAcme Project Management Docs

## Welcome to OctoAcme Project Management

OctoAcme follows a lightweight, repeatable lifecycle that moves initiatives from initiation through planning, execution, release, and retrospective. Work is governed by a set of core artifacts — a **Project One-pager** that captures problem, goals, and success metrics; a **prioritized backlog**; a **risk register**; and **release notes** — so decisions and progress have a single source of truth.

**Key workflows** emphasize small, incremental delivery and disciplined pull-request practices. Teams use a **project board** (Backlog → Ready → In Progress → In Review → QA → Done) and a **PR workflow** that favors small PRs (≤400 lines when possible), links to issues and acceptance criteria, passing CI and linters, and at least one approval before merging. **Releases** follow defined types (patch, minor, major) with pre-release checks including CI, security scans, smoke tests, and a rollback plan.

**Roles are explicit** — Project Managers coordinate delivery and communications; Product Managers own outcomes and prioritization; Developers, QA leads, Technical Leads, Scrum Masters, Security Officers, and Stakeholders each have clear responsibilities that support accountability. **Communication cadence** includes daily standups (15 min), twice-weekly delivery standups, weekly PM + Product Manager alignment, and milestone-based stakeholder updates. **QA practices** include unit, integration, and smoke tests; automated security scanning in CI; and manual QA and post-deploy verification when needed.

This approach ensures **transparency, predictability, and quality** at every stage while remaining lightweight enough for teams of any size to adopt and adapt.

---

## Documentation Index

### Core Guidance
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, principles, roles, and lifecycle
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed definitions of team roles, responsibilities, and communication patterns

### Project Lifecycle

| Phase | Document |
|-------|----------|
| **Initiation** | [Project Initiation Guide](octoacme-project-initiation.md) — Validate business need, align stakeholders, create one-pager |
| **Planning** | [Project Planning](octoacme-project-planning.md) — Break work into shippable increments, estimate, identify dependencies |
| **Execution** | [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day management, standups, PR workflow, quality gates |
| **Release** | [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardized release process, deployment checklist, rollback playbook |
| **Close** | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, track improvements, evolve practices |

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk register, escalation paths, stakeholder communication templates

---

## Quick Start

**Starting a new project?**
1. Begin with the [Project Initiation Guide](octoacme-project-initiation.md) to validate the idea and align stakeholders
2. Create a **Project One-pager** (template in the Initiation doc)
3. Move to [Project Planning](octoacme-project-planning.md) once initiated

**Running a project?**
- Use [Execution & Tracking](octoacme-execution-and-tracking.md) for daily team rhythms and quality standards
- Refer to [Risk Management & Communication](octoacme-risks-and-communication.md) for escalations and stakeholder updates
- Review the [Roles & Personas](octoacme-roles-and-personas.md) doc to clarify responsibilities

**Preparing a release?**
- Follow the [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release checks and deployment steps

**Learning from delivery?**
- Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

---

## Key Artifacts & Templates

Throughout these docs, you'll find templates and checklists for:
- **Project One-pager** (initiation)
- **Backlog item** (planning)
- **Risk register** (risk management)
- **Weekly status** (communication)
- **Release notes** (release & deployment)
- **Action item** (retrospective)

Each document includes practical examples and acceptance criteria checklists to keep projects on track.

---

## How to Use These Docs

- **Keep the Project Charter updated** in your project repository
- **Add process-specific docs** to `.copilot/` if you want Copilot Spaces to use them as context
- **Reference these docs** in kickoff meetings, planning sessions, and retrospectives
- **Customize** templates and workflows to fit your team's needs while maintaining the core principles

---

## Questions or Feedback?

These docs are living artifacts. If you see gaps, have suggestions for improvements, or want to capture new practices, open an issue or pull request using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
