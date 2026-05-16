# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (suggested additions)

### Technical Program Manager (TPM)
Role Summary  
Technical Program Managers coordinate large cross-functional initiatives that span multiple teams, timelines, and technical domains.

Responsibilities
- Drive cross-team planning and alignment for multi-team initiatives
- Maintain milestone schedules, risk logs, and integration points
- Facilitate technical trade-off discussions and coordinate dependencies
- Track cross-team blockers and ensure follow-through on mitigation actions

How they interact with existing roles
- Works closely with Project Managers to align schedules and risks
- Partners with Product Managers on cross-team prioritization trade-offs
- Coordinates with engineering leads and SRE for integration and operational readiness

When to involve
- For projects that span multiple teams, subsystems, or have complex integration requirements

---

### Release Manager
Role Summary  
Release Managers own release coordination, pre-release verification, and post-release follow-ups for non-trivial releases.

Responsibilities
- Define and drive release checklists and gating criteria
- Coordinate release windows, staging verification, and rollback plans
- Ensure release notes, migration steps, and stakeholder communications are ready
- Validate production readiness with SRE and QA

How they interact with existing roles
- Works with PMs and PdMs to schedule release timing
- Partners with Developers and QA to confirm acceptance criteria and CI status
- Escalates operational concerns to SRE and Project Manager as needed

When to involve
- For releases spanning multiple services, significant migrations, or production-impacting changes

---

### Security Engineer (Security SME)
Role Summary  
Security Engineers ensure that security considerations are integrated into design, development, and release processes.

Responsibilities
- Conduct threat modeling and security reviews for new features
- Review code and third-party dependencies for vulnerabilities
- Define security acceptance criteria and remediation SLAs
- Support incident response and post-incident analysis

How they interact with existing roles
- Reviews designs with Developers and Product Managers early in planning
- Works with CI/SRE teams to ensure automated security scanning
- Advises Project Managers on security-related risks and mitigations

When to involve
- For projects that touch sensitive data, require compliance, or introduce new architectures

---

### UX Researcher / Designer
Role Summary  
UX Researchers/Designers own user research, design validation, and usability outcomes for features.

Responsibilities
- Run research studies and usability tests to validate assumptions
- Produce wireframes, prototypes, and acceptance criteria that reflect user needs
- Advocate for accessibility and user-centered design in planning and reviews

How they interact with existing roles
- Collaborates with Product Managers to define user-focused success metrics
- Provides design artifacts to Developers and QA for implementation and verification
- Joins demos, planning, and retrospective discussions to close the feedback loop

When to involve
- During problem discovery, design validation, and before major UI changes

---

### Data Analyst / Analytics Owner
Role Summary  
Data Analysts own measurement, instrumentation, and metrics needed to evaluate feature success.

Responsibilities
- Define analytics events, dashboards, and success metrics for projects
- Validate data quality and implement instrumentation plans
- Produce analysis to inform prioritization and post-release decisions

How they interact with existing roles
- Works with Product Managers to define success metrics and experiments
- Coordinates with Developers to implement instrumentation and with QA to validate data
- Shares findings in demos, retrospectives, and stakeholder updates

When to involve
- During planning for features that require clear measurement or experimentation

---

### Site Reliability Engineer (SRE) / Operations
Role Summary  
SREs ensure systems are operable, reliable, and performant in production.

Responsibilities
- Define SLOs/SLIs and support load testing and capacity planning
- Create operational runbooks and incident playbooks for releases
- Assist in post-release monitoring, alerts tuning, and root cause analysis

How they interact with existing roles
- Works with Release Manager and Developers for deployment/rollback readiness
- Partners with Project Managers on operational risk and mitigation plans
- Provides on-call support and incident coordination when needed

When to involve
- For services that require production reliability, scaling, or operational coordination

---

### Stakeholder Liaison / Business Analyst
Role Summary  
Stakeholder Liaisons represent external or cross-organizational stakeholders to ensure requirements and constraints are captured.

Responsibilities
- Collect requirements from stakeholders and ensure alignment with project scope
- Surface risks tied to business operations, legal, or third-party integrations
- Coordinate required approvals and compliance checks

How they interact with existing roles
- Works with Product Managers and Project Managers to translate stakeholder needs into backlog items
- Escalates conflicting priorities and clarifies acceptance criteria

When to involve
- When projects require approvals, cross-org coordination, or have external dependencies

---

## Guidance for maintainers
- Add these personas where the Roles & Personas doc lists core roles; keep each entry short and focused.
- Encourage teams to adapt persona presence to project needs (not every project needs every persona in every meeting).
- Consider adding a short "When to involve" note for each persona to guide invitations to key ceremonies.
- When adding checklists/templates that reference personas, keep examples minimal and link to more detailed templates in docs/ as needed.
