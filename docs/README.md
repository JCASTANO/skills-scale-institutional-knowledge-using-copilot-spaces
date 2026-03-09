# OctoAcme Project Management Docs

Welcome! This README centralizes all project management process documents for the OctoAcme team. Use it to navigate to the right process, onboard quickly, or reference any part of the delivery workflow at a glance.

## Project Management Process Overview

OctoAcme follows a customer-first, iterative approach to project delivery. Every project begins with a structured **Initiation** phase — producing a lightweight one-pager that captures the problem statement, SMART goals, success metrics, and a stakeholder alignment plan — and passes a formal decision gate before moving into planning. This ensures the team only invests in work that has clear business value and measurable outcomes.

During **Planning**, the approved initiative is broken into a prioritized backlog with explicit acceptance criteria and a shared Definition of Done. Dependencies, risks, and integration points are surfaced early and captured in a risk register. Sprint planning follows a strict timebox cadence, pulling only items that are ready and well-defined. **Execution & Tracking** is governed by daily standups, weekly delivery syncs, and a project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests are kept small, linked to their issues, and require passing CI plus at least one peer approval before merging, with QA validating acceptance criteria before items are marked done.

Risks and stakeholder communication are managed continuously through a maintained risk register and a single source of truth for project status, with regular milestone-based updates delivered to each stakeholder group. **Release & Deployment** follows a standardized checklist — staging smoke tests, passing security scans, drafted release notes, and a documented rollback plan — before any change reaches production. Post-deploy verifications and an incident playbook ensure swift recovery if issues arise.

Finally, **Retrospectives** after every sprint, release, or incident convert learnings into tracked action items with clear owners and due dates, feeding back into the backlog for continuous improvement. Across all phases, four key personas drive the work: the **Project Manager** (delivery coordination, risk, communications), the **Product Manager** (outcomes and backlog prioritization), **Developers** (implementation, testing, and design), and **QA/Testing** (acceptance validation and quality assurance), supported by **Stakeholders** who provide inputs and approvals throughout.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, and key artifacts that apply to all OctoAcme projects |
| [Project Initiation Guide](octoacme-project-initiation.md) | One-pager template, stakeholder alignment, and the go/no-go decision gate |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, acceptance criteria, Definition of Done, dependencies, and release plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Team cadence, project board columns, PR workflow, quality gates, and escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, lifecycle, stakeholder updates, and single source of truth |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, and rollback/incident playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action item tracking, and continuous improvement loop |
| [Roles & Personas](octoacme-roles-and-personas.md) | Responsibilities and communication patterns for PM, PdM, Developers, QA, and Stakeholders |
