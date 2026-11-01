# University of Southern California

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

The University of Southern California is a private research university in Los Angeles, ranked #59 in the QS World University Rankings 2025. USC operates no central developer portal, publishes no OpenAPI, AsyncAPI or apis.json anywhere on its public surface, and issues no self-service API keys — www.usc.edu serves neither llms.txt nor .well-known/security.txt, and api.usc.edu is a default IIS Windows Server placeholder page last modified in 2019, not an API. What USC does operate, verified live on 2026-08-30, is three genuinely institutional machine surfaces: a Shibboleth SAML 2.0 identity provider whose metadata is published unauthenticated at shibboleth.usc.edu and registered with InCommon as urn:mace:incommon:usc.edu; a DataCite direct membership under its own name that carries eleven repositories and 1.5 million minted DOIs; and the FaceBase craniofacial data hub, whose keyless ERMrest REST API is built and run by USC's own Information Sciences Institute on ISI's Apache-2.0 DERIVA stack. Everything else that looks like a USC API is a vendor's contract running under USC's name and is recorded here as a tenant relationship, never as USC's engineering: Figshare, Ex Libris Primo/Alma, Orange Logic Cortex and Instructure Canvas. The Schedule of Classes Web Services API that this profile previously led with is gone — web-app.usc.edu no longer resolves at all.

**Areas:** University · Higher Education · Education · Research · Private Research University · Association of American Universities · United States · California · Los Angeles · Identity Federation · Research Data · Research Repository

## University of Southern California on APIs.io

Everything profiled for University of Southern California is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/usc/](https://apis.io/providers/usc/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [USC Shibboleth Identity Provider (SAML 2.0 Metadata)](https://apis.io/apis/usc/shibboleth-idp/) — USC's production single sign-on identity provider, operated by USC Information Technology Services on USC's own host, publishing its SAML 2.0 metadata…
- [FaceBase ERMrest Data API](https://apis.io/apis/usc/facebase-ermrest/) — Keyless, read-only JSON REST API of the FaceBase craniofacial data hub, an NIDCR-funded resource led from USC and engineered by USC's Information Sciences…
- [USC DataCite DOI Registration (Provider Account)](https://apis.io/apis/usc/datacite-membership/) — USC holds a DataCite direct membership in its own name and mints DOIs for eleven USC repositories under it. GET https://api.datacite.org/providers/usc…
- [USC Digital Library API (Orange Logic Cortex)](https://apis.io/apis/usc/digital-library-cortex/) — A live, token-gated REST API on USC's own host running Orange Logic's Cortex digital asset platform. GET…
- [USC Figshare Research Repository (Tenant)](https://apis.io/apis/usc/figshare-repository/) — USC Libraries offers Figshare to USC researchers as its data-output repository for datasets, posters and presentations, at the institution-specific tenant…
- [USC Libraries Discovery (Ex Libris Primo VE, Tenant)](https://apis.io/apis/usc/primo-discovery/) — USC Libraries' catalog and discovery layer runs on Ex Libris Primo VE as institution view 01USC_INST:01USC at uosc.primo.exlibrisgroup.com. The public Primo…
- [USC Canvas Learning Management System (Instructure, Tenant)](https://apis.io/apis/usc/canvas-lms/) — USC's learning management system is an Instructure Canvas tenant at usc.instructure.com, verified live 2026-08-30 (200, redirecting to /login/canvas).…
- [USC Schedule of Classes (SOC) — Web Services API, retired](https://apis.io/apis/usc/schedule-of-classes/) — USC's Schedule of Classes Web Services API, which exposed terms, departments, courses and sections and once powered the online schedule, is retired. Its…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Usc Context](https://apis.io/jsonld/usc/usc-context/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Usc Domain Security](https://apis.io/security/usc/usc-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Usc Plans Pricing](https://apis.io/plans/usc/usc-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Usc Rate Limits](https://apis.io/rate-limits/usc/usc-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Usc Finops](https://apis.io/finops/usc/usc-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.usc.edu/)
- [Documentation](https://catalogue.usc.edu/)
- [API reference](https://www.facebase.org/ermrest/catalog/1/schema)
- [Support](https://itservices.usc.edu/)
- [Blog](https://news.usc.edu/)
- [Privacy policy](https://www.usc.edu/privacy-notice/)
- [GitHub](https://github.com/informatics-isi-edu)

## API Evangelist rating

**Kin Score 21.6** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 14.3 |
| Contract governance | 18.2 |
| Operational transparency | 7.9 |
| Developer ergonomics | 23.8 |
| Access clarity | 15.8 |

**Agent readiness 0.6** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
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

**Regulatory alignment 22.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/usc/](https://apis.io/providers/usc/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Southern California: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/usc/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
