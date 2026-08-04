# University of Southern California (usc)

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

The University of Southern California (USC) is a private research university in Los Angeles, California, ranked #59 in the QS World University Rankings 2025. USC does not operate a single centralized public API developer portal; its most concretely documented public web service is the Schedule of Classes (SOC) Web Services API, with additional programmatic and data activity distributed across departmental and research GitHub organizations and library systems.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/usc/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=usc-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, United States, California, Courses

## APIs

- **USC Schedule of Classes (SOC) Web Services API** — A web service for integrating USC Schedule of Classes content (terms, departments, courses, sections) into other sites and applications.
  - Docs: https://web-app.usc.edu/web/soc/help
  - Source docs: https://web-app.usc.edu/web/soc/docs/html/

## Plans / Rate Limits / FinOps

- Plans: [plans/usc-plans-pricing.yml](plans/usc-plans-pricing.yml)
- Rate Limits: [rate-limits/usc-rate-limits.yml](rate-limits/usc-rate-limits.yml)
- FinOps: [finops/usc-finops.yml](finops/usc-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.usc.edu/
- GitHub (USC IR & Data Science): https://github.com/uscdatascience
- GitHub (USC Information Sciences Institute): https://github.com/isi-usc-edu
- LinkedIn: https://www.linkedin.com/school/university-of-southern-california/
- Twitter/X: https://twitter.com/USC
- Review: [review.yml](review.yml)

## Notes

- USC has no unified public API developer portal. The SOC Web Services API is documented by USC and a public archive API endpoint pattern (`/ws/soc_archive/soc/api/classes/{dept}/{term}`) has been observed, but the host `web-app.usc.edu` refused connections from this review's network at probe time, so endpoints could not be independently verified live.
- There is no single official USC-wide GitHub organization; multiple departmental and research labs maintain their own orgs. Two prominent, verified examples are listed above.
- No endpoints were fabricated. See [review.yml](review.yml) for per-URL probe status.

## Maintainers

- Kin Lane — kin@apievangelist.com
