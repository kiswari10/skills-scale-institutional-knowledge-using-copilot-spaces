# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation. This README serves as a centralized hub for all process documents, providing a quick reference for contributors, project leads, and stakeholders to understand how OctoAcme runs projects.

## Quick Navigation

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, principles, roles, and artifacts
- [Project Initiation](octoacme-project-initiation.md) — How to validate and authorize new work, align stakeholders, and create a lightweight plan
- [Project Planning](octoacme-project-planning.md) — Breaking work into shippable increments, defining acceptance criteria, and creating release plans
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, workflows, quality assurance, and blocker escalation
- [Risk Management & Communication](octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks, dependencies, and stakeholder updates
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardized processes for releasing features to production and managing rollbacks
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Post-project learnings and converting improvements into action items
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed definitions of Product Managers, Project Managers, and Developers with responsibilities and goals

---

## OctoAcme Project Management Overview

OctoAcme employs a **lightweight, outcome-driven project management approach** structured across a complete project lifecycle. The organization prioritizes customer value through iterative delivery, clear ownership, and data-informed decision-making.

### The Project Lifecycle

**1. Initiation** — Validate the business need and define success
- Define scope, objectives, stakeholders, and success criteria through a concise One-pager
- Identify risks and resource needs
- Decision gate: Move to planning when success metrics are clear and stakeholder alignment is confirmed

**2. Planning** — Create an actionable delivery plan
- Break work into shippable increments with prioritized backlogs
- Define acceptance criteria and Definition of Done
- Estimate scope using T-shirt sizing or story points
- Identify dependencies, create release plans, and document risk registers
- Conduct project kickoff with stakeholders and delivery team

**3. Execution & Tracking** — Deliver iteratively with continuous visibility
- Daily standups (15 min) focused on progress, blockers, and dependencies
- Weekly delivery syncs and sprint reviews
- Use GitHub Projects with workflow columns: Backlog → Ready → In Progress → In Review → QA → Done
- Small pull requests (≤400 lines), automated CI/CD testing, and peer code review
- Track velocity, burndown, and product success metrics

**4. Release & Deployment** — Reduce risk and maintain quality
- Validate all acceptance criteria are met and tests pass
- Deploy to staging with smoke tests before production
- Execute deployment checklist and post-deploy verifications
- Maintain documented rollback and incident playbooks
- Announce releases to stakeholders and support teams

**5. Retrospectives & Continuous Improvement** — Capture learnings
- Hold retrospectives after each sprint, release, or milestone
- Identify what went well and what could be improved
- Convert insights into 2–3 prioritized action items with clear owners and timelines
- Track improvements and celebrate iterative progress

### Key Personas & Responsibilities

**Product Managers** define what should be built to deliver customer and business value. They own the product vision, prioritize backlogs, and measure impact through data-driven decisions and user research.

**Project Managers** coordinate delivery timelines, manage risks and dependencies, facilitate key meetings, and ensure consistent communication with stakeholders and the delivery team.

**Developers** implement features to meet acceptance criteria, write and maintain tests, participate in design and code reviews, and help identify technical risks.

### Communication Strategy

OctoAcme maintains structured communication:
- **Weekly PM Sync** — Product Manager and Project Manager alignment
- **Twice-Weekly Standups** — Delivery team progress and blockers
- **Monthly Stakeholder Updates** — High-level status and milestone progress
- **Ad-hoc Escalations** — Three-level escalation path for critical blockers: Team → PM → Product Lead → Sponsor

A **Risk Register** (tracking ID, Description, Impact, Likelihood, Owner, and Mitigation) is updated weekly during syncs. Weekly status templates include progress, next steps, risks/blockers, and decisions needed.

### Quality Assurance & Testing

Quality is embedded throughout execution:
- **Automated CI/CD** — Tests, linting, and security scanning in every PR
- **Code Review** — At least one approval required before merging
- **Testing Strategy** — Unit tests for new logic, integration tests, end-to-end smoke tests for critical flows, and manual QA for feature acceptance
- **Pre-Release Validation** — Acceptance criteria verification, passing CI/security scans, release notes, rollback plans, and staged deployment verification

### Key Artifacts

- Project One-pager (Problem, Goal, Success Metrics, Stakeholders, Timeline, Risks, Team)
- Roadmap and Release Plan
- Sprint/Iteration Backlog with Acceptance Criteria
- Definition of Done
- Risk Register
- Retrospective Notes and Action Items
- Release Notes

### Principles

- **Customer-First** — Prioritize customer value and usability
- **Iterative Delivery** — Deliver small, testable increments
- **Clear Ownership** — Each project has a named PM and Product Lead
- **Data-Informed Decisions** — Measure impact and iterate based on evidence
- **Psychological Safety** — Encourage feedback, learning, and blameless retrospectives

---

## How to Use These Docs

1. **For New Project Leads** — Start with the [Project Management Overview](octoacme-project-management-overview.md), then follow the lifecycle docs in order.
2. **For Teams Starting a New Project** — Begin with [Project Initiation](octoacme-project-initiation.md) to create your One-pager and get stakeholder alignment.
3. **For Ongoing Execution** — Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for team rhythm, workflow standards, and quality practices.
4. **For Risk Management** — Use [Risk Management & Communication](octoacme-risks-and-communication.md) to maintain your Risk Register and keep stakeholders informed.
5. **For Releases** — Follow [Release & Deployment](octoacme-release-and-deployment.md) to ensure production readiness and incident preparedness.
6. **For Learning & Improvement** — Run retrospectives using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).
7. **For Copilot Spaces Integration** — Add these process docs to `.copilot/` in your project repository to provide Copilot with organizational context.

---

## Questions or Feedback?

If you have questions about these processes or need clarification, please reach out to the Project Management team or open an issue in this repository.

**Last Updated:** June 2026
