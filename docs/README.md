# OctoAcme Project Management Docs

## Overview
OctoAcme follows a structured, scalable project management approach designed to deliver customer value iteratively while maintaining clear ownership, accountability, and risk management. These docs provide a single landing page to navigate the project lifecycle guidance, roles, artifacts, and decision gates.

## Project Management Process Summary
OctoAcme runs projects with a lightweight, iterative lifecycle that starts with a formal initiation (one‑pager, stakeholder alignment, and a go/no‑go decision), moves into detailed planning (kickoff, prioritized backlog, estimates, Definition of Done), proceeds through execution and tracking (sprint delivery, PRs, CI, and demos), and finishes with release and retrospective activities. The documentation emphasizes small, incremental deliveries, measurable success criteria, and clear ownership—each project has a named Project Manager and Product Lead—so decisions and accountabilities are explicit throughout the lifecycle.

Work is organized around a practical workflow: a project board with Backlog → Ready → In Progress → In Review → QA → Done columns, a backlog item template with acceptance criteria and estimates, and timeboxed sprint planning that only pulls items meeting the DoD. The pull‑request conventions push for small PRs (<= 400 lines when possible), required CI checks and security scans before review, inclusion of issue links and acceptance criteria in PR descriptions, and at least one approval before merge. Planning artifacts (one‑pagers, release plans, risk registers) and a release checklist are maintained in the repo so the project’s source of truth is versioned and discoverable.

Communication is structured and frequent: short daily standups to surface progress and blockers, weekly delivery syncs to review progress and risks, regular demos at the end of sprints or milestones, and monthly or milestone‑based stakeholder updates. The docs include templates for weekly status and incident communications and an escalation path (team → PM → Product Lead → Sponsor) for unresolved blockers.

Quality assurance and risk management are woven into both day‑to‑day work and releases. The QA approach mandates unit and integration tests, end‑to‑end smoke tests for critical flows, manual QA for acceptance where needed, and security scans in CI. Releases follow a checklist (staging smoke tests, rollback plan, post‑deploy verification, release notes) and an incident/rollback playbook is available for failures. Progress and health are monitored via velocity/burndown and dashboards for errors, latency, and usage, and retrospectives capture actionable improvements that are tracked back into the backlog to continuously raise delivery quality.

## Quick Start
- New project? Start with: docs/octoacme-project-initiation.md
- In planning? See: docs/octoacme-project-planning.md
- Executing? Reference: docs/octoacme-execution-and-tracking.md
- Ready to ship? Check: docs/octoacme-release-and-deployment.md
- Sprint over? Run a retrospective: docs/octoacme-retrospective-and-continuous-improvement.md

## Core Principles
- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has named roles with clear accountability
- Data-informed decisions: measure impact and iterate based on evidence
- Psychological safety: encourage feedback and learning

## Process Documentation (links)
- docs/octoacme-project-management-overview.md — High-level intro to roles, artifacts, cadence
- docs/octoacme-project-initiation.md — One-pager and initiation checklist
- docs/octoacme-project-planning.md — Backlog, estimates, DoD, release planning
- docs/octoacme-execution-and-tracking.md — Team rhythm, PR workflow, CI expectations
- docs/octoacme-risks-and-communication.md — Risk register, communication templates, escalation
- docs/octoacme-release-and-deployment.md — Release checklist and rollback playbook
- docs/octoacme-retrospective-and-continuous-improvement.md — Retrospectives and action tracking
- docs/octoacme-roles-and-personas.md — Role definitions and responsibilities

## Key Artifacts & Decision Gates
- Project One-pager / Charter
- Roadmap & Release Plan
- Sprint Backlog & Acceptance Criteria
- Risk Register
- Retrospective action items
Decision gate to move from Initiation → Planning: clear success metrics, stakeholder alignment, and confirmed team availability.

## When to use each document
- Use the Initiation guide to validate new ideas and create the one-pager.
- Use Planning to produce a prioritized backlog and release plan.
- Use Execution & Tracking during day-to-day delivery and sprint work.
- Use Release & Deployment when preparing to ship and for rollback playbooks.
- Use Retrospective docs to convert learnings into backlog action items.
