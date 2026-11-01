# University of California, Davis

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

The University of California, Davis is a public land-grant research university in Davis, California and a member of the ten-campus University of California system. Its programmable footprint is real but decentralized: there is no campus-wide developer portal, no API gateway, no published deprecation policy and no self-service signup for anything. What UC Davis genuinely operates and authored itself is three things — the Aggie Experts API (UC Davis Library, OpenAPI 3.0.0 v5.0, twelve operations over experts, works and grants, callable anonymously and returning JSON-LD with ORCID iDs and UC Davis ARK identifiers), the DAMS API behind digital.ucdavis.edu (built on the Library's own open-source 'fin' framework, though several documented operations return soft-200 errors), and the PEAKS asset- and access-tracking API run by the College of Agricultural and Environmental Sciences (MIT-licensed, source at github.com/ucdavis/Peaks, API-key gated). Alongside those it runs a SAML 2.0 Shibboleth identity provider published to InCommon as urn:mace:incommon:ucdavis.edu, and UC Davis Health operates a live FHIR R4 endpoint on its own domain — although that endpoint's CapabilityStatement is Epic's work, not UC Davis's, and is deliberately not claimed here. Two further surfaces are TENANT relationships and are labelled as such rather than credited as UC Davis engineering: scholarly output in eScholarship (operated by the California Digital Library for all of UC) and library discovery on Ex Libris Primo. Several campus surfaces that plainly exist — the open data portal aggiedata.ucdavis.edu, the registrar's course search, research computing at hpc.ucdavis.edu — sit behind a Cloudflare bot challenge and could not be read; that is a limit on this profile, not evidence of absence.

**Areas:** University · Higher Education · Education · United States · California · UC System · Public Research University · Research · Research Data · Identity Federation · Digital Collections · Library

## University of California, Davis on APIs.io

Everything profiled for University of California, Davis is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/uc-davis/](https://apis.io/providers/uc-davis/)** — or go straight to one of the APIs or properties below.

### APIs (20)

- [UC Davis Shibboleth Identity Provider (SAML 2.0 / InCommon)](https://apis.io/apis/uc-davis/shibboleth-idp/) — UC Davis operates its own SAML 2.0 identity provider and publishes signed federation metadata as entityID urn:mace:incommon:ucdavis.edu. This is…
- [UC Davis Health FHIR R4 endpoint](https://apis.io/apis/uc-davis/health-fhir-r4/) — UC Davis Health runs a live HL7 FHIR R4 endpoint on its own domain at emrrp.ucdmc.ucdavis.edu, registered in Epic's public endpoint directory as 'UC Davis'…
- [IET Middleware Web Service APIs](https://apis.io/apis/uc-davis/iet-middleware/) — Information and Educational Technology (IET) Middleware Web Service APIs provide campus integration and identity-related middleware. Probed 2026-08-19: the…
- [UC Davis Health Systems Integration APIs](https://apis.io/apis/uc-davis/health-integration/) — UC Davis Health Systems Integration offers Epic (EHR), HL7 FHIR and custom SOAP/REST APIs, authenticated with API keys, OAuth2 or Epic Interconnect and…
- [CAES ACE API](https://apis.io/apis/uc-davis/ace/) — The CAES Computing Resources Unit documents an ACE API supporting college administrative and content workflows. Probed 2026-08-19: the documentation page…
- [PEAKS (CAES) — Access API](https://apis.io/apis/uc-davis/uc-davis-access-api/) — The Access resource of PEAKS (People, Equipment, Access, Keys, Space), the asset- and access-tracking application the UC Davis College of Agricultural and…
- [PEAKS (CAES) — Documents API](https://apis.io/apis/uc-davis/uc-davis-documents-api/) — The Documents resource of PEAKS (People, Equipment, Access, Keys, Space), the asset- and access-tracking application the UC Davis College of Agricultural…
- [PEAKS (CAES) — Equipment API](https://apis.io/apis/uc-davis/uc-davis-equipment-api/) — The Equipment resource of PEAKS (People, Equipment, Access, Keys, Space), the asset- and access-tracking application the UC Davis College of Agricultural…
- [PEAKS (CAES) — Keys API](https://apis.io/apis/uc-davis/uc-davis-keys-api/) — The Keys resource of PEAKS (People, Equipment, Access, Keys, Space), the asset- and access-tracking application the UC Davis College of Agricultural and…
- [PEAKS (CAES) — KeySerials API](https://apis.io/apis/uc-davis/uc-davis-keyserials-api/) — The KeySerials resource of PEAKS (People, Equipment, Access, Keys, Space), the asset- and access-tracking application the UC Davis College of Agricultural…
- [PEAKS (CAES) — People API](https://apis.io/apis/uc-davis/uc-davis-people-api/) — The People resource of PEAKS (People, Equipment, Access, Keys, Space), the asset- and access-tracking application the UC Davis College of Agricultural and…
- [PEAKS (CAES) — PeopleAdmin API](https://apis.io/apis/uc-davis/uc-davis-peopleadmin-api/) — The PeopleAdmin resource of PEAKS (People, Equipment, Access, Keys, Space), the asset- and access-tracking application the UC Davis College of Agricultural…
- [PEAKS (CAES) — Spaces API](https://apis.io/apis/uc-davis/uc-davis-spaces-api/) — The Spaces resource of PEAKS (People, Equipment, Access, Keys, Space), the asset- and access-tracking application the UC Davis College of Agricultural and…
- [PEAKS (CAES) — Workstations API](https://apis.io/apis/uc-davis/uc-davis-workstations-api/) — The Workstations resource of PEAKS (People, Equipment, Access, Keys, Space), the asset- and access-tracking application the UC Davis College of Agricultural…
- [eScholarship — UC Davis unit (tenant)](https://apis.io/apis/uc-davis/escholarship-tenant/) — UC Davis's open-access scholarly output is deposited into eScholarship, the University of California's shared repository, under the campus unit path…
- [UC Davis Library discovery — Ex Libris Primo (tenant)](https://apis.io/apis/uc-davis/library-primo-tenant/) — Library discovery at search.library.ucdavis.edu is an Ex Libris Primo instance. The subdomain is UC Davis's and the collection is UC Davis's, but the…
- [University of California, Davis Collection API](https://apis.io/apis/uc-davis/uc-davis-collection-api/) — The collection API from University of California, Davis — 2 operation(s) for collection.
- [University of California, Davis Expert API](https://apis.io/apis/uc-davis/uc-davis-expert-api/) — Expert Information
- [University of California, Davis Item API](https://apis.io/apis/uc-davis/uc-davis-item-api/) — The item API from University of California, Davis — 1 operation(s) for item.
- [University of California, Davis page search API](https://apis.io/apis/uc-davis/uc-davis-page-search-api/) — The page search API from University of California, Davis — 1 operation(s) for page search.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Uc Davis Agentic Access](https://apis.io/agentic-access/uc-davis/uc-davis-agentic-access/)

#### JSON Schema (7)

The data models the API reads and writes.

- [UC Davis Aggie Experts — Expert](https://apis.io/schemas/uc-davis/uc-davis-aggie-experts-expert/)
- [UC Davis Aggie Experts — Grant](https://apis.io/schemas/uc-davis/uc-davis-aggie-experts-grant/)
- [UC Davis Aggie Experts — Work](https://apis.io/schemas/uc-davis/uc-davis-aggie-experts-work/)
- [PEAKS Equipment](https://apis.io/schemas/uc-davis/uc-davis-equipment/)
- [PEAKS Key](https://apis.io/schemas/uc-davis/uc-davis-key/)
- [PEAKS Person](https://apis.io/schemas/uc-davis/uc-davis-person/)
- [PEAKS Space](https://apis.io/schemas/uc-davis/uc-davis-space/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Uc Davis Equipment Structure](https://apis.io/json-structure/uc-davis/uc-davis-equipment-structure/)
- [Uc Davis Key Structure](https://apis.io/json-structure/uc-davis/uc-davis-key-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Uc Davis Context](https://apis.io/jsonld/uc-davis/uc-davis-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [UC Davis CAES PEAKS Vocabulary](https://apis.io/vocabularies/uc-davis/uc-davis-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Uc Davis Aggie Experts Browse Example](https://apis.io/examples/uc-davis/uc-davis-aggie-experts-browse-example/)
- [Uc Davis Aggie Experts Work Browse Example](https://apis.io/examples/uc-davis/uc-davis-aggie-experts-work-browse-example/)
- [Uc Davis Equipment Create Example](https://apis.io/examples/uc-davis/uc-davis-equipment-create-example/)
- [Uc Davis Keys List Example](https://apis.io/examples/uc-davis/uc-davis-keys-list-example/)

#### Collections (9)

Postman and Open Collection request collections.

- [PEAKS API v1 Access API](https://apis.io/collections/uc-davis/open-uc-davis-access-api/)
- [PEAKS API v1 Access Documents API](https://apis.io/collections/uc-davis/open-uc-davis-documents-api/)
- [PEAKS API v1 Access Equipment API](https://apis.io/collections/uc-davis/open-uc-davis-equipment-api/)
- [PEAKS API v1 Access Keys API](https://apis.io/collections/uc-davis/open-uc-davis-keys-api/)
- [PEAKS API v1 Access KeySerials API](https://apis.io/collections/uc-davis/open-uc-davis-keyserials-api/)
- [PEAKS API v1 Access People API](https://apis.io/collections/uc-davis/open-uc-davis-people-api/)
- [PEAKS API v1 Access PeopleAdmin API](https://apis.io/collections/uc-davis/open-uc-davis-peopleadmin-api/)
- [PEAKS API v1 Access Spaces API](https://apis.io/collections/uc-davis/open-uc-davis-spaces-api/)
- [PEAKS API v1 Access Workstations API](https://apis.io/collections/uc-davis/open-uc-davis-workstations-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [University of California, Davis — jsonschema rules](https://apis.io/rules/uc-davis/uc-davis-jsonschema-spectral-rules/)
- [University of California, Davis API Rules](https://apis.io/rules/uc-davis/uc-davis-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Uc Davis Authentication](https://apis.io/security/uc-davis/uc-davis-authentication/)
- [Uc Davis Domain Security](https://apis.io/security/uc-davis/uc-davis-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Uc Davis Scopes](https://apis.io/scopes/uc-davis/uc-davis-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Uc Davis Plans Pricing](https://apis.io/plans/uc-davis/uc-davis-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Uc Davis Rate Limits](https://apis.io/rate-limits/uc-davis/uc-davis-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Uc Davis Finops](https://apis.io/finops/uc-davis/uc-davis-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ucdavis.edu/)
- [Documentation](https://library.ucdavis.edu/online-strategy/)
- [API reference](https://experts.ucdavis.edu/api/)
- [Support](https://www.ucdavis.edu/help)
- [Blog](https://www.ucdavis.edu/news)
- [Terms of service](https://experts.ucdavis.edu/termsofuse)
- [Privacy policy](https://www.ucdavis.edu/help/privacy-accessibility)
- [GitHub](https://github.com/ucdavis)

## API Evangelist rating

**Kin Score 43.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 49.8 |
| Contract governance | 9.8 |
| Operational transparency | 21.6 |
| Developer ergonomics | 42.9 |
| Access clarity | 53.2 |

**Agent readiness 20.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
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
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 34.3** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/uc-davis/](https://apis.io/providers/uc-davis/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of California, Davis: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/uc-davis/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
