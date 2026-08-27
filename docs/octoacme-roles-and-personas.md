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

## Quality Assurance (QA) Lead

### Role Summary
QA Leads own the testing strategy, validate acceptance criteria, and ensure quality standards are met before release. They work closely with developers, product managers, and project managers to define and execute comprehensive test plans.

### Responsibilities
- Define testing strategy and test plans for features and releases
- Validate acceptance criteria with product and development teams
- Execute manual and coordinate automated testing
- Identify, document, and track quality issues and defects
- Participate in release readiness reviews and gate decisions
- Establish quality metrics and monitor test coverage

### Goals
- Ensure high-quality, reliable releases
- Prevent critical issues from reaching production
- Reduce rework and improve team velocity
- Enable confident decision-making at release gates

### Typical Communication
- Quality metrics and test reports in weekly syncs
- Release readiness assessments and go/no-go recommendations
- Defect tracking and prioritization with development team
- Sprint planning participation for test estimation

### Interaction with Other Roles
- **Developers**: Collaborate on test scenarios, automation frameworks, and bug reproduction
- **Product Managers**: Clarify acceptance criteria and validate feature completeness
- **Project Managers**: Provide quality status updates and escalate release blockers
- **DevOps/Release Engineers**: Coordinate testing in staging environments and post-deployment verification

---

## Technical Architect

### Role Summary
Technical Architects provide technical guidance and governance, evaluate design tradeoffs, and identify scalability and infrastructure concerns. They work across teams to ensure technical decisions align with long-term vision and organizational standards.

### Responsibilities
- Review and provide feedback on technical designs and architecture decisions
- Evaluate scalability, performance, and security implications of proposed solutions
- Identify technical risks and propose mitigation strategies
- Recommend technology choices and frameworks aligned with organizational standards
- Support infrastructure and deployment planning with engineering teams
- Mentor developers on technical best practices and design patterns

### Goals
- Enable scalable, maintainable technical solutions
- Reduce technical debt and future rework
- Support organizational technical strategy and standards
- Accelerate decision-making by clarifying technical tradeoffs

### Typical Communication
- Design review participation and technical guidance documents
- Architecture decision records (ADRs) and technical memos
- Risk assessment and mitigation recommendations
- Ad-hoc consultations on technical tradeoffs

### Interaction with Other Roles
- **Developers**: Provide technical direction, review designs, and support implementation
- **Product Managers**: Advise on technical feasibility and explain tradeoffs
- **Project Managers**: Identify technical risks and dependencies for project planning
- **DevOps/Release Engineers**: Collaborate on infrastructure and deployment architecture

---

## Scrum Master / Delivery Coordinator

### Role Summary
Scrum Masters (or Delivery Coordinators in non-Scrum contexts) facilitate ceremonies, remove impediments, and help maintain team velocity and productivity. They serve as process enablers and servant leaders, supporting the team's ability to deliver incrementally.

### Responsibilities
- Schedule and facilitate sprint ceremonies (planning, standups, reviews, retrospectives)
- Identify and help resolve impediments blocking team progress
- Track team velocity and highlight capacity concerns
- Maintain sprint boards and project artifacts
- Coach team members on agile practices and mindset
- Escalate persistent blockers to Project Manager or stakeholders

### Goals
- Maintain consistent team rhythm and predictable delivery
- Maximize team efficiency and reduce context-switching
- Foster continuous improvement and psychological safety
- Support team self-organization and accountability

### Typical Communication
- Sprint planning and retrospective facilitation
- Daily standup summaries highlighting blockers
- Velocity and burndown metrics to PM and PdM
- One-on-ones with team members to address concerns

### Interaction with Other Roles
- **Developers**: Facilitate planning, remove impediments, protect from interruptions
- **Product Managers**: Ensure backlog clarity and prioritization at planning meetings
- **Project Managers**: Escalate risks and blockers; coordinate with dependencies
- **All roles**: Support agile ceremonies and retrospective action items

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide high-level business perspective, decision authority, and strategic direction for projects. They champion initiatives, allocate resources, and ensure alignment with organizational priorities.

### Responsibilities
- Provide business context and strategic alignment for project decisions
- Approve project scope, timeline, and resource allocation
- Participate in key project milestones and decision gates
- Escalate organizational barriers and secure necessary resources
- Communicate project importance to broader organization
- Make or unblock trade-off decisions when needed

