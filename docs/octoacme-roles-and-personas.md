# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Projects may combine roles or assign only the personas needed for their scope; when roles are combined, accountability should remain explicit.

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

## Executive Sponsors

### Role Summary
Executive Sponsors provide business-level sponsorship and ensure that the initiative remains aligned with organizational strategy.

### Responsibilities
- Confirm strategic alignment and sponsorship
- Approve major scope, funding, priority, or risk decisions
- Remove organizational blockers beyond the delivery team's authority
- Support escalation decisions when business impact is significant

### Interaction with Existing Roles
- Receive status, risk, and decision updates from the Project Manager and Product Manager
- Partner with the Product Manager on outcome and priority decisions
- Provide direction when the Project Manager escalates cross-functional or business constraints
- Support, rather than replace, the Product Manager's product ownership and the Project Manager's delivery coordination

---

## Product Owners / Business Analysts

### Role Summary
Product Owners and Business Analysts translate customer and business needs into actionable requirements and maintain traceability from outcomes to delivered work. Depending on the team structure, these responsibilities may be held by the Product Manager.

### Responsibilities
- Refine requirements and user needs into backlog-ready work
- Maintain traceability between goals, requirements, and acceptance criteria
- Clarify business rules, workflows, and edge cases
- Support backlog refinement and acceptance activities

### Interaction with Existing Roles
- Partner with the Product Manager to turn product priorities into clear requirements
- Work with stakeholders to validate business needs
- Collaborate with Developers and QA/Testing to clarify expected behavior and resolve requirement questions
- Coordinate with the Project Manager so requirements, dependencies, and decisions are reflected in the plan

---

## Technical Leads / Architects

### Role Summary
Technical Leads and Architects guide technical direction, design quality, integration decisions, and technical risk management.

### Responsibilities
- Define or review technical approaches and architecture
- Identify integration points, constraints, and technical dependencies
- Surface feasibility concerns and technical trade-offs
- Support consistent engineering standards and technical decision records

### Interaction with Existing Roles
- Guide Developers while leaving implementation ownership with the development team
- Provide the Product Manager with feasibility, trade-off, and sequencing information
- Coordinate with the Project Manager on technical risks, dependencies, and milestones
- Collaborate with QA/Testing, Security/Privacy, and Release/Operations roles to make quality and operational requirements actionable

---

## UX / Design Leads

### Role Summary
UX and Design Leads represent user experience, research, accessibility, and interaction design throughout delivery.

### Responsibilities
- Research user needs and validate proposed experiences
- Define interaction, visual, and accessibility requirements
- Produce and maintain designs and supporting design rationale
- Participate in usability validation and acceptance activities

### Interaction with Existing Roles
- Partner with the Product Manager and stakeholders to connect user needs to product outcomes
- Collaborate with Product Owners / Business Analysts on requirements and acceptance criteria
- Work with Developers and QA/Testing to ensure designs are implemented and verifiable
- Share user research and design risks with the Project Manager for planning and stakeholder communication

---

## Delivery Leads / Scrum Masters

### Role Summary
Delivery Leads and Scrum Masters improve team flow, facilitate agreed delivery practices, and help remove impediments. They do not replace the Project Manager's accountability for overall delivery.

### Responsibilities
- Facilitate planning, standups, reviews, retrospectives, and backlog refinement as appropriate
- Make impediments and delivery-flow issues visible
- Help the team maintain focus, capacity awareness, and continuous improvement
- Support healthy collaboration and predictable delivery practices

### Interaction with Existing Roles
- Coordinate with the Project Manager on blockers, capacity, risks, and delivery signals
- Support the Product Manager with backlog and feedback-flow facilitation
- Enable Developers and QA/Testing to plan and deliver work without taking over their technical or quality decisions
- Escalate unresolved impediments through the Project Manager's established escalation path

---

## Release Managers / Operations Leads

### Role Summary
Release Managers and Operations Leads coordinate release readiness, deployment execution, operational checks, rollback planning, and post-release verification.

### Responsibilities
- Define release readiness checks and coordinate deployment windows
- Confirm deployment, monitoring, rollback, and mitigation plans
- Coordinate staging validation and production verification
- Track operational follow-up after release

