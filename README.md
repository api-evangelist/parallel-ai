# Parallel

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

Parallel Web Systems builds web APIs purpose-built for AI agents: a high-accuracy Search API, an Extract API that turns URLs into clean LLM-ready markdown, a Task/Deep Research API with tiered processors (lite through ultra), FindAll for natural-language entity discovery and enrichment, a Monitor API for scheduled web-change tracking, an OpenAI-compatible Responses and Chat Completions pair, and a Memory API that lets agents reuse past research. The platform is API-key authenticated over https://api.parallel.ai, ships official Python and TypeScript SDKs and a CLI, emits Standard Webhooks and SSE event streams, and is SOC 2 Type I/II certified. Its agent surface is unusually complete: an anonymous hosted MCP server whose tools are publicly introspectable, an OAuth-gated Task MCP server, a conformant A2A agent card backed by a live /a2a endpoint, provider-published Agent Skills with a discovery document, an llms.txt, and markdown twins of every documentation page. Pricing is pay-as-you-go per request per product. Originally surfaced as a Kleiner Perkins portfolio company and enriched from Parallel's public developer surface.

**Areas:** Company · Artificial Intelligence · Web Search · Agents · Deep Research · Web Extraction · Data Enrichment · Web Monitoring · LLM Tools · A2A · AI Agents · MCP

## Parallel on APIs.io

