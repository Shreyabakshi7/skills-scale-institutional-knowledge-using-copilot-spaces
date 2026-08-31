# OctoAcme Project Management Docs

Welcome to OctoAcme's comprehensive project management documentation. These guides standardize how we run projects, coordinate teams, and deliver customer value.

## Quick Start

- **Just starting a new project?** → Read [OctoAcme Project Initiation Guide](octoacme-project-initiation.md)
- **Ready to plan execution?** → Read [OctoAcme Project Planning](octoacme-project-planning.md)
- **In active delivery?** → Read [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md)
- **Preparing for release?** → Read [OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Wrapping up?** → Read [OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Our Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle Overview

OctoAcme follows a structured five-phase approach to project management:

1. **Initiation**: Validate business need, align stakeholders, and create a lightweight Project One-pager that defines the problem, goals, success metrics, and initial timeline. This phase ensures all teams share a common understanding before committing resources.

2. **Planning**: Break work into shippable increments with clear acceptance criteria, estimate scope, establish the Definition of Done, and identify dependencies and risks. Planning creates an actionable roadmap with prioritized backlog and milestone dates.

3. **Execution**: Manage day-to-day delivery through daily standups, weekly syncs, and a project board (Backlog → Ready → In Progress → In Review → QA → Done). Quality is embedded via unit and integration tests, CI/CD automation, code reviews, and manual QA. Risks are tracked in a register and reviewed weekly with escalation paths for blockers.

4. **Release**: Standardize deployments to production with pre-release checklists, smoke test verification, documented rollback plans, and clear release notes. Patch, minor, and major releases are distinguished, with post-deployment verification and stakeholder communication.

5. **Close & Retrospective**: Capture learnings through structured retrospectives covering what went well, what could improve, and concrete action items with owners and due dates. These improvements feed back into the backlog and are tracked through weekly syncs, creating a continuous improvement culture.

## Complete Documentation

| Document | Purpose |
|----------|---------|
| [OctoAcme Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to our approach, core roles, key artifacts, and lifecycle |
| [OctoAcme Project Initiation Guide](octoacme-project-initiation.md) | Validate business need, align stakeholders, and create lightweight plan |
| [OctoAcme Project Planning](octoacme-project-planning.md) | Break work into shippable increments and align timelines |
| [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day execution, quality, testing, and progress tracking |
| [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| [OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize releases and deployments to production |
| [OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [OctoAcme Personas](octoacme-roles-and-personas.md) | Define typical roles and responsibilities |

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications to enable teams to deliver on commitments efficiently
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success to maximize customer value and impact
- **Developers**: Implement features and collaborate on design and testability to deliver reliable, maintainable code
- **QA/Testing**: Validate quality and acceptance criteria to ensure features meet standards before release
- **Stakeholders**: Provide inputs, approvals, and strategic direction

See [OctoAcme Personas](octoacme-roles-and-personas.md) for detailed role definitions and responsibilities.

## Communication & Cadence

OctoAcme maintains consistent communication across all project phases:

- **Daily standups** (15 min): Focus on progress, blockers, and dependencies
- **Weekly PM + PdM sync**: Alignment on priorities, risks, and strategic decisions
- **Twice-weekly team standups**: Delivery team coordination during active execution
- **Weekly delivery sync**: Progress updates, flagged risks, and blocker escalation
- **Monthly stakeholder updates**: Status reports and strategic alignment
- **Ad-hoc escalations**: Follow escalation paths (team-level → PM → Product Lead → Sponsor)

A single source of truth—the project README and charter—keeps all teams synchronized, reducing confusion and ensuring transparency.

## Quality & Testing Strategy

Quality is embedded throughout execution:

- **Unit tests** for new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI
- **Manual QA** for feature acceptance when needed
- **Automated CI/CD** for tests, linting, and security checks before PR review

Small, reviewable pull requests (≤400 lines) with clear descriptions and acceptance criteria enable efficient code review and testing.

## How to Use These Docs

**New to OctoAcme?** Start with [OctoAcme Project Management Overview](octoacme-project-management-overview.md) for context on our principles, roles, and overall approach.

**Starting a new project?** Follow the sequence:
1. [OctoAcme Project Initiation Guide](octoacme-project-initiation.md) — validate and authorize
2. [OctoAcme Project Planning](octoacme-project-planning.md) — create your roadmap
3. [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md) — manage day-to-day work
4. [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md) — identify and mitigate risks
5. [OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md) — prepare for production
6. [OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — capture learnings

**Handling risks or escalations?** Reference [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md) for risk register templates, escalation paths, and stakeholder communication strategies.

**Need role clarity?** See [OctoAcme Personas](octoacme-roles-and-personas.md) for detailed descriptions of responsibilities, goals, and typical communication patterns for each role.

## Contributing to These Docs

To propose updates or new process documents, open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template. Provide a summary of your proposed content, rationale, and suggested text. All updates should align with OctoAcme's core principles and be reviewed with relevant stakeholders.
