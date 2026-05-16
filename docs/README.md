# OctoAcme Project Management Docs

This folder contains OctoAcme's program and project management process documents. Use this README as the single source of truth for process artifacts, key workflows, roles, and templates.

## Overview
OctoAcme follows a customer-first, iterative delivery approach. Projects begin with a lightweight One‑pager during Initiation to align problem, objectives, and success metrics. During Planning teams break work into shippable increments, estimate effort, and identify dependencies and risks. Execution uses small pull requests, CI checks, and regular team rhythms (daily standups, weekly delivery syncs) to maintain momentum and visibility. Releases follow pre-release checklists, deployment automation when possible, and documented rollback/incident playbooks. Retrospectives capture learnings and feed continuous improvements back into the backlog.

Core roles include Project Manager (coordinates delivery and risks), Product Manager (defines outcomes and prioritization), Developers (build and test), and QA (validate acceptance). Communication cadences are defined (standups, syncs, stakeholder updates) and a risk register and escalation path ensure issues are surfaced and resolved. Quality practices combine automated tests, CI security scans, and manual acceptance testing where needed.

This README links to each process document below and provides quick guidance for newcomers and maintainers.

## Documents
- [Project Management Overview](./octoacme-project-management-overview.md) — concise intro to OctoAcme's approach, principles, lifecycle, and artifacts.
- [Project Initiation Guide](./octoacme-project-initiation.md) — one-pager template, when to use initiation, and decision gates.
- [Project Planning](./octoacme-project-planning.md) — backlog templates, estimation, DoD, and risk/dependency handling.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team rhythm, PR workflow, testing, metrics, and blocker escalation.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — risk register structure, stakeholder comms, and escalation paths.
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — release types, pre-release requirements, deployment checklist, and rollback playbook.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — running retros, action tracking, and improvement culture.
- [Roles & Personas](./octoacme-roles-and-personas.md) — role summaries and responsibilities for common project personas.

## How to use
- Start here when you join a project: read the Overview and the relevant stage doc (Initiation → Planning → Execution → Release → Retrospective).
- Keep the Project One-pager and project README in the project repo up to date; use the templates in the docs as needed.
- Propose changes by creating an issue using the "Add Content to Project Management Process Docs" template and include the target doc (or choose "<new document>" for a new file).
- For Copilot Spaces: add this repo and the docs folder as a source so the Space can index these documents.

## Quick checklist for maintainers
- [ ] Ensure links stay accurate when renaming files
- [ ] Update the summary paragraphs if processes change
- [ ] Add new templates/checklists to docs/ and link them here
