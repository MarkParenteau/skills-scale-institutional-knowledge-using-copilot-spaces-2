# OctoAcme — Role Interaction Matrix

This document provides a RACI-lite overview of who is **Responsible (R)**, **Accountable (A)**, **Consulted (C)**, or **Informed (I)** for key activities across the OctoAcme project lifecycle.

See [Roles & Personas](./octoacme-roles-and-personas.md) for full role descriptions.

---

## Key

| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome and has final sign-off |
| **C** | Consulted — provides input before or during the activity |
| **I** | Informed — notified of outcomes or decisions |

---

## Initiation

| Activity | Project Manager | Product Manager | Developer | UX Designer | Business Analyst | Customer Success | DevOps / SRE |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Draft project one-pager | R | A | C | C | C | I | I |
| Stakeholder alignment | R | A | I | I | C | C | I |
| Define success metrics | C | A | I | C | R | C | I |
| Initial risk identification | R | C | C | I | C | I | C |
| Approve to move to planning | A | A | I | I | I | I | I |

---

## Planning

| Activity | Project Manager | Product Manager | Developer | UX Designer | Business Analyst | Customer Success | DevOps / SRE |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Create & prioritize backlog | C | A | C | C | R | C | I |
| Write acceptance criteria | I | C | C | C | R | I | I |
| Define Definition of Done | R | C | A | C | C | I | C |
| Effort estimation | I | C | R | C | C | I | C |
| Release plan & milestones | R | A | C | I | I | I | C |
| Identify cross-team dependencies | R | C | C | I | C | I | C |

---

## Execution & Tracking

| Activity | Project Manager | Product Manager | Developer | UX Designer | Business Analyst | Customer Success | DevOps / SRE |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Daily standup facilitation | R | I | R | R | R | I | R |
| Feature implementation | I | I | R | C | C | I | C |
| Design handoff & review | I | C | C | R | C | I | I |
| PR authoring & code review | I | I | R | C | I | I | C |
| QA / acceptance validation | C | A | C | C | R | I | I |
| Update project board | R | I | R | R | R | I | R |
| Blocker escalation | R | C | C | I | I | I | C |

---

## Risk & Communication

| Activity | Project Manager | Product Manager | Developer | UX Designer | Business Analyst | Customer Success | DevOps / SRE |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Maintain risk register | R | C | C | I | C | C | C |
| Weekly status report | R | C | I | I | I | I | I |
| Stakeholder communications | R | A | I | I | I | C | I |
| Incident response | I | I | R | I | I | C | R/A |
| Post-incident retrospective | R | C | R | I | I | C | R |

---

## Release & Deployment

| Activity | Project Manager | Product Manager | Developer | UX Designer | Business Analyst | Customer Success | DevOps / SRE |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Pre-release checklist sign-off | R | A | C | I | I | C | C |
| Deploy to staging | I | I | C | I | I | I | R |
| Run smoke tests | I | I | R | I | C | I | R |
| Deploy to production | I | I | C | I | I | I | R/A |
| Release announcement | R | A | I | I | I | R | I |
| Rollback decision | R | A | C | I | I | C | R |

---

## Retrospective

| Activity | Project Manager | Product Manager | Developer | UX Designer | Business Analyst | Customer Success | DevOps / SRE |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Facilitate retrospective | R | C | C | C | C | C | C |
| Capture action items | R | C | C | C | C | C | C |
| Assign & track follow-ups | R | I | I | I | I | I | I |
| Share learnings with stakeholders | R | A | I | I | I | C | I |

---

*Last updated: see git history. Maintained alongside [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).*
