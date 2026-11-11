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

## UX / Design Lead

### Role Summary
The UX / Design Lead shapes the user experience and ensures the product is intuitive, usable, and aligned to customer needs. They translate product intent into user flows, visual design, and validation activities.

### Responsibilities
- Facilitate user research, usability testing, and customer feedback synthesis
- Define experience principles, interaction patterns, and design standards
- Partner with Product Managers on problem framing and priority trade-offs
- Collaborate with Developers and QA to ensure feasibility, accessibility, and usability validation
- Maintain design artifacts, prototypes, and handoff documentation for delivery

### Goals
- Deliver experiences that are easy to use and easy to trust
- Reduce friction between customer needs and implementation details
- Improve quality through user-centered design feedback loops

### Typical Communication
- Design reviews and user research summaries
- Collaboration with Product and Engineering during discovery and delivery
- Usability findings shared with project stakeholders and QA

### Interaction with existing roles
- Works closely with Product Managers on user needs, problem framing, and prioritization
- Coordinates with Developers on feasibility, implementation trade-offs, and design handoff
- Partners with QA/Testing on usability acceptance criteria and validation scenarios
- Keeps the Project Manager informed of design dependencies and schedule impacts

---

## Engineering Lead / Tech Lead

### Role Summary
The Engineering Lead / Tech Lead guides the technical direction of the solution and helps the team make sound implementation decisions. They balance delivery speed, maintainability, and architectural quality.

### Responsibilities
- Define and maintain technical approach, architecture guardrails, and standards
- Support estimation, sequencing, and dependency planning with the delivery team
- Guide implementation quality, code review practices, and technical risk mitigation
- Coordinate with Product and Project leads on delivery trade-offs and blockers
- Help resolve cross-team technical dependencies and integration issues

### Goals
- Keep the team aligned on a sustainable technical approach
- Reduce delivery risk and rework through early technical clarity
- Maintain system quality, performance, and operational readiness

### Typical Communication
- Engineering planning and design reviews
- Dependency and risk updates during standups and weekly syncs
- Architecture decisions and implementation trade-offs with Product and PM leadership

### Interaction with existing roles
- Works with Developers to maintain code quality and technical direction
- Partners with Product Managers on scope, feasibility, and sequencing trade-offs
- Supports Project Managers by clarifying delivery dependencies and risk exposure
- Coordinates with QA/Testing to ensure testability, release readiness, and defect prioritization

---

## Business Analyst

### Role Summary
The Business Analyst translates business needs into clear requirements, process understanding, and measurable outcomes. They help reduce ambiguity between stakeholder intent and delivery execution.

### Responsibilities
- Clarify business drivers, user workflows, and decision-making needs
- Document requirements, process details, and edge cases
- Partner with Product Managers and stakeholders to refine scope and acceptance criteria
- Identify gaps, assumptions, and risks in requirements before implementation
- Support validation by ensuring requirements are testable and measurable

### Goals
- Improve requirement quality and reduce rework caused by ambiguity
- Align business expectations with delivery outcomes
- Ensure stakeholder needs are represented in backlog and acceptance criteria

### Typical Communication
- Requirement workshops and stakeholder interviews
- Backlog refinement, acceptance criteria reviews, and status alignment
- Documentation shared with Product, QA, and Project leadership

### Interaction with existing roles
- Works closely with Product Managers to refine the problem definition and backlog priorities
- Supports Developers and QA/Testing by turning business needs into testable acceptance criteria
- Helps Project Managers track scope clarity, dependencies, and delivery risks
- Keeps stakeholders informed on how their requests are captured and prioritized

---

## Release Manager

### Role Summary
The Release Manager coordinates release readiness, deployment sequencing, and communication. They ensure the team is prepared to move changes safely into production and communicate the impact to impacted groups.

### Responsibilities
- Manage release plans, scheduling, and readiness checkpoints
- Coordinate rollback planning, risk mitigation, and post-release verification
- Align stakeholders on release timing, scope, and communication
- Partner with QA/Testing, Engineering, and Product leaders on deployment confidence
- Capture release outcomes and lessons learned for future improvements

### Goals
- Reduce release risk and avoid production disruption
- Improve predictability and transparency around deployments
- Support smooth customer-facing rollouts and operational readiness

### Typical Communication
- Release readiness reviews and launch checklists
- Stakeholder communication for deployment windows and status updates
- Incident and rollback coordination when issues arise

### Interaction with existing roles
- Works with Project Managers to sequence delivery and release windows
- Coordinates with Engineering Lead and Developers on deployment readiness and rollback options
- Partners with QA/Testing to confirm release criteria are met
- Communicates with stakeholders and support teams on release impact and timing

---

## Security / Privacy Lead

### Role Summary
The Security / Privacy Lead ensures security and privacy requirements are considered early, embedded in delivery, and reviewed before release. They help the team reduce risk while maintaining appropriate compliance controls.

### Responsibilities
- Identify security and privacy requirements, risks, and regulatory considerations
- Review architecture, data handling, and access patterns with engineering teams
- Define review gates and required controls for new features or integrations
- Partner with Product and Project leads to assess risk and trade-offs
- Support incident response, vulnerability triage, and remediation planning

### Goals
- Protect customer, product, and organizational data
- Reduce avoidable security and privacy issues in delivery
- Maintain confidence in release quality and operational safety

### Typical Communication
- Security review meetings and risk assessments
- Updates during planning, release readiness, and incident response
- Clear guidance for engineers, PMs, and stakeholders on requirements and risk

### Interaction with existing roles
- Reviews technical decisions with Developers and the Engineering Lead
- Ensures QA/Testing includes security and privacy validation where needed
- Helps Product Managers and Project Managers assess risk and delivery impact
- Provides escalation paths when risks require prioritization or remediation before launch

---

## Role Selection Guidance

Not every project requires every role. Smaller initiatives may combine responsibilities, while higher-risk or larger cross-functional programs may require distinct owners for design, architecture, release, or security. In all cases, the accountable owner for each responsibility should be clear so that decisions, quality gates, and escalations do not get lost between teams.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
