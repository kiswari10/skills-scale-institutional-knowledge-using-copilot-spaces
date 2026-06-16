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

## Release Manager

### Role Summary
Release Managers own the end-to-end release coordination process, including scheduling, deployment orchestration, release notes, and post-release verification. They ensure releases are smooth, documented, and communicated to all stakeholders.

### Responsibilities
- Coordinate release schedules and deployment windows
- Prepare and maintain release notes and runbooks
- Orchestrate deployment activities across environments
- Document and execute rollback plans
- Conduct post-release verification and communicate status to stakeholders
- Track release metrics and incidents

### Goals
- Execute releases with minimal risk and disruption
- Ensure clear communication to all stakeholder groups
- Maintain high observability and traceability for each release

### Typical Interactions
- Works closely with **Project Manager** on timelines and milestones
- Coordinates with **DevOps/Platform Engineer** for deployment automation and infrastructure
- Partners with **QA/Testing** for release verification and acceptance sign-off
- Communicates with **Support** and **Stakeholder Liaisons** for announcements and incident response
- References **Technical Writer** for release documentation and runbooks

### Typical Communication
- Release planning meetings and deployment coordination
- Release notes and deployment documentation
- Post-release status reports and incident logs

---

## Technical Writer

### Role Summary
Technical Writers produce and maintain clear, comprehensive documentation for users, operators, and developers. They ensure all features are properly documented, including release notes, user guides, API documentation, and runbooks.

### Responsibilities
- Author and maintain user-facing documentation and guides
- Create and update API documentation and technical references
- Produce release notes and migration guides
- Develop operational runbooks for support and operations teams
- Ensure documentation reflects the latest features and best practices
- Collaborate on accuracy of acceptance criteria documentation

### Goals
- Reduce support burden by providing clear, accessible documentation
- Ensure consistency and clarity in all user-facing materials
- Enable self-service adoption and troubleshooting

### Typical Interactions
- Collaborates with **Developers** on technical accuracy and implementation details
- Works with **Product Managers/PdMs** on feature descriptions and use cases
- Partners with **QA/Testing** to document acceptance criteria and reproducibility steps
- Coordinates with **Release Manager** on release notes and deployment guides
- Engages with **Support** to understand common questions and issues

### Typical Communication
- Documentation reviews and feedback cycles
- Sprint planning and release note coordination
- Support escalations and documentation gaps

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers run user research, translate insights into product requirements, and design user experiences. They produce wireframes, prototypes, and acceptance criteria informed by user needs and validation.

### Responsibilities
- Conduct user research and usability testing
- Define user journeys and personas
- Produce wireframes, mockups, and design specifications
- Create UX-focused acceptance criteria
- Validate designs with users and stakeholders
- Participate in design reviews and user feedback sessions

### Goals
- Ensure features are usable, discoverable, and meet user needs
- Reduce rework caused by poor UX assumptions
- Drive user satisfaction and adoption

### Typical Interactions
- Partners with **Product Managers/PdMs** to define user needs and success metrics
- Works with **Developers** to clarify implementation constraints and technical feasibility
- Collaborates with **QA/Testing** on usability testing and user acceptance testing
- Engages with **Stakeholders** and external users for feedback
- References **Technical Writers** for documentation of UX patterns

### Typical Communication
- User research sessions and findings presentations
- Design reviews and feedback cycles
- Acceptance criteria and design specifications

---

## Security Champion

### Role Summary
Security Champions advocate for security best practices within the delivery team, identify potential vulnerabilities, and coordinate with the central Security function. They ensure security requirements are integrated into the backlog and release process.

### Responsibilities
- Identify and flag security requirements and risks during planning
- Review acceptance criteria for security implications
- Coordinate security scanning and penetration testing
- Work with Developers on secure coding practices and vulnerability remediation
- Maintain a security risk register for the project
- Facilitate security reviews and incident response

### Goals
- Prevent security vulnerabilities from reaching production
- Build a culture of security awareness within the team
- Ensure compliance with organizational security policies

### Typical Interactions
- Works with **Developers** on code reviews, secure coding, and vulnerability fixes
- Coordinates with **DevOps/Platform Engineer** on infrastructure security and secrets management
- Partners with **Project Manager** to ensure security work is prioritized in the backlog
- Escalates to central **Security team** for guidance on novel risks
- Engages **QA/Testing** on security test coverage

