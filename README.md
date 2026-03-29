# 📘 Data Engineering Prep — Snowflake, dbt, Cloud & System Design

A comprehensive, production-focused interview guide covering **Snowflake, dbt, CDC, SQL, AWS, data pipelines, dimensional modelling, system design, and architect-level patterns**.

Built for engineers who want real answers — not textbook theory — with working SQL, real-world scenarios and the kind of depth that passes senior and staff-level interviews.

---

## 🌐 Live Version

👉 **View the guide online:**
https://surya7131.github.io/data_engineering_tips/

---

## 📌 What This Guide Covers (82 Questions)

### ❄️ Snowflake Core & Performance (Q1 – Q20)
- Compute hours, architecture, Time Travel, performance optimisation
- Micro-partitions, SCD implementation, JSON ingestion, file loading
- Stages, pipeline scheduling, stored procedures, UDFs, Git basics, QUALIFY

### 🔄 CDC, Data Ingestion & dbt Fundamentals (Q21 – Q40)
- CDC concepts & mechanisms (timestamp, log-based, trigger-based)
- File formats (AVRO, Parquet, ORC), CTEs, table types, schema evolution
- dbt overview, ephemeral vs permanent models, incremental patterns
- Python fundamentals, data loading strategies, pipeline design

### 🧠 Advanced SQL & Data Structures (Q41 – Q52)
- Window functions, timezone conversion, clustering keys, query optimization
- Zero-copy clones, task automation, Snowpipe, data masking policies
- Hashing vs encryption, storage integration, schema drift handling
- Late-arriving data patterns, quality frameworks

### 🛠️ dbt Mastery & Governance (Q53 – Q68)
- **dbt Models, Tests, Seeds & Custom Tests — deep dive**
- **dbt Incremental strategies: merge, append, delete+insert, Snapshots**
- dbt dependencies (ref/source), macros, Jinja templating, CI/CD, state comparison
- Data governance, RBAC, column-level security, Ataccama vs Collibra
- Data quality testing, modern data stack best practices

### 🏗️ System Design & Architecture (Q69 – Q82)
- **CDC pipeline: Oracle/SQL Server → Qlik Replicate → Snowflake**
- **Scalable ELT platform: 5M+ records/day on Snowflake + dbt Cloud**
- Snowflake Streams & Tasks, event-driven automation, dimensional modelling
- AWS + Snowflake integration (S3, IAM, Snowpipe), dbt exposures
- Performance tuning, multi-source lakehouse, Redshift-to-Snowflake migration

---

## 🧭 Key Features

- ✅ **82 comprehensive questions** — entry-level through senior architect
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
|------|----------|
| Interview prep | Read topic sections top-to-bottom; use sidebar to navigate |
| Quick revision | Jump directly via sidebar links; questions collapse to headers |
| System design practice | Focus on Q69–Q82 (architect section) |
| dbt deep-dive | Q53–Q59, Q65 cover models, incremental, macros, CI/CD patterns |
| Snowflake performance | Q4, Q18, Q27, Q66 cover optimisation in depth |
| CDC mastery | Q21–Q24 intro + Q69–Q70 real-world architectures |
| Share with recruiter | Single URL — everything is self-contained |

---

## 🛠️ How It's Built

- **Pure HTML + CSS + vanilla JavaScript** — zero build step, zero dependencies
- Hosted on GitHub Pages (free, instant deployment on push to `main`)
- Can also be hosted on: Netlify, AWS S3 static site, Vercel

---

---

## 🧩 Future Enhancements

- 🔍 Full-text search across all 82 questions
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