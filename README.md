# Griffith University (griffith)

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
