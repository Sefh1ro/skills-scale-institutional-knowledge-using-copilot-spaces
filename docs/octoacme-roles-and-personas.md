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

### Interaction with Other Roles
- Partner with QA/Testing Leads to ensure acceptance criteria are testable and quality gates are met
- Collaborate with Technical Leads on architecture and design decisions
- Work with Product Managers and Product Owners to refine requirements and validate solutions

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

### Interaction with Other Roles
- Work closely with Product Owners/Domain Experts to refine and validate business requirements
- Partner with Stakeholders/Sponsors for strategic alignment and resource decisions
- Collaborate with QA/Testing Leads on success metrics and acceptance validation

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

### Interaction with Other Roles
- Escalate technical risks and security concerns identified by Technical Leads and Security/Compliance Officers
- Coordinate with Stakeholders/Sponsors on resource allocation and scope changes
- Partner with QA/Testing Leads to ensure quality milestones are tracked and met

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute quality assurance strategies, own test automation, and validate that features meet acceptance criteria and quality standards before release.

### Responsibilities
- Develop test plans and test cases aligned with acceptance criteria
- Own and maintain test automation frameworks and CI test pipelines
- Execute manual QA and exploratory testing as needed
- Validate acceptance criteria with developers and product teams
- Coordinate smoke tests and release verification
- Report test metrics and defect trends to PM and delivery team

### Goals
- Ensure quality standards are met before release
- Reduce post-release defects through comprehensive testing
- Enable fast, confident deployments via automated testing

### Typical Communication
- Sprint planning and backlog refinement meetings
- Test status updates in standups and weekly syncs
- Defect reports and release readiness sign-off

### Interaction with Other Roles
- Collaborate with Developers to understand implementation and ensure testability
- Partner with Product Managers and Product Owners to validate acceptance criteria before implementation
- Work with Security/Compliance Officers to include security testing in test plans
- Support Project Managers with quality metrics and release readiness assessments

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors are business or executive leaders who approve project initiation, allocate resources, and receive strategic updates on project progress and risks.

### Responsibilities
- Review and approve project charters and business cases
- Allocate budget, headcount, and other resources
- Provide business context and customer perspective
- Receive and act on escalated risks and issues
- Approve major scope changes or release decisions
- Advocate for the project within the organization

### Goals
- Ensure projects align with business strategy
- Minimize business impact from delays or risks
- Support team success through resource and political support

### Typical Communication
- Project initiation and approval meetings
- Monthly or milestone-based stakeholder briefings
- Ad-hoc escalation and decision requests

### Interaction with Other Roles
- Partner with Project Managers for escalations and strategic decisions
- Collaborate with Product Managers on business priorities and success metrics
- Provide governance and oversight during project lifecycle stages

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure projects meet security and regulatory requirements, integrate security controls into delivery pipelines, and lead incident response.

### Responsibilities
- Review project plans for security and compliance implications
- Define security acceptance criteria and controls
- Enable security scanning and SAST/DAST in CI/CD
- Lead security incident response and triage
- Maintain security runbooks and post-incident reviews
- Provide security training and guidance to teams

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure compliance with regulatory and corporate policies
- Enable rapid response to security incidents

### Typical Communication
- Planning and design review meetings (security check-in)
- Security incident notifications and escalations
- Post-incident retrospectives and action items

### Interaction with Other Roles
- Collaborate with Technical Leads on architecture and security design decisions
- Partner with Developers to integrate security best practices and scanning into CI/CD
- Work with QA/Testing Leads to include security testing in test plans
- Escalate security risks to Project Managers and Stakeholders/Sponsors

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects provide technical strategy, own architectural decisions, and help teams navigate complex technical challenges during project planning and execution.

### Responsibilities
- Define or review technical architecture and design proposals
- Identify technical risks and propose mitigations
- Mentor developers on technical best practices
- Participate in design reviews and technical spike planning
- Help estimate technical complexity and dependencies
- Advocate for technical debt reduction and refactoring

### Goals
- Deliver scalable, maintainable technical solutions
- Reduce technical risk and rework
- Accelerate delivery through clear technical direction

### Typical Communication
- Kickoff and planning meetings
- Technical design review sessions
- Standups and escalation of technical blockers
- Architecture decision records (ADRs)

### Interaction with Other Roles
- Partner with Developers to mentor on technical best practices and design decisions
- Collaborate with Security/Compliance Officers on security architecture and threat modeling
- Work with Project Managers to identify and mitigate technical risks and dependencies
- Advise Product Managers on technical feasibility and trade-offs

---

## Product Owner / Domain Expert

### Role Summary
Product Owners and Domain Experts are subject matter experts who collaborate with Product Managers and developers to refine requirements and validate that solutions meet domain-specific criteria.

### Responsibilities
- Provide domain knowledge and context to product and delivery teams
- Refine user stories and acceptance criteria with Product Managers
- Validate solutions against domain-specific business rules
- Participate in backlog grooming and sprint planning
- Support UAT and acceptance testing
- Share subject matter expertise in design and technical reviews

### Goals
- Ensure solutions are domain-correct and business-ready
- Reduce rework from misunderstood requirements
- Accelerate decision-making through clear domain guidance

### Typical Communication
- Backlog refinement and story grooming sessions
- Sprint planning and standups (as needed)
- Acceptance criteria reviews with developers
- User acceptance testing (UAT) coordination

### Interaction with Other Roles
- Partner with Product Managers to refine requirements and ensure business alignment
- Collaborate with Developers to validate implementation against domain rules
- Work with QA/Testing Leads to ensure domain-specific acceptance criteria are tested
- Support Stakeholders/Sponsors with domain expertise on feasibility and customer impact

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction patterns to understand how roles collaborate across the project lifecycle.
