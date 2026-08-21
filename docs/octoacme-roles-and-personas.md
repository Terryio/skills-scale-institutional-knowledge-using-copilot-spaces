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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance and acceptance validation. They collaborate with developers and product managers to define test strategies, execute testing, and ensure features meet acceptance criteria before release.

### Responsibilities
- Define and execute test plans aligned with feature acceptance criteria
- Design and implement test cases (unit, integration, end-to-end)
- Manage test environments and test data
- Track and triage defects, working with developers on resolution
- Verify acceptance criteria and sign off on completion
- Participate in Definition of Done reviews

### Goals
- Ensure all features meet quality standards before release
- Reduce defects in production
- Provide clear visibility into testing progress and quality metrics

### Typical Communication
- Sprint planning and QA reviews
- Defect tracking and status updates
- Release readiness assessments

### Interactions with Other Roles
- **Developers**: Collaborate on test case design, defect resolution, and Definition of Done verification
- **Product Managers**: Validate acceptance criteria and feature specifications
- **Project Managers**: Provide quality metrics and release readiness assessments
- **Technical Leads**: Align on testing strategy for complex technical components

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide architectural guidance, design reviews, and technical risk management. They ensure solutions are scalable, maintainable, and aligned with system goals.

### Responsibilities
- Review architectural and design proposals
- Identify technical risks and propose mitigations
- Guide technology choices and integration strategies
- Mentor developers on technical excellence
- Participate in code reviews for complex changes
- Support estimation and feasibility assessments

### Goals
- Ensure technical quality and system scalability
- Reduce technical debt and rework
- Build maintainable, well-documented systems

### Typical Communication
- Design review sessions
- Architecture decision records (ADRs)
- Technical risk assessments in planning and risk reviews

### Interactions with Other Roles
- **Developers**: Provide mentorship, review complex technical decisions, and guide implementation approaches
- **Product Managers**: Assess feasibility of features and provide technical trade-offs
- **Project Managers**: Identify technical risks, dependencies, and mitigation strategies
- **QA/Testing Leads**: Collaborate on testability and technical testing strategies

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate process execution and team effectiveness. They remove impediments, coach the team on agile practices, and foster a culture of continuous improvement.

### Responsibilities
- Facilitate daily standups, planning, reviews, and retrospectives
- Help the team adopt and optimize agile practices
- Identify and help resolve team impediments and blockers
- Coach team members on collaboration and communication
- Track and report on team velocity and cycle time metrics
- Promote psychological safety and feedback culture

### Goals
- Maximize team productivity and predictability
- Foster continuous learning and improvement
- Reduce ceremony overhead and meeting waste
- Build a high-performing, self-organizing team

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- Metrics dashboards and process improvement discussions

### Interactions with Other Roles
- **Project Managers**: Provide metrics, capacity planning, and process optimization insights
- **All Team Members**: Remove impediments, facilitate ceremonies, and coach on agile practices
- **Product Managers**: Support backlog refinement and sprint planning

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests, approve priorities, and allocate resources. They provide executive context and decision-making authority for project success.

### Responsibilities
- Approve project charter and key decisions
- Provide business context and success metrics
- Allocate budget, team capacity, and resources
- Remove organizational blockers and escalations
- Receive and act on escalations beyond team authority
- Provide strategic feedback and direction

### Goals
- Ensure project delivers business value
- Support team success with resources and decision-making
- Maintain stakeholder alignment and confidence
- Unblock organizational constraints

### Typical Communication
- Monthly stakeholder updates
- Ad-hoc escalations and decisions
- Milestone reviews and go/no-go gates
- Budget and resource approval meetings

### Interactions with Other Roles
- **Project Managers**: Receive escalations, approve decisions, allocate resources
- **Product Managers**: Validate business strategy and success metrics
- **All Team Members**: Provide executive support and organizational context

---

## Security Officer

### Role Summary
Security Officers ensure that projects meet security and compliance requirements. They provide guidance on security practices, conduct security reviews, and manage risk mitigation for security-related issues.

### Responsibilities
- Define and enforce security requirements and compliance standards
- Conduct security reviews of designs and code
- Provide security guidance and best practices to the team
- Manage security risks and compliance issues
- Conduct security training and awareness activities
- Coordinate with external compliance and audit teams

### Goals
- Ensure product security and data protection
- Minimize security vulnerabilities and compliance violations
- Build security awareness across the team
- Reduce security-related incidents and breaches

### Typical Communication
- Security design reviews and threat assessments
- Security training and awareness sessions
- Risk registers and compliance reports
- Incident response and breach coordination

### Interactions with Other Roles
- **Developers**: Provide security guidance, review code for vulnerabilities, promote secure coding practices
- **Technical Leads**: Conduct architectural security reviews and threat modeling
- **Project Managers**: Identify security risks and compliance dependencies
- **QA/Testing Leads**: Coordinate security testing and vulnerability scanning
- **Stakeholders**: Report compliance status and security risks

---

## DevOps/Release Engineer

### Role Summary
DevOps and Release Engineers manage deployment pipelines, infrastructure, and release processes. They ensure reliable, repeatable deployments and maintain system observability and operational excellence.

### Responsibilities
- Design and maintain deployment pipelines and infrastructure-as-code
- Manage release workflows, versioning, and rollback procedures
- Monitor production systems and respond to operational issues
- Coordinate staging and production deployments
- Implement and maintain CI/CD automation
- Support incident response and post-incident analysis

### Goals
- Enable fast, reliable, and safe deployments
- Minimize deployment failures and production incidents
- Maintain high system availability and performance
- Reduce manual effort in release processes

### Typical Communication
- Release planning and deployment coordination
- Incident response and post-mortem reviews
- Infrastructure and operational metrics
- Deployment runbooks and automation documentation

### Interactions with Other Roles
- **Developers**: Provide deployment support, infrastructure guidance, and CI/CD pipeline maintenance
- **QA/Testing Leads**: Coordinate staging environment management and smoke test execution
- **Project Managers**: Provide deployment schedules and release readiness status
- **Technical Leads**: Collaborate on infrastructure design and performance optimization
- **Stakeholders**: Report deployment status and system health

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Consider how personas interact across project phases (planning, execution, release) to design realistic scenarios.