### Interaction with Existing Roles
- Work with the Project Manager to align release timing, dependencies, and stakeholder communications
- Coordinate with Developers, QA/Testing, and Technical Leads on readiness and verification
- Partner with Security/Privacy on required controls and approvals
- Coordinate with Customer/Support Representatives so support teams receive release information and known-issue guidance

---

## Security / Privacy Partners

### Role Summary
Security and Privacy Partners advise on threat modeling, privacy obligations, security controls, and risk acceptance.

### Responsibilities
- Identify security and privacy risks early in planning
- Recommend appropriate controls, testing, and documentation
- Review relevant designs, data flows, and release readiness evidence
- Define or approve mitigation and risk-acceptance requirements within their authority

### Interaction with Existing Roles
- Collaborate with Technical Leads / Architects and Developers on secure design and implementation
- Work with QA/Testing on security validation and evidence
- Coordinate with the Project Manager to record risks, owners, mitigations, and escalation needs
- Partner with the Release Manager / Operations Lead before production deployment
- Advise the Product Manager and stakeholders on customer or regulatory impact without replacing business decision ownership

---

## Customer / Support Representatives

### Role Summary
Customer and Support Representatives bring customer feedback, support trends, readiness needs, and communication requirements into delivery decisions.

### Responsibilities
- Share recurring customer problems, feedback, and support signals
- Identify customer-impact risks and support-readiness needs
- Review customer-facing messaging, documentation, and known issues
- Help validate customer impact after release

### Interaction with Existing Roles
- Partner with the Product Manager to inform prioritization and outcome validation
- Provide the Project Manager with communication, dependency, and readiness inputs
- Coordinate with the Release Manager / Operations Lead on announcements and support preparation
- Work with UX / Design Leads and QA/Testing to represent usability and acceptance concerns

---

## Data / Analytics Partners

### Role Summary
Data and Analytics Partners define measurement plans, instrumentation needs, dashboards, and outcome analysis so teams can evaluate whether delivered work achieves its goals.

### Responsibilities
- Translate success metrics into measurement and instrumentation requirements
- Advise on data quality, event definitions, reporting, and interpretation
- Build or maintain dashboards and outcome reports where appropriate
- Identify limitations, trends, and follow-up questions in the available data

### Interaction with Existing Roles
- Work with the Product Manager to define measurable outcomes and success criteria
- Coordinate with Developers and Technical Leads on instrumentation and data quality
- Help the Project Manager report progress and post-release results using agreed signals
- Provide evidence for retrospectives and prioritization without replacing product or delivery decision ownership

---

## Role Interaction Across the Project Lifecycle

The personas above are optional participants based on project needs, but accountability should be explicit whenever a role is used. A typical interaction pattern is:

- **Initiation:** Executive Sponsor confirms sponsorship; Product Manager and Product Owner / Business Analyst define the problem and outcomes; Project Manager identifies stakeholders, risks, and resources; UX / Design, Technical, Security / Privacy, Customer / Support, and Data / Analytics partners advise as needed.
- **Planning:** Product Manager prioritizes outcomes; Product Owner / Business Analyst refines requirements; Technical Lead identifies design and dependency constraints; Project Manager builds the delivery plan; Delivery Lead supports team planning; QA/Testing and specialist partners define readiness needs.
- **Execution:** Developers implement the work; UX / Design, Technical, Security / Privacy, and QA/Testing provide discipline-specific guidance; Project Manager tracks delivery, risks, and dependencies; Delivery Lead helps resolve flow impediments.
- **Release:** Release Manager / Operations Lead coordinates readiness and deployment; QA/Testing verifies acceptance; Security / Privacy confirms required controls; Project Manager coordinates stakeholders; Customer / Support prepares communications; Product Manager and Data / Analytics define outcome follow-up.
- **Retrospective:** Project Manager and Delivery Lead facilitate learning; all participating roles contribute evidence and improvement actions; Product Manager and Executive Sponsor use outcomes and lessons to inform future priorities.

When a project combines roles, document who is **Accountable**, **Responsible**, **Consulted**, and **Informed** for major decisions and deliverables. The Project Manager should maintain this clarity in the project plan or decision log, while the Product Manager retains ownership of product outcomes and the appropriate specialist retains ownership of their professional advice or control.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
