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

## QA / Testing Lead

### Role Summary
The QA / Testing Lead owns the quality assurance strategy and execution across the project lifecycle. They ensure that features meet acceptance criteria and that the product is fit for release, coordinating manual and automated testing with developers, the Product Manager, and the Scrum Master.

### Responsibilities
- Define and maintain the overall test strategy (unit, integration, end-to-end, manual acceptance)
- Review acceptance criteria with the Product Manager and flag ambiguities before development starts
- Own QA sign-off on features before they move to the Done column or are included in a release
- Maintain and improve automated test suites in coordination with developers
- Track and triage defects; prioritize bug fixes with the Product Manager
- Validate release readiness and participate in go/no-go decisions

### Goals
- Prevent defects from reaching production
- Reduce regression risk through automated coverage
- Ensure acceptance criteria are testable and verifiable

### Typical Communication
- Sprint planning and refinement sessions (to review acceptance criteria)
- QA status updates in the weekly delivery sync
- Defect reports and test results shared via project board or test management tool
- Release readiness sign-off documented in the release checklist

### Interactions with Existing Roles and Artifacts
- **Developers**: Collaborates on test coverage, code reviewability, and reproducing defects. Reviews PRs for testability.
- **Product Managers**: Validates acceptance criteria are testable; flags gaps before work begins. References the Definition of Done.
- **Project Managers**: Reports QA status and risks; flags scope creep or quality trade-off decisions to the risk register.
- **Key artifacts**: Acceptance criteria, Definition of Done, test plans, defect log, release checklist.

### Lifecycle Engagement
- **Planning**: Define test strategy and review acceptance criteria
- **Execution**: Own the QA column on the project board; run and maintain tests
- **Release**: Sign off on release readiness; validate smoke tests on staging
- **Retrospective**: Review defect trends and test coverage gaps for improvement actions

---

## UX / UI Designer

### Role Summary
The UX / UI Designer ensures that OctoAcme features are usable, accessible, and aligned with user needs. They bridge the gap between business requirements and user experience, delivering wireframes, prototypes, and design specifications that guide development.

### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Produce wireframes, prototypes, and high-fidelity designs for review and handoff
- Define UX acceptance criteria and review implemented UI against designs
- Collaborate with the Product Manager to align design with product goals
- Maintain and evolve the design system or style guide
- Ensure accessibility standards are considered in design and implementation

### Goals
- Deliver clear, user-validated designs that reduce rework during development
- Improve product usability and user satisfaction
- Reduce ambiguity in feature specs through visual artifacts

### Typical Communication
- Design reviews with the Product Manager and developers before implementation begins
- Handoff documentation (design specs, annotated prototypes) in the project repo or design tool
- Usability feedback shared in sprint reviews and planning sessions
- Async feedback via PR comments on UI changes

### Interactions with Existing Roles and Artifacts
- **Developers**: Provides design specs and annotated prototypes; reviews implemented UI for fidelity and accessibility.
- **Product Managers**: Collaborates on user stories, feature requirements, and success metrics. Co-owns acceptance criteria for user-facing features.
- **Project Managers**: Communicates design review timelines and flags dependencies that affect the project plan.
- **Key artifacts**: Wireframes, prototypes, design specs, acceptance criteria, Definition of Done.

### Lifecycle Engagement
- **Initiation**: Contribute UX perspective to problem framing and success metrics
- **Planning**: Produce initial wireframes and define UX acceptance criteria
- **Execution**: Conduct design reviews; answer developer questions; iterate on designs
- **Release**: Review production UI against designs; sign off on UX readiness
- **Retrospective**: Share usability findings and design improvement opportunities

---

## Technical Writer

### Role Summary
The Technical Writer owns the accuracy, completeness, and accessibility of all project and product documentation. They ensure that process docs, release notes, runbooks, and user-facing guides are up-to-date and discoverable.

### Responsibilities
- Author and maintain process documentation (guides, runbooks, onboarding materials)
- Draft and review release notes in collaboration with developers and the Product Manager
- Ensure documentation aligns with implemented features and is updated with each release
- Identify and close gaps in existing documentation
- Establish and uphold documentation standards and templates
- Support onboarding by maintaining clear role guides and getting-started docs

### Goals
- Ensure all stakeholders can find accurate, current documentation
- Reduce onboarding time for new team members
- Minimize incidents caused by outdated or missing runbooks

### Typical Communication
- Documentation review sessions with developers and the Product Manager before release
- Release notes collaboration with the QA Lead and Product Manager
- Async feedback via PR/doc comments
- Documentation status updates in the weekly delivery sync

### Interactions with Existing Roles and Artifacts
- **Developers**: Gathers technical details for runbooks and API docs; reviews PRs that affect documented behavior.
- **Product Managers**: Aligns on feature descriptions, user-facing messaging, and release notes content.
- **Project Managers**: Flags documentation-related risks and tracks doc completion in the project plan.
- **Key artifacts**: Release notes, runbooks, process docs, onboarding guides, Definition of Done.

### Lifecycle Engagement
- **Planning**: Identify documentation work as part of sprint scope; add doc tasks to backlog
- **Execution**: Draft documentation in parallel with feature development
- **Release**: Finalize and publish release notes; ensure runbooks are current
- **Retrospective**: Audit documentation accuracy and capture improvement actions

---

## Scrum Master / Delivery Lead

### Role Summary
The Scrum Master / Delivery Lead facilitates agile ceremonies, removes impediments, and coaches the team on delivery practices. They protect the team's focus and ensure a sustainable, predictable delivery cadence.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers; escalate impediments to the Project Manager when necessary
- Coach the team on agile principles and continuous improvement
- Track and communicate team velocity and sprint progress
- Coordinate cross-team dependencies and communication with the Project Manager
- Shield the team from unplanned work and scope changes mid-sprint

