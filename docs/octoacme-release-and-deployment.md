# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Release Roles

| Role | Responsibility |
|---|---|
| **Release Owner** (Project Manager) | Coordinates the release process end-to-end; makes the go/no-go call |
| **QA Lead** | Signs off that all acceptance criteria are met and tests pass |
| **SRE / Operations** | Owns deployment execution; monitors post-deploy health; leads rollback if needed |
| **Technical Writer** | Confirms release notes are complete and accurate before publishing |
| **Customer Support Liaison** | Confirms support team readiness (trained, runbooks updated, known issues documented) |
| **Product Manager** | Validates feature completeness against product requirements |

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted and reviewed by Technical Writer and Product Manager
- Rollback / mitigation plan documented and reviewed by SRE
- Smoke tests prepared and sign-off received from QA Lead
- Support readiness confirmed by Customer Support Liaison

## Deployment Checklist
- [ ] Release Owner (Project Manager) confirmed and go/no-go decision recorded
- [ ] QA sign-off received (QA Lead)
- [ ] SRE / on-call team notified of deployment window and runbook reviewed
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (SRE + QA Lead)
- [ ] Deploy to production (automated pipeline preferred; SRE leads)
- [ ] Run post-deploy verifications (SRE + QA Lead)
- [ ] Release notes published (Technical Writer)
- [ ] Announce release to stakeholders and support (Project Manager + Customer Support Liaison)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
