# Linden Lab

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

Linden Lab is the San Francisco company that created and has continuously operated Second Life since 2003 — the largest and longest-running user-built 3D virtual world, with its own economy, land market and L$ currency. Its public API surface is small and old, documented in prose on the Second Life wiki rather than in any machine-readable contract: anonymous Live Data Feeds publishing grid statistics and LindeX currency-market data, an api-key-authenticated username to agent-UUID lookup, a capability-based Registration API for creating accounts from a third-party site, an embeddable Leaflet-based Map API, and an outbound Marketplace webhook. Linden Lab also publishes the Second Life viewer, the LSL and SLua scripting documentation, and the LLSD serialization libraries on GitHub. It no longer owns Tilia, its former payments subsidiary, which was sold to Thunes in 2024.

**Areas:** Virtual Worlds · Metaverse · Gaming · 3D · Social · Virtual Economy · Digital Currency · Marketplace · Scripting · User Generated Content

## Linden Lab on APIs.io

Everything profiled for Linden Lab is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/linden-lab/](https://apis.io/providers/linden-lab/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Second Life Live Data Feeds](https://apis.io/apis/linden-lab/second-life-live-data-feeds/) — Anonymous, unauthenticated feeds publishing live Second Life grid statistics (grid status, total registered accounts, avatars currently inworld) and LindeX…
- [Second Life Name to Agent ID API](https://apis.io/apis/linden-lab/second-life-name-to-agent-id-api/) — Resolves a Second Life username, with an optional last name defaulting to "Resident", to the avatar's agent UUID. A JSON POST authenticated with an api-key…
- [Second Life Registration API](https://apis.io/apis/linden-lab/second-life-registration-api/) — Registers new Second Life residents from a third-party web page. Capability based — credentials are POSTed to a capability-minting endpoint which returns…
- [Second Life Map API](https://apis.io/apis/linden-lab/second-life-map-api/) — Embeds an interactive map of the Second Life world into a web page. A Leaflet-based JavaScript component (SLMap, gotoSLURL, setView) backed by two JSONP…
- [Second Life Marketplace Automatic Notification System](https://apis.io/apis/linden-lab/second-life-marketplace-automatic-notification-system/) — An outbound webhook that forwards information about every sale made on the Second Life Marketplace to a merchant-configured external URL. Delivers Purchase…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Linden Lab Ans Webhooks](https://apis.io/asyncapis/linden-lab/linden-lab-ans-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [linden-lab-mcp.yml](https://apis.io/servers/linden-lab/linden-lab-mcp-yml/)

#### Examples (1)

Example requests and responses.

- [Linden Lab Status](https://apis.io/examples/linden-lab/linden-lab-status/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Linden Lab Authentication](https://apis.io/security/linden-lab/linden-lab-authentication/)
- [Linden Lab Domain Security](https://apis.io/security/linden-lab/linden-lab-domain-security/)
- [Linden Lab Trust Center](https://apis.io/security/linden-lab/linden-lab-trust-center/)
- [Linden Lab Vulnerability Disclosure](https://apis.io/security/linden-lab/linden-lab-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Linden Lab Plans Pricing](https://apis.io/plans/linden-lab/linden-lab-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Linden Lab Rate Limits](https://apis.io/rate-limits/linden-lab/linden-lab-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://lindenlab.com/)
- [Documentation](https://create.secondlife.com/script/lsl-reference/)
- [Getting started](https://create.secondlife.com/script/)
- [API reference](https://wiki.secondlife.com/wiki/Category:APIs)
- [Pricing](https://secondlife.com/premium)
- [Sign up](https://join.secondlife.com/)
- [Support](https://lindenlab.freshdesk.com/support/home)
- [Blog](https://community.secondlife.com/blogs/)
- [Terms of service](https://lindenlab.com/tos)
- [Privacy policy](https://lindenlab.com/privacy)
- [GitHub](https://github.com/secondlife)
- [Status](https://status.secondlifegrid.net/)

## API Evangelist rating

**Kin Score 60.4** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 45.3 |
| Contract governance | 4.5 |
| Operational transparency | 73.7 |
| Developer ergonomics | 71.4 |
| Access clarity | 76.3 |

**Agent readiness 26.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/linden-lab/](https://apis.io/providers/linden-lab/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Linden Lab: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/linden-lab/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
