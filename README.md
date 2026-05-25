# spotdraft

SpotDraft — AI-powered Contract Lifecycle Management (CLM) platform headquartered in Bangalore, with offices in San Francisco, New York, and London.

## API

| API | OpenAPI | Documentation |
|---|---|---|
| SpotDraft Public API | [openapi/spotdraft-openapi.yml](openapi/spotdraft-openapi.yml) | [api.spotdraft.com/api/docs](https://api.spotdraft.com/api/docs/) |

The SpotDraft Public API is a unified OpenAPI 3.0.3 surface spanning v1, v2, and v2.1 endpoints — 148 paths across 48 tag groups and 211 component schemas — covering contracts, templates, counterparties, approvals, metadata, obligations, versions, recipients, clickwrap agreements, webhooks, analytics, users, organizations, and workspaces. The API is served from four regional clusters (India, United States, European Union, Middle East). Authentication uses Client ID + Client Secret or OAuth Bearer tokens generated from Developer Settings.

## Artifacts

- [openapi/](openapi/) — OpenAPI 3.0.3 spec for the SpotDraft Public API
- [capabilities/](capabilities/) — 29 Naftiko capability files (one per resource family)
- [json-schema/](json-schema/) — JSON Schemas for Contract, Counterparty, User, Organization, Clickwrap, ContractType
- [json-ld/](json-ld/) — JSON-LD context mapping SpotDraft terms to schema.org
- [examples/](examples/) — Example list-contracts, create-contract, and webhook event payloads
- [rules/](rules/) — Spectral ruleset enforcing SpotDraft conventions (versioned tags, /public/ paths, regional servers)
- [vocabulary/](vocabulary/) — Domain vocabulary covering CLM concepts, regions, auth, and integrations
- [plans/](plans/) — API Commons Plans 0.1 description of editions and add-ons
- [rate-limits/](rate-limits/) — API Commons Rate Limits 0.1 description of throttling and webhook retry
- [finops/](finops/) — FOCUS 1.3-aligned FinOps definition

## Links

- Website: https://www.spotdraft.com
- API Reference: https://api.spotdraft.com/api/docs/
- Developer Settings: https://help.spotdraft.com/hc/en-us/articles/19587223206429-Developer-Settings
- Public API Knowledge Base: https://help.spotdraft.com/hc/en-us/sections/20205760975133-Public-API
- GitHub: https://github.com/SpotDraft
- Integrations: https://www.spotdraft.com/integrations
- Status: https://status.spotdraft.com
- Trust Center: https://www.spotdraft.com/trust-center
