# OctoAcme Project Management Documentation

This repository centralizes project management processes and best practices for OctoAcme. Use this README as your starting point for all program and project management workflows.

## OctoAcme Project Management Approach

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles:

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Work in small, testable increments  
- **Clear ownership:** Each project has a named Project Manager (PM) and Product Lead
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

### Key Process Stages

The project lifecycle comprises five distinct phases:

1. **Initiation:** Validate business need and create a lightweight One-pager defining the problem, goals, success metrics, stakeholders, and initial risks
2. **Planning:** Break work into shippable increments with acceptance criteria, map dependencies, and establish a release timeline
3. **Execution & Tracking:** Manage day-to-day delivery through daily standups, weekly syncs, sprint-based iterations, and continuous risk monitoring
4. **Release & Deployment:** Standardize feature releases with pre-release requirements, deployment checklists, and rollback plans
5. **Retrospective & Continuous Improvement:** Capture learnings and convert them into actionable improvements

### Core Roles

- **Project Manager (PM):** Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, and measures success
- **Developers:** Implement features, collaborate on design, and maintain quality standards
- **QA/Testing:** Validate quality and acceptance criteria

### Key Practices

- **Daily standups** (15 min) focused on progress, blockers, and dependencies
- **Weekly delivery syncs** to show progress, updates, and flagged risks
- **Pull request workflow** with small PRs (≤400 lines), required CI passes, and peer review
- **Risk management** via a maintained Risk Register with mitigation tracking
- **Stakeholder communication** through weekly status templates and incident playbooks
- **Quality assurance** with unit tests, integration tests, security scanning, and smoke tests

## Process Documents

Navigate to the specific process documents below to understand each phase in detail:

- [**Project Management Overview**](octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, roles, artifacts, and lifecycle
- [**Project Initiation Guide**](octoacme-project-initiation.md) — Steps to validate work, align stakeholders, and create an initial plan
- [**Project Planning**](octoacme-project-planning.md) — How to turn an approved initiative into an actionable plan and backlog
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies
- [**Release & Deployment Guide**](octoacme-release-and-deployment.md) — Standardized processes for releasing features to production
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — How to capture learnings and drive improvements
- [**Roles & Personas**](octoacme-roles-and-personas.md) — Detailed descriptions of typical roles and responsibilities

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
3. **In active delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md)
4. **Preparing a release?** Check the [Release & Deployment Guide](octoacme-release-and-deployment.md)
5. **Wrapping up?** Review [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Purpose of This Documentation

This documentation serves to:

- Centralize scattered project management knowledge in a single, searchable location
- Convert tacit team insights into versioned, referenceable artifacts
- Give all team members equal access to processes, decisions, and rationale
- Enable consistent, repeatable project execution
- Accelerate onboarding and reduce single-person dependency risk
- Feed validated improvements back into living documentation

## Issue Templates

Issue templates for proposing updates to these process documents are available in `.github/ISSUE_TEMPLATE/`:

- [**Add Content to Project Management Process Docs**](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) — Use this template to propose additions or updates to any process document
