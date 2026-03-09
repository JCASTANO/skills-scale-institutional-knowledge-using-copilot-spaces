# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
  - **QA column**: Work enters QA after developer implementation is complete and the PR is merged. The **QA Lead** owns this column and is responsible for executing or coordinating test execution against the agreed acceptance criteria and Definition of Done. An item moves to Done only after the QA Lead provides explicit sign-off.
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
  - For UI changes, request review from the UX Designer to validate design fidelity

## Handoffs
Clear handoffs reduce dropped work and ambiguity at transition points:

| Handoff | From | To | Sign-off |
|---|---|---|---|
| Dev → QA | Developer | QA Lead | QA Lead confirms AC are met and all tests pass |
| QA → Release | QA Lead | Project Manager / SRE | QA Lead issues written sign-off; SRE confirms deployment readiness |
| Release → Support | Project Manager / SRE | Customer Support Liaison | Support Liaison confirms readiness (runbooks, release notes, known issues reviewed) |

All sign-offs should be recorded in the release checklist or project board before moving to the next stage.

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
