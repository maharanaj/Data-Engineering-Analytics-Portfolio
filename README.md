# Data-Engineering-Analytics-Portfolio
This repository showcases end-to-end data engineering and analytics solutions built with modern cloud tooling.   It is designed as a **mini-portfolio** to demonstrate my exposure to pipeline design, data quality, governance, and dashboarding skills.

---
## 🚀 Project Overview
- **Scenario 1 (Finance / Superannuation):**
  - Migration-style ELT pipeline (Snowflake → BigQuery) with dbt models.
  - Compliance artefacts aligned with APRA CPS 234.
  - Power BI dashboard: "Member Contributions & Balances."

- **Scenario 2 (Retail / FMCG):**
  - Near real-time pipeline (Pub/Sub → Dataflow → BigQuery).
  - dbt models for sales & promotions.
  - Power BI dashboard: "Sales by Product & Store."

---
## 🛠 Tech Stack
- **Cloud / Data:** BigQuery, Snowflake, Azure Data Factory, Databricks
- **Transformation:** dbt (staging, intermediate, mart layers)
- **Orchestration:** GitHub Actions (CI/CD), Cloud Composer (optional)
- **Dashboards:** Power BI, Looker Studio
- **Programming:** Python, SQL (Snowflake SQL + BigQuery SQL)

---
## 📂 Repository Structure
- `architecture/` → system diagrams
- `data/` → synthetic data & generator scripts
- `dbt_project/` → dbt models, tests, configs
- `adf_pipeline/` → Azure Data Factory pipeline JSON
- `databricks/` → PySpark notebook for ETL
- `dashboards/` → Power BI dashboards + screenshots
- `compliance/` → APRA compliance & governance docs
- `cicd/` → GitHub Actions workflows
- `case_study/` → PDF case study report
- `runbook/` → migration & incident runbooks

---
## ✅ How to Reproduce
1. Clone this repo.
2. Load `data/sample_data.csv` into BigQuery (sandbox account is free).
3. Run dbt project (`dbt run`) for staging → marts.
4. Review dashboards in `/dashboards/screenshots`.
5. Explore compliance artefacts in `/compliance`.

---
## 📊 Portfolio Deliverables
- End-to-end ELT pipeline
- Automated dbt tests in CI/CD
- Finance + Retail dashboards
- Compliance artefacts (mock APRA)
- Case study PDF (problem → solution → outcome)

---
## 📧 Contact
Created by **Jitendra Maharana**  
🔗 LinkedIn: https://www.linkedin.com/in/jitendra-maharana/  
📩 Email: jitendra.maharana@gmail.com
📞 Mobile: [0467-543-765]

