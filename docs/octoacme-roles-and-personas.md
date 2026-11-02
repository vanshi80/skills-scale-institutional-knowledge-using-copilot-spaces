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

## Engineering Manager / Technical Lead

### Role Summary
Engineering Managers and Technical Leads ensure the engineering organization can deliver work effectively, safely, and predictably. They balance technical feasibility, team health, and execution quality while partnering closely with Product and Project Management.

### Responsibilities
- Own engineering execution, sprint health, and delivery planning
- Break down technical work into actionable, feasible increments
- Guide architecture decisions, technical trade-offs, and dependency management
- Support resourcing, staffing, and delivery recovery when work is at risk
- Partner with Product Managers and Project Managers to align scope, priorities, and sequencing

### Goals
- Maintain healthy engineering velocity and predictable delivery
- Reduce technical and organizational blockers
- Improve the quality and maintainability of the system

### Typical Communication
- Engineering planning and staffing discussions
- Technical risk reviews and architecture decisions
- Cross-functional alignment with PM, PdM, and stakeholders on scope and trade-offs

### Interaction with Existing Roles
- Works with Product Managers to translate roadmap outcomes into feasible technical plans
- Works with Project Managers to manage delivery schedules, staffing, and risks
- Supports Developers by clarifying technical direction, reducing ambiguity, and helping resolve blockers
- Escalates cross-team or technical dependency issues when they threaten project commitments

---

## QA / Test Lead

### Role Summary
QA / Test Leads define the quality strategy and validate that software meets acceptance criteria, release readiness, and customer expectations.

### Responsibilities
- Define test strategy, quality gates, and regression coverage
- Validate acceptance criteria and release readiness across critical workflows
- Partner with Developers and Product Managers on defect triage and prioritization
- Monitor test health, flakiness, and risk coverage over time
- Support release decision-making with evidence and quality reporting

### Goals
- Ensure software is reliable, testable, and fit for release
- Reduce avoidable defects and regressions
- Maintain confidence in delivery quality

### Typical Communication
- Test plans, QA status updates, and release readiness reviews
- Defect triage with engineering and product partners
- Shared acceptance criteria validation in planning and review milestones

### Interaction with Existing Roles
- Works with Developers to define testable acceptance criteria and identify gaps in coverage
- Partners with Product Managers to validate that the shipped experience meets business expectations
- Coordinates with Project Managers to align quality checkpoints with milestones and release timing
- Escalates release blockers or critical defects to the appropriate project decision-makers

---

## Security / Compliance Partner

### Role Summary
Security and Compliance Partners help teams identify and manage security, privacy, and regulatory risks early in the lifecycle. They ensure required controls are in place without slowing delivery unnecessarily.

### Responsibilities
- Review risk, data handling, and compliance requirements for projects with security implications
- Help define security controls, access patterns, and guardrails
- Participate in threat reviews, architecture review, and incident planning
- Coordinate required approvals, documentation, and remediation activities
- Escalate security concerns when they affect risk, legal obligations, or customer trust

### Goals
- Reduce security and compliance risk
- Enable safe delivery without hidden operational surprises
- Build trust in the product through proactive controls

### Typical Communication
- Security review check-ins and architecture discussions
- Risk assessments and compliance reporting
- Incident escalation communication and remediation tracking

### Interaction with Existing Roles
- Works with Engineering Managers and Developers to design secure solutions and review technical trade-offs
- Collaborates with Product Managers and Project Managers on risk, release timing, and stakeholder communication
- Supports leadership with escalation paths when security issues affect delivery or legal obligations
- Helps define communication expectations for sensitive findings and mitigation plans

---

## Customer Success / Support Representative

### Role Summary
Customer Success and Support Representatives connect product delivery to real-world customer experience. They help teams understand user pain points, operational issues, and adoption signals.

### Responsibilities
- Capture customer feedback, issues, and service trends
- Translate user problems into actionable product or process improvements
- Support prioritization of customer-impacting work
- Coordinate with engineering and product teams on operational issues and workarounds
- Monitor adoption, satisfaction, and support signals after release

### Goals
- Improve customer outcomes and satisfaction
- Ensure adoption and operational support are considered in delivery decisions
- Reduce friction between product development and customer reality

### Typical Communication
- Customer feedback summaries, issue trends, and release impact updates
- Support escalation and operational follow-up
- Product feedback and prioritization discussions

### Interaction with Existing Roles
- Provides Product Managers with evidence on pain points and customer impact
- Works with Developers and QA to validate whether issues are resolved and measurable
- Coordinates with Project Managers on customer-facing timelines, launch communication, and escalations
- Helps identify whether a release issue requires urgent prioritization or a rollback decision

---

## UX / Research Partner

### Role Summary
UX and Research partners ensure that product decisions remain grounded in customer needs, usability, and user experience quality. They help translate user needs into usable design and clear requirements.

### Responsibilities
- Validate assumptions with user research, interviews, and feedback
- Support design quality, usability, and accessibility reviews
- Translate user needs into clear product requirements and flows
- Partner with Product and Engineering to refine scope and reduce rework
- Help evaluate outcomes after launch and suggest iteration opportunities

### Goals
- Improve ease-of-use and customer satisfaction
- Reduce risk of building low-value or confusing experiences
- Align product outcomes with real user needs

### Typical Communication
- Research insights, usability findings, and design review sessions
- User stories and journey refinements with product and engineering
- Stakeholder discussions on customer needs and experience quality

### Interaction with Existing Roles
- Works with Product Managers to define user-centered success criteria and feature direction
- Partners with Developers to ensure designs are feasible and testable
- Provides input to Project Managers on readiness, dependencies, and risk related to customer experience
- Escalates evidence of user friction or accessibility issues that may affect launch or adoption

---

## Role Coordination and Escalation

### Shared Accountability
OctoAcme projects work best when each role has clear ownership but also collaborates across boundaries. Product leads define value, project leads manage coordination, engineering leads drive technical execution, and support functions contribute validation, risk management, and customer insight.

### Typical Hand-offs
- Product Manager to Engineering Manager / Technical Lead: business goals, priorities, and trade-offs
- Engineering Manager / Technical Lead to Developers: technical direction, architecture decisions, and delivery planning
- QA / Test Lead to Product Manager and Developers: readiness validation and defect prioritization
- Customer Success / Support Representative to Product Manager: user feedback, issue trends, and customer impact
- UX / Research Partner to Product Manager and Developers: user insights and design validation
- Security / Compliance Partner to Engineering, PM, and leadership: risk identification and control guidance

### Escalation Paths
- Team-level issues are raised in daily standups or planning forums
- Delivery risks or dependency blockers move to the Project Manager
- Strategic or cross-functional issues are escalated to the Product Manager and Engineering Manager / Technical Lead
- Security, compliance, or customer-impacting issues move to the appropriate executive or sponsor stakeholder depending on severity

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
