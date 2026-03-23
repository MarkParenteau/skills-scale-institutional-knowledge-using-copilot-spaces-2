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

## UX Designer

### Role Summary
UX Designers create user flows, wireframes, and prototypes that ensure the product is intuitive, accessible, and user-centric. They bridge user research insights and technical implementation by collaborating closely with Product Managers and Developers.

### Responsibilities
- Conduct or synthesize user research and usability studies
- Design user flows, wireframes, and interactive prototypes
- Define and document UX acceptance criteria alongside Product Managers
- Participate in backlog refinement to ensure feasibility and usability alignment
- Review implemented features for design fidelity and accessibility

### Goals
- Deliver clear, validated designs that reduce rework during development
- Advocate for the end-user experience in every lifecycle stage
- Maintain a shared design system and component library for consistency

### Typical Communication
- Design handoff notes in shared tools (e.g., Figma) linked in the project board
- Participation in sprint planning and backlog refinement sessions
- Usability feedback summaries shared with Product Managers after testing

### Interactions with Other Roles
- **Product Managers:** Collaborate on problem framing, acceptance criteria, and user research; UX Designers translate product goals into concrete user experiences.
- **Developers:** Provide annotated design specs and participate in implementation reviews to confirm fidelity; flag accessibility or interaction edge cases early.
- **Project Managers:** Align design milestones with sprint timelines; flag scope or capacity risks when design iterations require additional cycles.
- **Business Analysts:** Share user research findings that validate or challenge business requirements; jointly refine acceptance criteria.
- **Customer Success:** Receive customer pain points and usage patterns to inform design priorities and usability improvements.

---

## Business Analyst

### Role Summary
Business Analysts translate business needs and stakeholder requirements into clear, actionable specifications for the delivery team. They maintain traceability between business objectives and delivered features.

### Responsibilities
- Facilitate requirements-gathering sessions with stakeholders and subject-matter experts
- Document functional requirements, user stories, and acceptance criteria
- Maintain requirements traceability to ensure delivered features meet business goals
- Validate completed work against requirements before sign-off
- Identify process gaps and propose workflow improvements

### Goals
- Eliminate ambiguity in requirements that leads to rework or missed expectations
- Enable faster, higher-confidence planning by providing well-defined backlog items
- Serve as a bridge between business stakeholders and the engineering team

### Typical Communication
- Requirements documents and user story write-ups in the project repo or wiki
- Participation in kickoff, planning, and review ceremonies
- Clarification threads on GitHub Issues or PRs when requirements need refinement

### Interactions with Other Roles
- **Product Managers:** Collaborate on roadmap translation into detailed requirements; BAs decompose high-level features into stories with clear acceptance criteria.
- **Developers:** Answer requirement questions during implementation; review PRs for acceptance-criteria alignment.
- **Project Managers:** Supply scope and dependency details to support timeline planning; escalate requirement ambiguities that may affect delivery milestones.
- **UX Designers:** Validate that design solutions satisfy documented business and user requirements.
- **Customer Success:** Gather customer-reported needs and escalations to feed into requirement backlog.

---

## Customer Success

### Role Summary
Customer Success represents the voice of the customer post-launch. They monitor adoption and satisfaction, surface actionable feedback to the product team, and ensure customers derive maximum value from OctoAcme's products.

### Responsibilities
- Collect and synthesize customer feedback, feature requests, and escalations
- Monitor post-launch adoption metrics and report trends to the Product Manager
- Coordinate customer onboarding and enablement activities at release time
- Escalate critical customer-impacting issues to the PM and project team
- Validate that release notes and documentation are customer-ready

### Goals
- Maximize customer satisfaction and retention
- Close the feedback loop between customers and the product team
- Reduce time-to-value for customers after each release

### Typical Communication
- Feedback digests shared with Product Managers after each release or milestone
- Participation in release planning to confirm customer-facing readiness
- Issue or ticket escalations linked to the risk register when customer impact is high

### Interactions with Other Roles
- **Product Managers:** Provide structured customer feedback that informs backlog prioritization; co-own success metrics for delivered features.
- **Project Managers:** Flag customer-impacting risks that should be added to the risk register; confirm release communications are ready before deployment.
- **Developers:** Report production bugs and usage edge cases discovered through customer interactions.
- **UX Designers:** Share qualitative usability observations from customer conversations to guide design improvements.
- **Business Analysts:** Provide real-world customer data to validate or refine documented business requirements.

---

## DevOps Engineer / SRE

### Role Summary
DevOps Engineers and Site Reliability Engineers own the CI/CD pipeline, infrastructure, deployment automation, and production reliability. They enable the team to ship frequently and safely while maintaining system health and observability.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and deployment tooling
- Define and enforce infrastructure-as-code (IaC) standards
- Manage environment configurations (development, staging, production)
- Establish and monitor SLIs/SLOs/SLAs and alerting thresholds
- Lead incident response, post-incident reviews, and reliability improvements
- Support and review the release checklist and rollback procedures

### Goals
- Enable safe, frequent, and low-friction releases to production
- Minimize mean time to recovery (MTTR) for production incidents
- Provide clear observability so teams can detect and diagnose issues quickly

### Typical Communication
- Infrastructure change proposals in PRs with runbook links
- Incident reports and post-mortems captured in the project repo
- Release readiness confirmation as part of the deployment checklist

### Interactions with Other Roles
- **Developers:** Review infrastructure-related PRs; advise on env config, secrets management, and testability in CI; co-own the deployment checklist.
- **Project Managers:** Communicate pipeline or environment risks that affect release timelines; confirm deployment windows and rollback readiness.
- **Product Managers:** Report reliability metrics and SLO health that influence release confidence and feature-flag strategies.
- **Customer Success:** Provide incident status updates so Customer Success can communicate timely and accurate information to affected customers.
- **Business Analysts:** Supply environment and operational constraints that inform technical feasibility of proposed requirements.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Interaction Matrix](./octoacme-role-interaction-matrix.md) for a RACI-lite view of who does what across each lifecycle stage.
- See [Handoff Checklist](./octoacme-handoff-checklist.md) for structured handoff guidance between PM, PdM, and Engineering.

