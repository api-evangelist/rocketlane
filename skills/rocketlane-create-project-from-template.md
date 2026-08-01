---
name: Create a Rocketlane project from a template and add members
description: Spin up a customer onboarding/delivery project from a template, then staff it by adding members.
api: https://developer.rocketlane.com
operations: [import-template, get-all-projects, add-members]
---

# Create a Rocketlane project from a template

Use this flow to launch a delivery/onboarding project and staff it.

## Auth
- Base URL: `https://api.rocketlane.com/api/1.0/`
- Send your workspace API key in the `api-key` request header on every call (see `authentication/rocketlane-authentication.yml`).

## Steps
1. **Create the project from a template** — call `import-template` with the template id and project details. This provisions the project with its phases and tasks pre-populated.
2. **Confirm it exists** — call `get-all-projects` (cursor pagination: `pageSize`, `pageToken`; read `data[]` + `pagination`) to locate the new project id.
3. **Staff the project** — call `add-members` on the project to attach the delivery team.

## Conventions & gotchas
- Pagination is cursor-based; `nextPageToken` is valid for 15 minutes (`conventions/rocketlane-conventions.yml`).
- Every response carries an `X-Request-Id` header — log it for support.
- No idempotency-key is supported; avoid blind retries on create calls.
