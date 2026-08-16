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

## Project Sponsor / Executive Sponsor

### Responsibilities
- Own strategic alignment, funding, and executive-level priority decisions
- Approve material scope, budget, or risk decisions beyond the team's delegated authority
- Remove organizational blockers and support escalations

### Interactions
- Partners with Project Managers and Product Managers on goals, scope, trade-offs, and decision gates
- Receives status and escalations from the Project Manager and represents stakeholder interests in major decisions

---

## Business Analyst

### Responsibilities
- Elicit, document, and validate requirements and business workflows
- Clarify acceptance criteria and translate stakeholder needs into actionable backlog items
- Maintain traceability between needs, requirements, and delivered outcomes

### Interactions
- Works with Product Managers on outcomes and prioritization, and with Project Managers on planning and dependencies
- Collaborates with Stakeholders on discovery and validation and with Developers and QA/Testing on clear, testable behavior

---

## UX / Product Designer

### Responsibilities
- Conduct user research and create interaction, visual, and accessibility designs
- Validate usability and document design decisions

### Interactions
- Partners with Product Managers and Business Analysts on customer value and needs, and with Stakeholders on validation
- Works with Developers and QA/Testing to ensure designs are feasible, accessible, and testable; keeps Project Managers informed of design dependencies

---

## Technical Lead / Architect

### Responsibilities
- Guide technical direction, architecture, and non-functional requirements
- Make or facilitate technical design decisions and mitigate technical risks

### Interactions
- Works with Project Managers on dependencies and risks and with Product Managers on value, scope, and technical trade-offs
- Guides Developers, coordinates with QA/Testing on quality and readiness, and partners with Security / Compliance Leads on controls

---

## Release Manager

### Responsibilities
- Coordinate release readiness, deployment sequencing, and rollout communications
- Ensure verification, rollback plans, and release evidence are available

### Interactions
- Partners with Project Managers on milestones and stakeholder communications and with Technical Leads on deployment risks
- Collects readiness evidence from Developers and QA/Testing and prepares Customer / Support Representatives for operational impact

---

## Security / Compliance Lead

### Responsibilities
- Define security, privacy, and compliance requirements and coordinate reviews
- Track control gaps and advise on risk treatment and material risk acceptance

### Interactions
- Works with Project Managers on risk escalation, Technical Leads and Developers on mitigations, and QA/Testing on validation
- Engages Product Managers and Stakeholders on requirements and the Sponsor on material risks requiring acceptance

---

## Customer / Support Representative

### Responsibilities
- Represent customer needs and prepare support and operational teams
- Communicate customer-impact considerations and collect post-release feedback

### Interactions
- Works with Product Managers, Business Analysts, and Stakeholders during discovery and with Project Managers on customer-impact communications
- Partners with Developers, QA/Testing, and the Release Manager on support readiness, then feeds incidents, adoption data, and feedback into improvements

---

## Role Interaction Guidance

Use the following ownership and handoff guidance to make responsibilities explicit:

| Activity | Accountable owner | Key handoff or collaboration | Lifecycle participation |
| --- | --- | --- | --- |
| Strategy, funding, and major escalations | Project Sponsor / Executive Sponsor | Sponsor decisions guide Product and Project Managers | Initiation, planning, governance |
| Requirements and priority | Product Manager | Business Analyst and Designer refine needs; Developers and QA/Testing receive testable backlog items | Discovery, planning, delivery |
| Delivery coordination, risks, and status | Project Manager | Coordinates dependencies, decisions, and stakeholder communication across all roles | All phases |
| Technical design and implementation | Technical Lead / Architect | Developers implement; QA/Testing and Security / Compliance validate quality and controls | Planning, delivery, release |
| Release readiness and rollout | Release Manager | Developers, QA/Testing, Technical Lead, and Support provide readiness evidence | Release, operations |
| Customer feedback and improvement | Customer / Support Representative | Product and Project Managers incorporate feedback into priorities and plans | Discovery, operations, improvement |

Projects may combine roles based on project size and context. When they do, assign each responsibility and decision to a named accountable owner, and preserve explicit handoffs and escalation paths.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
