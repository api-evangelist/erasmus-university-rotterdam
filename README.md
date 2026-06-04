# Erasmus University Rotterdam (erasmus-university-rotterdam)

Erasmus University Rotterdam (EUR) is a public research university in Rotterdam, the Netherlands, ranked #158 in the QS World University Rankings 2025. This repository catalogs EUR's discoverable public developer/API footprint as an [APIs.json](http://apisjson.org) profile. EUR has no single consolidated developer portal; its programmatic surface is concentrated in scholarly and research-data infrastructure (institutional repository, research information system, and a Figshare-hosted data repository).

- APIs.json: https://raw.githubusercontent.com/api-evangelist/erasmus-university-rotterdam/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=erasmus-university-rotterdam-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Access, Repository, OAI-PMH, Netherlands

## APIs

- **RePub OAI-PMH Metadata Feed** — Verified live OAI-PMH 2.0 metadata harvesting feed for the EUR institutional repository (RePub). Base: `https://repub.eur.nl/oai`. Docs: https://repub.eur.nl/
- **Pure Research Portal OAI-PMH** — OAI-PMH service for the EUR & Erasmus MC Research Information Portal (Elsevier Pure / CRIS). Base: `https://pure.eur.nl/ws/oai` (Identify returned HTTP 500 at review time; re-verify). Docs: https://www.eur.nl/en/library/research-support/eur-erasmus-mc-research-information-portal-and-pure-repository
- **EUR Research Data Repository (Figshare API)** — EUR research data repository hosted on Figshare (datarepository.eur.nl), accessible via the public Figshare v2 REST API. Base: `https://api.figshare.com/v2`. Docs: https://docs.figshare.com/

## Plans / Rate Limits / FinOps

- [Plans & Pricing](plans/erasmus-university-rotterdam-plans-pricing.yml)
- [Rate Limits](rate-limits/erasmus-university-rotterdam-rate-limits.yml)
- [FinOps](finops/erasmus-university-rotterdam-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.eur.nl/en
- GitHub: https://github.com/eur-nl
- LinkedIn: https://www.linkedin.com/school/erasmus-university-rotterdam/
- Review: [review.yml](review.yml)

## Notes

All listed endpoints were probed during review on 2026-06-03. The RePub OAI-PMH feed responds with valid OAI-PMH 2.0 XML and is confirmed live. The Pure OAI service path resolves but returned an HTTP 500 on the Identify verb and is flagged for re-verification. The data repository is Figshare-hosted; the public Figshare v2 REST API is the documented programmatic access path. No course/timetable/SIS, identity/SSO, or mobile-backend public APIs were found documented. No endpoints were fabricated — only confirmed URLs are cataloged.

## Maintainers

- Kin Lane — kin@apievangelist.com
