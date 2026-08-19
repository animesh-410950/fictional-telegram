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
- Work with **Tech Lead/Architect** on design reviews and technical direction
- Collaborate with **QA/Testing Lead** to ensure testability and acceptance criteria clarity
- Engage with **Product Managers** on feature requirements and prioritization
- Coordinate with **Project Managers** on status updates and timeline tracking
- Follow security guidance from **Security Engineer** during code reviews

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
- Define acceptance criteria with **QA/Testing Lead** for quality validation
- Work with **Tech Lead/Architect** to understand technical trade-offs
- Align with **Stakeholders/Sponsors** on business priorities and success metrics
- Collaborate with **Business Analysts** on requirement gathering and clarity
- Review security requirements with **Security Engineer** during feature planning

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
- Escalate blockers with input from all team members (Developers, QA, Tech Lead, etc.)
- Coordinate dependencies and timelines with **Tech Lead/Architect** on complex integrations
- Track QA and testing timelines with **QA/Testing Lead**
- Report progress to **Stakeholders/Sponsors** and manage expectations
- Flag security-related risks identified by **Security Engineer**
- Incorporate business requirements from **Business Analysts** into project scope

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and acceptance validation. They collaborate with development and product to define testability requirements and acceptance criteria.

### Responsibilities
- Develop comprehensive test plans and QA strategy for each feature
- Define acceptance testing approach, criteria, and test cases
- Execute manual and exploratory testing to validate features
- Triage and document defects with clear reproduction steps and severity levels
- Coordinate with developers on test coverage targets and CI integration
- Validate that features meet all acceptance criteria before release
- Review release readiness and recommend go/no-go decisions

### Goals
- Ensure features meet quality standards before release
- Reduce post-release defects and customer-impacting rework
- Maintain high test coverage and automated regression suites
- Improve team's testing discipline and quality mindset

### Typical Communication
- Test plan reviews and walkthroughs with Product Managers and Developers
- Daily standups focused on test progress and blockers
- Defect triage meetings with Developers
- Release readiness reports to Project Managers and Stakeholders

### Interaction with Other Roles
- Work closely with **Developers** to understand implementation details and coordinate testability
- Collaborate with **Product Managers** to clarify acceptance criteria and user scenarios
- Partner with **Tech Lead/Architect** on testing strategy for complex systems
- Report quality metrics and risks to **Project Managers** for timeline adjustments
- Coordinate with **Security Engineer** on security-focused test scenarios
- Validate requirements with **Business Analysts** to ensure test coverage aligns with business needs

---

## Security Engineer

### Role Summary
Security Engineers integrate security practices throughout the project lifecycle, from design review to deployment. They identify and mitigate security risks, ensuring compliance and reducing vulnerabilities.

### Responsibilities
- Participate in design reviews to identify security implications and risks
- Define security requirements and acceptance criteria for features
- Perform threat modeling and security architecture reviews
- Conduct code reviews with a focus on security vulnerabilities
- Advise on compliance requirements, data handling, and privacy considerations
- Validate security controls and perform security testing before release
- Respond to and investigate security-related incidents and escalations

### Goals
- Reduce security vulnerabilities in delivered features and production systems
- Maintain compliance with organizational security policies and regulatory standards
- Shift security considerations left by catching issues early in development
- Build a security-conscious culture within the project team

### Typical Communication
- Security review sessions during design and code phases
- Security requirements documentation and acceptance criteria
- Security incident response and investigation reports
- Compliance and risk assessment reports to stakeholders

### Interaction with Other Roles
- Review designs and code with **Developers** to identify and prevent vulnerabilities
- Define security acceptance criteria with **Product Managers** for features handling sensitive data
- Collaborate with **Tech Lead/Architect** on secure architecture patterns
- Coordinate security testing with **QA/Testing Lead** in the QA phase
- Escalate security risks through **Project Managers** to **Stakeholders/Sponsors**
- Work with **Business Analysts** to understand data flows and compliance requirements

---

## Tech Lead / Architect

### Role Summary
Tech Leads/Architects own technical direction, design, and architecture decisions for projects. They ensure scalability, maintainability, and alignment with technical standards and best practices.

