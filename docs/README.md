# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured, five-phase project lifecycle: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Every project begins with a lightweight Project One-pager that defines the problem statement, SMART objectives, success metrics, stakeholders, and a high-level timeline. A formal decision gate ensures a project only moves into planning once success metrics are clear, stakeholders are aligned, and team availability is confirmed. During planning, work is broken into shippable increments with a prioritized backlog, a Definition of Done, a release milestone map, and a Risk Register to capture dependencies, impact, likelihood, and mitigation plans.

OctoAcme's core team is built around four key personas: the **Project Manager (PM)**, who coordinates delivery, schedules, and cross-team communications; the **Product Manager (PdM)**, who owns the product vision, backlog prioritization, and outcome measurement; **Developers**, who implement features, write tests, and participate in design and code reviews; and **QA/Testing**, who validate quality and acceptance criteria. Each role has clearly defined responsibilities and communication norms — developers engage primarily through daily standups and PR reviews, while PMs and PdMs align weekly on roadmaps and stakeholder briefings. This clear ownership model minimizes ambiguity and supports accountability across the full delivery team.

OctoAcme's **communication strategy** is built around a consistent cadence and structured templates. The team runs daily 15-minute standups focused on progress, blockers, and dependencies, along with weekly delivery syncs and end-of-sprint demos. Stakeholders receive monthly updates and ad-hoc escalations as needed. Risk and status are communicated via a standard weekly template covering progress, next steps, risks/blockers, and decisions needed. Escalation paths are well-defined — moving from team-level triage, to PM escalation to the Product Lead, up to sponsor-level intervention for business-impacting issues — ensuring problems are surfaced and resolved at the right level.

**Quality assurance and release practices** are deeply embedded throughout the workflow. During execution, CI pipelines enforce automated unit, integration, and security checks on every pull request, which are kept small (≤400 lines when possible) and require at least one approval before merging. Before any release — categorized as Patch, Minor, or Major — all acceptance criteria must be met, CI and security scans must pass, release notes must be drafted, and smoke tests must be prepared. A rollback and incident playbook ensures fast recovery if a deployment fails. After each sprint or release, a retrospective captures what went well, what can be improved, and produces 2–3 actionable improvements tracked in the project backlog, fostering a continuous improvement culture across the team.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Introduction to how OctoAcme runs projects, core principles, and key artifacts
- [Project Initiation](octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning](octoacme-project-planning.md) — Turning an approved initiative into an actionable plan and backlog for delivery
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Managing day-to-day execution and tracking progress toward milestones
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardized process for releasing features to production
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and converting them into actionable improvements
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identifying, managing, and communicating risks and dependencies
- [Roles & Personas](octoacme-roles-and-personas.md) — Defined roles and responsibilities used across OctoAcme projects
