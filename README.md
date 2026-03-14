# 📘 Data Engineering Prep — Snowflake, dbt, Cloud & System Design

A comprehensive, production-focused interview guide covering **Snowflake, dbt, CDC, SQL, AWS, data pipelines, dimensional modelling, system design, and architect-level patterns**.

Built for engineers who want real answers — not textbook theory — with working SQL, real-world scenarios and the kind of depth that passes senior and staff-level interviews.

---

## 🌐 Live Version

👉 **View the guide online:**
https://surya7131.github.io/data_engineering_tips/

---

## 📌 What This Guide Covers (62 Questions)

### ❄️ Snowflake Core (Q1 – Q15)
| # | Topic |
|---|-------|
| 1 | Write a query to calculate compute hours consumed |
| 2 | Snowflake three-layer architecture (Storage, Compute, Cloud Services) |
| 3 | Time Travel: OFFSET, TIMESTAMP, STATEMENT modes |
| 4 | Query performance optimisation strategy |
| 5 | Micro-partitions vs traditional partitions |
| 6 | SCD Types 0–4 with real-world change handling |
| 7 | JSON ingestion: 6-step process |
| 8 | Loading a 50GB file into Snowflake |
| 9 | Internal vs External Stages |
| 10 | Scheduling data pipelines |
| 11 | Stored Procedures fundamentals |
| 12 | User Defined Functions (UDFs) |
| 13 | Git fundamentals for data teams |
| 14 | QUALIFY clause |
| 15 | Key benefits of Snowflake |

### 🔄 CDC & Ingestion (Q16 – Q27)
| # | Topic |
|---|-------|
| 16 | CDC: concept & mechanisms (timestamp, log-based, trigger-based) |
| 17 | Python: Lists vs Tuples |
| 18 | File formats: AVRO, Parquet, ORC comparison |
| 19 | CTE vs Temporary Tables |
| 20 | Snowflake table types (permanent, transient, temporary) |
| 21 | Handling schema changes in downstream systems |
| 22 | Ephemeral vs Permanent tables in dbt |
| 23 | Implementing CDC in Snowflake (without tools) |
| 24 | dbt overview & core concepts |
| 25 | Continuous data loading vs batch |
| 26 | End-to-end pipeline design |
| 27 | CDC vs full loads — real use case |

### 🧠 SQL & Advanced Concepts (Q28 – Q36)
| # | Topic |
|---|-------|
| 28 | Snowflake Tasks: troubleshooting & optimisation |
| 29 | Zero Copy Clone: instant data copies |
| 30 | Timezone conversion (CONVERT_TIMEZONE, AT TIME ZONE) |
| 31 | Clustering keys & automatic pruning |
| 32 | Monitoring Snowflake performance (Query History, Metering) |
| 33 | Ataccama vs Collibra: governance tool comparison |
| 34 | Snowpipe: continuous data ingestion |
| 35 | Window functions: RANK, DENSE_RANK, ROW_NUMBER, LAG, LEAD |
| 36 | Swap gender values query |

### 🛠️ dbt Fundamentals (Q37 – Q50)
| # | Topic |
|---|-------|
| 37 | dbt project structure & best practices |
| 38 | MERGE vs UPSERT explained |
| 39 | Data masking & masking policies |
| 40 | Hashing vs Encryption |
| 41 | Snowflake S3 storage integration |
| 42 | **dbt Models, Tests, Seeds & Custom Tests — deep dive** |
| 43 | **dbt Incremental strategies: merge, append, delete+insert & Snapshots** |
| 44 | Managing dbt dependencies with ref() |
| 45 | Jinja templating in dbt |
| 46 | Data governance best practices |
| 47 | Data quality testing strategies |
| 48 | Building a modern data stack |
| 49 | Future trends in data engineering |
| 50 | dbt Snapshots: implementing SCD Type 2 |

### 🧩 Data Quality & Resilience (Q51 – Q52)
| # | Topic |
|---|-------|
| 51 | Schema drift: detection, handling & real-world strategies |
| 52 | Late-arriving data: patterns, detection & correction strategies |

### 🏗️ Architect & System Design (Q53 – Q62)
| # | Topic |
|---|-------|
| 53 | **System Design: Real-time CDC pipeline — Oracle/SQL Server → Qlik Replicate → Snowflake** |
| 54 | **System Design: Scalable ELT platform for 5M+ records/day on Snowflake + dbt Cloud** |
| 55 | Snowflake Streams & Tasks: event-driven pipeline automation |
| 56 | dbt Macros, Jinja & Exposures — reusable patterns at scale |
| 57 | Dimensional modelling: Star schema, surrogate keys, conformed dims & Bus Matrix |
| 58 | AWS + Snowflake integration: S3 Stages, IAM, Snowpipe & event-driven ingestion |
| 59 | dbt CI/CD with Slim CI, state comparison & Git-based deployment |
| 60 | Snowflake performance tuning: clustering, query pruning, caching & profiling |
| 61 | Data quality framework design: 4-layer defence, freshness, anomaly detection |
| 62 | **Senior Architect: Multi-source Lakehouse — Redshift-to-Snowflake migration** |

