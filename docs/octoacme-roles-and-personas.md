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
- **Product Managers**: Review acceptance criteria and prioritization; receive feedback on feasibility
- **Project Managers**: Participate in planning and capacity discussions
- **QA/Testing Lead**: Collaborate on test coverage and quality standards
- **Technical Lead/Architect**: Follow technical guidance and design patterns
- **Release Manager**: Coordinate on PR completion and deployment readiness

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
- **Project Managers**: Weekly sync on priorities, timeline, and resource constraints
- **Developers**: Define acceptance criteria and success metrics; review implementation
- **Stakeholders/Sponsors**: Communicate business value and trade-offs; seek approval on priorities
- **QA/Testing Lead**: Define quality acceptance criteria and measurement of success
- **Technical Lead/Architect**: Align on technical feasibility and scalability concerns

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
- **Product Managers**: Weekly sync on backlog, priorities, and metrics
- **Developers**: Daily standups; track progress and blockers
- **Stakeholders/Sponsors**: Regular status updates and escalation path
- **Release Manager**: Coordinate on release timelines and deployment planning
- **Technical Lead/Architect**: Monitor technical dependencies and risks

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads coordinate test planning, validate quality standards, and ensure acceptance criteria are met. They bridge product requirements with quality assurance and collaborate across development, product, and stakeholders to deliver high-quality outcomes.

### Responsibilities
- Define test strategy and acceptance criteria in collaboration with Product Managers and Developers
- Coordinate test planning for features and releases
- Validate that acceptance criteria are met before release
- Identify quality gaps and recommend mitigations
- Coordinate manual and automated testing efforts
- Ensure test coverage meets organizational standards
- Track and triage quality issues and defects

### Goals
- Deliver high-quality, reliable features
- Reduce production defects and post-release issues
- Enable fast, confident releases through thorough validation
- Improve clarity on quality expectations across the team

### Typical Communication
- Test planning sessions with Developers and Product Managers
- Quality gate checkpoints before release
- Defect reports and quality metrics
- Acceptance criteria review and sign-off

### Interactions with Other Roles
- **Developers**: Collaborate on test coverage; provide feedback on code quality and test design
- **Product Managers**: Define quality acceptance criteria and measure success metrics
- **Project Managers**: Report on quality status; flag quality-related blockers and timeline impacts
- **Stakeholders/Sponsors**: Communicate quality readiness before releases
- **Release Manager**: Validate quality gates before deployment approval

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approve strategic decisions, and serve as the escalation path for critical issues. They represent business priorities, customer needs, and organizational constraints.

### Responsibilities
- Provide business context and strategic priorities
- Approve project charters and high-level scope
- Participate in project initiation and kickoff meetings
- Make or escalate critical trade-off decisions
- Approve resource allocations and team commitments
- Receive and act on regular status updates
- Communicate project value to broader organization
- Escalate blockers and risks that require executive resolution

### Goals
- Ensure projects deliver business and customer value
- Maintain alignment between project work and organizational strategy
- Reduce surprise issues and unplanned escalations
- Enable fast decision-making by providing timely approvals

### Typical Communication
- Monthly stakeholder updates and reports
- Initiation meetings and project approvals
- Ad-hoc escalations when critical blockers arise
- Release announcements and post-launch reviews

### Interactions with Other Roles
- **Project Managers**: Receive status updates and escalations; provide approvals
- **Product Managers**: Discuss business priorities, trade-offs, and strategic alignment
- **Developers**: Participate in kickoffs; may provide context on business constraints
- **Release Manager**: Receive release notifications and deployment updates
- **Technical Lead/Architect**: Consult on large technical decisions or technical risks

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects define technical approaches, guide implementation decisions, and identify technical risks and dependencies. They ensure solutions are scalable, maintainable, and align with organizational technical standards.

### Responsibilities
- Define technical approach and architecture for complex features
- Review and provide guidance on implementation patterns and design decisions
- Identify technical risks, dependencies, and integration points
- Advocate for code quality, scalability, and maintainability
- Mentor and support Developers on technical best practices
- Coordinate technical dependencies across teams
- Escalate technical blockers and unforeseen technical risks

### Goals
- Deliver technically sound, maintainable, and scalable solutions
- Reduce technical debt and long-term maintenance burden
- Enable fast, confident delivery through clear technical guidance
- Build team capability in technical practices and patterns

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and guidance
- Risk escalation and dependency coordination
- Technical mentoring and documentation

### Interactions with Other Roles
- **Developers**: Provide technical guidance, review designs, mentor on best practices
- **Product Managers**: Consult on technical feasibility and trade-offs
- **Project Managers**: Flag technical risks, dependencies, and timeline impacts
- **QA/Testing Lead**: Define technical test strategy and testability requirements
- **Release Manager**: Coordinate technical readiness and deployment considerations

---

## Release Manager

### Role Summary
Release Managers coordinate release planning, manage the deployment process, and communicate release status to stakeholders. They ensure consistent, predictable, and low-risk deployments through standardized checklists and clear communication.

### Responsibilities
- Coordinate release planning and scheduling with Project and Product Managers
- Manage and verify pre-release checklists (acceptance criteria, testing, security scans, etc.)
- Coordinate smoke testing and final validation before deployment
- Execute or coordinate deployment to staging and production environments
- Communicate release status and deployment windows to stakeholders
- Manage rollback procedures if issues arise post-deployment
- Coordinate post-deployment verification and monitoring
- Prepare and communicate release notes and known issues

### Goals
- Deliver releases consistently and predictably
- Minimize deployment risk and production incidents
- Reduce time from merge to production
- Maintain stakeholder confidence through clear, timely communication

### Typical Communication
- Release planning meetings with PM and developers
- Pre-release checklists and status updates
- Deployment notifications to stakeholders
- Post-deployment verification and incident reporting

### Interactions with Other Roles
- **Project Managers**: Align on release timelines, milestones, and deployment windows
- **Developers**: Coordinate on PR completion, merge timing, and deployment readiness
- **QA/Testing Lead**: Verify quality gates and obtain testing sign-off before deployment
- **Product Managers**: Communicate release scope and timeline; coordinate feature announcements
- **Stakeholders/Sponsors**: Notify of deployment status and post-launch readiness
- **Security/Compliance Officer**: Verify security scanning and compliance before deployment

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers review security requirements, validate security scanning results, and advise on incident response. They ensure projects meet organizational security standards and compliance obligations.

### Responsibilities
- Define security requirements and standards for projects
- Review security scanning results in CI/CD pipelines
- Provide guidance on secure coding practices and architectural patterns
- Conduct security reviews for critical features or releases
- Participate in incident response for security-related issues
- Escalate security risks and compliance concerns
- Maintain and communicate security policies and best practices
- Coordinate with external security audits or compliance reviews

### Goals
- Deliver secure, compliant solutions that protect customer and organizational data
- Reduce security incidents and vulnerabilities in production
- Enable fast, secure delivery through clear security guidance
- Maintain organizational compliance with regulatory and industry standards

### Typical Communication
- Security reviews and architecture consultation
- Feedback on security scanning results
- Security incident escalation and response
- Compliance and audit coordination

### Interactions with Other Roles
- **Developers**: Provide secure coding guidance; review implementation for security best practices
- **Technical Lead/Architect**: Consult on secure architectural patterns and security trade-offs
- **Project Managers**: Flag security risks and compliance concerns; coordinate incident response
- **QA/Testing Lead**: Coordinate on security testing and validation
- **Release Manager**: Verify security scanning completion and approve security readiness for deployment
- **Stakeholders/Sponsors**: Escalate critical security issues or compliance concerns

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