### Goals
- Maintain a healthy, sustainable team delivery rhythm
- Reduce blockers and impediments that slow delivery
- Build a culture of continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Blocker and impediment log shared with the Project Manager
- Velocity and capacity reports
- Retrospective action items tracked in the project backlog

### Interactions with Existing Roles and Artifacts
- **Developers**: Removes blockers and facilitates collaborative problem-solving; coaches on agile practices.
- **Product Managers**: Coordinates backlog refinement and helps protect sprint scope.
- **Project Managers**: Aligns on timelines, capacity, and escalation of cross-team impediments.
- **Key artifacts**: Sprint board, velocity metrics, retrospective action items, risk register.

### Lifecycle Engagement
- **Planning**: Facilitate sprint planning and ensure backlog items are refined and ready
- **Execution**: Own daily standups; track and remove blockers
- **Release**: Coordinate release sprint ceremonies and ensure readiness
- **Retrospective**: Facilitate retrospective sessions and drive action item follow-through

---

## Customer Support Liaison

### Role Summary
The Customer Support Liaison represents the voice of the customer within the project team. They surface user-reported issues, escalate critical bugs, and ensure that support readiness is achieved before and after each release.

### Responsibilities
- Gather and prioritize user feedback and bug reports from support channels
- Escalate critical or frequently reported issues to the Product Manager and Project Manager
- Validate that release notes and support documentation are accurate and complete before release
- Coordinate with developers on root cause analysis for user-reported defects
- Ensure the support team is prepared for new releases (training, known issues, workarounds)
- Provide post-release feedback on user adoption and issue trends

### Goals
- Reduce time-to-resolution for user-reported issues
- Ensure users receive timely, accurate communication about new features and known issues
- Close the feedback loop between end users and the product team

### Typical Communication
- Weekly sync with the Product Manager and Project Manager on top user issues
- Support readiness sign-off shared in the release checklist
- Post-release issue triage with developers and the QA Lead
- User feedback summaries shared in sprint reviews

### Interactions with Existing Roles and Artifacts
- **Developers**: Provides detailed bug reports; coordinates on hotfix prioritization.
- **Product Managers**: Feeds user feedback into backlog prioritization; validates feature decisions against user needs.
- **Project Managers**: Reports support risk and readiness status; contributes to communication plans.
- **Key artifacts**: Bug/issue log, release notes, communication plan, risk register.

### Lifecycle Engagement
- **Planning**: Surface known user pain points to inform backlog prioritization
- **Execution**: Monitor support channels and escalate newly discovered issues
- **Release**: Sign off on support readiness; review release notes and known issues
- **Retrospective**: Share support trends and user feedback as input for improvement actions

---

## Site Reliability Engineer (SRE) / Operations

### Role Summary
The SRE / Operations role owns system reliability, performance, and observability. They ensure that OctoAcme services meet uptime and latency targets, and that deployment and incident response processes are safe and efficient.

### Responsibilities
- Define and monitor Service Level Objectives (SLOs) and error budgets
- Build and maintain observability tooling (dashboards, alerting, logging)
- Own and maintain incident response runbooks and on-call rotations
- Review deployments for operational risk and participate in go/no-go decisions
- Conduct post-incident reviews and drive reliability improvement actions
- Collaborate with developers on infrastructure and deployment automation

### Goals
- Maintain agreed uptime and reliability targets
- Reduce mean time to detection (MTTD) and mean time to recovery (MTTR)
- Build confidence in deployment processes through automation and runbooks

### Typical Communication
- Deployment readiness reviews before releases
- Incident notifications and status updates during incidents
- Post-incident review reports shared with the team
- SLO/reliability dashboards visible to all stakeholders

### Interactions with Existing Roles and Artifacts
- **Developers**: Reviews infrastructure and deployment changes; advises on observability instrumentation.
- **Product Managers**: Shares reliability data that informs prioritization of reliability improvements.
- **Project Managers**: Provides deployment risk assessment; flags reliability risks in the risk register.
- **Key artifacts**: Deployment checklist, runbooks, incident log, risk register, SLO dashboards.

### Lifecycle Engagement
- **Planning**: Identify reliability and operational risks; ensure runbooks are scoped
- **Execution**: Review deployment-related PRs and infrastructure changes
- **Release**: Lead or review deployment execution; participate in go/no-go decision
- **Retrospective**: Drive post-incident reviews; surface reliability improvement actions

---

## Cross-Role RACI Matrix

The table below clarifies ownership (Responsible / Accountable / Consulted / Informed) for core recurring activities. Use this as a quick reference to reduce ambiguity and prevent gaps.

| Activity | Product Manager | Project Manager | Scrum Master | Developers | QA Lead | UX Designer | Tech Writer | Support Liaison | SRE |
|---|---|---|---|---|---|---|---|---|---|
| Define success metrics | **A/R** | C | C | C | C | C | I | C | I |
| Prioritize backlog | **A/R** | C | C | C | C | C | I | C | I |
| Maintain project plan | I | **A/R** | C | I | I | I | I | I | I |
| Own risk register | C | **A/R** | C | C | C | I | I | C | C |
| Define Definition of Done | C | C | **A/R** | R | R | C | C | I | C |
| QA sign-off | C | I | I | C | **A/R** | C | I | I | I |
| Release notes creation | C | I | I | C | C | I | **A/R** | C | I |
| Deployment execution | I | C | I | R | C | I | I | I | **A/R** |
| Incident escalation | C | C | C | R | C | I | I | C | **A/R** |
| Retrospective action tracking | C | C | **A/R** | C | C | C | C | C | C |

**Key:** A = Accountable (one owner), R = Responsible (does the work), C = Consulted, I = Informed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

