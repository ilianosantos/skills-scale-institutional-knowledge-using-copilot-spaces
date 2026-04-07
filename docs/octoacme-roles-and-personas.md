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

## UX Designer

### Role Summary
UX Designers advocate for users throughout the project lifecycle. They translate product requirements into intuitive designs and prototypes, and validate solutions through user research and usability testing.

### Responsibilities
- Conduct user research (interviews, surveys, usability tests) and synthesize findings
- Create wireframes, mockups, and interactive prototypes
- Maintain and evolve the design system and component library
- Partner with Product Managers to translate requirements into user flows
- Collaborate with Developers on implementation feasibility and design handoff
- Document design decisions and accessibility considerations

### Goals
- Deliver experiences that are usable, accessible, and delightful
- Reduce rework by surfacing usability issues early in the cycle
- Ensure design consistency across the product

### Typical Communication
- Design reviews and critique sessions with Developers and Product Managers
- Shared design files and annotated prototypes (e.g., Figma, Miro)
- Usability test reports shared with the full delivery team

### Interactions with Other Roles
- **Product Managers**: align on user needs, success metrics, and feature scope; participate in backlog refinement
- **Developers**: hand off finalized designs, clarify behavior and edge cases, review implementation for fidelity
- **Project Managers**: flag design dependencies or assets that are on the critical path
- **QA Specialists**: collaborate to define acceptance criteria for visual and interaction quality
- **Stakeholders**: present design concepts and incorporate feedback before development begins

---

## QA Specialist

### Role Summary
QA Specialists ensure that each release meets quality and acceptance standards. They define test strategies, execute test plans, and work closely with Developers and Project Managers to gate releases.

### Responsibilities
- Define test plans, test cases, and acceptance criteria in collaboration with Developers and Product Managers
- Execute functional, integration, regression, and exploratory testing
- Document, triage, and track defects through resolution
- Automate repeatable test scenarios where practical
- Provide release readiness sign-off to Project Managers
- Contribute to the Definition of Done and quality standards

### Goals
- Prevent defects from reaching production
- Shorten feedback loops by identifying issues as early as possible
- Build confidence in each release through clear test evidence

### Typical Communication
- Test plans and defect reports shared in the project tracking system
- Daily coordination with Developers during active sprint testing
- Release readiness summaries for Project Managers before deployment

### Interactions with Other Roles
- **Developers**: pair on defect reproduction and resolution; review pull requests for testability
- **Product Managers**: verify acceptance criteria are complete and testable; confirm edge cases are covered
- **Project Managers**: report test status and block/unblock release gates
- **UX Designers**: validate that implemented UI matches approved designs and accessibility requirements
- **Stakeholders**: participate in user acceptance testing (UAT) sessions as needed

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate documentation for both users and the delivery team. They ensure knowledge is captured and kept current at every stage of the project lifecycle.

### Responsibilities
- Author and maintain user-facing documentation (user guides, FAQs, release notes, help articles)
- Produce and update internal process documentation and runbooks
- Interview Developers, Product Managers, and QA Specialists to capture technical details
- Review documentation for clarity, accuracy, and consistency with the product
- Coordinate documentation milestones with the project plan

### Goals
- Ensure users and teammates can find accurate answers without escalation
- Reduce support burden through self-service documentation
- Keep docs up to date through every release cycle

### Typical Communication
- Documentation drafts and review cycles via pull requests or shared docs
- Regular syncs with Developers and Product Managers to capture feature details
- Documentation status updates to Project Managers before release

### Interactions with Other Roles
- **Developers**: gather technical implementation details; review code comments and changelogs for accuracy
- **Product Managers**: align on user-facing messaging, feature naming, and release notes
- **Project Managers**: coordinate documentation milestones as part of the release checklist
- **QA Specialists**: collaborate to document known issues and workarounds
- **Stakeholders**: incorporate feedback from UAT and support teams into documentation updates

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business goals and technical delivery. They elicit, document, and trace requirements, and verify that project outcomes align with organizational objectives.

### Responsibilities
- Elicit, document, and validate business requirements through workshops, interviews, and process mapping
- Translate business needs into functional requirements, user stories, and acceptance criteria
- Maintain requirements traceability from inception through delivery
- Serve as liaison between technical teams and non-technical stakeholders
- Identify scope gaps, risks, and process inefficiencies
- Support change management by documenting impacts and communicating adjustments

### Goals
- Ensure delivered solutions address the underlying business problem
- Reduce rework caused by misunderstood or incomplete requirements
- Build shared understanding between business stakeholders and the delivery team

### Typical Communication
- Requirements documents, process flows, and user story maps shared with the full team
- Regular stakeholder workshops and sign-off meetings
- Traceability matrices and impact assessments for Project Managers

### Interactions with Other Roles
- **Product Managers**: co-author problem statements and success metrics; align on scope and priorities
- **Developers**: provide detailed requirements and clarify ambiguities during development
- **Project Managers**: identify dependencies, scope changes, and business risk; contribute to status reporting
- **QA Specialists**: validate that test cases cover business requirements and acceptance criteria
- **Stakeholders**: facilitate requirements workshops and obtain sign-off on solution design

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [RACI Matrix](./octoacme-raci-matrix.md) for a consolidated view of who is responsible, accountable, consulted, or informed at each project phase.

