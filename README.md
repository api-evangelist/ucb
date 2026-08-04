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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of California, Berkeley (UC Berkeley) is a public land-grant research university and the flagship campus of the University of California system, ranked #12 in the QS World University Rankings 2025. This repository catalogs Berkeley's public developer and API footprint as an [APIs.json](https://apisjson.org/) profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ucb/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ucb-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education
- Higher Education
- University
- Research
- Open Data
- United States
- California

## APIs

- **API Central (Developer Portal)** — Centralized API management portal for discovering and requesting access to campus APIs, with interactive OpenAPI docs. Docs: https://integration-services.berkeley.edu/api-management/developer-portal-api-central / Portal: https://developers.api.berkeley.edu/
- **UC Berkeley API Gateway** — Centralized entry point for campus API requests handling auth, authorization, load balancing, and rate limiting. Docs: https://integration-services.berkeley.edu/api-management/api-gateway / Base: https://gateway.api.berkeley.edu/
- **eScholarship Repository API (OAI-PMH)** — UC-wide open-access repository with a public read API and OAI-PMH harvesting interface. Docs: https://help.escholarship.org/support/solutions/articles/9000223035-about-escholarship-apis
- **UC Berkeley Library Alma/Primo Integrations** — Ex Libris Alma/Primo platform with OAI-PMH metadata and public open-source utilities. Docs: https://github.com/BerkeleyLibrary/alma

## Plans, Rate Limits, and FinOps

- Plans / Pricing: [plans/ucb-plans-pricing.yml](plans/ucb-plans-pricing.yml)
- Rate Limits: [rate-limits/ucb-rate-limits.yml](rate-limits/ucb-rate-limits.yml)
- FinOps: [finops/ucb-finops.yml](finops/ucb-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.berkeley.edu/
- Developer Portal: https://developers.api.berkeley.edu/
- GitHub: https://github.com/ucberkeley
- LinkedIn: https://www.linkedin.com/school/uc-berkeley/
- Status: https://systemstatus.berkeley.edu/
- Twitter: https://twitter.com/UCBerkeley
- Authentication: https://integration-services.berkeley.edu/api-management/developer-portal-api-central

## Notes

- Berkeley's campus API program is real and formally governed, but most individual APIs (including the SIS class schedule API) are gated behind CalNet identity and Data Owner approval, so specific endpoints are not published publicly and were not fabricated here.
- The developer portal (developers.api.berkeley.edu) and main website return HTTP 403 to automated crawlers but are confirmed real per official Integration Services documentation.
- The legacy `api-central.berkeley.edu` hostname no longer resolves; it has been replaced by `developers.api.berkeley.edu`.
- eScholarship is a University of California system-wide service (not exclusive to Berkeley) but includes Berkeley scholarship and offers a confirmed public-read OAI-PMH interface.

## Maintainers

- Kin Lane — kin@apievangelist.com
