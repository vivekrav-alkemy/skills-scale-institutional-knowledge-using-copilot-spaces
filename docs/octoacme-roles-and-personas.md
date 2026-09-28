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

### Interactions with Other Roles
- Work with **Product Managers** to clarify acceptance criteria and feature requirements
- Collaborate with **Project Managers** on task planning and timeline estimates
- Receive technical guidance from **Technical Leads/Architects** on design and feasibility
- Participate in code reviews with other **Developers**
- Provide test results and status updates to **QA/Testing Leads**
- Support **DevOps/Release Engineers** with deployment questions and troubleshooting

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

### Interactions with Other Roles
- Define requirements and acceptance criteria for **Developers**
- Coordinate timelines and scope with **Project Managers**
- Obtain technical feasibility input from **Technical Leads/Architects**
- Report project status and metrics to **Sponsors/Stakeholders**
- Review quality outcomes with **QA/Testing Leads**

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

### Interactions with Other Roles
- Work with **Developers** on effort estimates and capacity planning
- Align with **Product Managers** on scope and priority changes
- Coordinate with **Technical Leads/Architects** on technical dependencies and risks
- Manage escalations with **Sponsors/Stakeholders**
- Ensure **QA/Testing Leads** have resources and timeline for quality activities
- Coordinate with **DevOps/Release Engineers** on deployment schedules and windows

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy and execution. They define testing approaches, build automation frameworks, and validate that acceptance criteria are met before features reach production.

### Responsibilities
- Develop test plans and QA strategies for features
- Create and maintain automated test frameworks (unit, integration, E2E)
- Execute manual testing when automation doesn't fit
- Identify defects and work with developers on root causes
- Verify acceptance criteria and sign off on feature completion
- Participate in release readiness reviews and smoke testing
- Track quality metrics (test coverage, defect escape rate, cycle time)

### Goals
- Ensure all features meet acceptance criteria before release
- Reduce production defects through early and comprehensive testing
- Build maintainable, scalable test automation
- Support rapid iteration without compromising quality

### Typical Communication
- Acceptance criteria review sessions with PMs and developers
- Sprint planning to understand what's being built
- Daily standups to report test status and blockers
- Release verification calls and post-deploy validation

### Interactions with Other Roles
- Collaborate with **Developers** on test coverage and defect resolution
- Review acceptance criteria with **Product Managers** to understand what "done" means
- Report quality metrics and risks to **Project Managers**
- Receive design context from **Technical Leads/Architects**
- Coordinate release readiness activities with **DevOps/Release Engineers**
- Provide quality assurance sign-off to **Sponsors/Stakeholders** for releases

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide technical strategy, design decisions, and help teams navigate complexity. They work with developers and product to ensure solutions are feasible, scalable, and aligned with the technical vision.

### Responsibilities
- Define technical approach and architecture for major features
- Conduct design reviews and provide feedback on proposed solutions
- Identify technical risks and propose mitigations
- Mentor developers and help them grow technical skills
- Contribute to platform standards and best practices
- Support capacity planning and technical dependency identification
- Escalate technical risks to Product Lead and PM

### Goals
- Deliver scalable, maintainable, and performant solutions
- Reduce technical debt and system complexity
- Empower team to make good technical decisions
- Balance speed with sustainability

### Typical Communication
- Technical design discussions and code reviews
- Planning sessions to assess feasibility and effort
- Architecture decision records (ADRs) when warranted
- Regular technical risk updates in PM syncs

### Interactions with Other Roles
- Guide **Developers** on design patterns, architecture, and best practices
- Advise **Product Managers** on technical feasibility and trade-offs
- Provide technical risk assessments to **Project Managers** for risk registers
- Support **QA/Testing Leads** with testability guidance and design insights
- Collaborate with **DevOps/Release Engineers** on deployment architecture and scalability
- Escalate architectural risks and decisions to **Sponsors/Stakeholders** when needed

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers own CI/CD pipelines, deployment infrastructure, and support the reliable, safe release of features to production.

### Responsibilities
- Design and maintain CI/CD pipelines for testing and deployment
- Manage infrastructure, configuration, and secrets securely
- Document deployment processes and runbooks
- Support pre-release verification (staging, smoke tests)
- Execute production deployments and monitor post-deploy health
- Troubleshoot deployment issues and support rollback if needed
- Collect and share deployment metrics and incident data

### Goals
- Enable frequent, safe, and reliable deployments
- Reduce deployment risk and time-to-recovery from incidents
- Maintain high system availability and observability
- Automate repetitive deployment tasks

### Typical Communication
- Release planning calls and deployment window coordination
- Incident response and post-mortems
- Infrastructure capacity and change planning
- Feedback on CI/CD pipeline effectiveness

### Interactions with Other Roles
- Support **Developers** with CI/CD tooling and deployment troubleshooting
- Provide deployment readiness updates to **Project Managers**
- Coordinate release windows and deployment strategy with **Product Managers**
- Partner with **QA/Testing Leads** on staging environment setup and smoke testing
- Implement deployment recommendations from **Technical Leads/Architects**
- Execute releases approved by **Sponsors/Stakeholders** and report post-deployment status

---

## Sponsor / Stakeholder (Executive)

### Role Summary
Sponsors and key stakeholders provide business context, approve major trade-offs, and serve as escalation authority for blockers that impact timeline, scope, or budget.

### Responsibilities
- Define business goals and success metrics for the project
- Approve project charter, timeline, and resource allocation
- Escalate and resolve business-impacting blockers
- Communicate project status to broader leadership
- Adjust priorities and trade-offs based on business needs
- Provide feedback and feedback loops from customers/market

### Goals
- Ensure project delivers measurable business value
- Remove organizational blockers
- Maintain stakeholder confidence and support

### Typical Communication
- Monthly stakeholder updates and reviews
- Ad-hoc escalation calls when needed
- Quarterly business review of outcomes and metrics

### Interactions with Other Roles
- Receive project status and risk reports from **Project Managers**
- Review business outcomes and feature impact with **Product Managers**
- Approve scope and timeline changes that impact **Developers** and team resources
- Provide business context and priorities to **Technical Leads/Architects** for trade-off decisions
- Sign off on release readiness from **QA/Testing Leads** and **DevOps/Release Engineers**
- Support escalation of deployment or incident issues from the delivery team

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
