# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner (assign to a specific role — see [Roles and Personas](octoacme-roles-and-personas.md))
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution (all roles contribute; Project Manager owns the register)
- Assess: estimate impact and likelihood (Project Manager with input from QA Lead and SRE for technical risks)
- Mitigate: reduced via actions, contingency plans (assigned to the risk owner by role)
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- **Customer Support Liaison** should be included in stakeholder comms for any user-facing changes
- **SRE** should be informed of any upcoming changes with infrastructure or reliability impact

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication (owned by SRE; coordinated with Project Manager and Customer Support Liaison)
- Triage summary
- Actions being taken
- Expected timeline
- Customer-facing impact and support talking points (Customer Support Liaison)
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> Scrum Master (removes blockers) -> Project Manager -> Product Lead -> Sponsor
- For reliability/infrastructure incidents: SRE on-call -> Project Manager -> Engineering Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- For user-facing service degradation: Customer Support Liaison notifies support team; SRE leads technical response
- For unresolved quality risks: QA Lead escalates to Project Manager and Product Manager
