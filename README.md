# Griffith University (griffith)

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

Griffith University is a public research university in Queensland, Australia, ranked #255 in the QS World University Rankings 2025. This repository catalogs Griffith's public, machine-readable developer and API footprint as an APIs.json provider profile. The university's confirmed public APIs center on research and library infrastructure: the Griffith Research Online (GRO) institutional repository (DSpace 7.6) exposes a REST API and an OAI-PMH 2.0 endpoint, and a Canvas LMS REST API is publicly documented.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/griffith/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=griffith-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Australia, Research, Open Data, Repository

## APIs

- **Griffith Research Online (GRO) DSpace REST API** — DSpace 7.6 REST interface for the institutional repository (communities, collections, items, metadata). Docs: https://research-repository.griffith.edu.au/ — Base: https://research-repository.griffith.edu.au/server/api
- **Griffith Research Online OAI-PMH** — OAI-PMH 2.0 metadata harvesting endpoint for Griffith research outputs. Docs: https://researchdata.edu.au/griffith-research-online-oai-protocol/8941 — Base: https://research-repository.griffith.edu.au/oai/request
- **Griffith Canvas LMS REST API** — Publicly documented Canvas (Instructure) LMS REST API; live access requires institutional credentials. Docs: https://lms.griffith.edu.au/doc/api/index.html

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/griffith-plans-pricing.yml](plans/griffith-plans-pricing.yml)
- Rate Limits: [rate-limits/griffith-rate-limits.yml](rate-limits/griffith-rate-limits.yml)
- FinOps: [finops/griffith-finops.yml](finops/griffith-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.griffith.edu.au/
- GitHub (Library): https://github.com/GriffithUniLibrary
- GitHub (eResearch): https://github.com/gu-eresearch
- LinkedIn: https://www.linkedin.com/school/griffith-university/
- Review: [review.yml](review.yml)

## Notes

All APIs and endpoints in this profile were verified live on 2026-06-03 where possible. The GRO DSpace REST API root and the OAI-PMH 2.0 Identify/ListMetadataFormats verbs returned HTTP 200 with content identifying "Griffith Research Online" (DSpace 7.6, protocol version 2.0). The Canvas LMS API documentation page returned HTTP 200; live LMS API calls require authentication. The official website (403) and LinkedIn page (999) return anti-bot status codes to automated probes but resolve normally in a browser. Griffith has no single unified self-service developer portal; no course, timetable, or identity APIs were found openly documented, and no endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
