# 📈 Quantitative UXR & Behavioral Analytics Portfolio: GajiKu Q1 2024

A comprehensive behavioral data analytics project analyzing product adoption, conversion funnels, retention cohorts, user health scoring, and financial growth metrics for **GajiKu**, a digital payroll and financial access platform.

---

## 📌 Project Overview & Objectives

This project analyzes **Q1 2024 transactional, session, and event tracking data** to diagnose user drop-offs, quantify cohort retention, segment user health, and establish automated BI export pipelines.

### Core Objectives:
1. **Funnel & Drop-off Analysis:** Pinpoint conversion bottlenecks across core transfer journeys.
2. **Cohort Retention Modeling:** Calculate D1, D7, and D30 user retention matrices.
3. **Advanced SQL Window Functions:** Measure Month-over-Month (MoM) revenue velocity and rolling moving averages.
4. **Multi-Layer CTE User Health Scoring:** Construct a composite Health Score (0–100) combining Recency, Engagement, and Transaction metrics.
5. **BI Ingestion Pipeline:** Export cleaned analytical datasets for interactive dashboarding in Looker Studio.

---

## 📂 Repository Structure

```text
quant-uxr-portfolio/
└── 03_behavioral_sql/
    ├── README.md                      ← Portfolio documentation & executive summary
    │
    ├── 01_fundamentals/               ← Foundational SQL queries
    │   ├── select_where.sql           ← Filtering & sorting fundamentals
    │   ├── group_by_agg.sql           ← Aggregations & group-level summaries
    │   ├── join_tables.sql            ← Relational table joins
    │   └── case_when_cte.sql          ← Conditional logic & CTEs
    │
    ├── 02_behavioral_patterns/        ← Core behavioral tracking queries
    │   ├── funnel_analysis.sql        ← Conversion funnels & drop-off evaluation
    │   ├── retention_cohort.sql       ← Weekly retention matrix (D1/D7/D30)
    │   ├── rfm_segmentation.sql       ← RFM scoring & user categorization
    │   └── event_analysis.sql         ← Feature adoption & dead-end event identification
    │
    ├── 03_advanced/                   ← Production analytical modeling
    │   ├── window_functions.sql       ← LAG, ROW_NUMBER, 7-day rolling moving averages
    │   ├── mom_analysis.sql           ← Month-over-Month revenue & active user growth
    │   └── health_score.sql           ← Composite multi-layer CTE user health score
    │
    ├── notebooks/
    │   └── behavioral_report.ipynb    ← End-to-end Python & SQL analytical report
    │
    └── exports/                       ← Looker Studio CSV data sources
        ├── monthly_metrics.csv        ← Financial trends & monthly active user volume
        ├── user_segments.csv          ← User plan tier & city demographic distribution
        └── event_summary.csv          ← Product taxonomy & interaction volume
