# US House of Representatives (us-house-of-representatives)

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

The United States House of Representatives is one of the two chambers of the United States Congress, with the other being the Senate. Its main function is to pass federal legislation, which must then be approved by the Senate before it can become law. The House also has the power to impeach government officials, including the President, and to initiate revenue-related bills. Congressional data is made available through the Congress.gov API, a REST API maintained by the Library of Congress that provides access to bills, members, committees, amendments, nominations, and treaties.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/us-house-of-representatives/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/us-house-of-representatives/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Legislation
- Congress
- Legislative Data
- Bills
- Members
- Committees

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### Congress.gov API

The Congress.gov API (v3) provides programmatic access to congressional data maintained by the Library of Congress. It offers machine-readable data covering bills, amendments, congressional records, committees, members of Congress, nominations, and treaties. An API key is required and can be obtained from api.data.gov. Responses are available in JSON or XML with a rate limit of 5,000 requests per hour and pagination up to 250 results per request.

- **Human URL:** [https://www.loc.gov/apis/additional-apis/congress-dot-gov-api/](https://www.loc.gov/apis/additional-apis/congress-dot-gov-api/)

#### Tags

- Legislation
- Congress
- Federal Government
- Legislative Data

#### Properties

- [Documentation](https://www.loc.gov/apis/additional-apis/congress-dot-gov-api/)
- [Git Hub](https://github.com/LibraryOfCongress/api.congress.gov)
- [Base U R L](https://api.congress.gov/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-house-of-representatives/refs/heads/main/openapi/congress-gov-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/congress-gov-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/congress-gov-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ProPublica Congress API

ProPublica's Congress API provides access to detailed congressional data including member profiles, voting records, bill sponsorship, and committee activity. This third-party API aggregates and enriches congressional data from multiple public sources.

- **Human URL:** [https://projects.propublica.org/api-docs/congress-api/](https://projects.propublica.org/api-docs/congress-api/)

#### Tags

- Legislation
- Congress
- Voting Records
- Campaign Finance

#### Properties

- [Documentation](https://projects.propublica.org/api-docs/congress-api/)
- [Postman Collection](collections/congress-gov-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/congress-gov-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/u-s-house-of-representatives)
- [Integrations](https://www.loc.gov/apps)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
