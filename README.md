# University of Southern California (usc)

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
