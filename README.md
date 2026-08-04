# SpotDraft (spotdraft)

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

SpotDraft is an AI-powered Contract Lifecycle Management (CLM) platform headquartered in Bangalore, India, with offices in San Francisco, New York, and London. The platform lets legal, sales, procurement, and operations teams create, negotiate, sign, store, and analyze contracts in one place. Core capabilities include conditional workflows and approval routing, collaborative Word-based negotiation, a searchable contract repository with granular access controls, embedded SpotDraft AI for metadata extraction and risk flagging, ESIGN/EIDAS-compliant e-signatures, Clickwrap agreements, obligation tracking, and analytics dashboards. SpotDraft serves 450+ companies and is recognized as a Leader in the IDC MarketScape for AI-enabled buy-side CLMs and a G2 Leader. The company exposes a documented Public API (OpenAPI 3.0.3) with versions v1, v2, and v2.1 covering contracts, templates, counterparties, approvals, workflows, clickwrap, webhooks, analytics, users, and organizations across four regional clusters (India, United States, European Union, Middle East). Webhooks notify external systems of contract lifecycle events in real time. Native integrations exist for Salesforce, HubSpot, Zoho, Slack, Microsoft Teams, Google Drive, Dropbox, Box, OneDrive, SharePoint, DocuSign, Okta, Jira, Coupa, Zapier, and Greenhouse.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/spotdraft/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/spotdraft/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Contract Lifecycle Management
- CLM
- Contracts
- Legal Tech
- E-Signature
- Clickwrap
- Workflows
- Approvals
- Negotiation
- Templates
- Counterparties
- Obligations
- Analytics
- Webhooks
- AI
- SaaS
- Bangalore

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### SpotDraft Public API

The SpotDraft Public API is a unified OpenAPI 3.0.3 surface for managing contracts, templates, counterparties, approvals, metadata, obligations, versions, recipients, clickwrap agreements, webhooks, analytics, users, organizations, and workspaces. Endpoints are versioned (v1, v2, v2.1) and are served from four regional clusters (api.in.spotdraft.com, api.us.spotdraft.com, api.eu.spotdraft.com, api.me.spotdraft.com). Authentication uses Client ID + Client Secret or OAuth Bearer tokens generated from Developer Settings. The API exposes 148 paths across 48 tag groups and 211 component schemas. Webhooks deliver real-time notifications for contract lifecycle events.

- **Human URL:** [https://api.spotdraft.com/api/docs/](https://api.spotdraft.com/api/docs/)
- **Base URL:** `https://api.us.spotdraft.com`

#### Tags

- Contracts
- Templates
- Counterparties
- Approvals
- Workflows
- Clickwrap
- Webhooks
- Analytics
- Users
- Organizations

#### Properties

- [Documentation](https://api.spotdraft.com/api/docs/)
- [Documentation](https://help.spotdraft.com/hc/en-us/sections/20205760975133-Public-API)
- [Documentation](https://help.spotdraft.com/hc/en-us/articles/19587223206429-Developer-Settings)
- [OpenAPI](openapi/spotdraft-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spotdraft.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spotdraft.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/spotdraft-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/spotdraft-contract-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spotdraft-counterparty-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spotdraft-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spotdraft-organization-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spotdraft-clickwrap-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spotdraft-contracttype-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Ruleset](rules/spotdraft-rules.yml)
- [Vocabulary](vocabulary/spotdraft-vocabulary.yml)
- [Plans](plans/spotdraft-plans-pricing.yml)
- [Rate Limits](rate-limits/spotdraft-rate-limits.yml)
- [Fin Ops](finops/spotdraft-finops.yml)
- [Example](examples/spotdraft-list-contracts-example.json)
- [Example](examples/spotdraft-create-contract-example.json)
- [Example](examples/spotdraft-webhook-event-example.json)
- [Webhooks](https://help.spotdraft.com/hc/en-us/articles/19587223206429-Developer-Settings)

## Common Properties

- [Website](https://www.spotdraft.com)
- [Documentation](https://api.spotdraft.com/api/docs/)
- [Support](https://support.spotdraft.com)
- [Support](https://help.spotdraft.com)
- [Integrations](https://www.spotdraft.com/integrations)
- [Pricing](https://www.spotdraft.com/pricing)
- [Sign Up](https://www.spotdraft.com/book-a-demo)
- [Login](https://app.spotdraft.com)
- [Blog](https://www.spotdraft.com/blog)
- [Newsroom](https://www.spotdraft.com/press)
- [Careers](https://www.spotdraft.com/careers)
- [Security](https://www.spotdraft.com/security)
- [Trust](https://www.spotdraft.com/trust-center)
- [Privacy Policy](https://www.spotdraft.com/privacy-policy)
- [Terms of Service](https://www.spotdraft.com/terms-of-service)
- [Git Hub](https://github.com/SpotDraft)
- [LinkedIn](https://www.linkedin.com/company/spotdraft)
- [Twitter](https://twitter.com/getspotdraft)
- [YouTube](https://www.youtube.com/@spotdraft)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
