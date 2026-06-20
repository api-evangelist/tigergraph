# TigerGraph (tigergraph)

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
