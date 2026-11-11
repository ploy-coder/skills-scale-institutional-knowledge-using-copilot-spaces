# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Assign these roles according to project needs; one person may cover multiple roles, especially on smaller projects.

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

## UX/UI Designer or Researcher

### Role Summary
This role researches user needs and shapes usable, accessible experiences through interaction design, visual design, and usability validation.

### Responsibilities
- Plan or conduct user research and synthesize findings
- Create user flows, prototypes, and design specifications
- Validate usability and accessibility with users and design reviews
- Document design decisions and open questions for implementation

### When to involve
Involve this role when work changes customer workflows, introduces a new interface, or requires user research or usability validation. For small changes, consult as needed rather than assigning a dedicated role.

### Collaboration and accountability
Partners with Product Managers to connect user needs and research to product outcomes and priorities. Works with Developers to assess feasibility and clarify design intent, and with QA/Testing to make experiences and accessibility requirements testable. The role recommends design decisions; the Product Manager remains accountable for product scope and prioritization.

---

## Data/Analytics Lead

### Role Summary
The Data/Analytics Lead ensures teams can measure whether a project achieves its intended outcomes and that the underlying data is trustworthy.

### Responsibilities
- Translate success metrics into an instrumentation and measurement plan
- Define event, reporting, and data-quality requirements
- Validate tracking and analyze results after launch
- Communicate metric definitions, limitations, and findings

### When to involve
Involve this role when success depends on quantitative outcomes, new instrumentation, or analysis of usage and performance. A Product Manager or Developer may cover basic measurement needs for a small project, with specialist support when data complexity or impact warrants it.

### Collaboration and accountability
Works with Product Managers to define meaningful measures and interpret results, and with Developers to implement and verify instrumentation. Coordinates with Project Managers to surface analytics dependencies and timing risks. Advises on measurement; the Product Manager owns product outcomes and decisions informed by the data.

---

## Security/Privacy Lead

### Role Summary
The Security/Privacy Lead advises the team on protecting systems and data, identifying relevant security and privacy risks, and meeting applicable requirements.

### Responsibilities
- Identify security, privacy, and compliance considerations early
- Review relevant designs, data flows, and planned changes
- Recommend mitigations and coordinate specialist reviews when needed
- Confirm that agreed security and privacy actions are tracked and addressed

### When to involve
Involve this role when a project handles sensitive data, changes authentication or access, introduces significant new integrations, or has elevated regulatory or threat exposure. For low-risk work, use the organization’s standard security guidance and escalation path.

### Collaboration and accountability
Partners with Developers to assess designs and implement mitigations, with Product Managers to explain risk and inform trade-offs, and with Project Managers to schedule reviews, track actions, and escalate unresolved blockers. Provides specialist advice and review; accountable risk acceptance and approval follow the organization’s designated security and product governance.

---

## Operations/SRE or Release Manager

### Role Summary
This role helps ensure that changes can be deployed and operated safely, reliably, and with appropriate monitoring and recovery plans.

### Responsibilities
- Advise on reliability, capacity, operability, and deployment approach
- Define or review monitoring, alerting, and operational readiness needs
- Coordinate release readiness, deployment dependencies, and rollback planning
- Support post-deployment verification and operational handoff

### When to involve
Involve this role for production releases, infrastructure or platform changes, services with important availability needs, or changes requiring coordinated rollout or rollback. For routine low-risk changes, existing deployment practices may be sufficient.

### Collaboration and accountability
Works with Developers and QA/Testing to define operational checks and verify readiness, and with Project Managers to coordinate release dates, dependencies, and communications. Partners with Product Managers on release trade-offs and customer impact. Advises on readiness and coordinates release activities; deployment approval follows the team’s established release policy.

---

## Customer Support/Enablement Representative

### Role Summary
This role brings customer-facing support needs into delivery and prepares support teams and users for relevant changes.

### Responsibilities
- Share recurring customer questions, issues, and feedback with the team
- Identify support, documentation, training, and enablement needs
- Review customer-facing guidance for clarity and readiness
- Help coordinate launch communications and route post-release feedback

### When to involve
Involve this role when a change affects customer workflows, support volume, help content, training, or external communications. Small internal or low-impact changes may need only an asynchronous review or no dedicated support involvement.

### Collaboration and accountability
Works with Product Managers to share customer insights and validate messaging, and with Project Managers and the Operations/SRE or Release Manager to coordinate launch readiness and timing. Provides support-readiness input; Product Managers own product messaging and priorities, while Project Managers coordinate delivery and communication plans.

---

## Applying roles proportionately
- Assign a named accountable owner for each decision or deliverable, even when one person performs several roles.
- Combine roles on smaller projects when skills and independence requirements allow; document who is covering each responsibility and any review needed from a specialist.
- Bring specialist roles in early when their expertise affects scope, acceptance criteria, risk, or release readiness, rather than treating consultation as a last-minute approval gate.
- Follow existing organizational policies for formal approvals, security review, and release authorization; these persona descriptions do not replace those policies.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
