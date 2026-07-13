---
title: "Deep Dive! Apache SeaTunnel: Core Concept of Data Flow"
url: "https://seatunnel.apache.org/blog/apache-seatunnel-core-concept-data-flow"
date: "2026-06-06"
author: ""
feed_url: "https://seatunnel.apache.org/blog/rss.xml"
---
SeaTunnel operates as a DAG execution engine centered on DataStream/DataFlow rather than a linear source-to-sink model. It uses plugin_output and plugin_input as connection ports for data flows, enabling multiple upstream branches to converge on downstream stages while maintaining schema consistency.
