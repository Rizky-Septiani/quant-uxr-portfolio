# 02 · Advanced UX Metrics & Psychometric Validation Pipeline

**Product Ecosystem:** TanamSaham + InvestPintar  
`Python` `Survey Engineering` `Psychometrics` `Scale Validation` `Statistical Inference` `Exploratory Factor Analysis`

---

## 📌 Executive Overview
This repository section details an end-to-end quantitative research and behavioral analytics pipeline bridging raw survey telemetry with rigorous psychometric validation. Designed to elevate standard UXR data into executive-level product strategy, this pipeline evaluates usability, sentiment, and core retention drivers across 500+ respondents using advanced statistical inference (**Bootstrap 95% CI**, **Cronbach’s Alpha**, **Post-Stratification Weighting**, and **Exploratory Factor Analysis**).

---

## 🎯 Strategic Research Objectives & Methodology

### 1. Unified UX Metric Baselines & De-biasing
Constructed a unified quantitative tracking framework using standard metrics (**NPS**, **CSAT**, **CES**, and **SUS**) mapped against target enterprise benchmarks. Audited survey instruments for cognitive biases and implemented post-stratification survey weighting to adjust for segment over/under-representation.

### 2. Psychometric Scale Validation
Executed rigorous structural validation on an 8-item Trust Scale using classical test theory (**Cronbach's Alpha**, **Item-Total Correlation**) and **Exploratory Factor Analysis (EFA)** with Varimax orthogonal rotation to expose latent user trust dimensions.

### 3. Inferential Persona & Segment Analytics
Applied **Bootstrap Resampling (1,000 iterations)** to calculate robust 95% Confidence Intervals for system-wide NPS, mitigating small-sample variance. Deployed **Chi-Square Tests of Independence** and **Cramer's V** to statistically isolate satisfaction deltas across demographic cohorts.

### 4. Executive Strategy & Prioritization
Synthesized diagnostic survey data into a C-suite ready **2x2 Feature Priority Matrix** and an **Executive UX Scorecard** to translate complex psychometric outputs into actionable product roadmap decisions.

---

## 📊 Key Performance Indicator (KPI) Summary

| Metric Framework | Empirical Value | Target Benchmark | Status / Health Alert |
| :--- | :---: | :---: | :---: |
| **Net Promoter Score (NPS)** | *Calculated via Bootstrap* | $\ge +30.0$ | 🟢 On Track |
| **Customer Satisfaction (CSAT %)** | *Weighted Aggregate* | $\ge 75.0\%$ | 🟢 On Track |
| **System Usability Scale (SUS)** | *Normalized Score* | $\ge 68.0$ | 🟢 On Track |
| **Trust Scale Reliability ($\alpha$)** | $> 0.80$ | $> 0.80$ | ✅ Validated |

---

## 📁 Repository Architecture & Visual Artifacts

* 📓 `ux_behavioral_metrics_complete.ipynb` — Cumulative production master notebook containing end-to-end code execution, weighting algorithms, and EFA modeling.
* 🖼️ `ux_scorecard.png` — Consolidated, C-suite ready executive dashboard summary with dynamic health status alerts.
* 🖼️ `sus_market_benchmarking.png` — Strategic visualization mapping product usability against international industry percentiles and grade curves.
* 🖼️ `sus_item_level_diagnostics.png` — Granular item-level SUS breakdown identifying specific usability friction points across positive vs. negative prompt items.
* 🖼️ `reliability_sus_diagnostic.png` — Psychometric visualization summarizing scale item-correlations, discrimination indices, and internal consistency ($\alpha$).
* 🖼️ `scree_plot_diagnostic.png` — Eigenvalue scree plot diagnostic used to mathematically determine optimal factor retention for EFA.
* 🖼️ `efa_diagnostic_dashboard.png` — Factor structure matrix charting latent construct dimensions and cross-loadings of user trust.
* 🖼️ `feature_dashboard.png` — Quantitative prioritization matrix charting user satisfaction vs. impact across key product features.

---
*Part of the Quantitative UX Research Portfolio.*