---

## 🧭 Key Features

- ✅ **62 comprehensive questions** — entry-level through senior architect
- ✅ **Real-world scenarios** grounded in production data engineering experience
- ✅ Working SQL, dbt config, and architecture diagrams in every answer
- ✅ Collapsible questions — expand only what you need
- ✅ **Animated hero** with typewriter topic cycling and live progress tracking
- ✅ Collapsible sidebar with smooth toggle (desktop & mobile)
- ✅ Dark / Light theme toggle with saved preference
- ✅ Live "questions viewed" progress bar
- ✅ Fully responsive — optimised for mobile, tablet, and desktop
- ✅ Anchor navigation — jump directly to any question
- ✅ No frameworks, no dependencies — pure HTML + CSS + vanilla JS

---

## 📐 Tech Stack Covered

| Area | Technologies |
|------|-------------|
| Data Warehouse | Snowflake (Streams, Tasks, Snowpipe, Time Travel, Zero-Copy Clone, Clustering) |
| Transformation | dbt Cloud, dbt Core, Macros, Jinja, Incremental Models, Snapshots, CI/CD |
| Ingestion / CDC | Qlik Replicate, Snowpipe, AWS S3, Fivetran |
| Cloud | AWS (S3, EC2, IAM, SQS), Azure Fundamentals |
| Data Modelling | Star & Snowflake schemas, SCD Types 1/2, Surrogate Keys, Bus Matrix |
| Programming | SQL (Advanced), Python, Git, Linux |
| Governance | Ataccama, Collibra, Data Masking, RBAC, Column-level Security |
| Observability | Query History, Warehouse Metering, Z-score anomaly detection |

---

## 📱 Responsive Design

- 📱 **Mobile** — full hero with animated stats, collapsible questions, sidebar as overlay
- 🖥️ **Desktop** — fixed sidebar (collapsible via ☰ toggle), wide content area, persistent state
- 🌙 **Theme** — dark/light toggle, preference saved to localStorage
- ⚡ **Performance** — no external JS frameworks; all animations via CSS + vanilla JS

---

## 📄 Project Structure

```
data_engineering_tips/
├── index.html    # Complete interactive guide (62 questions, ~200KB)
├── README.md     # This file
└── LICENSE       # MIT License
```

---

## 🚀 How to Use This Guide

| Goal | Approach |
|------|---------|
| Interview prep | Read topic sections top-to-bottom; use sidebar to navigate |
| Quick revision | Jump directly via sidebar links; questions collapse to headers |
| System design practice | Focus on Q53–Q62 (architect section) |
| dbt deep-dive | Q42–Q45, Q56, Q59 cover macros, CI/CD, incremental patterns |
| Snowflake performance | Q4, Q31, Q60 cover optimisation in depth |
| Share with recruiter | Single URL — everything is self-contained |

---

## 🛠️ How It's Built

- **Pure HTML + CSS + vanilla JavaScript** — zero build step, zero dependencies
- Hosted on GitHub Pages (free, instant deployment on push to `main`)
- Can also be hosted on: Netlify, AWS S3 static site, Vercel

---

## 🧩 Future Enhancements

- 🔍 Full-text search across all 62 questions
- 🏷️ Difficulty badges (Junior / Mid / Senior / Architect)
- 📄 PDF export for offline revision
- 🎯 Topic filter (show only dbt questions, only Snowflake questions, etc.)
- 💬 Community-contributed answers & discussion threads
- 📊 Personal progress persistence across sessions

---

## 📬 Feedback & Contributions

Found an error? Want to add a question? Have a better real-world scenario?

1. Fork the repository
2. Edit `index.html` — questions follow a consistent `<div class="question" id="qN">` structure
3. Add the corresponding sidebar entry: `<a href="#qN" class="sidebar-item" data-q="qN">`
4. Test in a browser — the stat counters update automatically from the DOM
5. Submit a pull request

Or open an issue with a suggestion.

---

## ⭐ If This Helped You

- Star the repository ⭐
- Share with fellow data engineers and analytics engineers
- Use it as your personal interview prep handbook

---

**Happy learning & best of luck with your interviews! 🚀**

---

*Last Updated: March 2026*
*Maintained by: Vemula Suryateja*
*Repository: [data_engineering_tips](https://github.com/surya7131/data_engineering_tips)*