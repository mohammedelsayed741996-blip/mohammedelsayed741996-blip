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
| **[Customer Churn: Classification, Risk Scoring & Segmentation](https://github.com/mohammedelsayed741996-blip/telco-customer-churn-ml)**<br/>Which telecom customers will leave, and who are they? | Python · scikit-learn (Pipeline, LogisticRegression, KMeans) · Colab | **ROC-AUC 0.84, 80 % churn recall**; top-risk decile churns at **71 % (2.55× average)**; 49 % churn in the riskiest segment | A leakage-free ML pipeline, calibrated probabilities (Brier score, lift table) that a retention team can act on, and segmentation profiled after the fact |
| **[Solar Energy Output Forecasting](https://github.com/mohammedelsayed741996-blip/solar-energy-forecasting)**<br/>Predicting PV plant output from weather data | Python · pandas · scikit-learn (LinearRegression, RandomForest) · Colab | 197,088 readings cleaned; **R² 0.86–0.87**; error grows **10–13 % on an unseen year**, which a random split hides | Honest validation: a chronological test year, explicit data cleaning, and diagnosing a forecast bias (panel ageing) instead of chasing a higher R² |

All five repositories run their tests in **GitHub Actions** on every push, the two newest open directly in **Google Colab**, and each README states where the data is simulated.

### Berlin data portfolio, by business domain

New projects go into one repo, **[berlin-data-portfolio](https://github.com/mohammedelsayed741996-blip/berlin-data-portfolio)**, each built around a real Berlin working-student or internship opening.

| Domain | Project | Headline result |
|---|---|---|
| Energy / Grid Technology | **[Procurement spend cube, data quality and commodity price forecasting](https://github.com/mohammedelsayed741996-blip/berlin-data-portfolio/tree/main/energy-grid-technology/procurement-spend-analytics)**<br/>Python · SQL · Power BI (DAX) · Excel · PowerPoint · Colab | Two ERP exports into one spend cube: 12 data quality rules with owner roles find **all 789 planted problems**, 167 supplier records become 115 golden records with **no false merges**; contract coverage, Pareto, supplier scorecard and Kraljic matrix; commodity forecasts tested against naive with **80% bands that held 80% of outcomes**; German management deck |
| Data & AI Consulting / Generative AI | **[Agentic lakehouse reference architecture](https://github.com/mohammedelsayed741996-blip/berlin-data-portfolio/tree/main/b2b-saas-data-platforms/agentic-lakehouse-reference-architecture)**<br/>Python · SQL · Terraform · AWS · Amazon Bedrock · Docker | A Finance assistant over a medallion lakehouse where access control lives in the tools, not the prompt: semantic layer with row-level security, approval queue with four-eyes, traces; **42 red-team runs, 0 leaks, 0 unauthorised actions**, enforced as a CI gate; Terraform, six ADRs and a delivery plan |
| HR Tech / Generative AI | **[HR policy assistant: RAG with citations and access control](https://github.com/mohammedelsayed741996-blip/berlin-data-portfolio/tree/main/hr-tech/hr-policy-rag-assistant)**<br/>Python · TypeScript · Docker · PostgreSQL · Kubernetes · CI/CD | Answers HR questions from 13 fictional policies with cited sections, declines out-of-scope questions (100% on held-out set) and **never leaks restricted documents** (0 leaks, enforced in CI); PII redaction, optional LLM with citation checks, container smoke test in CI |
| Academic Research / Behavioural Science | **[Intertemporal choice: discount functions, heuristics or ML?](https://github.com/mohammedelsayed741996-blip/berlin-data-portfolio/tree/main/academic-research/time-preference-choice-models)**<br/>Python · R · SciPy · scikit-learn · NLP · Colab | Simulated 400-person experiment: four choice models vs gradient boosting by out-of-sample **completeness** (ML 84%, ITCH 63%, **79% with empirical-Bayes shrinkage**); a date-framing nudge lowers discounting (Δlog k −0.82, 95% CI −1.02 to −0.62); NLP pilot, literature review, 10-page paper draft, base-R replication in CI |
| Mobility & Transport | **[Bus network: validation, demand and offer planning](https://github.com/mohammedelsayed741996-blip/berlin-data-portfolio/tree/main/mobility/bus-network-demand-planning)**<br/>Python · SQL · NetworkX · MILP · Excel · Colab | Eight checks across four planning systems find **all 6 planted data problems**, including a partner running 49-seat buses on a line sold with 79 seats; a forecast that corrects for sold-out buses (WAPE 4.5% vs 15.8% naive); a winter plan with **+5.0% contribution on 5.6% fewer bus-hours** and the same passengers |
| FinTech / Brokerage | **[AML monitoring oversight and MI](https://github.com/mohammedelsayed741996-blip/berlin-data-portfolio/tree/main/fintech-brokerage/aml-monitoring-oversight)**<br/>Python · SQL · Excel · Colab | Second-line checks on a broker's transaction monitoring found **all 9 planted control failures**, including a sanctions hit closed by mistake, 1,016 deposits the rules never saw and an unapproved threshold change; QA sampling with confidence intervals, KRIs, Excel MI pack and a board report with German summary |
| Consulting / Financial Services | **[Credit downgrade early warning from news](https://github.com/mohammedelsayed741996-blip/berlin-data-portfolio/tree/main/consulting-financial-services/credit-downgrade-early-warning)**<br/>Python · NLP · scikit-learn · Colab | Reads **66,000 English and German articles** on 360 rated issuers; with 15 reviews a month, **29% of alerts** were followed by a downgrade (base rate 3.9%), catching more downgrades than the negative-outlook rule with less than half the work; behavioural tests and a model card |
| AgriTech & Corporate Finance | **[Month-end close and rolling forecast](https://github.com/mohammedelsayed741996-blip/berlin-data-portfolio/tree/main/agritech-corporate-finance/month-end-close-forecast)**<br/>Python · SQL · Excel · Power BI · Colab | 12 close checks catch **all 11 planted errors** in an SAP-style ledger and pass a clean month; a backtest picks the forecast method per function and beats a run rate everywhere; 3+9 outlook EBIT EUR 29.9m vs EUR 35.8m budget, explained line by line |
| Data & AI Consulting / B2B SaaS | **[Incremental ELT platform for SaaS revenue data](https://github.com/mohammedelsayed741996-blip/berlin-data-portfolio/tree/main/b2b-saas-data-platforms/saas-revenue-elt)**<br/>Python · SQL · dbt · DuckDB · Colab | 93 daily runs with six planted incidents; warehouse MRR **equals the source to the cent on every day**; 2,852 data tests and 1,456 reconciliation checks, none failed |
| Climate Tech & Energy Finance | **[Solar loan credit risk and stress testing](https://github.com/mohammedelsayed741996-blip/berlin-data-portfolio/tree/main/climate-tech-energy-finance/solar-loan-credit-risk)**<br/>Python · scikit-learn · SQL · Colab | Scorecard **Gini 0.64 out of time**; cut-off at 79 % approval cuts the bad rate from 3.0 % to 1.3 %; a 20 % fall in power prices adds **47 % to expected credit loss** |

<details>
<summary><b>More projects</b></summary>

- **[E-commerce big data pipeline](https://github.com/mohammedelsayed741996-blip/big-data-processing-instacart-analytics)** (Hadoop HDFS, Hive, PySpark, Java MapReduce, scikit-learn) – the Instacart dataset processed with three distributed engines, plus a Random Forest reorder model
- **[Residential rent valuation](https://github.com/mohammedelsayed741996-blip/residential-rent-valuation)** (Python) – hold-out R² = 0.908, 6.2 % MAPE vs 16.0 % for a city-median baseline
- **[Hospital management database](https://github.com/mohammedelsayed741996-blip/Hospital-Management-System-SQL-Database-Architecture-)** (MySQL, 3NF, window functions) and **Tableau KPI dashboards** ([Tableau Public](https://public.tableau.com/shared/D3WWDK8RK))

</details>

---

## Toolbox

| Area | Tools |
|---|---|
| **Survey research & statistics** | Questionnaire design and routing, codebooks, CAWI trackers, data cleaning / QC, weighting (raking, trimming, Kish efficiency), significance testing, NPS, Shapley key-driver analysis, open-end coding |
| **Programming** | Python (pandas, NumPy, SciPy, scikit-learn, matplotlib, pytest) · R (`survey`, `openxlsx`) · SQL (CTEs, window functions, `QUALIFY`, `MERGE`) · Jupyter · Google Colab |
| **Data engineering & BI** | Snowflake · PostgreSQL · MySQL · Hadoop HDFS · Hive · PySpark · Power BI (DAX, semantic models) · Tableau · Power Query · Azure Data Factory |
| **Finance & cost domain** | Financial consolidation, P&L, cash flow, budget vs actual, working capital, cost control (EVM), Bills of Quantities, contractor claims, digital banking CX metrics |

## How I work

- **Reproducible:** fixed seeds, one-command pipelines, results written by code rather than typed by hand.
- **Verified:** automated tests, independent cross-checks (R vs pandas, Snowflake vs a pandas reference engine) and planted "known answers" in simulated data.
- **Transparent about AI:** I use AI tools for drafting and code review and keep a written log of what was checked and how.

---

📫 The best way to reach me is **[LinkedIn](https://linkedin.com/in/mohamed-abdelrasoul-b07002173)**.
