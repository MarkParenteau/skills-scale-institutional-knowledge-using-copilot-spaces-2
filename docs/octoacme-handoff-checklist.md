# OctoAcme — Handoff Checklist

Structured checkpoints for handing off work between Product Management (PdM), Project Management (PM), and Engineering across key lifecycle transitions.

See [Roles & Personas](./octoacme-roles-and-personas.md) for role descriptions and [Role Interaction Matrix](./octoacme-role-interaction-matrix.md) for a full RACI view.

---

## 1. PdM → PM: Initiation to Planning Handoff

Trigger: Project one-pager approved; ready to move from Initiation into Planning.

**Product Manager confirms:**
- [ ] Problem statement, objective, and SMART success metrics are documented in the one-pager
- [ ] Stakeholder list is complete with communication plan attached
- [ ] Initial backlog or feature list is drafted (epics are sufficient at this stage)
- [ ] Key constraints (budget, compliance, timeline) are noted
- [ ] UX Designer and Business Analyst are identified and looped in (if applicable)

**Project Manager accepts when:**
- [ ] One-pager is reviewed and approved by the sponsor
- [ ] Team resourcing is confirmed (all roles identified and available)
- [ ] Initial risk list is captured in the risk register
- [ ] Project board skeleton is created with agreed lifecycle columns
- [ ] Kickoff meeting is scheduled

---

## 2. PM + PdM → Engineering: Planning to Execution Handoff

Trigger: Kickoff completed; sprint 1 is ready to start.

**Product Manager confirms:**
- [ ] Backlog items are written with clear titles, descriptions, and acceptance criteria
- [ ] Items in "Ready" column meet the Definition of Ready (estimated, no unresolved blockers)
- [ ] UX designs are available for items that require them (Figma links in issues)
- [ ] Business Analyst has validated requirements against business objectives

**Project Manager confirms:**
- [ ] Definition of Done (DoD) is documented and agreed by the team
- [ ] Sprint cadence and ceremonies (standup, review, retro) are scheduled
- [ ] CI/CD pipeline is configured and DevOps / SRE has reviewed the deployment approach
- [ ] Risk register is up-to-date with mitigations assigned

**Engineering accepts when:**
- [ ] Developers confirm they understand the top-priority items and acceptance criteria
- [ ] DevOps / SRE has confirmed environment readiness (dev, staging)
- [ ] Any open UX or requirements questions are resolved or tracked as follow-ups

---

## 3. Engineering → QA / Release: Execution to Release Handoff

Trigger: Feature implementation complete; ready for QA sign-off and release.

**Engineering confirms:**
- [ ] All PRs for this release are merged; feature branch deleted
- [ ] CI passes (tests, linting, security scans)
- [ ] Technical documentation and inline code comments updated
- [ ] Deployment runbook or release notes drafted (hand to DevOps / SRE)

**DevOps / SRE confirms:**
- [ ] Staging deploy successful and smoke tests passed
- [ ] Rollback plan documented and validated
- [ ] Monitoring and alerting are in place for new functionality
- [ ] Deployment window scheduled (if required)

**PM / PdM confirms:**
- [ ] All acceptance criteria are verified by QA or Business Analyst
- [ ] Customer Success has been briefed on the release scope and customer-facing changes
- [ ] Release notes and stakeholder announcement are ready
- [ ] Go/no-go decision made and communicated

---

## 4. Post-Release: Retrospective & Handback

Trigger: Release deployed and monitored; ready to capture learnings.

- [ ] DevOps / SRE confirms production health metrics are stable
- [ ] Customer Success reports no critical issues from initial customer contacts
- [ ] Retrospective is scheduled (within 3–5 business days of release)
- [ ] Action items from retrospective are filed as issues with owners and due dates
- [ ] Risk register is closed or updated with resolved items
- [ ] Learnings are shared with broader team via the project README or retrospective notes

---

*Maintain this checklist alongside [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) and [octoacme-project-planning.md](./octoacme-project-planning.md).*
