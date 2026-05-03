# Tableaux De Bord

Tableaux de Bord (French for "dashboards") is an API industry topic covering dashboard and data visualization APIs. The landscape includes open-source platforms such as Grafana (with its comprehensive HTTP API for dashboards, datasources, and alerting) and Metabase (with its REST API for questions, dashboards, and administration). These tools enable programmatic creation and management of business intelligence dashboards for monitoring, analytics, and operational visibility.

## APIs

### Grafana HTTP API

The Grafana HTTP API provides programmatic access to dashboards, datasources, alerting, organization management, users, teams, annotations, and folders.

- **Documentation:** [https://grafana.com/docs/grafana/latest/developer-resources/api-reference/http-api/](https://grafana.com/docs/grafana/latest/developer-resources/api-reference/http-api/)
- **OpenAPI:** [openapi/grafana-dashboard-openapi.yml](openapi/grafana-dashboard-openapi.yml)
- **GitHub:** [https://github.com/grafana/grafana](https://github.com/grafana/grafana)

### Metabase API

The Metabase REST API enables automation of BI workflows including dashboards, questions, users, and embedded analytics.

- **Documentation:** [https://www.metabase.com/learn/metabase-basics/administration/administration-and-operation/metabase-api](https://www.metabase.com/learn/metabase-basics/administration/administration-and-operation/metabase-api)
- **GitHub:** [https://github.com/metabase/metabase](https://github.com/metabase/metabase)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [grafana-dashboard-openapi.yml](openapi/grafana-dashboard-openapi.yml) | Grafana HTTP API - dashboards, datasources, alerting, annotations |

### JSON Schema

| Schema | Description |
|--------|-------------|
| [tableaux-de-bord-dashboard-schema.json](json-schema/tableaux-de-bord-dashboard-schema.json) | Common schema for dashboard definitions |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [tableaux-de-bord-dashboard-structure.json](json-structure/tableaux-de-bord-dashboard-structure.json) | Field documentation for dashboard objects |

### JSON-LD

| Context | Description |
|---------|-------------|
| [tableaux-de-bord-context.jsonld](json-ld/tableaux-de-bord-context.jsonld) | Linked data context for dashboard entities |

### Examples

| Example | Description |
|---------|-------------|
| [grafana-create-dashboard-example.json](examples/grafana-create-dashboard-example.json) | Create a new Grafana dashboard |
| [grafana-search-dashboards-example.json](examples/grafana-search-dashboards-example.json) | Search dashboards by tag |

### Vocabulary

| File | Description |
|------|-------------|
| [tableaux-de-bord-vocabulary.yml](vocabulary/tableaux-de-bord-vocabulary.yml) | Domain vocabulary for dashboard API concepts |

## Key Platforms

- **Grafana** - Open-source observability and metrics visualization
- **Metabase** - Self-service business intelligence and embedded analytics
- **Kibana** - Elasticsearch-native data visualization and dashboards
- **Apache Superset** - Open-source BI tool with SQL-first approach

## Tags

- Dashboards
- Business Intelligence
- Analytics
- Data Visualization
- Monitoring
- Grafana
- Metabase
