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

### Cross-functional Interactions
- **With UX Designers**: Collaborate on design implementation and feasibility
- **With QA Automation Engineers**: Partner on test strategy and automation coverage
- **With Security Lead**: Consult on secure coding practices and threat mitigation
- **With Product Managers**: Clarify requirements and discuss trade-offs

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

### Cross-functional Interactions
- **With Data Analysts**: Review success metrics and usage data for prioritization
- **With UX Designers**: Align on user needs and feature requirements
- **With Developers**: Discuss feasibility and timeline estimates
- **With Support Engineers**: Gather customer feedback and pain points

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

### Cross-functional Interactions
- **With all teams**: Facilitate communication and escalate blockers
- **With Security Lead**: Track security review status and risk mitigation
- **With Data Analyst**: Monitor project metrics and progress dashboards
- **With Support Engineer**: Coordinate release planning and go-live support

---

## UX Designers

### Role Summary
UX Designers create user-centered solutions that are intuitive, accessible, and delightful. They research customer needs, design interfaces, and ensure usability throughout the product development lifecycle.

### Responsibilities
- Conduct user research and translate insights into design requirements
- Design wireframes, prototypes, and visual mockups
- Define information architecture and user flows
- Ensure accessibility standards (WCAG) and inclusive design
- Participate in design reviews and iterate based on feedback
- Validate designs through user testing and usability studies

### Goals
- Deliver intuitive, accessible user experiences
- Reduce support burden through better design
- Maximize user satisfaction and product adoption
- Ensure brand consistency across touchpoints

### Typical Communication
- Design specifications and user journey maps
- Prototypes and design system documentation
- User research findings and design rationale documents
- Feedback in design reviews and sprint planning

### Cross-functional Interactions
- **With Developers**: Clarify design intent and collaborate on feasibility
- **With Product Managers**: Align on user needs and feature prioritization
- **With QA/Testers**: Define acceptance criteria for UX quality
- **With Support Engineers**: Gather feedback on user confusion points

---

## Security Lead

### Role Summary
Security Leads identify, assess, and mitigate security risks throughout the project lifecycle. They advise on secure design patterns, conduct threat assessments, and ensure compliance with security standards.

### Responsibilities
- Conduct threat modeling and risk assessments during design and planning
- Review architecture and code for security vulnerabilities
- Advise on secure coding practices and design patterns
- Manage and escalate security incidents
- Ensure compliance with security policies and external standards
- Provide security training and awareness to the team

### Goals
- Prevent security breaches and data loss
- Build security into the development process (shift-left)
- Maintain customer trust and regulatory compliance
- Minimize time-to-remediation for discovered vulnerabilities

### Typical Communication
- Threat assessment and security architecture reviews
- Security incident runbooks and incident response coordination
- Security training materials and best practices documentation
- Risk registers and mitigation plans

### Cross-functional Interactions
- **With Developers**: Review code, design patterns, and provide secure coding guidance
- **With Project Managers**: Escalate security risks and track mitigation timelines
- **With Product Managers**: Discuss security trade-offs and compliance requirements
- **With QA/Testers**: Define security test scenarios and penetration testing plans

---

## Support Engineer

### Role Summary
Support Engineers are the voice of the customer post-release. They handle customer issues, triage bugs, and provide feedback to product and engineering teams to improve product quality and customer satisfaction.

### Responsibilities
- Respond to and triage customer issues and support tickets
- Reproduce and document bugs with clear steps and environment details
- Escalate critical issues to development and project management
- Gather customer feedback and pain points
- Create and maintain support documentation and FAQs
- Participate in release planning to coordinate go-live support

### Goals
- Maximize customer satisfaction and retention
- Reduce mean-time-to-resolution (MTTR) for customer issues
- Identify product gaps and usability improvements
- Enable customer self-service through documentation

### Typical Communication
- Support ticket summaries and escalations
- Customer feedback reports and trend analysis
- Bug reports with reproduction steps and logs
- Release notes and customer-facing documentation

### Cross-functional Interactions
- **With Developers**: Report bugs, provide reproduction steps, and discuss fixes
- **With Product Managers**: Share customer feedback and usage patterns for prioritization
- **With UX Designers**: Identify usability issues and confusing flows
- **With Project Managers**: Coordinate release timing and support readiness

---

## Data Analyst

### Role Summary
Data Analysts define, track, and interpret success metrics and usage data. They provide insights to Product and Project Managers to inform decisions and drive continuous improvement.

### Responsibilities
- Define success metrics and KPIs aligned with project goals
- Set up analytics instrumentation and data pipelines
- Monitor and report on key metrics and dashboards
- Analyze trends, anomalies, and opportunities for optimization
- Provide insights to support prioritization and strategic decisions
- Conduct post-launch analysis to measure impact and ROI

### Goals
- Enable data-driven decision making across the organization
- Identify product improvements through usage insights
- Demonstrate project ROI and business impact
- Predict trends and opportunities early

### Typical Communication
- Weekly/monthly metric dashboards and analytics reports
- Deep-dive analysis on specific questions or trends
- Data-informed recommendations for product changes
- Post-launch impact assessments

### Cross-functional Interactions
- **With Product Managers**: Report on feature adoption, user behavior, and ROI
- **With Project Managers**: Track progress metrics and milestone achievement
- **With Developers**: Define instrumentation requirements and data schemas
- **With Support Engineers**: Analyze support ticket patterns and product gaps

---

## QA Automation Engineer

### Role Summary
QA Automation Engineers develop and maintain automated test suites that enable fast, reliable, and safe releases. They partner with developers and testers to build quality into the development process.

### Responsibilities
- Design and develop automated test scripts for functional, integration, and end-to-end scenarios
- Maintain and update test suites as features evolve
- Set up test infrastructure and CI/CD integration
- Identify gaps in test coverage and recommend improvements
- Triage and debug test failures to support rapid releases
- Partner with QA testers on exploratory and manual testing strategies

### Goals
- Enable fast, safe releases through reliable automation
- Reduce manual testing effort and human error
- Improve test coverage and identify edge cases early
- Support continuous integration and deployment pipelines

### Typical Communication
- Test automation plans and test case documentation
- CI/CD pipeline configuration and health reports
- Test coverage metrics and gap analysis
- Collaboration with testers and developers on test strategy

### Cross-functional Interactions
- **With Developers**: Define testable interfaces and collaborate on test strategy
- **With QA/Manual Testers**: Coordinate on exploratory testing and test case coverage
- **With Project Managers**: Report on test automation health and release readiness
- **With DevOps/Platform**: Integrate tests into CI/CD pipelines and monitoring

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference cross-functional interactions to understand dependencies and communication patterns across teams.