Everything profiled for Parallel is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/parallel-ai/](https://apis.io/providers/parallel-ai/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Parallel Chat API (Beta) API](https://apis.io/apis/parallel-ai/parallel-ai-chat-api-beta-api/) — The Chat API provides a programmatic chat-style text generation interface. It accepts a sequence of messages and returns model responses. Intended for…
- [Parallel Extract API](https://apis.io/apis/parallel-ai/parallel-ai-extract-api/) — Extract returns excerpts or full content from one or more URLs. Inputs are a list of URLs and an optional search objective and keyword queries. The returned…
- [Parallel Find All API](https://apis.io/apis/parallel-ai/parallel-ai-findall-api/) — The FindAll API discovers and evaluates entities that match complex criteria from natural language objectives. Submit a high-level goal and the service…
- [Parallel Memory API](https://apis.io/apis/parallel-ai/parallel-ai-memory-api/) — The Memory API retrieves and manages memories created by Tasks, Monitors, and FindAll runs. Memories can be personal or isolated with a `memory_scope_key`.
- [Parallel Monitor API](https://apis.io/apis/parallel-ai/parallel-ai-monitor-api/) — The Monitor API watches the web for material changes on a fixed frequency. Each monitor runs once on creation and then on its configured schedule, emitting…
- [Parallel Responses API](https://apis.io/apis/parallel-ai/parallel-ai-responses-api-api/) — An OpenAI-Responses-compatible interface for answers grounded in live web research, with URL citations. Point any Responses-API client — the OpenAI Python…
- [Parallel Search API](https://apis.io/apis/parallel-ai/parallel-ai-search-api/) — Search returns ranked URLs with extended excerpts suitable for LLM consumption. Inputs are a natural-language objective and optional keyword queries. Source…
- [Parallel Tasks API](https://apis.io/apis/parallel-ai/parallel-ai-tasks-api/) — The Task API executes web research and extraction tasks. Clients submit a natural-language objective with an optional input schema; the service plans…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Parallel Webhooks](https://apis.io/asyncapis/parallel-ai/parallel-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [parallel-mcp.yml](https://apis.io/servers/parallel-ai/parallel-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Parallel Agentic Access](https://apis.io/agentic-access/parallel-ai/parallel-agentic-access/)

#### Collections (12)

Postman and Open Collection request collections.

- [Parallel Chat API (Beta) Chat API (Beta) Chat API (Beta) API](https://apis.io/collections/parallel-ai/open-parallel-chat-api-beta-api/)
- [Parallel Chat API (Beta) Chat API (Beta) Extract API](https://apis.io/collections/parallel-ai/open-parallel-extract-api/)
- [Parallel Chat API (Beta) Chat API (Beta) FindAll API](https://apis.io/collections/parallel-ai/open-parallel-findall-api/)
- [Parallel Chat API (Beta) Chat API (Beta) Monitor API](https://apis.io/collections/parallel-ai/open-parallel-monitor-api/)
- [Parallel Chat API (Beta) Chat API (Beta) Search API](https://apis.io/collections/parallel-ai/open-parallel-search-api/)
- [Parallel Chat API (Beta) Chat API (Beta) Tasks API](https://apis.io/collections/parallel-ai/open-parallel-tasks-api/)
- [Parallel Chat API (Beta) Chat API (Beta) Chat API (Beta) API](https://apis.io/collections/parallel-ai/postman-parallel-chat-api-beta-api/)
- [Parallel Chat API (Beta) Chat API (Beta) Extract API](https://apis.io/collections/parallel-ai/postman-parallel-extract-api/)
- [Parallel Chat API (Beta) Chat API (Beta) FindAll API](https://apis.io/collections/parallel-ai/postman-parallel-findall-api/)
- [Parallel Chat API (Beta) Chat API (Beta) Monitor API](https://apis.io/collections/parallel-ai/postman-parallel-monitor-api/)
- [Parallel Chat API (Beta) Chat API (Beta) Search API](https://apis.io/collections/parallel-ai/postman-parallel-search-api/)
- [Parallel Chat API (Beta) Chat API (Beta) Tasks API](https://apis.io/collections/parallel-ai/postman-parallel-tasks-api/)

#### Overlays (9)

OpenAPI overlays, including conversational phrasing for each operation.

- [Parallel Chat Api Beta Api Phrasing Overlay](https://apis.io/overlays/parallel-ai/parallel-chat-api-beta-api-phrasing-overlay/)
- [Parallel Extract Api Phrasing Overlay](https://apis.io/overlays/parallel-ai/parallel-extract-api-phrasing-overlay/)
- [Parallel Findall Api Phrasing Overlay](https://apis.io/overlays/parallel-ai/parallel-findall-api-phrasing-overlay/)
- [Parallel Memory Api Phrasing Overlay](https://apis.io/overlays/parallel-ai/parallel-memory-api-phrasing-overlay/)
- [Parallel Monitor Api Phrasing Overlay](https://apis.io/overlays/parallel-ai/parallel-monitor-api-phrasing-overlay/)
- [Parallel Openapi Overlay](https://apis.io/overlays/parallel-ai/parallel-openapi-overlay/)
- [Parallel Responses Api Api Phrasing Overlay](https://apis.io/overlays/parallel-ai/parallel-responses-api-api-phrasing-overlay/)
- [Parallel Search Api Phrasing Overlay](https://apis.io/overlays/parallel-ai/parallel-search-api-phrasing-overlay/)
- [Parallel Tasks Api Phrasing Overlay](https://apis.io/overlays/parallel-ai/parallel-tasks-api-phrasing-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Parallel Authentication](https://apis.io/security/parallel-ai/parallel-authentication/)
- [Parallel Domain Security](https://apis.io/security/parallel-ai/parallel-domain-security/)
- [Parallel Trust Center](https://apis.io/security/parallel-ai/parallel-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Parallel Scopes](https://apis.io/scopes/parallel-ai/parallel-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Parallel Plans Pricing](https://apis.io/plans/parallel-ai/parallel-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Parallel Rate Limits](https://apis.io/rate-limits/parallel-ai/parallel-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.parallel.ai)
- [Documentation](https://docs.parallel.ai/home)
- [Getting started](https://docs.parallel.ai/getting-started/overview)
- [API reference](https://docs.parallel.ai/api-reference)
- [Pricing](https://docs.parallel.ai/getting-started/pricing)
- [Sign up](https://platform.parallel.ai)
- [Support](https://docs.parallel.ai/resources/faqs)
- [Blog](https://parallel.ai/blog)
- [Terms of service](https://parallel.ai/terms-of-service)
- [Privacy policy](https://parallel.ai/privacy-policy)
- [GitHub](https://github.com/parallel-web)
- [Status](https://status.parallel.ai/)

## API Evangelist rating

**Kin Score 74.2** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 65.0 |
| Contract governance | 18.2 |
| Operational transparency | 84.2 |
| Developer ergonomics | 90.0 |
| Access clarity | 81.6 |

**Agent readiness 64.7** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | mostly |

**Regulatory alignment 36.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/parallel-ai/](https://apis.io/providers/parallel-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Parallel: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/parallel-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
