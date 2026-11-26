# Threads MCP

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

Threads MCP provides a connector service that links a user's Threads social media account to AI assistants such as Claude and ChatGPT via the Model Context Protocol (MCP). It enables drafting, publishing, replying, and moderating Threads posts directly from chat interfaces, while handling OAuth 2.1 authentication and storing only minimal user identifiers and encrypted access tokens. The service runs on Vercel and Supabase in the EU and respects user privacy, offering transparent data handling and compliance with applicable regulations.

**Areas:** Company · Threads · MCP · AI · Connector

## Threads MCP on APIs.io

Everything profiled for Threads MCP is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/threads-mcp-app/](https://apis.io/providers/threads-mcp-app/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Threads MCP Authorization API](https://apis.io/apis/threads-mcp-app/threads-mcp-app-authorization-api/) — OAuth 2.1 discovery metadata. The authorization server is Supabase Auth.
- [Threads MCP Discovery API](https://apis.io/apis/threads-mcp-app/threads-mcp-app-discovery-api/) — Machine-readable documents that describe the MCP server.
- [Threads MCP MCP API](https://apis.io/apis/threads-mcp-app/threads-mcp-app-mcp-api/) — The Model Context Protocol endpoint (JSON-RPC 2.0 over streamable HTTP).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Threads MCP Agentic Access](https://apis.io/agentic-access/threads-mcp-app/threads-mcp-app-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [AgentSkillsIndex](https://apis.io/schemas/threads-mcp-app/threads-mcp-app-agent-skills-index/)
- [AuthorizationServerMetadata](https://apis.io/schemas/threads-mcp-app/threads-mcp-app-authorization-server-metadata/)
- [JsonRpcRequest](https://apis.io/schemas/threads-mcp-app/threads-mcp-app-json-rpc-request/)
- [McpManifest](https://apis.io/schemas/threads-mcp-app/threads-mcp-app-mcp-manifest/)
- [McpServerCard](https://apis.io/schemas/threads-mcp-app/threads-mcp-app-mcp-server-card/)
- [ProtectedResourceMetadata](https://apis.io/schemas/threads-mcp-app/threads-mcp-app-protected-resource-metadata/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Threads Mcp App Context](https://apis.io/jsonld/threads-mcp-app/threads-mcp-app-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Threads MCP API Rules](https://apis.io/rules/threads-mcp-app/threads-mcp-app-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Threads MCP Authentication](https://apis.io/security/threads-mcp-app/threads-mcp-app-authentication/)
- [Threads MCP Domain Security](https://apis.io/security/threads-mcp-app/threads-mcp-app-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Threads MCP Scopes](https://apis.io/scopes/threads-mcp-app/threads-mcp-app-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://threads-mcp.app/)
- [Documentation](https://threads-mcp.app/developers)
- [Support](https://threads-mcp.app/contact)
- [Terms of service](https://threads-mcp.app/terms)
- [Privacy policy](https://threads-mcp.app/privacy)

## API Evangelist rating

**Kin Score 44.9** — developing · rubric 0.28.0 · scored 2026-11-26

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 62.8 |
| Contract governance | 79.1 |
| Operational transparency | 0.0 |
| Developer ergonomics | 35.7 |
| Access clarity | 17.0 |

**Agent readiness 46.0** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 26.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/threads-mcp-app/](https://apis.io/providers/threads-mcp-app/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Threads MCP: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/threads-mcp-app/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
