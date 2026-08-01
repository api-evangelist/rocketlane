---
name: Create a task and log time against it
description: Create a task on a project, assign it, then log a time entry for the work.
api: https://developer.rocketlane.com
operations: [create-task, add-assignee-to-task, create-time-entry, get-all-time-entries]
---

# Create a task and log time

Use this flow to add work and record effort in Rocketlane.

## Auth
- Base URL: `https://api.rocketlane.com/api/1.0/`
- Send your workspace API key in the `api-key` request header on every call.

## Steps
1. **Create the task** — call `create-task` with the target project (and phase, if applicable).
2. **Assign it** — call `add-assignee-to-task` with the task id and the assignee user id.
3. **Log time** — call `create-time-entry` referencing the task, user, date, and minutes.
4. **Verify** — call `get-all-time-entries` (cursor pagination) filtered to the task to confirm the entry.

## Conventions & gotchas
- Use `pageSize`/`pageToken` for pagination; response envelope is `{ data, pagination }`.
- No idempotency key — do not silently retry `create-time-entry` on timeout; verify with `get-all-time-entries` first.
- Errors are HTTP status codes + JSON body (no `application/problem+json`).
