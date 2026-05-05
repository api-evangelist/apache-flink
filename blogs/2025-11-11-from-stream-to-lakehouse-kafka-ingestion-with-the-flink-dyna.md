---
title: "From Stream to Lakehouse: Kafka Ingestion with the Flink Dynamic Iceberg Sink"
url: "https://flink.apache.org/2025/11/11/from-stream-to-lakehouse-kafka-ingestion-with-the-flink-dynamic-iceberg-sink/"
date: "Tue, 11 Nov 2025 00:00:00 +0000"
author: ""
feed_url: "https://flink.apache.org/posts/index.xml"
---
Ingesting thousands of evolving Kafka topics into a lakehouse often creates complex, brittle pipelines that require constant manual intervention as its write patterns change. But what if your ingestion pipeline could adapt on its own, with zero downtime?
Enter the Flink Dynamic Iceberg Sink, a powerful pattern for Apache Flink that allows users to write streaming data into multiple Iceberg tables—dynamically, efficiently, and with full schema evolution support. The sink can create and write to new tables based on instructions within the records themselves.
