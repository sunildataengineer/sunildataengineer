<div align="center">

![header](./header.svg)

</div>

---

<img align="right" width="320" src="https://github-readme-stats.vercel.app/api?username=sunildataengineer&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=FF6B35&text_color=C9D1D9&hide_title=true"/>

### `$ cat about_me.json`

```json
{
  "name"    : "Sunil Kumar Reddy",
  "role"    : "Data Engineer",
  "location": "Bangalore, India",
  "clouds"  : ["AWS ☁", "GCP ☁", "Azure ☁"],
  "certs"   : [
    "AWS Certified Data Engineer Associate",
    "Databricks Certified Data Engineer Associate"
  ],
  "events_per_day" : "620,000+",
  "pipelines_built": 3,
  "uptime"         : "99.97%",
  "available"      : true
}
```

<br clear="right"/>

---

## `$ ls -la ./projects`

---

### 🔴 Project 1 — Real-Time Fraud & Anomaly Detection · AWS

![p1](./p1_pipeline.svg)

> **Stack:** Apache Kafka · Spark Structured Streaming · PySpark · Amazon S3 · Redshift · Python

**The Problem:** Traditional fraud detection runs in batch mode — detecting fraud 4-6 hours after it happens. Money is already gone.

**What I Built:** A Kafka-to-Spark streaming pipeline ingesting 120K+ daily transaction events — reducing fraud detection latency from batch hours to under 60 seconds, with exactly-once semantics and zero data loss.

| Metric | Result |
|:-------|:------:|
| Daily Events | **120K+** |
| Latency | Batch hours → **< 60s** |
| Pipeline Failures | **↓ 80%** |
| Query Time | **↓ 40%** |
| Data Loss | **0** |

[![View Project](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sunildataengineer/Real-Time-Fraud-Anomaly-Detection-Streaming-Platform)

---

### 🔵 Project 2 — Real-Time Data Quality & Streaming Governance · Azure

![p2](./p2_pipeline.svg)

> **Stack:** Azure Event Hubs · Databricks · Delta Lake · PySpark · Azure Data Factory · Python

**The Problem:** Bad data silently corrupts every downstream system — wrong dashboards, broken ML models, compliance risk. Most companies catch it after it reaches the warehouse.

**What I Built:** A medallion architecture platform (Bronze→Silver→Gold) enforcing 6 data quality rules at ingestion — 200K+ daily records validated with full quarantine audit trail and schema evolution support.

| Metric | Result |
|:-------|:------:|
| Daily Records | **200K+** |
| Downstream Rejections | **↓ 40%** |
| Recovery Time | **↓ 30%** |
| Delta Layers | **3 (B→S→G)** |
| Data Loss | **0** |

[![View Project](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sunildataengineer/Real-Time-Data-Quality-Streaming-Governance-Platform)

---

### 🟢 Project 3 — Global Real-Time Event Processing · GCP

![p3](./p3_pipeline.svg)

> **Stack:** Google Pub/Sub · Apache Beam · Cloud Dataflow · BigQuery · Python · SQL

**The Problem:** Users across 3 global regions generate events that arrive out-of-order due to network delays. Naive processing gives wrong aggregations. Late-arriving events are silently dropped.

**What I Built:** A stateful streaming platform processing 300K+ daily events across multi-region with event-time windowing, watermarking (2min tolerance), and 3 window types — Fixed, Sliding, and Session.

| Metric | Result |
|:-------|:------:|
| Daily Events | **300K+ (3 regions)** |
| Latency | **< 60 seconds** |
| Accuracy Gain | **+30%** (event-time) |
| Query Speedup | **↓ 45%** (BQ partition) |
| Data Loss | **0** |

[![View Project](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sunildataengineer/Global-Real-Time-Event-Processing-Stateful-Streaming-Platform)

---

## `$ cat tech_stack.yaml`

```yaml
languages:
  - Python          # pandas, PySpark, Apache Beam
  - SQL             # window functions, CTEs, query optimization

streaming:
  - Apache Kafka    # consumer groups, offset management, exactly-once
  - Azure Event Hubs
  - Google Pub/Sub
  - Apache Airflow

processing:
  - Apache Spark    # structured streaming, checkpointing
  - PySpark
  - Azure Databricks
  - Google Dataflow

storage:
  - Delta Lake      # medallion architecture, schema evolution
  - Amazon S3       # parquet-partitioned datasets
  - Amazon Redshift
  - Google BigQuery

cloud:
  - AWS             # S3, Glue, Redshift, Kinesis
  - GCP             # Pub/Sub, Dataflow, BigQuery
  - Azure           # Event Hubs, Databricks, Data Factory, ADLS

observability:
  - OpenTelemetry   # distributed tracing, span instrumentation
  - Structured Logging
  - Prometheus
```

---

## `$ cat certifications.txt`

```
┌──────────────────────────────────────────┬──────────────────────────────────────────┐
│  ☁  AWS Certified Data Engineer          │  ▣  Databricks Certified Data Engineer   │
│     Associate                            │     Associate                            │
│     Amazon Web Services · Jan 2026       │     Databricks · Feb 2026               │
│     Status: ██████████  ACTIVE ✓         │     Status: ██████████  ACTIVE ✓        │
└──────────────────────────────────────────┴──────────────────────────────────────────┘
```

---

## 📊 GitHub Stats

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=sunildataengineer&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=FF6B35&currStreakLabel=7FDBFF)](https://github.com/sunildataengineer)

</div>

---

## `$ git log --oneline --all`  *(current sprint)*

```
🟢 [NOW]  Deep-diving MySQL advanced queries + window functions
🟢 [NOW]  Python for Data Engineering — Pandas, OOP, ETL scripting
⬜ [NEXT] PySpark + Airflow pipelines from scratch
⬜ [NEXT] Mock interviews — Accenture · Deloitte · IBM
⬜ [GOAL] First Data Engineer offer — June 2026 🎯
```

---

<div align="center">

**→ Open to Data Engineer roles — Let's build pipelines together**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/suniil-data-engineer/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-FF6B35?style=for-the-badge&logo=netlify&logoColor=white)](https://sunildataengineer.netlify.app/)
[![Email](https://img.shields.io/badge/Email-Hire_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sunildataengineer@outlook.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-Solve-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/sunildataengineer/)

*"Bad pipelines fail silently. Good engineers don't let them."*

</div>
