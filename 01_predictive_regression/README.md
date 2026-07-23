# 📊 Stage 1: Predictive Regression Analysis — KreditKu Fintech UX Audit

## 📌 Executive Summary
This project delivers a data-driven UX audit for **KreditKu**, a fintech lending platform. Utilizing post-cleaning telemetry and user feedback data ($n = 200$), this quantitative study identifies structural friction in the onboarding flow and measures key drivers of transaction satisfaction.

---

## 🔑 Key Empirical Findings

* **Overall Satisfaction Gap:** Current satisfaction stands at **$M = 6.82$ ($SD = 0.97$)**, slightly below management’s internal KPI threshold of **7.00/10.00**.
* **Systemic Nature of UX Deficits:** No significant differences were observed across account tenure ($p = 0.633$) or device ecosystems ($p = 0.746$), confirming that satisfaction friction is a global workflow issue rather than an isolated edge case.
* **Primary Friction Vector:** Multiple Linear Regression isolated **Steps Count ($\beta = -0.537, r = -0.51$)** as the dominant negative driver. Every extra screen in the onboarding flow severely degrades satisfaction.
* **Core Satisfaction Anchors:** **Clarity Score ($\beta = +0.321$)** and **Trust Score ($\beta = +0.286$)** serve as the strongest positive anchors, highlighting the importance of micro-copy clarity and safety perception.

---

## 🛠️ Methodology & Tech Stack

* **Statistical Framework:** Data Cleaning & Anomaly Removal $\rightarrow$ Welch's T-Test $\rightarrow$ Pearson Correlation $\rightarrow$ OLS Multiple Linear Regression.
* **Tools:** Python (`pandas`, `numpy`, `statsmodels`, `scipy`, `seaborn`, `matplotlib`).

---

## 🚀 Strategic Recommendations & Action Items

| Priority | Action Item | Empirical Rationale |
| :--- | :--- | :--- |
| 🔴 **P1 High** | **Reduce Form Length / Steps:** Implement OCR auto-fill & step bundling. | Eliminates primary barrier ($\beta = -0.537$). |
| 🔴 **P1 High** | **Overhaul Micro-copy Clarity:** Simplify guidance during high-risk financial entries. | Leverages primary positive anchor ($\beta = +0.321$). |
| 🟡 **P2 Med** | **Enhance Security Badges:** Display licensing and security credentials prominently. | Capitalizes on trust vectors ($\beta = +0.286$). |

---

📂 **Project Artifacts:**
* 📓 `01_predictive_regression/kreditku_satisfaction.ipynb` — Complete Python analysis script & automated report.
* 📊 `kreditku_clean_dataset.csv` — Cleaned dataset ($n = 200$).
* 🖼️ `kreditku_executive_dashboard.png` — High-resolution visualization suite.
* 🎴 `kreditku_summary_card.png` — High-resolution executive summary card.
