# Open GI (open-gi)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Open GI is a Worcester-headquartered insurance software house that has supplied the UK and Ireland general insurance market for more than 45 years, serving over 600 broker, MGA and insurer customers across personal and commercial lines. Its product estate spans the legacy Core policy administration system and the newer cloud Mobius platform — policy administration and client management, product management, Insurer Hosted Pricing (IHP and IHP+), Ratings, the Dynamic Pricing Tool, quote-and-buy websites, customer portals and a Partner Network of 150-plus insurers, aggregators, premium finance, payment and data-enrichment providers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/open-gi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/open-gi/refs/heads/main/apis.yml)

## API Posture

Open GI's API posture is honestly partner-gated. Mobius genuinely ships APIs — Open GI's own public release notes describe a Client Checks API with sanctions-check endpoints and an API-triggered custom event — but everything about them sits behind a customer relationship:

- **No public developer portal.** A "Developer Portal" is named in Open GI's Mobius release notes and platform-services terms, but its URL is never published. `developer`, `developers`, `docs`, `api`, `apis`, `portal`, `partners`, `developerportal` and `mobius` subdomains of `opengi.co.uk` all fail to resolve, and a certificate-transparency sweep of the domain returned 39 hostnames with no developer-, docs-, api- or portal-named host among them.
- **No developer paths.** `/developers`, `/developer`, `/developer-portal`, `/api`, `/apis`, `/partners` and `/integrations` on the marketing site all return HTTP 404.
- **Even the API terms are gated.** `/supplementary-sales-and-product-terms/api-terms-of-use` is listed in the public sitemap but is Webflow password-protected (HTTP 401), as is the Mobius platform-services terms page.
- **No downloadable specification.** No OpenAPI or Swagger artifact is reachable anonymously, so the `openapi/` directory is deliberately omitted from this repo.
- **No ACORD.** ACORD, AL3, ACORD XML, NGDS, IVANS, Applied Epic and Vertafore appear nowhere across the public site. What Open GI does document is UK-market insurer **EDI** inside Mobius — the release notes describe an insurer authorisation code being carried in the EDI message when a quote converts to a policy.
- **Quote, bind, issue and FNOL** are all performed inside the platform. None are exposed through a publicly documented API.
- **No public auth model, sandbox, webhook catalog, AsyncAPI, GraphQL surface or Postman workspace** was found.

The only anonymous login surfaces are a Jira Service Management customer service desk and a BeyondTrust remote-support portal — neither is a developer portal.

## APIs

### Mobius APIs

The API layer of Open GI's cloud Mobius broking platform. Open GI's public Mobius release notes document a Client Checks API whose sanctions-check endpoints include a POST to initiate a sanction check for a customer, GET endpoints for automated and manual sanction-check matches, a GET for the detail of a specific sanction and a POST to update notes and overridden matches — plus the ability to trigger a Mobius custom event from an external system via an API call. Access is restricted to existing "Mobius APIs users" through the unpublished Mobius Developer Portal. No base URL, OpenAPI definition, authentication scheme, rate limits or sandbox are publicly documented.

- **Human URL:** [https://www.opengi.co.uk/mobius-release](https://www.opengi.co.uk/mobius-release)

#### Tags

- Insurance
- Policy Administration
- Sanctions Screening
- Client Checks
- Broker
- Partner Gated

#### Properties

- [Documentation](https://www.opengi.co.uk/mobius-release)

## Tags

- Insurance
- United Kingdom
- Ireland
- Broker
- Agency Management
- Policy Administration
- Underwriting
- Insurtech
- Property and Casualty
- MGA
- Insurer Hosted Pricing
- Partner Gated

## Links

- [Website](https://www.opengi.co.uk/)
- [Who We Are](https://www.opengi.co.uk/who-we-are)
- [Newsroom](https://www.opengi.co.uk/newsroom)
- [Mobius Release Notes](https://www.opengi.co.uk/mobius-release)
- [Partner Network](https://www.opengi.co.uk/sub-solutions/partner-network)
- [Support](https://www.opengi.co.uk/support)
- [LinkedIn](https://www.linkedin.com/company/open-gi)

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25
