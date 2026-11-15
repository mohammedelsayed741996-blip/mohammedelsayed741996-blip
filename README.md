# Hi, I'm Mohamed Abdelrasoul 👋

### Data Analyst · MSc Data Analytics student at BSBI Berlin

I turn messy quantitative data into clear, decision-ready findings, from survey research to cost and financial data.
Before data analytics I spent 3+ years as a **Technical Office Engineer (quantity surveying and cost estimation)** in Egypt,
where I reconciled **40+ Bills of Quantities and payment certificates worth €15M+** line by line and resolved 25+ contractor claims.
That background shapes how I work: every number traced to its source, every analysis reproducible and checked by automated tests.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed%20Abdelrasoul-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/mohamed-abdelrasoul-b07002173)
[![Tableau Public](https://img.shields.io/badge/Tableau%20Public-Dashboards-E97627?logo=tableau&logoColor=white)](https://public.tableau.com/shared/D3WWDK8RK)
![Location](https://img.shields.io/badge/Based%20in-Berlin%2C%20Germany-555)

- 🎓 **MSc Data Analytics**, Berlin School of Business and Innovation (UCA-accredited), Oct 2025 – Jun 2027
- 🏗️ **BSc Civil Engineering**, The Canadian International College, Cairo (2021)
- 💼 **Open to** working-student roles (20 h/week) now, and full-time roles from July 2027
- 🎯 **Focus:** quantitative market research, data analytics, financial services / fintech, cost and financial data analysis
- 🌍 **Languages:** Arabic (native), English (professional, IELTS), German (B1, in progress)

---

## Featured projects

| Project | Tech stack | Headline result | What it proves to a recruiter |
|---|---|---|---|
| **[Digital Bank CX Tracker](https://github.com/mohammedelsayed741996-blip/mosaik-cx-tracker)**<br/>4-wave CAWI tracking study for a (fictional) German digital bank | Python (pandas, SciPy, pytest) · R (`survey`) · Destatis data · PPTX | Weighted Shapley R² = 0.33: **card fees drive 40 %** and **app ease 28 %** of explained NPS variance; QC recall and precision 1.000 | The full market-research workflow: questionnaire and codebook, data cleaning and QC, raking to official population margins, significance testing on effective bases, key-driver analysis and a client-ready deck |
| **[Construction Cost Overrun Early-Warning](https://github.com/mohammedelsayed741996-blip/construction-cost-overrun-risk)**<br/>Flags projects that will overrun their budget by >10 % | Python (scikit-learn) · SQL (CTEs, window functions) · Power BI (DAX) | At **30 % of the schedule: 87 % recall, 93 % precision, ROC-AUC 0.96** vs 66 % recall for the standard EVM rule | Predictive modelling without leakage, an honest baseline, a 650-project cost-control data mart, and domain knowledge from real quantity-surveying work |
| **[Pharma Group Financial Consolidation](https://github.com/mohammedelsayed741996-blip/pharma-group-consolidation-snowflake-final)**<br/>IFRS consolidation of a (fictional) 12-entity group | Snowflake · SQL (QUALIFY, MERGE, streams, tasks) · Python · Power BI | **12 entities, 8 currencies, 36 monthly closes (~98,000 TB rows)**; all 12 planted data errors caught; 86 tests (67 offline in CI + 19 Snowflake) | Data engineering for finance: layered ELT, IAS 21 translation, intercompany eliminations, a 12-rule close-control framework and reconciliation against an independent reference engine |

All three repositories run their tests in **GitHub Actions** on every push, and each README states where the data is simulated.

<details>
<summary><b>More projects</b></summary>

- **E-commerce big data pipeline** (Hadoop HDFS, Hive, PySpark, Java MapReduce, scikit-learn) – the Instacart dataset processed with three distributed engines, plus a Random Forest reorder model
- **Residential rent valuation** (Python) – hold-out R² = 0.908, 6.2 % MAPE vs 16.0 % for a city-median baseline
- **Solar energy forecasting** (Python, Random Forest) – R² = 0.9139
- **Hospital management database** (MySQL, 3NF, window functions) and **Tableau KPI dashboards** ([Tableau Public](https://public.tableau.com/shared/D3WWDK8RK))

</details>

---

## Toolbox

| Area | Tools |
|---|---|
| **Survey research & statistics** | Questionnaire design and routing, codebooks, CAWI trackers, data cleaning / QC, weighting (raking, trimming, Kish efficiency), significance testing, NPS, Shapley key-driver analysis, open-end coding |
| **Programming** | Python (pandas, NumPy, SciPy, scikit-learn, matplotlib, pytest) · R (`survey`, `openxlsx`) · SQL (CTEs, window functions, `QUALIFY`, `MERGE`) · Jupyter |
| **Data engineering & BI** | Snowflake · PostgreSQL · MySQL · Hadoop HDFS · Hive · PySpark · Power BI (DAX, semantic models) · Tableau · Power Query · Azure Data Factory |
| **Finance & cost domain** | Financial consolidation, P&L, cash flow, budget vs actual, working capital, cost control (EVM), Bills of Quantities, contractor claims, digital banking CX metrics |

## How I work

- **Reproducible:** fixed seeds, one-command pipelines, results written by code rather than typed by hand.
- **Verified:** automated tests, independent cross-checks (R vs pandas, Snowflake vs a pandas reference engine) and planted "known answers" in simulated data.
- **Transparent about AI:** I use AI tools for drafting and code review and keep a written log of what was checked and how.

---

📫 The best way to reach me is **[LinkedIn](https://linkedin.com/in/mohamed-abdelrasoul-b07002173)**.
