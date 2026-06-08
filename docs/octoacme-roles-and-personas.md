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

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and the technical delivery team. They elicit, document, and validate requirements to ensure the right solutions are built.

### Responsibilities
- Elicit and document business requirements through stakeholder interviews and workshops
- Translate business needs into clear user stories and acceptance criteria
- Analyse current processes and identify gaps or improvement opportunities
- Maintain a shared understanding of scope between business and technical teams
- Support user acceptance testing (UAT) and sign-off

### Goals
- Ensure requirements are clear, complete, and actionable before development begins
- Reduce rework caused by misunderstood or missing requirements
- Bridge communication gaps between non-technical stakeholders and developers

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story refinement sessions with the Product Manager and developers
- UAT coordination with QA Lead and business stakeholders

### Interactions with Existing Roles
- **Developers**: Provides detailed acceptance criteria and clarifies requirements during implementation; reviews delivered features against documented requirements.
- **Product Managers**: Collaborates on backlog refinement, translating high-level product goals into detailed user stories and success metrics.
- **Project Managers**: Surfaces requirement risks and scope changes early; supports status reporting by tracking requirement coverage.

---

## QA Lead

### Role Summary
QA Leads coordinate all testing activities across the delivery lifecycle. They define quality standards, establish testing processes, and ensure deliverables meet acceptance criteria before release.

### Responsibilities
- Define and maintain the test strategy, test plans, and quality gates
- Coordinate functional, regression, integration, and performance testing
- Review acceptance criteria and Definition of Done for testability
- Track, triage, and report on defects; escalate blockers appropriately
- Champion continuous improvement of testing practices and automation coverage

### Goals
- Prevent defects from reaching production through rigorous, early testing
- Increase confidence in releases through consistent quality standards
- Reduce manual testing overhead by growing automated test coverage

### Typical Communication
- Sprint ceremonies (planning, reviews, retrospectives) to embed quality gates
- Defect triage meetings with developers and Product Manager
- Test completion and quality reports to Project Manager and stakeholders

### Interactions with Existing Roles
- **Developers**: Collaborates on test coverage strategies, reviews code for testability, and works together on reproducing and resolving defects.
- **Product Managers**: Validates acceptance criteria are testable; communicates quality status and defect impact on release readiness.
- **Project Managers**: Reports test progress, defect trends, and quality risks; helps assess whether the team is ready to release.

---

## DevOps Engineer

### Role Summary
DevOps Engineers own the continuous integration and delivery pipelines, infrastructure provisioning, and deployment processes. They enable teams to ship reliably and recover quickly from incidents.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and build automation
- Manage cloud infrastructure using infrastructure-as-code practices
- Monitor system health, performance, and reliability; respond to incidents
- Define and enforce deployment, rollback, and environment-promotion processes
- Collaborate on security hardening, secrets management, and compliance requirements

### Goals
- Enable frequent, low-risk deployments through automation and repeatability
- Minimise time to detect and recover from production incidents
- Improve developer productivity by reducing friction in the build and release process

### Typical Communication
- On-call and incident response channels with real-time alerts
- Infrastructure change reviews and deployment runbooks shared with developers and QA Lead
- Capacity and reliability updates in weekly team syncs with Project Manager

### Interactions with Existing Roles
- **Developers**: Partners on build configuration, environment parity, and deployment tooling; reviews infrastructure-impacting code changes.
- **Product Managers**: Provides input on release scheduling, environment availability, and infrastructure costs that may affect roadmap decisions.
- **Project Managers**: Communicates deployment readiness, planned maintenance windows, and incident impact on delivery timelines.

---

## UX Designer

### Role Summary
UX Designers are responsible for the user interface design and overall user experience of OctoAcme products. They conduct user research, create prototypes, and ensure that solutions are intuitive and accessible.

### Responsibilities
- Conduct user research, interviews, and usability testing to inform design decisions
- Create wireframes, prototypes, and high-fidelity design specifications
- Maintain and evolve the design system and component library
- Collaborate with developers to ensure designs are implemented accurately
- Advocate for accessibility and inclusive design standards

### Goals
- Deliver experiences that are intuitive, accessible, and aligned with user needs
- Reduce user errors and support-request volume through clear, consistent design
- Shorten the feedback loop between design concepts and validated user outcomes

### Typical Communication
- Design reviews and critique sessions with Product Manager and developers
- Usability testing read-outs shared with stakeholders and the delivery team
- Handoff artefacts (specs, assets, annotated prototypes) provided to developers

### Interactions with Existing Roles
- **Developers**: Works closely during implementation to clarify design intent, review built interfaces, and iterate on feedback; provides annotated specs and assets via the design handoff process.
- **Product Managers**: Aligns on user needs and product goals early in discovery; co-facilitates user research and validates designs against success metrics.
- **Project Managers**: Communicates design milestone progress and flags scope changes arising from usability findings; agrees timelines for design deliverables.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

