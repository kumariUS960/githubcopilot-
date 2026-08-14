# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This folder contains the core process documents and checklists the team uses to run projects from initiation through retrospective. Use this README as the single entry point to find the right guidance, artifacts, and templates for each phase of the project lifecycle.

OctoAcme follows an iterative, outcome-driven project management approach that moves work through clear lifecycle stages: Initiation, Planning, Execution, Release, and Retrospective. Initiation centers on a concise Project One‑pager to validate the problem, success metrics, stakeholders, and go/no‑go. Planning breaks approved initiatives into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done; release planning and milestone maps are produced alongside a risk register and dependency tracking.

Day‑to‑day workflows are lightweight and practical: teams use a project board with Backlog → Ready → In Progress → In Review → QA → Done columns, and a pull request workflow that favors small PRs, explicit acceptance criteria, and CI/lint gating before review. Branching and PR conventions plus automated tests are required, and repositories should document CI and test requirements. A consistent checklist and demo cadence help ensure predictable delivery and visibility.

Roles and communication are clearly defined to ensure ownership and alignment. Core personas include a named Project Manager (PM) who coordinates delivery and communications, a Product Manager/Product Lead (PdM) who defines outcomes and prioritizes the backlog, developers, and QA/testing personnel; stakeholders provide approvals and context. Cadence is frequent and structured: daily standups for blockers and progress, weekly delivery syncs and PM–PdM check‑ins, end‑of‑sprint demos, and monthly stakeholder updates. Quality assurance includes unit/integration/e2e smoke tests, security scanning in CI, manual QA as needed, and a deployment checklist with rollback and incident playbooks. Progress and health are measured with velocity, burndown, dashboards, and a living Risk Register.

## Documentation by Project Phase (quick links)
- Initiation: octoacme-project-initiation.md — Project one‑pager, stakeholder alignment, go/no‑go
- Planning: octoacme-project-planning.md — Backlog, estimates, Definition of Done, risk register
- Execution: octoacme-execution-and-tracking.md — Team rhythm, PR workflow, CI, reporting, escalations
- Release: octoacme-release-and-deployment.md — Release types, pre‑release checks, deployment & rollback
- Retrospective: octoacme-retrospective-and-continuous-improvement.md — Running retros, action items, follow‑up

## Cross-cutting guides
- Risk & Communication: octoacme-risks-and-communication.md — Risk register, stakeholder comms, escalation
- Roles & Personas: octoacme-roles-and-personas.md — Role descriptions and responsibilities
- Overview: octoacme-project-management-overview.md — Principles, lifecycle, key artifacts

## Quick reference — key artifacts and checklists
- Project One‑pager (Initiation) — Problem, goal, success metrics, stakeholders
- Backlog items — Title, description, acceptance criteria, estimate, owner
- Definition of Done — Conditions to consider work complete
- CI & PR checklist — Tests pass, lint, one approval, linked issue, acceptance criteria
- Deployment checklist — Staging smoke tests, backups, rollback plan, post‑deploy verification
- Risk Register — ID, impact, likelihood, owner, mitigation, status

## When to use each document
- Start with the Project Initiation guide when validating new ideas and creating the one‑pager.
- Use Project Planning to translate an approved initiative into a backlog and release plan.
- Follow Execution & Tracking for day‑to‑day development, PRs, test/CI expectations, and escalation.
- Consult Release & Deployment when preparing and executing deployments.
- Run Retrospective & Continuous Improvement after each sprint or release to capture learnings and convert them into action items.
- Use Risk & Communication and Roles & Personas whenever you need templates for stakeholder updates or to clarify responsibilities.

## Contributing
To propose updates, use the Add Content to Project Management Process Docs issue template in .github/ISSUE_TEMPLATE/. For changes to these docs, open a PR that references the relevant issue and includes the acceptance criteria checklist.