### Goals
- Ensure projects deliver business value aligned with strategy
- Remove organizational blockers and secure stakeholder buy-in
- Maintain executive visibility and support for project success
- Enable timely decision-making at project gates

### Typical Communication
- Project initiation and milestone reviews
- Monthly or quarterly stakeholder status updates
- Escalation of business-critical risks and decisions
- Resource allocation and priority alignment discussions

### Interaction with Other Roles
- **Project Managers**: Sponsor provides authority, guidance, and escalation path
- **Product Managers**: Align on business objectives and success metrics
- **Developers**: Communicate project importance and business context
- **All roles**: Provide decision authority and remove organizational barriers

---

## UX/Design Lead

### Role Summary
UX/Design Leads define user experience requirements, establish design standards, and validate usability with end users. They ensure solutions are intuitive, accessible, and aligned with user needs and organizational design systems.

### Responsibilities
- Conduct user research and define user personas and journey maps
- Create wireframes, prototypes, and design specifications
- Establish and maintain design system standards and component libraries
- Validate designs through user testing and feedback
- Collaborate with product and development teams on implementation
- Ensure accessibility compliance and cross-platform consistency

### Goals
- Deliver intuitive, accessible user experiences
- Reduce usability issues and user friction
- Build consistent, recognizable product identity
- Enable data-informed design decisions

### Typical Communication
- Design specifications and component documentation
- User research findings and usability testing results
- Design system updates and component library maintenance
- Design review participation with developers and product teams

### Interaction with Other Roles
- **Product Managers**: Align on user needs and feature priorities
- **Developers**: Review implementation fidelity to design specifications
- **QA/Testing**: Validate usability and accessibility compliance
- **Project Managers**: Participate in planning for design validation activities

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers manage CI/CD pipelines, deployment infrastructure, and production monitoring. They enable teams to deploy reliably and observe system health in production.

### Responsibilities
- Build and maintain CI/CD pipelines and automation
- Manage deployment infrastructure and environments (staging, production)
- Execute or coordinate production deployments
- Monitor system health, performance, and error rates in production
- Support rollback procedures and incident response
- Establish deployment standards, runbooks, and playbooks

### Goals
- Enable safe, rapid, repeatable deployments
- Reduce time-to-recovery from incidents
- Maintain high system reliability and observability
- Minimize manual work and human error in deployment

### Typical Communication
- Deployment coordination and runbook documentation
- Production monitoring dashboards and alerts
- Incident response and post-mortem participation
- Release readiness assessments with QA and Project Managers

### Interaction with Other Roles
- **Developers**: Support local development, CI pipeline configuration, and troubleshooting
- **QA/Testing**: Coordinate staging deployments and testing infrastructure
- **Project Managers**: Provide deployment schedules and release coordination
- **Technical Architect**: Collaborate on infrastructure design and deployment architecture

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

## Cross-Functional Collaboration Matrix

| Activity | Developer | Product Manager | Project Manager | QA Lead | Technical Architect | Scrum Master | Stakeholder | UX/Design | DevOps/Release |
|----------|-----------|-----------------|-----------------|---------|---------------------|--------------|-------------|-----------|-----------------|
| Project Initiation | Consult | Owner | Lead | Consult | Consult | Support | Owner | Consult | Consult |
| Backlog Refinement | Owner | Owner | Support | Consult | Consult | Facilitate | - | Owner | - |
| Sprint Planning | Owner | Owner | Consult | Consult | Consult | Facilitate | - | - | - |
| Design Review | Owner | Consult | Consult | Consult | Owner | - | - | Owner | Consult |
| Quality Gate | Consult | Consult | Consult | Owner | Consult | - | - | Consult | Consult |
| Release Planning | Consult | Owner | Owner | Owner | Owner | Support | Owner | Consult | Owner |
| Deployment | Consult | - | Coordinate | Consult | Consult | - | - | - | Owner |
| Incident Response | Owner | Consult | Coordinate | Owner | Consult | - | Escalate | Consult | Owner |
| Retrospective | Owner | Owner | Owner | Owner | Owner | Facilitate | - | Owner | Owner |

**Key:** Owner = Primary responsibility | Consult = Provide input | Support = Enable/facilitate | Coordinate = Orchestrate across teams | Lead = Drive decisions | - = Not typically involved
