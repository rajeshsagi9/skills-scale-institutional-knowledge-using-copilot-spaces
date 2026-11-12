# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Assign roles according to project size and risk; one person may hold more than one role when appropriate, but ownership and decision authority should remain explicit.

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

### Ownership, Decisions, and Collaboration
- Own the implementation quality of assigned work and raise technical issues early.
- Make day-to-day implementation decisions within agreed architecture and security requirements; escalate material design or scope trade-offs to the Technical Lead and Product Manager.
- Work with QA/Testing on testability and defect resolution, DevOps/SRE on build and operational needs, and Security/Privacy on required controls.
- Hand off completed work with tests, documentation, and deployment considerations ready for review.

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

### Ownership, Decisions, and Collaboration
- Own product outcomes, priority, and acceptance criteria, informed by users and stakeholders.
- Decide product scope and priority; consult the Technical Lead on feasibility and the Project Manager on delivery impact. Escalate decisions outside delegated authority to the sponsor or relevant stakeholders.
- Partner with UX/UI on user needs and experience, QA/Testing on acceptance, and Customer Support/Operations on readiness and feedback.
- Confirm product acceptance against agreed criteria and feed outcome measures into future prioritization.

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

### Ownership, Decisions, and Collaboration
- Own the integrated delivery plan, coordination, reporting, and escalation process—not product priority or technical design.
- Coordinate sequencing, milestones, and responses to delivery risks with accountable role owners; bring scope, resource, or schedule trade-offs to the Product Manager and stakeholders for decisions.
- Gather readiness inputs from QA/Testing, DevOps/SRE, Security/Privacy, and Customer Support/Operations before release milestones.
- Maintain decisions, dependencies, and handoffs in the project’s agreed source of truth.

---

## QA/Testing Lead

### Role Summary
The QA/Testing Lead defines the test approach and coordinates evidence that a change meets its acceptance criteria and quality expectations. The role may be held by a dedicated tester or shared by team members on smaller projects.

### Responsibilities
- Establish a risk-based test plan covering relevant unit, integration, end-to-end, and manual testing.
- Review requirements and acceptance criteria for clarity, testability, and coverage.
- Coordinate test execution, record results, and prioritize defect triage with Developers and the Product Manager.
- Report quality risks and readiness evidence; verify fixes and regression coverage.

### Goals
- Detect important defects early and provide transparent release-quality evidence.
- Ensure critical customer flows and acceptance criteria are validated.

### Typical Communication
- Test plans, test results, and defect reports
- QA checkpoints in delivery and release readiness reviews
- Daily coordination with Developers and updates to the Project Manager on blockers

### Ownership, Decisions, and Collaboration
- Own the test strategy and communicate quality status; do not unilaterally change product scope or waive acceptance criteria.
- Partner with the Product Manager to interpret acceptance criteria, with Developers to build testable changes and resolve defects, and with DevOps/SRE on test environments and release verification.
- Provide the Project Manager with evidence and unresolved risks for readiness tracking. Escalate critical quality concerns to the Product Manager and Project Manager before release decisions.
- Expected outputs include a test approach, execution results, and a clear list of defects or accepted residual risks.

---

## Technical Lead/Architect

### Role Summary
The Technical Lead/Architect guides technical design, architecture, and integration decisions so the solution is maintainable, feasible, and aligned with agreed constraints.

### Responsibilities
- Facilitate design decisions and document significant architecture choices.
- Identify integration points, technical dependencies, and maintainability risks.
- Support estimation and decomposition with Developers; review implementation for consistency with agreed design.
- Advise on technical options, constraints, and migration implications.

### Goals
- Deliver a coherent, reliable technical solution that supports product outcomes.
- Reduce avoidable technical risk and make important trade-offs visible.

### Typical Communication
- Design proposals and architecture decision records
- Technical planning and code reviews
- Dependency and risk updates with the Project Manager

### Ownership, Decisions, and Collaboration
- Own technical direction within the project’s agreed architecture and engineering standards; consult affected teams for cross-system changes.
- Work hands-on with Developers on design and implementation, advise the Product Manager on feasibility and options, and report technical dependencies and risks to the Project Manager.
- Collaborate with Security/Privacy and DevOps/SRE to incorporate controls, deployment, reliability, and observability needs early.
- Escalate decisions that materially change scope, cost, risk, or organizational architecture to the appropriate product and technical decision-makers. Expected outputs include design decisions, integration guidance, and technical risk mitigations.

