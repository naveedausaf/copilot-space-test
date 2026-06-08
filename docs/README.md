# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This README serves as the single entry point to all process documents, providing an overview of how OctoAcme runs projects and where to find detailed guidance.

## Overview

OctoAcme operates on a customer-first, iterative delivery model with clearly defined roles and responsibilities. **Project Managers** coordinate delivery activities, manage schedules, risks, and communications to keep teams aligned. **Product Managers** define what should be built, prioritize the backlog, and measure outcomes through data-driven decisions. **Developers** design and implement features while collaborating on quality standards, test coverage, and technical risk mitigation. **QA** validates quality and acceptance criteria throughout the delivery cycle. This clear ownership structure ensures accountability while fostering psychological safety through regular feedback loops and collaborative decision-making.

Projects flow through five distinct phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with acceptance criteria), **Execution** (daily standups, PR reviews, and quality gates), **Release** (controlled deployment with rollback plans), and **Retrospective** (capturing learnings for continuous improvement). The planning phase produces a lightweight One-pager documenting the problem statement, SMART goals, success metrics, stakeholders, and resource needs. Execution follows a structured rhythm with daily 15-minute standups, weekly delivery syncs, and end-of-sprint demos, with project boards using standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to maintain full transparency.

Communication occurs through a consistent cadence: weekly syncs between PM and PdM, twice-weekly standups for delivery teams, and monthly stakeholder updates. A three-level escalation path ensures issues reach appropriate decision-makers quickly. Risk management is formalized through a **Risk Register** that tracks ID, description, impact/likelihood, mitigation plans, and status, reviewed weekly during syncs. Dependencies across teams are marked on project boards and escalated during weekly meetings to prevent silos and unplanned delays.

Quality assurance is embedded throughout execution with unit tests, integration tests, end-to-end smoke tests for critical flows, and security scanning in the CI pipeline. Releases follow a standardized checklist ensuring all acceptance criteria are met, CI passes, release notes are drafted, and rollback plans exist. The organization closes the feedback loop with retrospectives held after each sprint or milestone, using a "what went well / what could improve" structure with prioritized action items tracked in the project backlog — embedding continuous improvement into the organizational culture.

## Process Documentation

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
