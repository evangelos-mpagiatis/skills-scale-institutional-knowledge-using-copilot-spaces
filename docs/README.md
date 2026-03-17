# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This README serves as the entry point for all process documentation covering how OctoAcme plans, executes, delivers, and continuously improves its projects.

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that spans five phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Every project begins with a lightweight one-pager capturing the problem statement, SMART goals, success metrics, and stakeholder alignment before any planning work begins. Clear ownership is central to the model — each project has a named **Project Manager (PM)** responsible for delivery coordination and a **Product Manager (PdM)** who owns the product vision and backlog prioritization. Developers implement features against well-defined acceptance criteria, while QA/Testing validates quality. This role clarity ensures accountability across the full delivery lifecycle.

Planning translates approved initiatives into actionable backlogs using T-shirt sizing or story points, with a defined **Definition of Done (DoD)** and a release milestone map. Dependencies and risks are captured in a **Risk Register** (tracking ID, impact, likelihood, owner, and mitigation) and reviewed weekly. Execution is managed through a **GitHub Projects** board with columns spanning Backlog through Done, supported by small pull requests (≤ 400 lines), CI-enforced tests and linting, and a minimum one-approval policy before merging. A multi-level **blocker escalation path** (team → PM → Product Lead → Sponsor) ensures issues are surfaced and resolved at the right level without delay.

Communication follows a predictable cadence designed to keep stakeholders informed and teams unblocked. Delivery teams hold **daily standups** (15 min) focused on progress and blockers, while a **weekly delivery sync** tracks overall progress, risks, and decisions. PMs and PdMs align weekly, and stakeholders receive **monthly updates**. Risk and status communication uses standardized templates — weekly status updates cover progress, next steps, blockers, and decisions needed — while incident communication follows a structured triage and post-incident retrospective process. A single source of truth (project README or release doc) is maintained for stakeholder-facing status.

Quality assurance is embedded throughout the lifecycle rather than treated as a final gate. Unit tests, integration tests, and end-to-end smoke tests are required, with security scanning integrated into CI. Pre-release requirements include passing CI and security scans, drafted release notes, and a documented rollback plan. After each sprint, release, or incident, the team runs a **timeboxed retrospective** (45–75 min) covering what went well, what could improve, and 2–3 prioritized action items with clear owners and due dates. These action items feed back into the project backlog, creating a continuous improvement loop that compounds over time.

## Process Documentation

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
