# 02 · Advanced UX Metrics & Psychometric Validation Pipeline

`Python` `Exploratory Factor Analysis (EFA)` `Cronbach's Alpha` `Bootstrap Resampling` `SUS & NPS`

---

## 📌 Executive Overview
This repository section details an end-to-end quantitative research and behavioral analytics pipeline bridging raw telemetry/user logs with rigorous psychometric validation. Designed to elevate standard UXR data into executive-level product strategy, this pipeline evaluates usability, sentiment, and core retention drivers through rigorous statistical inference (**Bootstrap 95% CI**, **One-Way ANOVA**, and **Exploratory Factor Analysis**).

---

## 🎯 Analytical Pillars & Methodology

### Pillar A: Behavioral Diagnostics & User Engagement
* **Methodology:** Aggregated task completion rates, error frequencies, and engagement duration across distinct user cohorts.
* **Key Visual:** `feature_dashboard.png` — Summarizes user interaction patterns and task-level efficiency metrics.

### Pillar B: Inferential NPS & Persona Analysis
* **Methodology:** Executed **Bootstrap Resampling (1,000 iterations)** to calculate robust 95% Confidence Intervals for system-wide Net Promoter Score (NPS), mitigating small-sample variance. Evaluated NPS variance across user personas using **One-Way ANOVA**.
* **Key Finding:** Identified statistically significant variance in promoter rates across cohorts, pinpointing specific power-user segments driving organic growth.

### Pillar C: Psychometric Scale Validation (System Usability Scale - SUS)
* **Methodology:** Validated internal consistency and item-level reliability via **Cronbach’s Alpha ($\alpha$)**. Benchmarked calculated SUS composite scores against normalized industry percentiles.
* **Key Visual:** `sus_market_benchmarking.png` — Visualizes calculated SUS score against global usability standards and grade curves.

### Pillar D: Latent Structure Extraction (Exploratory Factor Analysis - EFA)
* **Methodology:** Assessed sampling adequacy using **Kaiser-Meyer-Olkin (KMO > 0.7)** and **Bartlett’s Test of Sphericity ($p < 0.05$)**. Applied Principal Axis Factoring to extract underlying construct dimensions from multivariate Likert data.
* **Key Visuals:** 
  * `scree_plot_diagnostic.png` — Visualizes eigenvalues and variance explained for optimal factor retention.
  * `efa_diagnostic_dashboard.png` — Comprehensive dashboard illustrating factor loadings and construct cross-loadings.

---

## 📁 Included Assets & Deliverables

* 📓 **Master Notebook:** Stage 2 Python pipeline (`ux_behavioral_metrics_complete.ipynb`) containing full data processing, psychometric functions, and statistical modeling.
* 📊 **Executive Visuals:** High-resolution diagnostic charts (`feature_dashboard.png`, `sus_market_benchmarking.png`, `scree_plot_diagnostic.png`, `efa_diagnostic_dashboard.png`).

---

*Part of the Quantitative UX Research Portfolio.*
