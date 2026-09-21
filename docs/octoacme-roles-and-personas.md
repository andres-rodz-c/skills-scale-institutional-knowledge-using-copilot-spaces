# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It also captures the cross-functional partners that support delivery at scale, clarify accountability, and improve coordination across product, engineering, quality, and operations.

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

## Delivery Lead / Team Lead

### Role Summary
Delivery Leads coordinate sprint execution, unblock teams, and help keep cross-functional work moving from idea to release.

### Responsibilities
- Maintain sprint flow and prioritize work for execution readiness
- Remove blockers and escalate dependencies across teams
- Coordinate with PMs and engineering leads on delivery sequencing
- Support capacity planning and resourcing trade-offs
- Help translate goals into actionable team commitments

### Goals
- Improve delivery predictability and execution quality
- Keep work moving without sacrificing team health or clarity
- Ensure dependencies are identified and resolved early

### Typical Communication
- Daily standups and sprint reviews
- Dependency tracking in planning and delivery syncs
- Cross-team coordination with PM, engineering, and stakeholders

### How this role interacts with others
- Works closely with Project Managers to align delivery plan, status, and risks
- Partners with Product Managers to ensure backlog items are ready and sequenced well
- Supports Developers by removing friction and escalating issues that affect scope or throughput

---

## Technical Lead / Architecture Lead

### Role Summary
Technical Leads provide design direction, technical decision-making, and engineering quality guardrails for the solution.

### Responsibilities
- Define technical direction, architecture, and design standards
- Review trade-offs between speed, maintainability, and system complexity
- Guide implementation decisions and ensure technical consistency across teams
- Identify technical risks, dependencies, and integration concerns
- Support onboarding and mentoring for engineering contributors

### Goals
- Create scalable, maintainable solutions
- Reduce costly rework and avoid architecture drift
- Support delivery without sacrificing quality or long-term health

### Typical Communication
- Technical design reviews and architecture discussions
- Engineering planning sessions and dependency mapping
- Partnering with QA to define testability and release confidence

### How this role interacts with others
- Works with Developers to prioritize technical quality and solution fit
- Advises Product Managers and Project Managers on scheduling, complexity, and risk trade-offs
- Collaborates with Security and QA partners on design review, compliance, and validation requirements

---

## QA Lead / Test Manager

### Role Summary
QA Leads define the quality strategy and ensure that features meet acceptance criteria, release readiness standards, and regression expectations.

### Responsibilities
- Define test strategy, regression plans, and quality gates
- Validate new functionality against acceptance criteria and user impact
- Coordinate testing across unit, integration, and end-to-end scenarios
- Partner with engineering and release teams to assess readiness for deployment
- Identify gaps in coverage and drive defect prioritization

### Goals
- Reduce release risk and customer-facing defects
- Increase confidence in product quality and operational stability
- Ensure that quality is considered throughout the lifecycle, not just at the end

### Typical Communication
- Acceptance review and QA planning meetings
- Defect triage and release readiness checkpoints
- Collaboration with Product, Engineering, and Release partners

### How this role interacts with others
- Works with Product Managers to confirm acceptance criteria are testable and measurable
- Coordinates with Developers to validate fixes and monitor regression risk
- Provides release readiness input to Project Managers and Release Managers

---

## Security / Compliance Partner

### Role Summary
Security and Compliance partners review solutions for risk, policy alignment, and data protection considerations throughout the project lifecycle.

### Responsibilities
- Assess architecture, workflows, and integrations for security risks
- Review compliance requirements, data handling practices, and policy alignment
- Help define security controls, review processes, and risk mitigations
- Support incident response preparedness and vulnerability triage
- Guide teams on acceptable risk and secure-by-default practices

### Goals
- Protect customer trust and organizational compliance obligations
- Reduce security and regulatory risk in delivery decisions
- Ensure security is built into the process, not treated as a late-stage gate

### Typical Communication
- Security review meetings and architecture checkpoints
- Risk assessment and remediation planning
- Escalation paths for incidents, vulnerabilities, or policy exceptions

### How this role interacts with others
- Partners with Technical Leads and Developers to assess designs and implementation risks
- Advises PMs and Product Managers when requirements or timelines create security trade-offs
- Coordinates with Release Managers on secure deployment and rollback readiness

---

## Customer Success / Stakeholder Partner

### Role Summary
Customer Success and Stakeholder partners represent user impact, adoption readiness, and stakeholder communication needs across the project lifecycle.

### Responsibilities
- Represent end-user and stakeholder feedback in product decisions
- Communicate project progress, changes, and readiness to affected groups
- Help translate customer needs into requirements, onboarding plans, and support prep
- Support adoption, rollout readiness, and post-launch feedback loops
- Surface business and customer risks that may affect success metrics

### Goals
- Improve customer adoption and stakeholder confidence
- Ensure launch readiness reflects real user needs and operational constraints
- Link product delivery to measurable customer impact

### Typical Communication
- Stakeholder updates and milestone reviews
- Customer feedback loops, adoption check-ins, and training/support planning
- Cross-functional alignment for launch and post-release readiness

### How this role interacts with others
- Works with Product Managers to validate value and customer impact
- Coordinates with Project Managers and Release Managers on communication timing and stakeholder readiness
- Helps Developers and QA teams understand user scenarios and operational edge cases

---

## Release Manager / Operations Partner

### Role Summary
Release Managers coordinate the deployment process, operational readiness, and rollout communications needed to move work into production reliably.

### Responsibilities
- Schedule deployment windows, release activities, and change checkpoints
- Coordinate communication with stakeholders, support teams, and operational owners
- Validate rollout readiness, smoke tests, and post-deployment checks
- Support rollback planning and incident response coordination when needed
- Track release quality, customer impact, and operational follow-up

### Goals
- Reduce deployment risk and customer disruption
- Improve release predictability and operational readiness
- Ensure releases align with stakeholder expectations and support capacity

### Typical Communication
- Release planning, readiness reviews, and go/no-go checkpoints
- Post-release verification and incident response coordination
- Stakeholder announcements and rollback communication when needed

### How this role interacts with others
- Collaborates with Project Managers on release timing and milestones
- Works with QA and Engineering leaders to confirm readiness and validation evidence
- Coordinates with Customer Success and Security partners to align launch communications and risk posture

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional role definitions help clarify accountability, decision rights, and communication paths for growing projects.

