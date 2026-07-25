# Open GI (open-gi)

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
