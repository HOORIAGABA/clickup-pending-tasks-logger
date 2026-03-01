# clickup-pending-tasks-logger

Daily Pending Task Logger for AI Team
n8n automation that:
• Listens to ClickUp task status changes (pending by frontend / backend / deployment blocked)
• Fetches full task details
• Formats task info with Pakistan time (Asia/Karachi)
• Accumulates pending tasks per member per day in Google Sheets
• Prevents duplicate entries when the same task updates multiple timesPart of a set of similar workflows created for different teams (devops, backend, frontend, QA, AI).Integrations: ClickUp (trigger + get task), Google Sheets (append/update), JavaScript code nodes for formatting & duplicate check.Useful for team leads / managers who want automatic daily snapshots of stalled/blocked work without manual reporting.
