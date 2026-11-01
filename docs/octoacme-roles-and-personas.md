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

## QA / Test Lead

### Role Summary
QA / Test Leads coordinate the test approach and provide evidence that work meets agreed acceptance and quality criteria. Teams may assign this role to a dedicated tester or share it across team members.

### Responsibilities
- Plan unit, integration, regression, and end-to-end testing with the team
- Validate acceptance criteria and record test results and defects
- Coordinate defect triage and communicate quality risks before release
- Identify gaps in test coverage and accessibility or reliability validation

### Goals
- Find and resolve defects before they reach customers
- Make release-quality evidence visible and actionable
- Keep validation aligned with agreed acceptance criteria

### Typical Communication
- Test plans, defect reports, and release-readiness updates
- QA coordination during planning and delivery reviews

### Interactions with Existing Roles
- Works with Developers on testability, coverage, and defect resolution.
- Works with Product Managers (PdMs) to clarify acceptance criteria; QA validates against them but does not redefine product priorities.
- Works with Project Managers (PMs) to schedule validation, track QA dependencies, and escalate readiness risks.

---

## Technical Lead / Solution Architect

### Role Summary
Technical Leads guide technical design and integration decisions so solutions are reliable, maintainable, and consistent with engineering standards.

### Responsibilities
- Facilitate technical design and document significant decisions
- Identify architecture, integration, performance, and technical-debt risks
- Support Developers with implementation guidance and technical reviews
- Advise on feasibility and technical estimates without owning product scope

### Goals
- Enable sound technical decisions and sustainable delivery
- Reduce avoidable integration risks and rework
- Make technical trade-offs clear to the team

### Typical Communication
- Design reviews, architecture notes, and technical risk updates
- Planning discussions about estimates, dependencies, and implementation options

### Interactions with Existing Roles
- Partners with Developers on design, implementation, and code reviews; the team remains responsible for quality and maintainability.
- Advises PdMs on feasibility and trade-offs; the PdM retains backlog priority and outcome ownership.
- Shares technical risks, estimates, and dependencies with PMs, who coordinate the delivery plan.

---

## UX / Design Lead

### Role Summary
UX / Design Leads research user needs and shape accessible, usable interactions that support the intended product outcomes.

### Responsibilities
- Plan and conduct user research and synthesize findings
- Create and validate interaction designs, prototypes, and design guidance
- Identify usability and accessibility requirements and review solutions against them
- Communicate design decisions and open questions to the delivery team

### Goals
- Deliver clear, accessible experiences that address user needs
- Validate assumptions early and reduce usability rework
- Keep design intent understood through implementation

### Typical Communication
- Research findings, prototypes, design reviews, and usability feedback
- Design handoffs and implementation discussions

### Interactions with Existing Roles
- Works with PdMs to connect user research to product outcomes and backlog decisions; the PdM retains prioritization ownership.
- Collaborates with Developers on technical constraints and design implementation.
- Coordinates research and design milestones with PMs so dependencies and reviews are reflected in the plan.

---

## DevOps / Release Coordinator

### Role Summary
DevOps / Release Coordinators support reliable deployment and operational readiness. The project must identify who is authorized to approve deployment and initiate rollback under its release policy.

### Responsibilities
- Coordinate pipeline and environment readiness, deployment steps, and observability
- Prepare smoke tests, rollback or mitigation steps, and operational handoffs
- Confirm required release evidence is available and surface unresolved operational risks
- Record deployment outcomes and coordinate follow-up on incidents or defects

### Goals
- Make releases observable, repeatable, and recoverable
- Reduce deployment risk and improve post-release response
- Ensure support teams receive the information needed to operate the service

### Typical Communication
- Deployment plans, readiness checks, runbooks, and post-deploy updates
- Coordination with on-call and support during releases

### Interactions with Existing Roles
- Works with Developers on pipeline changes, deployments, and remediation; developers remain responsible for their changes.
- Coordinates with QA / Test Leads on smoke-test evidence and with PdMs on release scope and customer impact.
- Works with PMs on release windows, dependencies, stakeholder communications, and handoff tracking. Deployment approval and rollback authority follow the project's stated policy, not this role title alone.

