# Erasmus University Rotterdam

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

Erasmus University Rotterdam (EUR) is a Dutch public research university founded in 1913, ranked #158 in the QS World University Rankings 2025, with ROR https://ror.org/057w15z03 and the registrable domain eur.nl. Re-profiled on 2026-08-30 under the API Evangelist university pipeline, which settles WHO OPERATES a surface before crediting it to the institution. The June 2026 profile credited EUR with eleven API entries and ten OpenAPI contracts. Every one of them was api.figshare.com/v2 — one Figshare document that the same pass attributed to twenty-five different universities, split by tag into ten apparent surfaces titled "Figshare altmetric Articles API", "Figshare altmetric Authors API" and so on, and it put EUR fifth in the whole 248-institution university cohort. Those contracts, and the twenty Postman and OpenCollection files, four JSON Schemas, three JSON Structures, four payload examples, the JSON-LD context, the vocabulary, the OAuth scopes, the authentication summary, the agentic-access classification, the two Spectral rulesets and the capability map derived from them, have all been removed — 51 files. The attribution was wrong twice over: EUR's Figshare tenancy ENDED on 30 October 2025, when the EUR Data Repository moved to DataverseNL hosted by DANS, and datarepository.eur.nl now has no DNS record at all. What is left is what EUR actually operates. The genuine institution-run surface is the RePub OAI-PMH 2.0 endpoint at repub.eur.nl/oai — keyless, live, correctly configured with an OpenAIRE and an NWO set and three metadata formats, on the university library's own infrastructure with @ubib.eur.nl administrative contacts and no vendor CNAME in the chain. Beside it sits api.eur.nl, a Kong API gateway EUR runs on its own address space that answers 401 with WWW-Authenticate: Basic realm="kong" and publishes no route, no reference and no contract to the public internet. EUR holds its own DataCite membership (symbol DHCM, 3,722 DOIs minted) and publishes a live RFC 9116 security.txt. Everything else programmable is a tenancy that is a real institutional fact but somebody else's engineering: the EUR Research Repository on Elsevier Pure at pure.eur.nl, the EUR Data Repository on DataverseNL, the course catalogue on Caci's OSIRIS, the Canvas LMS with a live LTI 1.3 keyset, and the SURFconext/eduGAIN identity provider that is a Microsoft Entra tenant behind SURF's proxy. EUR publishes no OpenAPI of its own, no developer portal, no open data portal and no llms.txt.

**Areas:** University · Higher Education · Education · Netherlands · Rotterdam · Research · Research Data · Open Access · Repository · OAI-PMH · Identity Federation · Course Catalog

## Erasmus University Rotterdam on APIs.io

Everything profiled for Erasmus University Rotterdam is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/erasmus-university-rotterdam/](https://apis.io/providers/erasmus-university-rotterdam/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [EUR API Gateway (api.eur.nl)](https://apis.io/apis/erasmus-university-rotterdam/api-gateway/) — An EUR-operated Kong API gateway. It is unambiguously live and unambiguously closed: the root returns 401 application/json {"message":"Unauthorized"} with…
- [EUR Research Repository — Pure OAI-PMH (Elsevier tenancy)](https://apis.io/apis/erasmus-university-rotterdam/pure-oai/) — The EUR & Erasmus MC research information portal runs on Elsevier Pure (CRIS). Its OAI-PMH endpoint is live (Identify 200, repositoryName "EUR Research…
- [EUR Data Repository (DataverseNL tenancy)](https://apis.io/apis/erasmus-university-rotterdam/edr-dataverse/) — EUR's institutional research DATA repository, distinct from the RePub publication repository. This entry replaces the ten Figshare contracts the June 2026…
- [Canvas LMS (Instructure tenancy) — REST + LTI 1.3](https://apis.io/apis/erasmus-university-rotterdam/canvas-lms/) — EUR's learning management system. Live and credentialed: /api/v1/courses returns 401 {"status":"unauthenticated","errors":[{"message":"user authorisation…
- [OSIRIS Course Catalogue (Caci tenancy)](https://apis.io/apis/erasmus-university-rotterdam/osiris-course-catalog/) — EUR's course catalogue and student self-service, on Caci's OSIRIS. The public entry points courses.eur.nl and osiris.eur.nl both land on an Angular SPA…
- [SURFconext / eduGAIN Identity Provider](https://apis.io/apis/erasmus-university-rotterdam/surfconext-idp/) — EUR's identity federation entry — the machine-readable institutional surface universities almost never get catalogued for. EUR is registered as an identity…
- [Erasmus University Rotterdam Oai Pmh API](https://apis.io/apis/erasmus-university-rotterdam/erasmus-university-rotterdam-oai-pmh-api/) — OAI-PMH 2.0 verbs, dispatched by the `verb` query parameter on a single path.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Vocabulary (1)

The provider's domain terms, defined.

- [Erasmus University Rotterdam Research Data Vocabulary](https://apis.io/vocabularies/erasmus-university-rotterdam/erasmus-university-rotterdam-vocabulary/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Erasmus University Rotterdam Authentication](https://apis.io/security/erasmus-university-rotterdam/erasmus-university-rotterdam-authentication/)
- [Erasmus University Rotterdam Domain Security](https://apis.io/security/erasmus-university-rotterdam/erasmus-university-rotterdam-domain-security/)
- [Erasmus University Rotterdam Vulnerability Disclosure](https://apis.io/security/erasmus-university-rotterdam/erasmus-university-rotterdam-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Erasmus University Rotterdam Plans Pricing](https://apis.io/plans/erasmus-university-rotterdam/erasmus-university-rotterdam-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Erasmus University Rotterdam Rate Limits](https://apis.io/rate-limits/erasmus-university-rotterdam/erasmus-university-rotterdam-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Erasmus University Rotterdam Finops](https://apis.io/finops/erasmus-university-rotterdam/erasmus-university-rotterdam-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.eur.nl/en)
- [Documentation](https://www.eur.nl/en/library/research-support)
- [Terms of service](https://www.eur.nl/en/disclaimer)
- [Privacy policy](https://www.eur.nl/en/privacy)

## API Evangelist rating

**Kin Score 35.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 76.8 |
| Contract quality | 52.6 |
| Contract governance | 18.2 |
| Operational transparency | 10.5 |
| Developer ergonomics | 21.4 |
| Access clarity | 26.3 |

**Agent readiness 24.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/erasmus-university-rotterdam/](https://apis.io/providers/erasmus-university-rotterdam/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Erasmus University Rotterdam: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/erasmus-university-rotterdam/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
