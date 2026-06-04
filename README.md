# University of California, Berkeley (ucb)

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
