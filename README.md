# Apache Flink (apache-flink)

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

Apache Flink is a framework and distributed processing engine for stateful computations over unbounded and bounded data streams. It provides a REST API for job management, cluster operations, metrics collection, and checkpoint management for real-time streaming and batch processing workloads.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-flink/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, Batch Processing, Big Data, Open Source, Real-Time Analytics, Stateful Computing, Stream Processing

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Apache Flink REST API
The REST API provides programmatic access to monitor and control Flink jobs and clusters. It supports job submission, cluster management, metrics retrieval, checkpoint management, and TaskManager administration.

**Human URL:** [https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/rest_api/](https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/rest_api/)

#### Tags:

 - Big Data, Distributed Computing, Job Management, Real-Time Processing, REST API, Streaming

#### Properties

- [Documentation](https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/rest_api/)
- [OpenAPI](openapi/apache-flink-rest-openapi-original.yml)
- [JSONSchema](json-schema/flink-rest-job-details-info-schema.json)
- [JSON-LD](json-ld/apache-flink-rest-context.jsonld)

### Apache Flink Monitoring API
Monitoring REST API for accessing job metrics, checkpoints, and cluster statistics for Apache Flink deployments.

**Human URL:** [https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/monitoring/](https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/monitoring/)

#### Tags:

 - Metrics, Monitoring, Observability

#### Properties

- [Documentation](https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/monitoring/)
- [Metrics Reference](https://nightlies.apache.org/flink/flink-docs-stable/docs/ops/metrics/)

## Common Properties

- [GettingStarted](https://nightlies.apache.org/flink/flink-docs-stable/docs/try-flink/local_installation/)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/flink)
- [Blog](https://flink.apache.org/blog/)
- [Support](https://flink.apache.org/community.html)
- [Training](https://nightlies.apache.org/flink/flink-docs-stable/docs/learn-flink/overview/)
- [StackOverflow](https://stackoverflow.com/questions/tagged/apache-flink)

## Features

| Name | Description |
|------|-------------|
| Unified Stream and Batch Processing | Single engine for both unbounded stream processing and bounded batch workloads with a unified API. |
| Stateful Computations | Rich stateful processing with managed state backends (RocksDB, heap), exactly-once guarantees, and state versioning. |
| Exactly-Once Semantics | End-to-end exactly-once processing guarantees with distributed snapshots and transactional sinks. |
| Event Time Processing | Native event-time support with watermarks for out-of-order event handling in streaming workloads. |
| Checkpointing and Savepoints | Automatic fault-tolerance via checkpointing and manual savepoints for job migration and upgrades. |
| High Availability | JobManager HA via ZooKeeper or Kubernetes for zero-downtime cluster operations. |
| Scalable Architecture | Horizontally scalable TaskManagers with fine-grained resource management and dynamic slot allocation. |
| REST API Management | Comprehensive REST API for job submission, monitoring, metrics collection, and cluster administration. |
| SQL and Table API | Declarative SQL and Table API for streaming analytics with connector ecosystem support. |

## Use Cases

| Name | Description |
|------|-------------|
| Real-Time Analytics | Process and analyze event streams in real time for dashboards, alerts, and operational intelligence. |
| ETL Pipelines | Build scalable ETL pipelines for data lake ingestion, transformation, and enrichment. |
| Fraud Detection | Detect fraudulent transactions in real time using stateful pattern matching over event streams. |
| IoT Data Processing | Process high-volume IoT device telemetry with stateful aggregations and time-window computations. |
| Machine Learning Inference | Serve ML model predictions at scale with streaming feature computation and online inference. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Kafka source and sink connectors for high-throughput event streaming ingestion and output. |
| Apache Hadoop / HDFS | HDFS integration for batch data reading and writing in distributed storage. |
| Apache Hive | Hive catalog integration and batch SQL queries over Hive tables. |
| Kubernetes | Native Kubernetes deployment with FlinkDeployment CRD and the Flink Kubernetes Operator. |
| Apache Iceberg | Iceberg table format integration for lakehouse workloads with ACID guarantees. |
| Elasticsearch | Elasticsearch sink connector for real-time search index updates from Flink jobs. |
| Amazon Kinesis | Kinesis source and sink connectors for AWS-native streaming pipelines. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Flink REST API](openapi/apache-flink-rest-openapi-original.yml)

### JSON Schema

- 132 schema files in [json-schema/](json-schema/)

### JSON Structure

- 132 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache Flink REST Context](json-ld/apache-flink-rest-context.jsonld)

### Examples

- 132 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Flink REST API](capabilities/shared/flink-rest.yaml) — 5 operations for job and cluster management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Flink Job Management](capabilities/flink-job-management.yaml) | flink-rest | 5 | Data Engineer, Platform Operator |

## Vocabulary

- [Apache Flink Vocabulary](vocabulary/apache-flink-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Flink Spectral Rules](rules/apache-flink-spectral-rules.yml) — 11 rules across 5 categories enforcing Apache Flink API conventions

## Maintainers

**FN:** Apache Software Foundation

**Email:** user@flink.apache.org
