# 📊 Stage 2: Advanced UX Metrics & Psychometric Validation Pipeline

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square&logo=python)
![Scipy](https://img.shields.io/badge/Scipy-Statistical%20Inference-green?style=flat-square)
![Factor Analysis](https://img.shields.io/badge/Psychometrics-EFA%20%26%20CFA-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

---

## 📌 Executive Summary
This repository contains the end-to-end quantitative research and behavioral analytics pipeline for **Stage 2: Quant UXR Mastery**. The project bridges raw user behavior logs with rigorous psychometric validation (Factor Analysis & Reliability Metrics) and C-Suite executive dashboards.

The core objective is to establish a **data-driven UX Measurement Framework** that evaluates product usability, user sentiment, and systemic retention drivers using statistical inference (Bootstrap 95% CI, ANOVA, and Exploratory Factor Analysis).

---

## 🛠️ Key Architectural Pillars

### 🔵 Pillar A: Behavioral Metric Ingestion & Descriptive Diagnostics
- Processed engagement metrics, task completion rates, and error frequencies across user cohorts.
- Integrated automated feature distribution profiling (`feature_dashboard.png`).

### 🟢 Pillar B: Net Promoter Score (NPS) Relational & Inferential Analysis
- Executed **Bootstrap Resampling (1,000 iterations)** to calculate a true 95% Confidence Interval for system-wide NPS.
- Evaluated segment-level score variance using **One-Way ANOVA**, determining statistically significant disparities across user personas (Beginner, Intermediate, Advanced).

### 🟡 Pillar C: Psychometric Validation (System Usability Scale - SUS)
- Conducted item-level reliability diagnostics using **Cronbach’s Alpha ($\alpha$)**.
- Benchmarked SUS scores against industry standard percentiles and grading curves (`sus_market_benchmarking.png`).

### 🔴 Pillar D: Exploratory Factor Analysis (EFA) & Dimensionality Reduction
- Validated sampling adequacy via **Kaiser-Meyer-Olkin (KMO)** test and **Bartlett’s Test of Sphericity**.
- Extracted latent UX dimensions using Scree Plot diagnostics (`scree_plot_diagnostic.png`) and rotated factor loadings (`efa_diagnostic_dashboard.png`).

---

## 📈 Visual Asset Index

| Asset Name | Description |
| :--- | :--- |
| `ux_scorecard.png` | C-Suite Executive Summary UX Scorecard |
| `feature_dashboard.png` | Multi-panel behavioral distribution analysis |
| `reliability_sus_diagnostic.png` | Chronbach Alpha item-rest correlation breakdown |
| `scree_plot_diagnostic.png` | Eigenvalue extraction curve for construct validity |
| `efa_diagnostic_dashboard.png` | Latent factor structure & item loading heatmaps |
| `sus_market_benchmarking.png` | SUS score vs Global Industry Benchmarks |

---

## 🚀 How to Run the Pipeline

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/Rizky-Septiani/quant-uxr-portfolio.git](https://github.com/Rizky-Septiani/quant-uxr-portfolio.git)
   cd quant-uxr-portfolio
   Environment Setup & Dependencies:
2. Ensure Python 3.10+ is installed along with the required libraries:
pip install numpy pandas matplotlib seaborn scipy factor_analyzer
3. Execute the Notebook:
Open and run all cells in ux_behavioral_metrics_complete.ipynb using Jupyter Notebook or Google Colab.
## 👤 Author & Contact
- **Rizky Septiani** — Quantitative UX Researcher & Behavioral Data Analyst
- **LinkedIn**: [Rizky Septiani]((https://www.linkedin.com/in/rizky-septiani-psy))
- **GitHub**: [@Rizky-Septiani](https://github.com/Rizky-Septiani)
