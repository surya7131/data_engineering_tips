# 📘 Snowflake & Data Engineering Interview Guide

A comprehensive, practical, and interview-focused guide covering **Snowflake, dbt, SQL, CDC, data pipelines, and data engineering concepts**.

This guide is designed for:
- Data Engineers
- Analytics Engineers
- Snowflake / dbt interview preparation
- Real-world production understanding (not textbook theory)

---

## 🌐 Live Version

👉 **View the guide online:**  
https://surya7131.github.io/data_engineering_tips/

---

## 📌 What This Guide Covers

### ❄️ Snowflake (10+ questions)
- Architecture & three-layer design (Storage, Compute, Cloud Services)
- Virtual warehouses & cost optimization
- Time Travel, Zero-Copy Cloning, and instant snapshots
- Micro-partitions vs traditional partitions
- Clustering keys & automatic pruning
- Streams, Tasks, and Snowpipe
- Native CDC implementation
- Data Sharing & governance
- Query performance optimization

### 🧱 Data Modeling & SCD (8+ questions)
- SCD Types 0-4 with real examples
- Type 2 with effective dates (most common)
- DBT snapshots for automated SCD
- Dimensional vs Fact tables
- Transient, temporary, and permanent tables
- Schema change handling in downstream systems

### 🔄 Data Ingestion & Pipelines (10+ questions)
- JSON ingestion (6-step process)
- Large file handling strategies (50GB+ examples)
- Internal vs External Stages
- File format selection (Parquet, AVRO, ORC)
- CDC patterns (timestamp-based, log-based, streams)
- Real-world use cases: E-commerce inventory, real-time dashboards
- Continuous data loading vs batch
- End-to-end pipeline design

### 🛠️ dbt (Data Build Tool) (10+ questions)
- dbt overview & core concepts
- Models, refs, and dependencies (DAG)
- Materializations: View, Table, Incremental, Ephemeral
- dbt snapshots for SCD Type 2
- Tests: not_null, unique, relationships, accepted_values
- Project structure best practices (staging, intermediate, marts)
- Jinja templating for dynamic SQL
- dbt with Snowflake integration

### 🧠 SQL & Advanced Concepts (8+ questions)
- Window functions (RANK, DENSE_RANK, ROW_NUMBER, LAG, LEAD)
- QUALIFY clause for clean filtering
- CTE vs Temporary Tables (scope & materialization)
- MERGE vs UPSERT patterns
- Timezone conversion (CONVERT_TIMEZONE, AT TIME ZONE)
- Advanced salary queries (nth highest, top N per group)
- Query optimization (filtering, caching, indexing)

### 🐍 Python for Data Engineering
- Lists vs Tuples (mutable vs immutable)
- Use cases and performance implications

### 🔐 Data Governance & Security (3+ questions)
- Data masking policies (role-based visibility)
- Hashing vs Encryption (one-way vs two-way)
- Collibra vs Ataccama (governance vs quality tools)
- Data quality testing strategies

### 📊 Monitoring & Observability (2+ questions)
- Performance monitoring with Query History
- WAREHOUSE_METERING_HISTORY for cost tracking
- External monitoring tools (Datadog, New Relic)

**Total: 50 comprehensive, production-focused questions covering entry-level to advanced topics**

---

## 🧭 Key Features

- ✅ **50 comprehensive interview questions** (consolidated from 74, removing duplicates)
- ✅ **Full-width responsive layout** for optimal reading on all devices
- ✅ Clickable **Table of Contents** with anchor navigation
- ✅ Code examples, tables, and real-world use cases
- ✅ Mobile & desktop responsive with single-column & multi-column support
- ✅ Clean navigation with "Back to Contents" links
- ✅ Practical, production-oriented explanations
- ✅ No fluff, no theory-only answers

---

## 📱 Responsive Design

- 📱 Mobile: Single-column, optimized for touch navigation
- 🖥️ Desktop: **Full-width layout** with two-column Table of Contents
- 💡 Optimized for reading, scrolling, and keyboard navigation
- 🎨 Modern gradient styling with Snowflake blue theme (#007acc)

---

## 📄 Project Structure

```
data_engineering_tips/
├── index.html          # Main interactive guide (all 50 questions)
├── README.md          # This file
└── LICENSE            # MIT License
```

## 🚀 How to Use This Guide

- 📖 Read topic-by-topic for interview prep
- 🔍 Jump directly to questions using the Contents
- 🧠 Revise before interviews
- 📤 Share as a single link with recruiters or peers

---

## 🛠️ How It’s Built

- Pure HTML + CSS
- No frameworks
- Lightweight & fast
- Can be hosted on:
  - GitHub Pages
  - Netlify
  - AWS S3 (static site)

---

## 🧩 Future Enhancements (Coming Soon)

- 🔍 Search bar for quick question lookup
- 🌙 Dark mode theme
- 📘 Topic-wise collapsible sections
- 📄 PDF export version
- 🎯 Difficulty level indicators (Beginner/Intermediate/Advanced)
- 💬 Community contributions & discussions

---

## 📬 Feedback & Contributions

Found an error? Want to improve an answer? Have a great use case to add?

We welcome contributions! How to contribute:
1. Fork the repository
2. Edit `index.html` directly (clear HTML structure)
3. Test your changes in a browser
4. Submit a pull request

Or simply open an issue with suggestions.

---

## ⭐ If This Helped You

Consider:
- Starring the repository ⭐
- Sharing with fellow data engineers
- Using it as your personal interview prep handbook

---

**Happy learning & best of luck with your interviews! 🚀**

---

*Last Updated: March 2026*  
*Maintained by: Surya*  
*Repository: [data_engineering_tips](https://github.com/surya7131/data_engineering_tips)*

