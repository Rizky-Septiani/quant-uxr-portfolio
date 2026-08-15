# 📊 Quantitative UX Research & Behavioral Data Science Portfolio

*Bridging Deep Behavioral Science, Psychometric Integrity, and Advanced SQL/Python Analytics to Drive Product Strategy.*

---

## 👋 About Me
I am a Licensed Clinical Psychologist who has successfully transitioned into Quantitative UX Research & Behavioral Data Science. My professional background spans academic, technical, and clinical domains—giving me a unique edge in understanding complex human behaviors, unconscious user processes, and emotional friction points. By marrying psychological rigor with advanced statistical computing in Python and SQL, I translate messy behavioral data into airtight, bulletproof business insights and feature prioritization models that executive leaders can confidently act upon.

**Core Competencies:** Python (Pandas, Statsmodels, SciPy, Seaborn) | Advanced Statistical Modeling (OLS Regression, ANOVA, Hypothesis Testing) | Psychometric Scaling (Likert, SUS) | Data Communication & Product Strategy.

---

## 📁 Key Projects

### 01 · KreditKu FinTech App: Predictive User Satisfaction & Feature Prioritization
`Python` `OLS Multiple Regression` `Statistical Diagnostic Testing` `Data Visualization`

An end-to-end quantitative UX evaluation of the KreditKu micro-lending mobile application ($N = 200$ respondents):
* **Descriptive Profiling:** Segmented and cross-analyzed core behaviors between new and existing users.
* **Statistical Diagnostics:** Audited regression assumptions including Multicollinearity (VIF checks) and Residual Normality to ensure maximum data integrity.
* **Predictive Modeling:** Built a Multiple Linear Regression (OLS) framework to isolate the true mathematical drivers of overall user satisfaction.
* **Key Finding:** Information clarity (`clarity_score`) emerged as the single most powerful driver of user satisfaction ($\beta = +0.321, p < 0.001$), completely outperforming physical system efficiency metrics. The final optimized model successfully accounts for **54.7% (Adjusted R-Squared)** of the total variance in user satisfaction.
* **Strategic Recommendation:** Prioritize immediate UX simplification of terms and credit transparency over micro-level page optimization to maximize user retention.

➔ [View Full Python Notebook & Diagnostics](./01_predictive_regression/)

---

### 02. Advanced UX Metrics & Psychometric Validation Pipeline
**Ecosystem:** TanamSaham + InvestPintar | **Tools:** `Python` `Psychometrics` `Factor Analysis (EFA)` `Survey Weighting`

* **Methodological Rigor:** Validated an 8-item user trust scale using Classical Test Theory (**Cronbach’s Alpha**, Item-Total Correlation) and **Exploratory Factor Analysis (EFA)** with Varimax rotation to expose latent user dimensions.
* **Bias Mitigation & Inferential Analytics:** Applied **post-stratification survey weighting** across 500+ respondents to correct sampling bias, combined with **Bootstrap Resampling (1,000 iterations)** for NPS confidence intervals ($95\%$ CI) and **Chi-Square/Cramer’s V** tests.
* **Executive Impact:** Delivered standard metrics (NPS, CSAT, CES, SUS) mapped against global benchmarks, item-level usability diagnostics, and a C-suite ready 2x2 Feature Priority Matrix.

➔ [View Full Stage 2 Diagnostics & Notebook](./02_advanced_metrics/)

---

### 03 · GajiKu Q1 2024: End-to-End Behavioral Analytics & Growth Report

Tools: SQL (SQLite) | Python (Pandas, Matplotlib) | Looker Studio Pipeline

Behavioral Diagnostics: Constructed multi-step transactional conversion funnels, D1/D7/D30 cohort retention matrices, and session exit event taxonomy (isolating `help_open` as a major dead-end friction point).

Advanced SQL Engineering: Developed ANSI SQL window function trendlines (`LAG()`, 30-day moving averages, cumulative revenue aggregation) and designed an enterprise-grade multi-layer CTE composite User Health Scoring engine (0–100 scale).

Executive Impact & Data Pipeline: Uncovered a 55% drop-off rate between app open and transfer initiation, validated higher long-term retention among Premium subscribers, and built automated CSV data pipelines for executive Looker Studio dashboarding.

➔ [View Full Stage 3 SQL Analytics Notebook & BI Pipeline](./03_behavioral_sql)

---

### 04 · [Stage 4 — Coming Soon]

---

## 🛠️ Data Science & UX Research Tech Stack

| Category | Tools & Libraries |
|----------|-------------------|
| **Programming Languages** | Python, SQL (SQLite, ANSI SQL, PostgreSQL / BigQuery) |
| **Statistical Computations** | `statsmodels`, `scipy.stats`, `numpy`, `scikit-learn` |
| **Data Manipulation** | `pandas` |
| **Data Visualization & BI** | `matplotlib`, `seaborn` (Custom Executive Dashboards), Google Looker Studio |
| **Advanced SQL Analytics** | Window Functions (`LAG()`, Moving Averages, Running Totals), Multi-Layer CTEs, Funnel & Cohort Analytics |
| **UX & Psychometric Metrics** | Likert Scaling, System Usability Scale (SUS), HEART Framework, Exploratory Factor Analysis (EFA) |
| **Environments** | Google Colab, Jupyter Notebooks, GitHub |

---
## 🚀 How to Run the Pipeline

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/Rizky-Septiani/quant-uxr-portfolio.git](https://github.com/Rizky-Septiani/quant-uxr-portfolio.git)
   cd quant-uxr-portfolio
2. Environment Setup & Dependencies:
Ensure Python 3.10+ is installed along with the required libraries:
pip install numpy pandas matplotlib seaborn scipy factor_analyzer
3. Execute the Notebook:
Open and run all cells in stage 1 & 2 using Jupyter Notebook or Google Colab.

*This portfolio serves as a live testament to continuous learning and empirical rigor. Updated regularly.*  
*Open for global opportunities, technical collaborations, and research discussions.*

---

## 👤 Author & Contact
- **Rizky Septiani** — Quantitative UX Researcher | Behavioral Data Scientist | Product Analytics Specialist
- 📧 **Email:** [rizky.septiani91@gmail.com]
- **LinkedIn**: [Rizky Septiani](https://www.linkedin.com/in/rizky-septiani-psy)
- **GitHub**: [@Rizky-Septiani](https://github.com/Rizky-Septiani)
