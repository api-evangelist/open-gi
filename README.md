# Open GI

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

Open GI is a Worcester-headquartered insurance software house that has supplied the UK and Ireland general insurance market for more than 45 years, serving over 600 broker, MGA and insurer customers across personal and commercial lines. Its product estate spans the legacy Core policy administration system and the newer cloud Mobius platform — policy administration and client management, product management, Insurer Hosted Pricing (IHP and IHP+), Ratings, the Dynamic Pricing Tool, quote-and-buy websites, customer portals and a Partner Network of 150-plus insurers, aggregators, premium finance, payment and data-enrichment providers. Its API posture is honestly partner-gated. Mobius genuinely ships APIs — Open GI's own public release notes describe Client Checks / sanctions-check endpoints and an API-triggered custom-event call — but the Mobius Developer Portal is a customer-only surface whose URL Open GI does not publish, no developer, docs, api or partners subdomain resolves on opengi.co.uk, every /developers, /developer, /api and /partners path on the marketing site returns 404, and even the company's own API Terms of Use page is password-protected. There is no public self-serve developer portal, no downloadable OpenAPI or Swagger, no public sandbox, no published auth model and no ACORD reference anywhere on the public site; insurer connectivity is delivered through UK-market EDI messaging inside the platform and through pre-agreed Partner Network integrations rather than through an open API programme.

**Areas:** Insurance · United Kingdom · Ireland · Brokerage · Agency Management · Policy Administration · Underwriting · Insurtech · Property and Casualty · MGA · Insurer Hosted Pricing

## Open GI on APIs.io

Everything profiled for Open GI is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/open-gi/](https://apis.io/providers/open-gi/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Mobius APIs](https://apis.io/apis/open-gi/mobius-apis/) — The API layer of Open GI's cloud Mobius broking platform. Open GI's public Mobius release notes document real API capability — a Client Checks API whose…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Open Gi Domain Security](https://apis.io/security/open-gi/open-gi-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.opengi.co.uk/)
- [Documentation](https://www.opengi.co.uk/insurance-software-solutions)
- [Support](https://www.opengi.co.uk/support)
- [Changelog](https://www.opengi.co.uk/mobius-release)
- [Blog](https://www.opengi.co.uk/news/)
- [Compliance](https://www.opengi.co.uk/legals/operational-resilience)
- [Terms of service](https://www.opengi.co.uk/legals/terms-and-conditions)
- [Privacy policy](https://www.opengi.co.uk/legals/privacy-notice)

## API Evangelist rating

**Kin Score 19.7** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 15.8 |
| Developer ergonomics | 16.7 |
| Access clarity | 28.9 |

**Agent readiness 0.0** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 21.1** — Insurance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/open-gi/](https://apis.io/providers/open-gi/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Open GI: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/open-gi/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
