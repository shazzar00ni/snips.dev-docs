# GitHub Projects Board: Snips.dev Scrum Setup

## Columns (Kanban Workflow)
- **To Do**: New, unassigned tasks
- **In Progress**: Assigned issues currently being worked on
- **In Review**: Tasks with an open Pull Request
- **Done**: Completed and merged tasks

---

## Suggested Automation Rules (via GitHub Projects or Actions)
- When an issue is **assigned**, move it to `In Progress`.
- When a **Pull Request is opened** and linked to an issue, move it to `In Review`.
- When a **Pull Request is merged**, move the linked issue to `Done`.
- Use **labels** to trigger auto-filters (e.g., `type:bug`, `priority:high`, `component:frontend`).

---

## Example Custom Fields
| Field               | Description                               |
|--------------------|-------------------------------------------|
| Priority            | High, Medium, Low                         |
| Estimated Effort    | Story points (1, 2, 3, 5, 8)              |
| Target Release      | Version milestone (v1.0, Beta, etc.)      |
| Component           | Frontend, Backend, API, Docs              |
| Assigned Developer  | GitHub username                           |

---

## Sprint Naming Convention
- Sprint 1 (YYYY-MM-DD to YYYY-MM-DD)
- Sprint 2 (YYYY-MM-DD to YYYY-MM-DD)
- Use weekly or bi-weekly iterations depending on team pace.

---

## Initial Setup Steps
1. Go to the **Projects** tab in GitHub.
2. Create a new project using the **"Scrum" template**.
3. Add columns: `To Do`, `In Progress`, `In Review`, `Done`.
4. Add custom fields as above.
5. Connect the project to your repository and start linking issues.

