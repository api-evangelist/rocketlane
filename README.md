# Rocketlane

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Rocketlane is an AI-powered Professional Services Automation (PSA) platform that unifies customer onboarding, project delivery, resource management, time tracking, and professional-services financials in one system. Its public REST API (base https://api.rocketlane.com/api/1.0/) exposes projects, tasks, phases, spaces, space documents, custom fields, time entries, time-offs, resource allocations, users, and invoices, authenticated with a workspace api-key header and paginated with cursors. Outbound webhooks broadcast task, project, and phase lifecycle events, and a first-party CLI (@rocketlane/rli) supports building apps for the Rocketlane Marketplace. Originally added to the API Evangelist network as a portfolio-company lead (8vc, Insight Partners); enriched from its live developer surface.

**Areas:** Company · Professional Services Automation · Project Management · Customer Onboarding · Resource Management · Time Tracking · PSA · Software-as-a-Service

## Rocketlane on APIs.io

Everything profiled for Rocketlane is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/rocketlane/](https://apis.io/providers/rocketlane/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Rocketlane Comments API](https://apis.io/apis/rocketlane/rocketlane-comments-api/) — Endpoints for comments resource
- [Rocketlane Conversations API](https://apis.io/apis/rocketlane/rocketlane-conversations-api/) — Endpoints for conversations resource
- [Rocketlane Fields API](https://apis.io/apis/rocketlane/rocketlane-fields-api/) — Endpoints for fields resource
- [Rocketlane Invoices API](https://apis.io/apis/rocketlane/rocketlane-invoices-api/) — Endpoints for invoices resource
- [Rocketlane Phases API](https://apis.io/apis/rocketlane/rocketlane-phases-api/) — Endpoints for phases resource
- [Rocketlane Projects API](https://apis.io/apis/rocketlane/rocketlane-projects-api/) — Endpoints for projects resource
- [Rocketlane Resource Allocations API](https://apis.io/apis/rocketlane/rocketlane-resource-allocations-api/) — Endpoints for resource allocation resource
- [Rocketlane Space Documents API](https://apis.io/apis/rocketlane/rocketlane-space-documents-api/) — Endpoints for space tabs resource
- [Rocketlane Spaces API](https://apis.io/apis/rocketlane/rocketlane-spaces-api/) — Endpoints for space resource
- [Rocketlane Tasks API](https://apis.io/apis/rocketlane/rocketlane-tasks-api/) — Endpoints for tasks resource
- [Rocketlane Time-Offs API](https://apis.io/apis/rocketlane/rocketlane-time-offs-api/) — Endpoints for time-offs resource
- [Rocketlane Time Tracking API](https://apis.io/apis/rocketlane/rocketlane-time-tracking-api/) — Endpoints for time entries and timesheets
- [Rocketlane Users API](https://apis.io/apis/rocketlane/rocketlane-users-api/) — Endpoints for users resource

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Rocketlane Webhooks](https://apis.io/asyncapis/rocketlane/rocketlane-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [rocketlane](https://apis.io/servers/rocketlane/rocketlane/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Rocketlane Agentic Access](https://apis.io/agentic-access/rocketlane/rocketlane-agentic-access/)

#### Collections (13)

Postman and Open Collection request collections.

- [Rocketlane Comments API](https://apis.io/collections/rocketlane/open-rocketlane-comments-api/)
- [Rocketlane Comments Conversations API](https://apis.io/collections/rocketlane/open-rocketlane-conversations-api/)
- [Rocketlane Comments Fields API](https://apis.io/collections/rocketlane/open-rocketlane-fields-api/)
- [Rocketlane Comments Invoices API](https://apis.io/collections/rocketlane/open-rocketlane-invoices-api/)
- [Rocketlane Comments Phases API](https://apis.io/collections/rocketlane/open-rocketlane-phases-api/)
- [Rocketlane Comments Projects API](https://apis.io/collections/rocketlane/open-rocketlane-projects-api/)
- [Rocketlane Comments Resource Allocations API](https://apis.io/collections/rocketlane/open-rocketlane-resource-allocations-api/)
- [Rocketlane Comments Space Documents API](https://apis.io/collections/rocketlane/open-rocketlane-space-documents-api/)
- [Rocketlane Comments Spaces API](https://apis.io/collections/rocketlane/open-rocketlane-spaces-api/)
- [Rocketlane Comments Tasks API](https://apis.io/collections/rocketlane/open-rocketlane-tasks-api/)
- [Rocketlane Comments Time-Offs API](https://apis.io/collections/rocketlane/open-rocketlane-time-offs-api/)
- [Rocketlane Comments Time Tracking API](https://apis.io/collections/rocketlane/open-rocketlane-time-tracking-api/)
- [Rocketlane Comments Users API](https://apis.io/collections/rocketlane/open-rocketlane-users-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Rocketlane Overlay](https://apis.io/overlays/rocketlane/rocketlane-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Rocketlane Authentication](https://apis.io/security/rocketlane/rocketlane-authentication/)
- [Rocketlane Domain Security](https://apis.io/security/rocketlane/rocketlane-domain-security/)
- [Rocketlane Trust Center](https://apis.io/security/rocketlane/rocketlane-trust-center/)
- [Rocketlane Vulnerability Disclosure](https://apis.io/security/rocketlane/rocketlane-vulnerability-disclosure/)

#### Rate limits (1)

Published request limits.

- [Rocketlane Rate Limits](https://apis.io/rate-limits/rocketlane/rocketlane-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://rocketlane.com)
- [Documentation](https://developer.rocketlane.com/docs/overview)
- [Getting started](https://developer.rocketlane.com/docs/overview)
- [API reference](https://developer.rocketlane.com/reference/tasks)
- [Pricing](https://www.rocketlane.com/pricing)
- [Sign up](https://www.rocketlane.com/signup)
- [Support](https://help.rocketlane.com/support/home)
- [Blog](https://www.rocketlane.com/blogs)
- [Security](https://www.rocketlane.com/responsible-disclosure)
- [Compliance](https://www.rocketlane.com/trust)
- [Terms of service](https://www.rocketlane.com/legal/terms)
- [Privacy policy](https://www.rocketlane.com/legal/privacy-policy)
- [GitHub](https://github.com/Rocketlane)
- [Status](https://status.rocketlane.com)

## API Evangelist rating

**Kin Score 55.6** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 59.1 |
| Contract governance | 18.2 |
| Operational transparency | 57.9 |
| Developer ergonomics | 47.0 |
| Access clarity | 60.5 |

**Agent readiness 39.3** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/rocketlane/](https://apis.io/providers/rocketlane/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Rocketlane: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/rocketlane/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
