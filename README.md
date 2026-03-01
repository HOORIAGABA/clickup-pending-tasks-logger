# clickup-pending-tasks-logger

n8n workflow that tracks daily pending tasks per team member from ClickUp → accumulates them in Google Sheets (avoids duplicates).
Triggered on task status updates (pending by frontend/backend, deployment blocked). Formats dates in PKT.
Part of departmental productivity logging system (used for AI team — variants exist for devops, backend, frontend, QA).