---

## Project Sponsor / Business Stakeholder

### Role Summary
The Project Sponsor champions the business case, helps secure resources, and resolves escalated business-level trade-offs. Business stakeholders provide domain knowledge, feedback, or approvals only within authority explicitly assigned to them; not every stakeholder is an approver.

### Responsibilities
- Sponsor: confirm business alignment, support resourcing, and decide escalated business trade-offs
- Stakeholder: provide timely subject-matter input, review relevant deliverables, and state approval or consultation needs
- Communicate business constraints, dependencies, and decisions to the project team

### Goals
- Keep project decisions aligned with business needs and constraints
- Resolve escalations at the appropriate decision level
- Provide clear, timely input without obscuring ownership

### Typical Communication
- Initiation and milestone reviews, decision records, and sponsor escalations
- Domain feedback and approvals through agreed project channels

### Interactions with Existing Roles
- Aligns with PdMs on business outcomes and priority; the PdM translates outcomes into product direction and backlog decisions.
- Receives concise status and escalations from PMs and makes decisions within sponsor authority.
- Provides Developers with domain constraints through the PdM or agreed review process, avoiding conflicting or untracked direction.

---

## Customer Support / Customer Success Representative

### Role Summary
Customer Support / Customer Success Representatives prepare customer-facing teams for changes, help resolve customer-impacting issues, and bring post-release feedback back to the product team.

### Responsibilities
- Prepare support guidance, known-issue information, and customer enablement
- Coordinate customer-impact reporting and route issues to the right owners
- Gather recurring feedback and share it with the product team
- Confirm support handoff requirements before release

### Goals
- Make customer transitions clear and supportable
- Improve response to customer-impacting issues
- Turn customer feedback into actionable product insights

### Typical Communication
- Release briefings, support documentation, incident updates, and feedback summaries
- Coordination with customer-facing teams before and after deployment

### Interactions with Existing Roles
- Works with PdMs to share customer feedback and inform future prioritization; does not independently commit product scope.
- Works with Developers to provide issue details and help reproduce customer-reported problems.
- Coordinates with PMs on release announcements, support readiness, handoffs, and follow-up ownership.

---

## Security / Compliance Lead

### Role Summary
Security / Compliance Leads advise on security and applicable compliance requirements, coordinate reviews, and ensure security concerns reach the appropriate incident response path.

### Responsibilities
- Identify relevant security and compliance requirements and review evidence
- Advise on risk assessment and coordinate reviews with the team
- Track findings and recommended mitigations to closure or documented acceptance by an authorized owner
- Route security incidents through the security incident runbook and notify Security on-call

### Goals
- Address security and compliance risks early and consistently
- Make review findings, owners, and status visible
- Ensure incidents follow the established response process

### Typical Communication
- Security reviews, risk-register updates, compliance evidence, and incident channels
- Direct coordination with Security on-call for security incidents

### Interactions with Existing Roles
- Partners with Developers on secure implementation and remediation.
- Advises PdMs on security requirements and scope implications; product prioritization does not replace required security review.
- Works with PMs to track review milestones and project risks. Security incidents follow the security incident runbook rather than routine project escalation alone.

---

## Working Across Roles

- At initiation or planning, the PM and PdM clarify who is assigned to each responsibility, who can make each decision, and who must be consulted. In these docs, “Product Lead” means the PdM unless a project explicitly assigns a separate Product Lead and documents the distinction.
- A person may hold multiple roles in a small team. Combining roles does not remove responsibilities, required independent review, or approval requirements defined by project policy.
- For a release, the PdM confirms scope and acceptance criteria; Developers implement the change; QA records validation evidence; the authorized release owner confirms readiness and deploys; the PM coordinates status and stakeholder communication; Support receives customer guidance and the operational handoff. Unmet criteria or unresolved risks are escalated before proceeding under the project's release policy.
- Review ownership-related blockers, approval turnaround, escaped defects, and post-release handoff gaps in retrospectives and use findings to improve role assignments and process.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
