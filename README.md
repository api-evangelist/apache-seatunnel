# Apache SeaTunnel (apache-seatunnel)
Apache SeaTunnel is a high-performance, distributed data integration platform that supports real-time and batch data synchronization. It provides a connector API with support for over 200 data sources and sinks.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-seatunnel/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-seatunnel/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Data Integration, ETL, ELT, Batch, Streaming, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache SeaTunnel REST API
SeaTunnel provides REST endpoints for job submission, status monitoring, and cluster management, along with a Connector API for building custom data sources and sinks supporting over 200 built-in connectors.

**Human URL:** [https://seatunnel.apache.org/docs/](https://seatunnel.apache.org/docs/)

#### Tags:

 - Data Integration, Job Management, REST, Apache, Open Source

#### Properties

- [Documentation](https://seatunnel.apache.org/docs/)
- [OpenAPI](openapi/apache-seatunnel-rest-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/seatunnel)
- [Documentation](https://seatunnel.apache.org/)
- [SpectralRules](rules/apache-seatunnel-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-seatunnel-vocabulary.yaml)
- [NaftikoCapability](capabilities/seatunnel-workflow.yaml)
- [JSON-LD](json-ld/apache-seatunnel-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| 200+ Connectors | Over 200 built-in connectors for databases, warehouses, and file systems |
| Batch and Streaming | Unified API for both batch ETL and real-time streaming jobs |
| Schema Evolution | Automatic schema detection and evolution support |
| Distributed Execution | Zeta execution engine with no external dependencies |
| CDC Support | Change Data Capture for real-time database synchronization |
| Transform Layer | Built-in SQL and custom transform functions |

## Use Cases

| Name | Description |
|------|-------------|
| Database Migration | Migrate data between databases with schema mapping |
| Data Warehouse Loading | Load and sync data into data warehouses |
| Real-Time Synchronization | CDC-based real-time sync between source and target systems |
| Data Lake Ingestion | Ingest data from multiple sources into a data lake |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Kafka source and sink connector for streaming pipelines |
| Apache Flink | Run SeaTunnel jobs on Flink execution engine |
| Apache Spark | Run SeaTunnel jobs on Spark execution engine |
| ClickHouse | High-performance ClickHouse sink connector |
| Doris | Apache Doris connector for analytical workloads |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache SeaTunnel REST API](openapi/apache-seatunnel-rest-api.yaml)

### JSON Schema

- [Job Info](json-schema/apache-seatunnel-job-info-schema.json)
- [Job Detail](json-schema/apache-seatunnel-job-detail-schema.json)
- [Job Metrics](json-schema/apache-seatunnel-job-metrics-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache SeaTunnel JSON Structures](json-structure/)

### JSON-LD

- [Apache SeaTunnel Context](json-ld/apache-seatunnel-context.jsonld)

### Examples

- [Apache SeaTunnel Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Data Integration Workflow](capabilities/seatunnel-workflow.yaml) | Apache SeaTunnel | 6 | Data Engineer, Platform Engineer |

## Vocabulary

- [Apache SeaTunnel Vocabulary](vocabulary/apache-seatunnel-vocabulary.yaml) — Unified taxonomy mapping data integration resources, actions, workflows, and personas

## Rules

- [Apache SeaTunnel Spectral Rules](rules/apache-seatunnel-spectral-rules.yml) — Rules enforcing Apache SeaTunnel API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