### Responsibilities
- Define technical architecture, design patterns, and technology selections
- Lead design reviews and technical discussions with the development team
- Mentor Developers on best practices, code quality, and design principles
- Identify and help address technical debt and refactoring opportunities
- Make informed trade-off decisions between speed, quality, scalability, and maintainability
- Plan for scalability, performance, operational concerns, and monitoring
- Provide technical feasibility assessments and effort estimation guidance

### Goals
- Deliver technically sound, maintainable, and scalable solutions
- Reduce future rework, maintenance burden, and technical debt
- Build strong engineering capabilities and foster knowledge sharing
- Ensure systems can grow and adapt to future business needs

### Typical Communication
- Design review sessions and architectural decision records (ADRs)
- Technical mentoring and code review feedback
- Scalability and performance assessments
- Dependency and integration planning with other teams

### Interaction with Other Roles
- Guide **Developers** on architectural patterns, code structure, and best practices
- Collaborate with **Product Managers** to understand scalability and performance needs
- Work with **QA/Testing Lead** to define testing strategies for complex systems
- Advise **Project Managers** on technical dependencies and risk mitigation
- Review security-relevant design decisions with **Security Engineer**
- Align technical feasibility with **Business Analysts** on requirements
- Report technical risks and capacity to **Stakeholders/Sponsors** as needed

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders/Sponsors provide business context, approvals, and resources for projects. They represent customer and business needs and have authority to make key go/no-go decisions and resolve escalations.

### Responsibilities
- Approve project charter, milestones, and major scope changes
- Provide business context, success metrics, and measurable outcomes
- Make prioritization and trade-off decisions between competing initiatives
- Approve and allocate necessary resources (budget, headcount, tools)
- Communicate project status and progress to broader leadership and customers
- Escalate and resolve blockers that impact project success
- Validate that delivered solutions meet business objectives

### Goals
- Ensure projects deliver measurable business value and ROI
- Maintain alignment between project execution and organizational strategy
- Remove cross-functional and business-level blockers efficiently
- Support a culture of transparency and data-driven decision-making

### Typical Communication
- Monthly status briefings and milestone reviews
- Escalation resolution and priority-setting discussions
- Business case and ROI assessments
- Organizational announcements and communications

### Interaction with Other Roles
- Receive updates and escalations from **Project Managers** on status and risks
- Review business-focused deliverables and outcomes from **Product Managers**
- Resolve resource and priority conflicts between projects
- Approve security and compliance requirements identified by **Security Engineer**
- Validate success metrics and outcomes with **Product Managers**
- Provide business context and constraints to guide **Tech Lead/Architect** decisions
- Communicate project impact to broader organization

---

## Business Analyst (if applicable)

### Role Summary
Business Analysts bridge product and engineering by documenting requirements, acceptance criteria, and use cases. They ensure clarity and testability across functional boundaries.

### Responsibilities
- Gather and document detailed business requirements from stakeholders
- Create clear acceptance criteria, user stories, and test scenarios
- Facilitate discussions and alignment between product, engineering, and business teams
- Document business processes, rules, and workflows affected by features
- Validate that proposed solutions address identified business needs
- Create traceability between business requirements and technical implementation
- Support solution validation and user acceptance testing

### Goals
- Reduce requirement ambiguity and rework due to misalignment
- Improve cross-functional communication and collaboration
- Ensure solutions deliver measurable business value and user impact
- Create a shared understanding of requirements across all team members

### Typical Communication
- Requirements documentation and user story refinement sessions
- Facilitated workshops and stakeholder interviews
- Acceptance criteria reviews and walkthroughs
- Solution validation and UAT support

### Interaction with Other Roles
- Work with **Product Managers** to clarify and prioritize requirements
- Collaborate with **Developers** to ensure requirements are implementable and testable
- Partner with **QA/Testing Lead** to translate requirements into test scenarios
- Support **Tech Lead/Architect** with business context for technical decisions
- Engage **Stakeholders/Sponsors** to validate business requirements and success criteria
- Consult with **Security Engineer** on compliance and data-handling requirements
- Coordinate with **Project Managers** on requirements traceability and scope management

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction sections to understand cross-functional dependencies and collaboration patterns.
