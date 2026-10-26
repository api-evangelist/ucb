# University of California, Berkeley (ucb)

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

The University of California, Berkeley is a public land-grant research university and the founding
campus of the University of California system. This repository catalogs Berkeley's public developer
and API footprint as an [APIs.json](https://apisjson.org/) profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ucb/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ucb-api-evangelist&utm_content=repo

## Type

- University / Public Research University / Index / Consumer / 3rd-Party

## Who operates what

Every surface below carries an `x-operator` in `apis.yml`. A university is a federation of buyers,
and most of what appears under an institution's name is a vendor's contract. Berkeley is an unusual
case in this cohort: it genuinely runs its own API program.

### Institution-operated

- **API Central (Developer Portal)** — Berkeley IT / Engineering and Integration Services. The
  catalog is public: ~28 campus APIs across Student Information, UCB Administration and integration
  tooling, each with its UC data classification (P1/P2/P3) and a named Data Owner. Contracts are
  CalNet-gated. https://developers.api.berkeley.edu/apis
- **UC Berkeley API Gateway** — centralized entry point for campus API requests, handling load
  balancing, authentication, authorization and rate limiting. https://gateway.api.berkeley.edu/
- **CalNet Shibboleth Identity Provider (SAML 2.0 metadata)** — a complete, unauthenticated,
  machine-readable federation description. entityID `urn:mace:incommon:berkeley.edu`, scope
  `berkeley.edu`, SAML 1.1/2.0 with an AttributeAuthority. This is the largest machine-readable
  artifact Berkeley publishes to an anonymous caller. https://shib.berkeley.edu/idp/shibboleth
- **Library GeoData (GeoBlacklight) Catalog API** — 5,156 geospatial dataset records in
  OpenGeoMetadata Aardvark fields, served as JSON with no credentials.
  https://geodata.lib.berkeley.edu/catalog.json
- **MyBRC Cluster Access Management API** — allocation and access management for the Savio HPC
  cluster; answers with a JSON 401. https://mybrc.brc.berkeley.edu/api/

### Tenant relationships (Berkeley's data, someone else's contract)

- **Digital Collections OAI-PMH** — live OAI-PMH 2.0, admin `digicoll@berkeley.edu`, but the host
  CNAMEs to `berkeley.lb.service.tind.io`. TIND's contract, Berkeley's collections.
- **eScholarship** — operated system-wide by the California Digital Library, not by Berkeley. Its
  OAI-PMH exposes a single set ("everything"); there is no Berkeley-scoped set.
- **UC Library Search / Primo VE** — `search.library.berkeley.edu` CNAMEs to
  `berkeley.primo.exlibrisgroup.com`. Berkeley is a view (`01UCS_BER:UCB`) inside a UC-wide Ex Libris
  network zone, not the operator of its own Alma instance.

## What is deliberately absent

Berkeley publishes **no public OpenAPI**. Every contract in API Central sits behind CalNet SSO plus
Data Owner approval. This repository therefore holds zero OpenAPI, JSON Schema or example artifacts,
and none were generated — generating them would credit Berkeley with contracts it has not published.
See `x-coverage` in `apis.yml` for the full evidence table.

Berkeleytime (`berkeleytime.com`), the well-known student-built Berkeley course-data API, is live but
runs on a non-institution domain under the ASUC student association. No evidence of University
operation or endorsement was found, so it is not credited to Berkeley here.

## Education-regime conformance

Verified by protocol response, not by link presence — see
[conformance/ucb-education-standards-conformance.yml](conformance/ucb-education-standards-conformance.yml).

| Standard | Status | Evidence |
|---|---|---|
| `oai-pmh` | confirmed | `digicoll.lib.berkeley.edu/oai2d?verb=Identify` → OAI-PMH 2.0 |
| `shibboleth` | confirmed | `shibmd:Scope` extension in the CalNet IdP metadata |
| `saml` | confirmed | SAML 2.0 `EntityDescriptor` / `IDPSSODescriptor` |
| `lti` | historical, not counted | Berkeley-authored Canvas LTI tools, archived 2025 |
| `caliper` | historical, not counted | `caliper-js` / `xapicaliper`, last pushed 2017–2018 |

Not found: `scim`, `oneroster`, `ed-fi`, `qti`, `orcid`, `datacite`, `crossref`.

## Artifacts

- Authentication: [authentication/ucb-authentication.yml](authentication/ucb-authentication.yml)
- Conformance: [conformance/ucb-education-standards-conformance.yml](conformance/ucb-education-standards-conformance.yml)
- Domain Security: [security/ucb-domain-security.yml](security/ucb-domain-security.yml)
- Plans / Pricing: [plans/ucb-plans-pricing.yml](plans/ucb-plans-pricing.yml)
- Rate Limits: [rate-limits/ucb-rate-limits.yml](rate-limits/ucb-rate-limits.yml)
- FinOps: [finops/ucb-finops.yml](finops/ucb-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.berkeley.edu/
- Developer Portal: https://developers.api.berkeley.edu/
- API Reference: https://developers.api.berkeley.edu/apis
- Terms of Service: https://developers.api.berkeley.edu/terms_of_service
- Privacy Policy: https://www.berkeley.edu/privacy-policy/
- Status: https://systemstatus.berkeley.edu/
- Identity Federation: https://shib.berkeley.edu/idp/shibboleth
- Open Data: https://geodata.lib.berkeley.edu/
- Course Catalog: https://classes.berkeley.edu/
- Research Computing: https://research-it.berkeley.edu/services-projects/high-performance-computing-savio
- AI Policy: https://ai.berkeley.edu/guidance
- AI Tooling: https://ai.berkeley.edu/tools-training
- Security: https://security.berkeley.edu/
- GitHub: https://github.com/ucberkeley / https://github.com/BerkeleyLibrary / https://github.com/ets-berkeley-edu

## Maintainers

- Kin Lane — kin@apievangelist.com
