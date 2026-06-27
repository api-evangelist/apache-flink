---
title: "Introducing Flink's Native S3 FileSystem: Built for Performance, Designed for Production"
url: "https://flink.apache.org/2026/06/26/announcing-native-s3-fs/"
date: "2026-06-26"
feed_url: "https://flink.apache.org/index.xml"
---
Apache Flink relies on the underlying filesystem for much of its work: reading and writing application data, materializing streaming sinks, and storing checkpoints and savepoints for recovery. For years, S3 support in Flink meant choosing between two Hadoop-based plugins, each with its own trade-offs and configuration quirks. With Flink 2.3, there is a better option.