---

## UX/UI Designer or Researcher

### Role Summary
The UX/UI Designer or Researcher brings user evidence and interaction design into discovery and delivery, helping ensure the product is understandable, accessible, and useful.

### Responsibilities
- Plan or conduct user research and synthesize findings.
- Create user journeys, interaction designs, prototypes, and usability guidance as appropriate.
- Identify accessibility and usability needs and incorporate them into design recommendations.
- Validate designs with users or other appropriate evidence and share findings with the team.

### Goals
- Improve customer outcomes through clear, usable, and inclusive experiences.
- Reduce uncertainty about user needs before implementation decisions are costly.

### Typical Communication
- Research summaries, design artifacts, and usability findings
- Design reviews with Product Managers and Developers
- Validation and accessibility discussions with QA/Testing

### Ownership, Decisions, and Collaboration
- Own the quality and rationale of research and design recommendations; the Product Manager remains accountable for product priorities and scope.
- Partner with the Product Manager to connect user needs to outcomes and acceptance criteria, and with Developers and the Technical Lead to assess feasibility.
- Work with QA/Testing to make important experience and accessibility expectations verifiable, and with Customer Support/Operations to incorporate recurring customer issues.
- Hand off designs, findings, and open questions before implementation; flag evidence that suggests revisiting scope or assumptions.

---

## DevOps/SRE

### Role Summary
DevOps/SRE helps teams build, deploy, and operate services reliably, with appropriate automation, observability, and incident readiness.

### Responsibilities
- Maintain or advise on CI/CD, deployment automation, infrastructure, and environments.
- Define or improve monitoring, alerting, reliability practices, and operational documentation.
- Assess operational readiness, capacity, recovery, and rollback considerations.
- Support incident response and contribute operational learning to follow-up actions.

### Goals
- Make releases repeatable and services observable and recoverable.
- Reduce deployment risk and improve service reliability.

### Typical Communication
- Deployment plans, runbooks, dashboards, and reliability reviews
- Release readiness coordination with QA/Testing and the Project Manager
- Incident updates with Developers and Customer Support/Operations

### Ownership, Decisions, and Collaboration
- Own or advise on operational standards and the reliability of deployment and runtime practices; service-specific ownership is agreed by the team.
- Partner with Developers on automation, infrastructure, and instrumentation; with QA/Testing on environments and smoke-test verification; and with the Project Manager on release windows, dependencies, and incident coordination.
- Coordinate with Security/Privacy on operational controls and with Customer Support/Operations on service-impact communications.
- Provide operational readiness evidence and runbooks. Escalate reliability or deployment risks to the Project Manager and relevant technical decision-makers before release.

---

## Security/Privacy Lead

### Role Summary
The Security/Privacy Lead advises the team on security and privacy requirements, threat and data risks, and appropriate risk treatment throughout delivery.

### Responsibilities
- Identify applicable security, privacy, and data-handling requirements with stakeholders.
- Review designs and data flows for risks and recommend proportionate controls.
- Coordinate security reviews or assessments and track findings to resolution or explicit risk acceptance.
- Help ensure security scanning, privacy considerations, and incident escalation paths are addressed.

### Goals
- Reduce security and privacy risk while enabling delivery of the intended product outcomes.
- Make control requirements and residual risks visible and actionable.

### Typical Communication
- Security/privacy requirements and review findings
- Design reviews with the Technical Lead and Product Manager
- Risk register updates and release readiness discussions

### Ownership, Decisions, and Collaboration
- Own security and privacy advice and assessment findings; formal risk acceptance follows the organization’s designated authority and is not assumed to belong to this role alone.
- Partner with the Product Manager and stakeholders to clarify requirements, the Technical Lead and Developers to design and implement controls, and QA/Testing and DevOps/SRE to verify controls in testing and operations.
- Inform the Project Manager of material risks, mitigations, owners, and decision deadlines so they can be tracked and escalated.
- Escalate urgent or high-impact concerns through the security incident process and designated Security on-call; expected outputs include requirements, review findings, and tracked mitigations.

