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

## Scrum Master

### Role Summary
Facilitates agile ceremonies and coaches the team on agile best practices. Acts as a servant-leader who removes impediments and fosters a productive team environment.

### Responsibilities
- Facilitates agile ceremonies (standup, sprint planning, review, retrospective)
- Coaches team on agile best practices and continuous improvement
- Removes impediments and shields team from distractions
- Coordinates with PM for delivery blockers
- Tracks sprint progress and team velocity

### Goals
- Enable a high-performing, self-organizing team
- Protect team capacity and ensure ceremonies are effective

### Typical Communication
- Daily standups, sprint reviews, retrospectives
- Direct coordination with PM and PdM on blockers

### Interactions
- **PM**: escalation of blockers
- **PdM**: backlog readiness
- **Developers**: facilitation and coaching

---

## UX Designer

### Role Summary
Champions user experience and usability across the product. Translates user needs into designs that guide development.

### Responsibilities
- Advocates for user needs and usability throughout the project lifecycle
- Designs wireframes, prototypes, and interaction flows
- Supports user testing and synthesizes feedback
- Collaborates with Product Manager on requirements and acceptance criteria
- Works closely with Developers during implementation to maintain design fidelity

### Goals
- Ensure features are intuitive, accessible, and meet user expectations

### Typical Communication
- Design reviews, user research readouts, collaboration sessions with PdM and Developers

### Interactions
- **PdM**: requirements and prioritization
- **Developers**: design handoff and implementation review
- **QA Lead**: usability acceptance

---

## Technical Writer

### Role Summary
Owns the quality and accessibility of technical and process documentation. Ensures that knowledge is captured, versioned, and available to all team members.

### Responsibilities
- Drafts and maintains process and product documentation
- Champions accessible, clear, and consistent documentation standards
- Integrates documentation into the development workflow (e.g., docs-as-code)
- Collaborates with PM, Developers, and QA to capture changes and decisions
- Reviews and updates docs in `docs/` as part of release cycles

### Goals
- Reduce knowledge silos and onboarding friction
- Ensure documentation is always current and searchable

### Typical Communication
- Pull request reviews, documentation sprints, coordination with PM and QA Lead

### Interactions
- **PM**: process docs
- **Developers**: technical content
- **QA Lead**: test and release documentation

---

## QA Lead

### Role Summary
Owns the testing strategy and quality standards for the project. Ensures features meet acceptance criteria before release.

### Responsibilities
- Develops and maintains the test strategy and quality standards
- Coordinates manual and automated testing efforts
- Works with Developers to ensure code quality and acceptance criteria are met
- Provides test results and release readiness reports
- Participates in sprint planning to estimate testing effort

### Goals
- Deliver high-quality, regression-free releases
- Provide clear release readiness signals

### Typical Communication
- Sprint reviews, test result summaries, coordination with Developers and Release Manager

### Interactions
- **Developers**: test coverage and defect triage
- **Release Manager**: release readiness
- **PM**: quality escalations

---

## Business Analyst

### Role Summary
Bridges business needs and technical implementation by gathering, analyzing, and clarifying requirements.

### Responsibilities
- Gathers, analyzes, and clarifies business and technical requirements
- Documents workflows, use cases, and edge cases
- Collaborates with Product Manager and Developers to refine the backlog
- Identifies gaps between current and desired state
- Supports acceptance criteria definition and user story writing

### Goals
- Ensure requirements are clear, complete, and actionable
- Reduce rework caused by ambiguous specifications

### Typical Communication
- Requirements workshops, backlog refinement sessions, collaboration with PdM and Developers

### Interactions
- **PdM**: requirements alignment
- **Developers**: technical clarification
- **PM**: scope and timeline impact

---

## Release Manager

### Role Summary
Plans and coordinates production releases to ensure they are safe, well-communicated, and repeatable.

### Responsibilities
- Plans and coordinates production release schedules and windows
- Communicates release plans, schedules, and changes to stakeholders
- Ensures pre-release checklists (from `octoacme-release-and-deployment.md`) are complete
- Works with QA Lead on release readiness confirmation
- Coordinates with Developers on go-live execution and rollback plans

### Goals
- Reduce release risk and ensure reliable, well-communicated deployments

### Typical Communication
- Release planning meetings, deployment announcements, post-release summaries

### Interactions
- **QA Lead**: release readiness
- **Developers**: deployment coordination
- **PM**: timeline and risk
- **Stakeholders**: announcements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

