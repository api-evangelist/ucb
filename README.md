# University of California, Berkeley

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

The University of California, Berkeley is a public land-grant research university and the founding campus of the University of California system. Berkeley is one of the few universities in this cohort that genuinely operates its own API program rather than merely appearing to: Berkeley IT's Engineering and Integration Services team runs an API Central developer portal and a shared API Gateway on Berkeley's own infrastructure, publishing a public catalog of roughly 28 campus APIs across Student Information, HR, finance and identity, each listed with its UC data classification (P1/P2/P3) and a named Data Owner. That program is real, but it is internal-first: the catalog is public and the contracts are not. No OpenAPI definition is retrievable without a CalNet identity and Data Owner approval, so this profile holds ZERO OpenAPI documents and that is the accurate measurement, not a gap in the research. What Berkeley does publish without credentials is narrower and mostly overlooked: a complete Shibboleth/SAML 2.0 identity provider metadata document at shib.berkeley.edu (InCommon entity urn:mace:incommon:berkeley.edu), a live GeoBlacklight JSON catalog of 5,156 geospatial datasets at geodata.lib.berkeley.edu, and a gated but well-formed research-computing API for the Savio cluster's access management system. Its research repositories are not its engineering: the Digital Collections OAI-PMH endpoint runs on TIND, and eScholarship is a California Digital Library service for the entire UC system. Both are recorded here as tenant relationships, not as Berkeley contracts.

**Areas:** University · Higher Education · Education · Public Research University · United States · California · UC System · Research · Identity Federation · Research Repository · Research Computing · Course Catalog

## University of California, Berkeley on APIs.io

Everything profiled for University of California, Berkeley is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ucb/](https://apis.io/providers/ucb/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [API Central (Developer Portal)](https://apis.io/apis/ucb/api-central/) — Berkeley IT's centralized API management developer portal, operated by the Engineering and Integration Services (EIS) team. The catalog itself is public: an…
- [UC Berkeley API Gateway](https://apis.io/apis/ucb/api-gateway/) — The single centralized entry point for API requests across the Berkeley campus, operated by Berkeley IT on Berkeley's own CloudFront distribution. The…
- [CalNet Shibboleth Identity Provider (SAML 2.0 Metadata)](https://apis.io/apis/ucb/calnet-shibboleth/) — UC Berkeley's Shibboleth identity provider, operated by IST-CalNet, publishes a complete unauthenticated SAML 2.0 metadata document describing how any…
- [UC Berkeley Library GeoData (GeoBlacklight) Catalog API](https://apis.io/apis/ucb/geodata/) — The UC Berkeley Library's GIS and map discovery application, built and hosted by the Library itself (the application source is public at…
- [MyBRC Cluster Access Management API](https://apis.io/apis/ucb/mybrc/) — Berkeley Research Computing's cluster access management system, which handles allocations, project membership and access requests for the Savio…
- [UC Berkeley Digital Collections OAI-PMH (TIND tenant)](https://apis.io/apis/ucb/digicoll-oai/) — Berkeley's Digital Collections repository exposes a live OAI-PMH 2.0 interface, confirmed with an actual verb=Identify response reporting repositoryName…
- [eScholarship Repository and OAI-PMH (California Digital Library tenant)](https://apis.io/apis/ucb/escholarship/) — eScholarship is the University of California's open-access publishing platform and institutional repository, operated system-wide by the California Digital…
- [UC Library Search / Primo VE Discovery (Ex Libris tenant)](https://apis.io/apis/ucb/library-search/) — Library discovery for the Berkeley campus runs on Ex Libris Primo VE as part of the shared UC Library Search environment. search.library.berkeley.edu is a…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ucb Context](https://apis.io/jsonld/ucb/ucb-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ucb Authentication](https://apis.io/security/ucb/ucb-authentication/)
- [Ucb Domain Security](https://apis.io/security/ucb/ucb-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ucb Plans Pricing](https://apis.io/plans/ucb/ucb-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ucb Rate Limits](https://apis.io/rate-limits/ucb/ucb-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ucb Finops](https://apis.io/finops/ucb/ucb-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.berkeley.edu/)
- [Documentation](https://integration-services.berkeley.edu/api-management/developer-portal-api-central)
- [API reference](https://developers.api.berkeley.edu/apis)
- [Support](https://developers.api.berkeley.edu/contact_us)
- [Terms of service](https://developers.api.berkeley.edu/terms_of_service)
- [Privacy policy](https://www.berkeley.edu/privacy-policy/)
- [GitHub](https://github.com/ucberkeley)

## API Evangelist rating

**Kin Score 27.0** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 14.3 |
| Contract governance | 0.0 |
| Operational transparency | 18.4 |
| Developer ergonomics | 42.9 |
| Access clarity | 26.3 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ucb/](https://apis.io/providers/ucb/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of California, Berkeley: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ucb/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