---

## Customer Support/Operations Representative

### Role Summary
The Customer Support/Operations Representative represents customer-facing and operational needs, helping the team prepare for launch and connect post-release feedback to product decisions.

### Responsibilities
- Share customer pain points, support trends, and operational constraints during discovery and planning.
- Review support impact and contribute to help content, FAQs, and escalation procedures.
- Prepare support teams for changes, including known issues and release timing.
- Relay post-release issues and usage feedback to Product Managers and the delivery team.

### Goals
- Ensure customer-facing teams can support changes effectively.
- Shorten the path from customer feedback or incidents to informed product and operational action.

### Typical Communication
- Support-readiness reviews and release notes
- Customer issue trends, FAQs, and known-issue summaries
- Post-release feedback and incident coordination with Product Managers and the Project Manager

### Ownership, Decisions, and Collaboration
- Own support-readiness inputs and customer issue communication in coordination with the relevant support organization; does not determine product priority alone.
- Work with the Product Manager to connect customer evidence to product decisions, with UX/UI to share user pain points, and with Developers and QA/Testing to clarify reported defects and verification.
- Coordinate with DevOps/SRE on operational impact and incident communications, and with the Project Manager on readiness milestones and stakeholder updates.
- Hand off recurring feedback and unresolved customer impacts to the Product Manager; expected outputs include support materials, known issues, and feedback summaries.

---

## Stakeholders and Sponsors

### Role Summary
Stakeholders provide domain expertise, constraints, feedback, and approvals; sponsors provide direction and decisions for matters escalated beyond the team’s delegated authority.

### Responsibilities
- Clarify business, user, regulatory, or operational needs and relevant constraints.
- Review proposals and deliverables at agreed decision gates.
- Make or obtain decisions when trade-offs exceed the authority delegated to the delivery team.

### Goals
- Ensure the work is aligned with business objectives and stakeholder needs.
- Resolve escalated decisions in a timely and transparent way.

### Typical Communication
- Initiation and milestone reviews
- Weekly or milestone-based status updates and decision requests
- Escalations, approvals, and release communications as appropriate

### Ownership, Decisions, and Collaboration
- Own decisions explicitly assigned to them, such as sponsorship, funding, or cross-organizational trade-offs; the Product Manager continues to own product priority within their remit.
- Provide timely input to the Product Manager and Project Manager, who coordinate requirements, plans, risks, and decision records.
- Consult relevant specialists—including Technical Lead, QA/Testing, Security/Privacy, DevOps/SRE, UX/UI, and Customer Support/Operations—before decisions that affect their areas of expertise.

---

## Lifecycle Handoffs and Role Assignment

- **Initiation and discovery:** Product Managers define the problem and desired outcomes with stakeholders; UX/UI and Customer Support/Operations contribute user and customer evidence; the Project Manager coordinates alignment and the initial risk and dependency picture.
- **Planning:** The Product Manager prioritizes outcomes and acceptance criteria. The Project Manager coordinates the plan and capacity. The Technical Lead, QA/Testing, Security/Privacy, DevOps/SRE, and UX/UI identify design, test, control, operational, and usability needs before work is ready.
- **Execution:** Developers deliver increments with ongoing input from the Technical Lead, QA/Testing, UX/UI, and Security/Privacy. The Project Manager tracks progress and dependencies; the Product Manager resolves product questions and priority trade-offs.
- **Release:** QA/Testing reports validation evidence; DevOps/SRE reports operational readiness and rollback considerations; Security/Privacy communicates outstanding risks; Customer Support/Operations prepares customer-facing readiness. The Product Manager confirms product acceptance and the Project Manager coordinates the decision and communications with the designated approvers.
- **Post-release and improvement:** DevOps/SRE and Customer Support/Operations surface reliability and customer signals; Product Managers use outcomes to guide priorities; the Project Manager coordinates retrospective actions with named owners.

Roles advise and decide within their stated authority. When authority or risk acceptance is unclear, record the decision owner, consult affected roles, and escalate through the Project Manager to the Product Lead, sponsor, or designated specialist/on-call process as appropriate. For smaller projects, combine roles where practical, but retain the responsibilities, necessary reviews, and explicit handoffs.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
