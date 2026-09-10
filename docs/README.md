# OctoAcme Project Management Documentation

## Welcome

This folder contains the complete OctoAcme project management process documentation. Whether you're starting a new project, managing execution, or closing out an initiative, you'll find guidance here.

## Our Project Management Approach

OctoAcme follows an iterative, outcome-focused approach to project delivery. We emphasize:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments rather than big-bang releases
- **Clear ownership**: Each project has named Project Manager (PM) and Product Manager (PdM) roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

Projects flow through distinct phases—from initiation through close—with defined gates, artifacts, and team rhythms at each stage.

## Core Process Documentation

### Phase-Based Guides

1. **[Project Initiation](octoacme-project-initiation.md)** — Validate the business need, align stakeholders, and decide go/no-go
   - Problem statement and objectives
   - Stakeholder identification and alignment
   - Decision gates before moving to planning

2. **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments, identify risks, and define milestones
   - Backlog creation and prioritization
   - Estimation and resource planning
   - Release plan and milestone mapping

3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, measure progress, and escalate blockers
   - Daily standups and weekly syncs
   - PR workflows and Definition of Done
   - Quality gates and testing requirements
   - Progress tracking and blocker escalation

4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize how features reach production safely
   - Pre-release requirements and checklists
   - Deployment procedures and rollback plans
   - Release notes and post-deploy verification

5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive iterative improvements
   - Running effective retrospectives
   - Tracking and implementing action items
   - Building a culture of continuous improvement

### Cross-Cutting Topics

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, assess, and communicate risks across all phases
  - Risk register maintenance and lifecycle
  - Stakeholder communication strategies
  - Escalation paths and incident communication

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Understand responsibilities and communication patterns for key roles
  - Developer responsibilities and goals
  - Product Manager priorities and communication
  - Project Manager role and expectations

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to principles, lifecycle, and key artifacts
  - Core principles and lifecycle overview
  - Key roles and artifacts
  - Communication cadence

## Quick Reference by Role

### Developers

Start with **[Execution & Tracking](octoacme-execution-and-tracking.md)** for PR workflows and Definition of Done standards. Review **[Roles & Personas](octoacme-roles-and-personas.md)** for developer responsibilities and communication patterns.

**Key focus areas:**
- Small PRs (≤ 400 lines when possible)
- Automated testing and linting requirements
- Code review and approval process

### Product Managers

Begin with **[Project Initiation](octoacme-project-initiation.md)** and **[Project Planning](octoacme-project-planning.md)** to understand how to validate problems and define success. See **[Roles & Personas](octoacme-roles-and-personas.md)** for PM priorities and communication patterns.

**Key focus areas:**
- Problem validation and customer research
- Success metrics and outcome measurement
- Backlog prioritization and roadmap planning

### Project Managers

Consult **[Project Planning](octoacme-project-planning.md)**, **[Execution & Tracking](octoacme-execution-and-tracking.md)**, and **[Risk Management & Communication](octoacme-risks-and-communication.md)**. Review **[Roles & Personas](octoacme-roles-and-personas.md)** for PM responsibilities and expectations.

**Key focus areas:**
- Project timelines, milestones, and deliverables
- Risk and dependency management
- Cross-team coordination and escalation

## How to Use These Docs

1. **Getting Started:** Read **[Project Management Overview](octoacme-project-management-overview.md)** first for a high-level introduction to our approach and key roles.

2. **Starting a Project:** Follow the flow through Initiation → Planning → Execution → Release based on where your project is in its lifecycle.

3. **Mid-Project:** Consult relevant phase guides and cross-cutting topics as needed. Keep your Project Charter and Risk Register updated.

4. **Process Improvements:** If you identify gaps or improvements in these docs, open an issue using the "Add Content to Project Management Process Docs" template in `.github/ISSUE_TEMPLATE/`.

5. **Copilot Spaces:** Add role-specific or project-specific docs to `.copilot/` if using Copilot Spaces for contextual, AI-assisted guidance.

## Key Artifacts Across Phases

| Phase | Key Artifacts |
|-------|----------------|
| Initiation | Project One-pager, Stakeholder List, Approval Decision |
| Planning | Project Charter, Backlog, Release Plan, Definition of Done |
| Execution | Sprint Backlog, Risk Register, Status Reports, PRs/Reviews |
| Release | Release Notes, Deployment Plan, Rollback Plan, Post-Deploy Verification |
| Close | Retrospective Notes, Action Items, Lessons Learned |

## Communication Cadence

- **Daily:** Team standups (15 min) — progress, blockers, dependencies
- **Twice Weekly:** Delivery team syncs (as agreed)
- **Weekly:** PM + PdM sync — roadmap, risks, decisions
- **Weekly:** Stakeholder status updates
- **Monthly:** Stakeholder updates and strategy alignment
- **Per Sprint/Milestone:** Sprint planning, demo/review, retrospective

## Contributing & Feedback

These docs are **living artifacts**. As processes evolve and new insights emerge, we keep them up to date. If you identify gaps, outdated information, or improvements:

1. Open an issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Describe the gap or improvement clearly
3. Suggest content changes if possible
4. Include rationale and acceptance criteria

Your feedback helps us continuously improve how we run projects at OctoAcme.