### Typical Communication
- Security reviews and design walkthroughs
- Vulnerability reports and remediation tracking
- Security training and awareness sessions

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers maintain CI/CD pipelines, deployment automation, observability infrastructure, and platform reliability. They enable rapid, safe deployments and provide operational tooling for the team.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage deployment infrastructure and environments
- Implement monitoring, logging, and observability solutions
- Manage infrastructure as code and configuration management
- Support Developers with deployment issues and platform problems
- Coordinate with Security on infrastructure hardening

### Goals
- Enable fast, reliable, automated deployments
- Maintain high availability and performance
- Provide self-service tooling and visibility to the team

### Typical Interactions
- Supports **Developers** with CI/CD pipeline issues and deployment support
- Partners with **Release Manager** during deployment execution
- Collaborates with **Security Champion** on infrastructure security and secrets
- Works with **Data Analysts** to expose operational metrics and logs
- Engages with **Project Manager** on infrastructure capacity and constraints

### Typical Communication
- Pipeline status and deployment logs
- Infrastructure documentation and runbooks
- Incident response and post-mortems

---

## Data Analyst

### Role Summary
Data Analysts define, implement, and track success metrics for projects. They set up dashboards, interpret telemetry, and help the team understand product usage and impact to inform decisions.

### Responsibilities
- Define measurable success metrics aligned with project goals
- Instrument features to collect relevant telemetry
- Build and maintain dashboards for key metrics and signals
- Analyze product usage and user behavior data
- Provide insights to inform prioritization and acceptance decisions
- Support retrospectives with performance data

### Goals
- Enable data-driven decision-making across the team
- Ensure all metrics are clearly defined, measurable, and tracked
- Provide actionable insights on product usage and impact

### Typical Interactions
- Partners with **Product Managers/PdMs** on success metrics and measurement strategy
- Works with **Developers** and **QA** to ensure metrics are instrumented correctly
- Collaborates with **DevOps/Platform Engineer** to access operational data and logs
- Engages with **Release Manager** on release impact and post-deployment metrics
- References **Technical Writers** for metric documentation and interpretation guides

### Typical Communication
- Metrics definition and instrumentation reviews
- Weekly/monthly dashboard reviews and insights presentations
- Retrospective data and trend analysis

---

## Engineering Manager

### Role Summary
Engineering Managers lead engineering teams, manage capacity and staffing, foster technical growth, and remove engineering blockers. They work across technical and project management to align team capability with project needs.

### Responsibilities
- Manage team staffing, hiring, and growth
- Plan team capacity and workload balance
- Conduct 1-on-1s and performance feedback
- Remove technical blockers and organizational impediments
- Ensure code quality standards and technical practices
- Represent engineering in planning and prioritization discussions

### Goals
- Grow a high-performing, sustainable engineering team
- Ensure technical excellence and maintainability
- Reduce unplanned work caused by technical debt or poor practices

### Typical Interactions
- Works with **Project Manager** on capacity planning and resource allocation
- Collaborates with **Developers** on technical direction, code quality, and growth opportunities
- Partners with **Product Manager/PdM** on realistic estimation and prioritization
- Engages with **Release Manager** on deployment readiness and team capacity
- Coordinates with **Security Champion** on security training and practices

### Typical Communication
- Capacity planning and resource discussions
- Technical direction and architecture reviews
- Performance feedback and team retrospectives

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons serve as the primary point of contact between external stakeholders (sales, support, legal, operations) and the core delivery team. They gather requirements, communicate status, and ensure alignment without overloading the delivery team.

### Responsibilities
- Act as single point of contact for external stakeholder groups
- Gather and translate stakeholder requirements into backlog items
- Provide regular status updates and manage stakeholder expectations
- Escalate issues and decisions that require stakeholder input
- Facilitate approvals and sign-offs
- Coordinate communication across multiple stakeholder groups

### Goals
- Reduce context-switching and interruptions for the delivery team
- Ensure stakeholder concerns are heard and addressed
- Maintain clarity and transparency in stakeholder relationships

### Typical Interactions
- Works with **Product Manager/PdM** to translate stakeholder needs into product requirements
- Partners with **Project Manager** for status reporting and escalation
- Engages with **Release Manager** on stakeholder communication for releases
- Communicates with **Support**, **Sales**, and external stakeholders on behalf of the delivery team
- References **Technical Writers** for stakeholder-facing documentation

### Typical Communication
- Stakeholder meeting facilitation
- Status updates and expectation management
- Requirements gathering and escalation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to interaction patterns to understand handoffs, dependencies, and communication flows.
- Map roles to your actual team members and clarify ownership for each OctoAcme project phase.
