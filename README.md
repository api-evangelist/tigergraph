# TigerGraph (tigergraph)

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

TigerGraph is a distributed, native parallel graph database and analytics platform. Its database server exposes a built-in REST++ API for reading and writing vertices and edges, running installed GSQL queries, managing schema, and issuing authentication tokens, alongside the GSQL server and the fully managed TigerGraph Savanna (Cloud) service.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tigergraph/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tigergraph/refs/heads/main/apis.yml)

## Tags

- Graph Database
- Analytics
- GSQL
- REST++
- Graph Analytics

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### TigerGraph REST++ Data API (Vertices & Edges)

Built-in REST++ endpoints to retrieve, upsert, and delete vertices and edges in a graph by type and ID, with select / filter / limit / sort parameters.

- **Human URL:** [https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints](https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints)
- **Base URL:** `http://localhost:9000/restpp`

#### Tags

- Vertices
- Edges
- Upsert

#### Properties

- [Documentation](https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints)
- [API Reference](https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints)
- [OpenAPI](openapi/tigergraph-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tigergraph.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tigergraph.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TigerGraph Query API (Run GSQL Queries)

Run installed GSQL queries as dynamic REST++ endpoints via GET/POST /query/{graph}/{queryName}, or run interpreted queries, plus built-in path-finding (shortest path, all paths).

- **Human URL:** [https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints](https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints)
- **Base URL:** `http://localhost:9000/restpp`

#### Tags

- Query
- GSQL
- Analytics

#### Properties

- [Documentation](https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints)
- [API Reference](https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints)
- [OpenAPI](openapi/tigergraph-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tigergraph.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tigergraph.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TigerGraph Schema API

Retrieve graph schema metadata, list installed endpoints, and run loading jobs (DDL) to ingest data into a graph.

- **Human URL:** [https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints](https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints)
- **Base URL:** `http://localhost:9000`

#### Tags

- Schema
- Metadata
- DDL

#### Properties

- [Documentation](https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints)
- [API Reference](https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints)
- [OpenAPI](openapi/tigergraph-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tigergraph.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tigergraph.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TigerGraph Auth & Tokens API

Exchange a GSQL-generated secret for a bearer authentication token via POST /requesttoken, refresh or delete tokens, and call /echo and /ping for health checks.

- **Human URL:** [https://docs.tigergraph.com/tigergraph-server/current/API/authentication](https://docs.tigergraph.com/tigergraph-server/current/API/authentication)
- **Base URL:** `http://localhost:9000/restpp`

#### Tags

- Authentication
- Tokens
- Security

#### Properties

- [Documentation](https://docs.tigergraph.com/tigergraph-server/current/API/authentication)
- [API Reference](https://docs.tigergraph.com/tigergraph-server/current/api/built-in-endpoints)
- [OpenAPI](openapi/tigergraph-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tigergraph.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tigergraph.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TigerGraph Savanna (Cloud) API

The same REST++ surface served by fully managed TigerGraph Savanna workspaces over HTTPS, where compute and storage scale independently with usage-based billing.

- **Human URL:** [https://docs.tigergraph.com/savanna/main/](https://docs.tigergraph.com/savanna/main/)
- **Base URL:** `https://<workspace-id>.i.tgcloud.io:443/restpp`

#### Tags

- Cloud
- Savanna
- Managed

#### Properties

- [Documentation](https://docs.tigergraph.com/savanna/main/)
- [API Reference](https://docs.tigergraph.com/cloud/main/solutions/access-solution/rest-requests)
- [OpenAPI](openapi/tigergraph-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Plans](plans/tigergraph-plans-pricing.yml)

## Common Properties

- [GitHub Organization](https://github.com/tigergraph)
- [LinkedIn](https://www.linkedin.com/company/tigergraph)
- [Website](https://www.tigergraph.com)
- [Documentation](https://docs.tigergraph.com)
- [Plans](plans/tigergraph-plans-pricing.yml)
- [Rate Limits](rate-limits/tigergraph-rate-limits.yml)
- [Fin Ops](finops/tigergraph-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
