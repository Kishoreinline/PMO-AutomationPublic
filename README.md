# PMO Automation (public overview)

**This repository is still in progress. It exists purely to demonstrate PM automation using AI.**

Public showcase for **PMO Automation** — an AI-assisted wrapper on **Azure DevOps** that helps run Agile / Scrum (and related board) project management. This repo holds **overview material and screenshots only**. Application source code is **not** published here.

Connect an Azure DevOps organization through the product UI. AI can recommend story points, order work, pack sprints within team capacity, realign plans when the backlog changes, surface reports, and propose bounded agent guidance. **Azure DevOps remains the live board.** Humans confirm before writes.

## Status

| | |
| --- | --- |
| Purpose | Demonstrate PM automation with AI on Azure DevOps |
| This repo | Screenshots + product narrative (no app source) |
| Maturity | Work in progress |

## Screenshots

### Connect

PAT-based connect. The token stays in the browser session only.

![Connect to Azure DevOps](docs/screenshots/01-connect.png)

### Projects

Pick an Azure DevOps project to open the PMO tabs.

![Projects](docs/screenshots/02-projects.png)

### Story points

Fibonacci or T-shirt scale (**1 point = 1 day**). AI can suggest points and execution order. Plan changes are reviewed before anything is written to Azure DevOps.

![Story points and confirm plan](docs/screenshots/03-story-points.png)

### Sprints

Set duration and start dates, then pack whole stories into dated sprints without exceeding team capacity.

![Sprints](docs/screenshots/04-sprints.png)

### Team resources

ADO members, start dates, story burn per sprint, and assigned load after the latest plan.

![Team resources](docs/screenshots/05-resources.png)

### Financials

Fixed or T&M style tracking — people, work, and money, with capacity-aware sprint billing.

![Financials](docs/screenshots/06-financials.png)

## What the product demonstrates

After connect (personal access token) and project pick, the PMO workspace guides delivery work across tabs, including:

| Area | What you see |
| --- | --- |
| Backlog upload | CSV / Excel style story intake into Azure DevOps |
| Story points & grooming | Estimates, order, acceptance readiness |
| Sub-tasks | Child tasks under pointed stories |
| Sprint / cycle planning | Capacity-capped packing; confirm before ADO write |
| Team resources | Burn rates and load |
| Finance | Fixed vs T&M style forecast views |
| Boards | Kanban / Spiral oriented board views |
| Reports | Burndown, capacity vs planned vs delivered, and related charts |
| AI Agents | Ask / starter prompts; recommendations stay advisory until humans act |

Any material plan change is meant to show as a **recommendation**, then a **confirm** step. Discard leaves Azure DevOps unchanged.

## Principles

- Azure DevOps is the source of truth for work-item state.
- AI recommendations are distinguishable from authoritative board data.
- External writes are validated and auditable (confirm before write).
- Personal Microsoft accounts: **PAT-based Connect** is the supported path (not work/school Entra for that scenario).

## Source of truth

- **This GitHub repository:** public overview and screenshots only.
- **Private development:** application code is developed separately and is not mirrored here.
- **Azure DevOps:** live work items, sprints, and team membership — users connect their org through the app UI.

---

*Work in progress — demonstration of PM automation using AI.*
