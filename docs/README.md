# OctoAcme Project Management Docs

## Overview
OctoAcme runs projects with a lifecycle-driven, principles-led approach: Initiation to validate the problem and set success metrics, Planning to break approved work into shippable increments and identify dependencies, Execution using an iterative backlog and a disciplined PR workflow, and Release/Close with post-release verification and retrospectives. Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and each deliverable is tied to acceptance criteria and a lightweight release plan so scope and progress remain visible.

The process assigns clear personas and responsibilities to ensure ownership and coordination. Product Managers define problem statements, success metrics, and prioritization; Project Managers coordinate delivery, schedules, risks, and stakeholder communications; Developers build the work, write tests, and participate in reviews; and QA validates acceptance criteria and quality. Role clarity helps accelerate decisions, reduce single-person risk, and provides a clear escalation path for blockers.

Communication is structured and regular: short daily standups for progress and blockers, a weekly delivery sync for progress and risks, scheduled demos at sprint or milestone ends, and monthly stakeholder updates for broader visibility. Risks and incidents are tracked in a Risk Register and use defined escalation paths (team → PM → Product Lead → Sponsor) and incident playbooks. These docs also include templates to keep status and decisions consistent.

Quality assurance is integrated into delivery: small, testable PRs linked to issues and acceptance criteria, automated CI for tests and linting, security scans, unit/integration/end-to-end smoke tests for critical flows, and manual QA where needed. Releases follow pre-release checklists, rollback plans, and post-deploy smoke tests. Retrospectives capture learnings and action items so QA and delivery practices continuously improve.

## Process documentation (docs/)
- OctoAcme Project Management Overview
  - octoacme-project-management-overview.md — High-level introduction to OctoAcme’s approach, lifecycle, roles, and key artifacts.
- OctoAcme Project Initiation Guide
  - octoacme-project-initiation.md — How to validate a project idea, create a one-pager, and reach a go/no-go decision.
- OctoAcme Project Planning
  - octoacme-project-planning.md — Break approved initiatives into a prioritized backlog, estimates, DoD, and release plan.
- OctoAcme Execution & Tracking
  - octoacme-execution-and-tracking.md — Day-to-day team rhythm, PR conventions, boards, and execution checklists.
- OctoAcme Risk Management & Communication
  - octoacme-risks-and-communication.md — Risk register format, communication templates, and escalation paths.
- OctoAcme Release & Deployment Guide
  - octoacme-release-and-deployment.md — Release types, pre-release requirements, deployment checklist, and rollback playbook.
- OctoAcme Retrospective & Continuous Improvement
  - octoacme-retrospective-and-continuous-improvement.md — Retrospective structure, action item tracking, and improvement culture.
- OctoAcme Roles and Personas
  - octoacme-roles-and-personas.md — Role summaries and responsibilities for Developers, PMs, PdMs, and QA.

## Quick start
- New to OctoAcme projects? Start with the Project Management Overview.
- Initiating a new project? Complete the Project One-pager and follow the Project Initiation Guide.
- Running a project? Use the Execution & Tracking guide for board and PR conventions, and check the Risk Management doc for escalation templates.
- Need a process change? Use the repository issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Acceptance criteria
- Content aligns with existing process docs
- Update improves clarity and discoverability
- README placed at docs/README.md and linked to the existing docs
