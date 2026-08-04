# Tableaux De Bord (tableaux-de-bord)

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

Tableaux de Bord (French for "dashboards") is an API industry topic covering dashboard and data visualization APIs. The landscape includes open-source platforms such as Grafana (with its comprehensive HTTP API for dashboards, datasources, and alerting) and Metabase (with its REST API for questions, dashboards, and administration). These tools enable programmatic creation and management of business intelligence dashboards for monitoring, analytics, and operational visibility.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Dashboards
- Business Intelligence
- Analytics
- Data Visualization
- Monitoring
- Grafana
- Metabase

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Grafana HTTP API

The Grafana HTTP API provides programmatic access to Grafana's dashboard, datasource, alerting, organization, user, and annotation management capabilities. Grafana is an open-source observability and analytics platform widely used for infrastructure and application monitoring.

- **Human URL:** [https://grafana.com/docs/grafana/latest/developer-resources/api-reference/http-api/](https://grafana.com/docs/grafana/latest/developer-resources/api-reference/http-api/)
- **Base URL:** `https://your-grafana-instance.com`

#### Tags

- Grafana
- Dashboards
- Monitoring
- Observability

#### Properties

- [Documentation](https://grafana.com/docs/grafana/latest/developer-resources/api-reference/http-api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/openapi/grafana-dashboard-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Git Hub](https://github.com/grafana/grafana)
- [Postman Collection](collections/grafana-dashboard.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grafana-dashboard.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Metabase API

The Metabase REST API enables automation of business intelligence workflows including creating and managing dashboards, running questions (queries), managing users and groups, and embedding analytics in applications.

- **Human URL:** [https://www.metabase.com/learn/metabase-basics/administration/administration-and-operation/metabase-api](https://www.metabase.com/learn/metabase-basics/administration/administration-and-operation/metabase-api)
- **Base URL:** `https://your-metabase-instance.com`

#### Tags

- Metabase
- Business Intelligence
- Analytics
- Dashboards

#### Properties

- [Documentation](https://www.metabase.com/learn/metabase-basics/administration/administration-and-operation/metabase-api)
- [Git Hub](https://github.com/metabase/metabase)
- [Postman Collection](collections/grafana-dashboard.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/grafana-dashboard.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Grafana  Website](https://grafana.com/)
- [Metabase  Website](https://www.metabase.com/)
- [Grafana  Documentation](https://grafana.com/docs/grafana/latest/developer-resources/api-reference/http-api/)
- [Metabase  Documentation](https://www.metabase.com/learn/metabase-basics/administration/administration-and-operation/metabase-api)
- [Grafana  Git Hub](https://github.com/grafana/grafana)
- [Metabase  Git Hub](https://github.com/metabase/metabase)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/tableaux-de-bord/refs/heads/main/vocabulary/tableaux-de-bord-vocabulary.yml)
- [Integrations](https://grafana.com/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
