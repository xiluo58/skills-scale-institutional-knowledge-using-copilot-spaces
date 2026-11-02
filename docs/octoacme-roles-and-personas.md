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

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects shape the technical direction, design decisions, and integration standards for the project. They ensure the solution remains feasible, scalable, and aligned with platform and engineering best practices.

### Responsibilities
- Define architecture, technical constraints, and key design decisions
- Guide technical trade-offs and implementation strategy with product and delivery teams
- Review major design choices, dependencies, and integration points
- Facilitate technical risk identification and mitigation plans
- Support developers with architectural clarity and solution quality reviews

### Goals
- Deliver a maintainable and scalable solution
- Reduce architecture-related rework and delivery risk
- Align engineering decisions with business and technical constraints

### Typical Communication
- Architecture reviews and technical design discussions
- Planning sessions with Product Managers and Project Managers
- Cross-team dependency and integration alignment

### Interaction with Existing Roles
- Works with Product Managers to assess feasibility and sequencing of roadmap items
- Partners with Project Managers to flag technical dependencies, milestones, and delivery risk
- Guides Developers on design quality, standards, and implementation decisions
- Provides technical input to stakeholders when trade-offs affect scope, schedule, or platform approach

---

## QA Lead / Testing Partner

### Role Summary
QA Leads define the quality strategy, test plan, and validation approach for a project. They ensure the team ships features that meet acceptance criteria and are reliable in real-world use.

### Responsibilities
- Define test strategy, coverage goals, and release validation criteria
- Review user stories and acceptance criteria for completeness and testability
- Coordinate automated, integration, and manual testing activities
- Identify quality risks and support release readiness decisions
- Partner with Developers and Product Managers on defect triage and validation

### Goals
- Improve product confidence and reduce production issues
- Ensure quality is built into delivery rather than added at the end
- Support faster, safer releases with clear validation standards

### Typical Communication
- Test planning and defect review meetings
- Acceptance criteria validation with product and engineering teams
- Release readiness check-ins and signoff discussions

### Interaction with Existing Roles
- Collaborates with Product Managers to confirm that user-facing requirements are testable and measurable
- Works with Developers to establish test coverage and validation workflows
- Coordinates with Project Managers on QA scheduling, milestones, and release readiness
- Communicates risks and quality signals to stakeholders when release confidence is low

---

## Security / Compliance Partner

### Role Summary
Security and Compliance partners identify and reduce risk related to data protection, system integrity, and regulatory requirements. They help the team build trust and meet required controls before release.

### Responsibilities
- Review projects for security, privacy, and compliance requirements
- Identify control gaps, data handling risks, and incident exposure
- Help define mitigation plans and approval checkpoints
- Support security reviews, audits, and incident response coordination
- Ensure release decisions consider legal, privacy, and operational safeguards

### Goals
- Reduce preventable risks and compliance issues
- Increase stakeholder trust in release readiness
- Ensure secure-by-default decisions across the project lifecycle

### Typical Communication
- Security reviews and risk discussions
- Compliance checkpoints during planning and release readiness
- Incident response and escalation updates

### Interaction with Existing Roles
- Advises Product Managers and Project Managers on risk trade-offs and approval gates
- Reviews technical designs with Technical Leads and Developers to reduce exploitability
- Coordinates with QA to align validation with security and compliance requirements
- Escalates critical issues to stakeholders when risks impact release timing or customer trust

---

## Customer Success / Support Liaison

### Role Summary
Customer Success and Support Liaisons connect delivery teams to real user feedback, operational pain points, and adoption issues. They help translate customer needs into backlog priorities and product improvements.

### Responsibilities
- Capture recurring support issues, customer pain points, and adoption barriers
- Translate user feedback into product opportunities and backlog inputs
- Coordinate with Product Managers on customer-impacting priorities
- Help support readiness for launches, releases, and proactive communication
- Surface operational gaps that affect usability, reliability, or retention

### Goals
- Improve customer satisfaction and product adoption
- Reduce time between user feedback and product response
- Increase alignment between delivery work and customer value

### Typical Communication
- Customer feedback summaries and support trend reviews
- Release support briefings and launch readiness check-ins
- Prioritization and escalation conversations with product and project teams

### Interaction with Existing Roles
- Provides Product Managers with evidence to prioritize roadmap and backlog changes
- Supports Project Managers by highlighting dependencies, customer impacts, and launch readiness concerns
- Shares observations with Developers and QA to improve usability and reliability based on real usage
- Keeps stakeholders informed of customer impacts and expected mitigation steps

---

## Data / Analytics Owner

### Role Summary
Data and Analytics Owners define the metrics, instrumentation, and reporting needed to evaluate whether a project is delivering business value. They help teams make decisions using evidence rather than assumptions.

### Responsibilities
- Define success metrics, dashboard requirements, and instrumentation plans
- Ensure data sources and reporting pipelines support business decisions
- Review feature impact using usage, quality, and performance data
- Partner with Product Managers and stakeholders to confirm value realization
- Support experimentation, monitoring, and post-launch evaluation

### Goals
- Make value delivery measurable and transparent
- Improve decision quality with timely, trusted data
- Connect project execution to business outcomes and customer impact

### Typical Communication
- Metric definitions and dashboard review sessions
- Launch and performance reporting for stakeholders
- Post-release analysis and outcome reviews

### Interaction with Existing Roles
- Works with Product Managers to validate that success metrics match product goals
- Supports Project Managers with milestone and release reporting on measurable progress
- Provides Developers and QA with evidence about usage, quality, and risk signals
- Helps stakeholders understand whether the project is achieving expected outcomes

---

## Release Manager

### Role Summary
Release Managers coordinate the planning, sequencing, and communication required for successful deployment. They help ensure launches are well prepared, visible, and operationally safe.

### Responsibilities
- Plan release windows, sequencing, and rollout dependencies
- Coordinate communication across engineering, QA, support, and stakeholders
- Prepare rollback and incident readiness for launch events
- Validate that deployment requirements and post-release checks are complete
- Support release communications and issue escalation during launch windows

### Goals
- Reduce deployment risk and improve release confidence
- Increase coordination across teams during launch events
- Support clear stakeholder communication before and after release

### Typical Communication
- Release checklists and readiness reviews
- Launch briefings and stakeholder updates
- Post-release verification and issue coordination

### Interaction with Existing Roles
- Works with Project Managers to align timelines and release dependencies
- Collaborates with QA and Security partners to confirm readiness criteria are met
- Coordinates with Product Managers on launch messaging and business impact communication
- Supports Developers in validating deployment and rollback readiness for critical changes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These definitions help teams clarify responsibility boundaries, decision-making, and collaboration patterns across complex projects.

