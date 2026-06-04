# University of California, Davis (uc-davis)

The University of California, Davis (UC Davis) is a public land-grant research university in Davis, California, ranked #48 in the QS World University Rankings 2025. This repository catalogs the institution's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. UC Davis has no single unified developer portal; its API surfaces are decentralized across campus units (IET middleware, UC Davis Health, CAES Computing Resources Unit) plus the official `ucdavis` GitHub organization.

- APIs.json: <https://raw.githubusercontent.com/api-evangelist/uc-davis/refs/heads/main/apis.yml>
- Run with Naftiko: <https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=uc-davis-api-evangelist&utm_content=repo>

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, United States, California, Identity, Health

## APIs

- **IET Middleware Web Service APIs** — campus integration/identity middleware. Docs: <https://iet-ws.ucdavis.edu/api/>
- **UC Davis Health Systems Integration APIs** — Epic (EHR), HL7 FHIR, and custom REST/SOAP APIs with API Key/OAuth2 auth. Docs: <https://health.ucdavis.edu/systems-integration/developers>
- **CAES PEAKS API** — CAES Computing Resources Unit API with Swagger/OpenAPI docs. Docs: <https://computing.caes.ucdavis.edu/documentation/peaks/api>
- **CAES ACE API** — CAES Computing Resources Unit administrative/content API. Docs: <https://computing.caes.ucdavis.edu/documentation/ace/api>

## Plans

See [plans/uc-davis-plans-pricing.yml](plans/uc-davis-plans-pricing.yml).

## Rate Limits

See [rate-limits/uc-davis-rate-limits.yml](rate-limits/uc-davis-rate-limits.yml).

## FinOps

See [finops/uc-davis-finops.yml](finops/uc-davis-finops.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: <https://www.ucdavis.edu/>
- Developer Portal (internal SIG): <https://developers.ucdavis.edu/>
- GitHub: <https://github.com/ucdavis>
- LinkedIn: <https://www.linkedin.com/school/uc-davis/>
- Status: <https://status.ucdavis.edu/>

## Notes

All listed URLs were probed during cataloging; the four documented API surfaces and the GitHub org, website, developer SIG, library, and status page returned HTTP 200. The AggieData institutional data portal returned HTTP 403 (bot-blocked) and LinkedIn returned 999 (anti-scraping) — both pages exist. No openly documented public library/repository REST API was confirmed, so none was invented. Most identity and administrative APIs are gated behind institutional affiliation, SSO, or partner agreements rather than open self-service signup.

## Maintainers

- Kin Lane — kin@apievangelist.com
