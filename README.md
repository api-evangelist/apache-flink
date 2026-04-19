# Apache Flink (apache-flink)
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
