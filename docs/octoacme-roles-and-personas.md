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

## Technical Architect

### Role Summary
Technical Architects provide technical strategy and design oversight for project solutions. They ensure that architecture decisions align with organizational standards and support long-term scalability and maintainability.

### Responsibilities
- Define technical strategy and architectural approach for projects
- Review and validate technical designs proposed by development teams
- Identify and mitigate technical risks and dependencies
- Ensure compliance with organizational technical standards and best practices
- Mentor development teams on architecture and design patterns
- Participate in technology selection and evaluation

### Goals
- Ensure technically sound, scalable, and maintainable solutions
- Reduce technical debt and future refactoring needs
- Enable team capability and knowledge transfer

### Key Interactions
- **Collaborates with**: Project Manager (during planning), Development teams (execution), Quality Assurance Lead (validation)
- **Decision-making authority**: Approves technical designs, recommends technology choices, escalates architectural concerns
- **Typical Communication**: Architecture design reviews, technical spike recommendations, design decision records

---

## Compliance Officer

### Role Summary
Compliance Officers ensure that projects adhere to regulatory requirements, organizational policies, and industry standards. They reduce organizational risk and ensure projects meet governance expectations.

### Responsibilities
- Review project scope and objectives for compliance requirements
- Validate risk assessments for regulatory and compliance gaps
- Approve release and deployment plans to ensure compliance readiness
- Maintain compliance documentation and audit trails
- Provide guidance on regulatory changes and policy updates
- Escalate compliance concerns to leadership

### Goals
- Ensure zero compliance violations
- Reduce regulatory and organizational risk
- Maintain organizational credibility and trust

### Key Interactions
- **Collaborates with**: Project Manager (initiation and planning), Technical Architect (technical compliance), Quality Assurance Lead (release validation)
- **Decision-making authority**: Approves or blocks releases based on compliance readiness, escalates compliance risks
- **Typical Communication**: Compliance checklists, risk review meetings, release approval gates, audit documentation

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads oversee testing strategy and quality standards for projects. They ensure that delivered solutions meet quality expectations and user requirements.

### Responsibilities
- Define testing strategy and quality acceptance criteria
- Oversee test planning, execution, and coverage
- Identify and track quality issues and regressions
- Conduct release validation and sign-off
- Collaborate on quality metrics and reporting
- Contribute insights to retrospectives on quality improvement

### Goals
- Deliver high-quality solutions that meet user expectations
- Reduce production issues and customer impact
- Continuously improve testing processes and coverage

### Key Interactions
- **Collaborates with**: Development teams (test execution), Project Manager (timeline coordination), Technical Architect (architecture validation), Compliance Officer (compliance testing)
- **Decision-making authority**: Approves or blocks releases based on quality criteria, escalates quality concerns
- **Typical Communication**: Test plans and reports, quality dashboards, release readiness meetings, defect escalation

---

## Community Liaison

### Role Summary
Community Liaisons manage stakeholder communication and feedback loops. They ensure that diverse stakeholder perspectives are heard and incorporated, and that project status and outcomes are effectively communicated.

### Responsibilities
- Gather and synthesize feedback from stakeholders and end-users
- Coordinate stakeholder engagement activities and forums
- Communicate project status, milestones, and outcomes to broad audiences
- Identify and escalate stakeholder concerns and expectations
- Support release communication and training initiatives
- Foster community participation and engagement

### Goals
- Ensure stakeholder alignment and satisfaction
- Reduce communication gaps and misalignment
- Build community support for projects and initiatives

### Key Interactions
- **Collaborates with**: Project Manager (communication planning), Product Manager (user feedback), Release/Deployment team (launch communication)
- **Decision-making authority**: Influences product decisions through stakeholder feedback, shapes communication strategy
- **Typical Communication**: Stakeholder forums and surveys, community newsletters, feedback synthesis reports, launch event coordination

---

## Role Interaction Matrix (RACI)

This matrix clarifies decision-making authority and responsibilities across roles:

| Activity | Developer | PM | Product Manager | Tech Architect | Compliance | QA Lead | Community |
|----------|-----------|----|----|--------|-----------|---------|----------|
| Define requirements | C | R | A | I | I | C | I |
| Architecture review | C | I | I | A | C | I | - |
| Compliance check | I | C | I | C | A | C | - |
| Test planning | A | R | I | C | - | R | - |
| Release approval | C | A | R | C | A | A | C |
| Stakeholder communication | - | C | R | - | - | C | A |
| Risk identification | R | A | I | R | R | C | I |
| Retrospective | A | A | I | R | I | R | C |

**Legend**: A = Accountable (final authority), R = Responsible (does the work), C = Consulted (provides input), I = Informed (kept in the loop), - = Not involved

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the RACI matrix when assigning activities and clarifying decision-making authority in project scenarios.
