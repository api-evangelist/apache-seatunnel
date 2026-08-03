# Apache SeaTunnel (apache-seatunnel)

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
