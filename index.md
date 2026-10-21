<style>
.lang-toggle-wrap {
  display: flex;
  justify-content: flex-end;
  margin: 0 0 1rem 0;
}
.lang-toggle-btn {
  background: #0A0E14;
  color: #00E9D8;
  border: 2px solid #00E9D8;
  border-radius: 999px;
  padding: 0.5rem 1.1rem;
  font-weight: 700;
  font-size: 0.95rem;
  cursor: pointer;
  transition: background 0.15s ease, color 0.15s ease;
}
.lang-toggle-btn:hover {
  background: #00E9D8;
  color: #0A0E14;
}
.i18n-es-block, .i18n-es-inline { display: none; }
.lang-es .i18n-en-block, .lang-es .i18n-en-inline { display: none; }
.lang-es .i18n-es-block { display: block; }
.lang-es .i18n-es-inline { display: inline; }
</style>

<div class="lang-toggle-wrap">
<button id="langToggleBtn" class="lang-toggle-btn" onclick="toggleLanguage()" type="button">🇲🇽 Ver en Español</button>
</div>

# Max Santana
### <span class="i18n-en-inline">Data Analyst, Business Intelligence & Strategic Foresight Specialist</span><span class="i18n-es-inline">Analista de Datos, Especialista en Inteligencia de Negocios y Prospectiva Estratégica</span>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
---

<div class="i18n-en-block" markdown="1">

Hi there 👋, welcome to my portfolio

### 👨‍💻 A brief about me

* 📊 I use **rigorous data analytics** and **strategic intelligence** to turn complex, messy data into actionable business intelligence 📈 and long-term strategic decisions 🎯.
* 🌐 International relations graduate specialised in data analysis and strategic foresight 🔮 — transforming chaos to clarity ✨ and moving from uncertainty to opportunities 💡.
* 🚀 Currently advancing into **Data analysis** and **Applied AI** & **Data Science Solutions** 🤖.
* ⚡ Fun fact: I love Dachshunds; hoping to fulfil my dream to have one or two little wieners to join me while I code

### 📬 Connect & Collaborate

* 📧 **Email:** msantana.r@outlook.com
* 📱 **Phone:** +52 220 501 4335

### 🛠️ Technical Stack & Capabilities

* **Data Analytics & BI:** SQL, Python (`pandas`, `numpy`, `seaborn`, `matplotlib`), R (`tidyverse`, `ggplot2`), Power BI, Tableau, RStudio, Jupyter, Google Colab.

* **Core Technical Focus:** End-to-end data pipelines, cleaning raw datasets (100k+ records), data modeling, statistical forecasting, and dynamic dashboard design.

* **Business & Strategy:** Business question-oriented analysis, KPI framework design, executive communication (CFI consulting framework), decision support, and stakeholder alignment, Project Management, Conflict resolution

* **Strategic Foresight & Risk Analysis:** Strategy facilitation, scenario planning, horizon scanning, geopolitical risk analysis, actor mapping, long-term scenario building under uncertainty, HUMINT, and OSINT.

* **Social Science & Research:** Qualitative research (expert consultations, interviews, surveys, focus groups), public policy analysis, and political economy.

### 📁 Projects

<!-- ==========================================
1. Botones de Control (Pestañas)
Los estilos viven en /assets/css/style.scss
========================================== -->
<div class="filter-buttons">
<button class="filter-btn active" data-category="bi" onclick="filterProjects('bi')">Data Analysis / BI</button>
<button class="filter-btn" data-category="ds" onclick="filterProjects('ds')">Data Science</button>
<button class="filter-btn" data-category="foresight" onclick="filterProjects('foresight')">Foresight</button>
</div>

<!-- ==========================================
2. Contenedor: Data Analysis / BI
========================================== -->
<div class="project-wrapper bi active" markdown="1">

<img class="section-banner" src="https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy/main/banner-data-analysis.gif" alt="Animated banner: a scatter plot resolving into a regression line, bar chart and correlation metric">

<p class="section-intro">Work that starts from a business question and ends with a decision someone can defend. Cleaning, modeling, and dashboard design across customer behavior, territorial profitability, experimentation, and public-sector indicators.</p>

# Where to Concentrate Marketing Spend Across Six Markets — Cycling Retail · SQL

## 🎯 Objective
Determine where to allocate marketing spend for maximum ROI across territories by analyzing revenue, costs, and marketing investment.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/adventure-works-profitability-analysis-SQL)
[![Download Infographic PDF](https://img.shields.io/badge/📥_Download_Infographic_PDF-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/adventure-works-profitability-analysis-SQL/main/outputs/assets/Infographic_AdventureWorks_EN_v2.pdf)

<details markdown="1">

<summary markdown="1">
🔍 See full case study
</summary>

## 🔧 What I Did
1. **Schema Integration** — Joined 6 tables (sales, products, categories, territories, campaigns) using `clave_territorio` and `clave_producto`
2. **Data Cleaning** — Calculated `ingreso_total` and `costo_total` per order, handled NULLs with COALESCE
3. **KPI Calculation** — Aggregated revenue, gross profit, margin %, and ROI % by territory
4. **Validation** — Reconciled totals across joins, confirmed no data anomalies

## 🛠️ Technologies
SQL (JOINs, GROUP BY, aggregations, COALESCE, NULLIF) | Relational database with 6 tables | Data validation & QA

## 📊 Results

| Country | Revenue | Margin % | ROI % |
|---------|---------|----------|-------|
| 🇺🇸 USA | $3.35M | 43.4% | **75.8%** ⭐ |
| 🇦🇺 Australia | $2.53M | 41.7% | **49.2%** |
| 🇬🇧 UK | $1.19M | 42.7% | **22.1%** |
| 🇩🇪 Germany | $1.07M | 42.9% | **20.3%** |
| 🇫🇷 France | $0.92M | 42.9% | **17.9%** |
| 🇨🇦 Canada | $0.71M | 44.8% | **17.4%** |

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/adventure-works-profitability-analysis-SQL/main/outputs/assets/Revenue_by_Country_EN_whitebg.png" alt="Revenue per country" width="600">
</p>

## 💡 Key Insight
**USA leads with 75.8% ROI** on $1.92M spend. **Australia (49.2% ROI) punches above weight.** **UK underperforms** with only 22.1% ROI despite $2.3M investment. All margins healthy (41–45%), but ROI divergence driven by **marketing spend efficiency.**

**Recommendation:** Reallocate ~$500K from underperforming EU/CA markets to USA/Australia for 30–40% ROI improvement.

</details>

---

# Which Customers Drive Value in Messy Usage Data — Telecom · Python

## 🎯 Objective
Determine which customers drive the most value for a Latin American telecom by cleaning usage data, resolving data-quality issues, and segmenting customers by usage intensity and age.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/connectatel-customer-behavior-analysis)
[![Download Infographic PDF](https://img.shields.io/badge/📥_Download_Infographic_PDF-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/connectatel-customer-behavior-analysis/main/assets/Infographic_ConnectaTel_EN.pdf)

<details markdown="1">

<summary markdown="1">
🔍 See full case study
</summary>

## 🔧 What I Did
1. **Data Quality Diagnosis** — Detected sentinel values (`age` = -999, `city` = '?'), impossible dates (40 records dated 2026), and confirmed `duration`/`length` nulls were Missing At Random by usage `type`
2. **Cleaning** — Replaced sentinels, standardized dates, and preserved MAR nulls as meaningful signal rather than imputing them away
3. **Feature Engineering** — Aggregated 40,000 usage records into a per-user profile (messages, calls, call minutes)
4. **Outlier & Segmentation Analysis** — Used IQR and Z-scores to identify power users, then segmented all 4,000 customers by usage (`Low`/`Medium`/`High use`) and age

## 🛠️ Technologies
Python (pandas, numpy) | seaborn, matplotlib | IQR & Z-score outlier detection | Rule-based segmentation | Google Colab

## 📊 Results
`Medium use` is the largest usage segment; a consistent minority of 21–47 users per metric are high-volume "power users" retained as an upsell target rather than cleaned away as noise. `Basic plan` dominates every segment, including the heaviest users, pointing to under-monetized power users.

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/connectatel-customer-behavior-analysis/main/assets/usage_and_age_segments_by_plan.png" alt="Customers by usage segment and age segment, split by plan (Basico vs Premium)" width="700">
</p>

## 💡 Key Insight
**Outliers were the opportunity, not the noise.** The heaviest 21–47 users per usage metric were kept — not trimmed — since they represent ConnectaTel's clearest upsell segment.

**Recommendation:** Design an ultra-premium tier for these power users and target `Medium use` customers, already the largest segment, for migration incentives toward `High use`/`Premium`.

</details>

---

# Which Customer Behaviors Track Annual Revenue — E-Commerce · Python & SciPy

## 🎯 Objective
Identify which customer behaviors are most strongly associated with the annual revenue each of 15,000 e-commerce customers generates — matching the correlation coefficient to the variable type, and separating statistical significance from practical relevance.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/novaretail-revenue-correlation-analysis)
[![Download Infographic PDF](https://img.shields.io/badge/📥_Download_Infographic_PDF-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/novaretail-revenue-correlation-analysis/main/assets/Infographic_NovaRetail_EN.pdf)

<details markdown="1">

<summary markdown="1">
🔍 See full case study
</summary>

## 🔧 What I Did
1. **Variable Typing** — Classified 12 columns into numerical, binary and categorical families, since variable type is what determines which coefficient is valid
2. **Distribution Profiling** — Diagnosed right skew and long tails in `monthly_visits`, `monthly_purchases` and `targeted_ad_spend` — the reason the analysis does not rely on Pearson alone
3. **Coefficient Selection** — Spearman as the primary coefficient, with Pearson–Spearman differencing across all six key pairs to *measure* the outlier impact rather than assume it; point-biserial for the binary variables and Cramér's V for the categorical pair
4. **Significance vs Effect Size** — Reported every p-value alongside its effect size, and documented explicitly what a correlational design cannot claim

## 🛠️ Technologies
Python (pandas, numpy) | `scipy.stats` (`spearmanr`, `pointbiserialr`, `chi2_contingency`) | seaborn, matplotlib | Jupyter Notebook

## 📊 Results

| Relationship | Coefficient | Value | Read |
|---|---|---|---|
| Purchases ↔ Revenue | Spearman ρ | **0.968** ⭐ | Dominant signal |
| Visits ↔ Ad spend | Spearman ρ | 0.559 | Ads buy traffic |
| Visits ↔ Revenue | Spearman ρ | 0.321 | Secondary |
| Ad spend ↔ Revenue | Spearman ρ | 0.185 | Weak |
| Premium member ↔ Revenue | Point-biserial r | 0.093 (p ≈ 3e-30) | Significant, negligible |
| Device type × Region | Cramér's V | 0.012 (p = 0.60) | No association |

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/novaretail-revenue-correlation-analysis/main/assets/figure_5_secondary_drivers_regression.png" alt="Secondary drivers of annual revenue with regression lines" width="700">
</p>

## 💡 Key Insight
**Purchase frequency dominates (ρ = 0.97); premium membership does not move revenue.** With n = 15,000, an r of 0.09 clears any significance threshold while remaining commercially meaningless — the effect size, not the p-value, is the decision-relevant quantity. Churn shows no behavioral signature at all (every coefficient within ±0.01).

**Recommendation:** Optimize for conversion rather than traffic, judge campaigns on conversion-based return instead of spend or visits, and validate the purchases–revenue construction (ρ = 0.97 is a collinearity red flag) before using both in any predictive model.

</details>

---

# Which Homepage Version to Ship — E-Commerce A/B Test · Python & statsmodels

## 🎯 Objective
Decide which homepage version an e-commerce platform should implement, using a 40,000-user, 28-day experiment — with each comparison matched to a test its assumptions actually justify.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/landing-page-ab-test-analysis)
[![Download Infographic PDF](https://img.shields.io/badge/📥_Download_Infographic_PDF-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/landing-page-ab-test-analysis/main/assets/Infographic_LandingAB_EN.pdf)

<details markdown="1">

<summary markdown="1">
🔍 See full case study
</summary>

## 🔧 What I Did
1. **Validation & Balance Check** — 40,000 rows verified for nulls, duplicates and repeated user IDs; arms compared on region, device, channel and user type (largest gap: 0.8 pp)
2. **Assumption-Driven Test Selection** — Levene's test (p = 6.9e-08) ruled out equal variances, so **Welch's t-test** was used for spending instead of Student's
3. **Sensitivity Analysis** — IQR flagged 2.8% of buyers in each arm as high spenders; verified as genuine purchases and **kept**, then re-ran the test without them to confirm the tail was not creating the effect
4. **Proportions & Independence** — Two-proportion z-test for conversion; chi-square on contingency tables of counts for traffic source and user type, with expected-frequency validation
5. **Effect Sizes Everywhere** — Cohen's d and Cramér's V reported with every significant result, because at n = 40,000 significance is cheap

## 🛠️ Technologies
Python (pandas, numpy) | `scipy.stats` (`levene`, Welch `ttest_ind`, `chi2_contingency`) | `statsmodels` (`proportions_ztest`) | Cohen's d & Cramér's V | Jupyter Notebook

## 📊 Results

| Question | Test | Result | Effect size |
|---|---|---|---|
| Conversion rate | Two-proportion z | 15.96% vs 12.57% — **+3.38 pp (+26.9%)**, p = 3.8e-22 | The decisive effect ⭐ |
| Spending per converted user | Welch's t | 68.75 vs 61.09 — **+12.5%**, 95% CI [+6.08, +9.24] | Cohen's d = 0.25 (small) |
| Outlier sensitivity | IQR + re-run | Difference moves +7.66 → +7.61 | d rises to 0.30 |
| Conversion by traffic source | χ² | p = 0.034 (significant) | Cramér's V = 0.015 (negligible) |
| Conversion by user type | χ² | p = 0.474 | V = 0.004 — nothing |

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/landing-page-ab-test-analysis/main/assets/figure_2_conversion_rate_by_version.png" alt="Conversion rate by landing page version, A versus B" width="700">
</p>

## 💡 Key Insight
**Version B wins on both metrics — but only one of them should carry the decision.** The +26.9% relative conversion gain is worth considerably more than a +12.5% spending difference sitting at d = 0.25. Channel is *statistically* associated with conversion and *practically* irrelevant: V = 0.015 across a 1.2 pp spread.

**Recommendation:** Implement Landing Page B platform-wide; do not reallocate budget by channel or segment the roll-out by user type on this evidence; track refunds, support contacts and acquisition cost as guardrails the experiment cannot see.

</details>

---

# Where a Development Bank Should Fund Transit — 15 LatAm Cities · Python

## 🎯 Objective
Determine where a development bank should invest in transport infrastructure by analyzing how urban mobility (congestion, delay) relates to economic productivity (GDP per capita, unemployment) across 15 Latin American cities.

[![VIEW REPOSITORY FILES](https://img.shields.io/badge/VIEW%20REPOSITORY%20FILES-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity)
[![DOWNLOAD INFOGRAPHIC](https://img.shields.io/badge/DOWNLOAD%20INFOGRAPHIC-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity/blob/main/assets/Infographic_UrbanMobility_LatAm_HighRes_1.png)

<details markdown="1">

<summary markdown="1">
🔍 See full case study
</summary>

- **Data Integration** — Merged TomTom traffic records with OECD city economic indicators using city and year keys
- - **Data Cleaning** — Standardized column formats, parsed European numeric formatting, converted timestamps, filtered to 2024
- **Aggregation** — Grouped traffic records by city to calculate mean delay, congestion, and travel-time metrics per city-year
- **Analysis** — Computed a congestion-to-productivity ratio and ran correlation analysis across GDP, congestion, unemployment, and population

## 🛠️ Technologies
Python (pandas, numpy) | seaborn, matplotlib | Data wrangling & correlation analysis | Jupyter Notebook

## 📊 Results

| City | GDP/Capita | Ratio | Profile |
|---|---|---|---|
| 🇨🇴 Bogotá | $11,442 | 0.100 | Highest urgency ⭐ |
| 🇵🇪 Lima | $13,472 | 0.078 | Highest urgency ⭐ |
| 🇲🇽 Mexico City | $21,111 | 0.134 | High-scale congestion |
| 🇧🇷 São Paulo | $14,703 | 0.118 | High-scale congestion |
| 🇧🇷 Brasília | $16,251 | 0.006 | Efficient benchmark |
| 🇺🇾 Montevideo | $26,176 | 0.002 | Efficient benchmark |

![Jams delay and GDP per capita by city](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity/blob/main/assets/figure_1.png?raw=true)

## 💡 Key Insight
The correlation matrix suggests that traffic jam is driven mainly by population size (r = 0.88), not GDP per capita (r = 0.28) as initially expected. Bogotá and Lima combine high traffic friction with lower economic output — the clearest case for investment. Mexico City and São Paulo show the highest absolute congestion, but it's scale-driven, not inefficiency. Montevideo and Brasília stand out as efficient benchmarks.

![Correlation matrix](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity/blob/main/assets/figure_2.png?raw=true)

**Recommendation:** Prioritize transit investment in Bogotá and Lima for the highest expected economic return per dollar spent.

</details>

---

# Which Federal Institutions Carry Procurement Risk — Public Sector · R & Tableau

## 🎯 Objective
Identify corruption risk in public procurement across 260+ Mexican federal institutions by evaluating compliance with three principles: competition, transparency, and rule of law.

[![View Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/risk-corruption-index-IMCO)
[![Download Infographic](https://img.shields.io/badge/📥_Download_Infographic-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/risk-corruption-index-IMCO/main/assets/Infographic_IRC_IMCO_EN.jpg)

<details markdown="1">

<summary markdown="1">
🔍 See full case study
</summary>

## 🔧 What I Did
1. **Research Support** — Supported the IRC project in a research capacity, focused on interpreting procurement risk findings
2. **Results Presentation** — Helped translate analytical results into clear insights and presentation materials for public policy audiences
3. **Stakeholder Reporting** — Contributed to progress reporting to USAID as project funder

## 🛠️ Technologies
R (data analysis) | Tableau (interactive dashboard) | Public policy & governance research

## 📊 Results
[![View IRC Report](https://img.shields.io/badge/📄_View_IRC_Report-0A0E14?style=for-the-badge&logo=readthedocs&logoColor=00E9D8)](https://imco.org.mx/indice-de-riesgos-de-corrupcion/)
[![View Interactive Dashboard](https://img.shields.io/badge/📊_View_Interactive_Dashboard-FB2E89?style=for-the-badge&logo=tableau&logoColor=white)](https://imco.org.mx/riesgosdecorrupcion)

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/imco-irc-dashboard.png" alt="IRC dashboard — public procurement risk by institution" width="700">
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/risk-corruption-index-IMCO/main/assets/IRC_2020_High_Spending_Institutions.png" alt="IRC score 2020 — institutions with annual spend over MXN 3,000M (IMCO)" width="700">
</p>

## 💡 Key Insight
Between 2018 and 2020, corruption risk increased in 147 of 247 federal institutions (59%), driven by weak competition, low transparency, and non-compliance. The tool was adopted as a reference in Mexican public policy debates on transparency and institutional integrity.

</details>
</div>

<!-- ==========================================
3. Contenedor: Data Science
========================================== -->
<div class="project-wrapper ds" markdown="1">

<img class="section-banner" src="https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy/main/banner-data-science.gif" alt="Animated banner: a classifier searching for a decision boundary, with loss curve and confusion matrix">

<p class="section-intro">Where description gives way to modeling — estimating what is likely, what is uncertain, and how much the data can actually support. Methods chosen to fit the problem, validated against data they haven’t seen, and reported with their limits rather than without them.</p>

# Does Curve Structure Beat a Naive Forecast — Sovereign Debt · Python (PCA + VAR)

## 🎯 Objective
Test whether the common structure of Mexico's nominal yield curve — nine CETES and MBONOS maturities, 240 months — forecasts better than simply assuming rates stay where they are.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/forecasting-mexican-yield-curve)
[![Read the Notebook](https://img.shields.io/badge/📓_Read_the_Notebook-056B67?style=for-the-badge&logo=jupyter&logoColor=white)](https://maxsantana-data2strategy.github.io/forecasting-mexican-yield-curve/analisis_curva_banxico_notebook.html)
[![Download Infographic](https://img.shields.io/badge/📥_Download_Infographic-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/forecasting-mexican-yield-curve/main/assets/Infographic_YieldCurve_EN.jpg)

<details markdown="1">

<summary markdown="1">
🔍 See full case study
</summary>

## 🔧 What I Did
1. **Missingness Audit** — Pivoted 1,936 long-format records to a monthly matrix and found the gaps appear only on alignment: just **40 of 240 months** observe all nine maturities (30% missing at 30 years)
2. **Causal Forward-Fill** — Each gap takes the last *past* observation, never future information, applied before trimming the sample; a dedicated script compares both orderings and documents the difference
3. **PCA on Levels** — Estimated unstandardized so genuine differences in variability across maturities are preserved rather than normalized away
4. **Benchmark Selection** — Compared persistence, expanding historical mean and 12-month moving average, then measured both models against **the hardest of the three**
5. **Expanding-Window Evaluation** — Training ends Sept 2022; 45 origins at h = 3 and 36 at h = 12, with the PCA re-estimated at every origin so factors are never contaminated by unavailable data

## 🛠️ Technologies
Python (pandas, numpy) | `sklearn.decomposition.PCA` | `statsmodels.tsa.api.VAR` | Expanding-window out-of-sample evaluation (RMSE/MAE) | matplotlib, PIL | Jupyter Notebook

## 📊 Results

| Component | Variance explained | Interpretation |
|---|---|---|
| PC1 | **94.09%** | Level — same sign across all maturities |
| PC2 | 4.60% | Slope — short against long |
| PC3 | 0.69% | Curvature — middle against the extremes |
| **Three components** | **99.38%** | Reconstructs nine rates to **15.07 bp** |

| Horizon | Best model | RMSE | vs persistence |
|---|---|---|---|
| h = 3 | **Direct VAR(1)** | 0.5103 | −7.2% ⭐ |
| h = 12 | **PCA(3) + VAR(1)** | 1.1630 | −8.6% ⭐ |
| h = 12 | Direct VAR(1) | 1.2808 | +0.7% *worse* |

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/forecasting-mexican-yield-curve/main/assets/figure_model_rmse.png" alt="Out-of-sample RMSE by model and horizon against the persistence benchmark" width="700">
</p>

## 💡 Key Insight
**The curve is three numbers wide — but compression only pays at the long horizon.** Modelling changes directly wins at 3 months and *loses to the benchmark* at 12, where the factor representation delivers the biggest gap in the table. No single specification dominates, and persistence beats one of the two models at each horizon.

**Recommendation:** Select the model by horizon rather than seeking one winner. Results are labelled **exploratory**: forward-fill can manufacture zero monthly changes, no significance test between models was run, and the auction-availability treatment is the limitation most likely to change the ranking.

</details>

# Segmenting Fantasy Premier League Players for Dynamic Pricing — OnSports · Python (Unsupervised Learning)

## 🎯 Objective
Cluster English Premier League fantasy players on last season's performance (goals, assists, minutes, creativity, influence, threat, bonus, clean sheets) so a fantasy sports platform can set tiered player prices for the new season.

[![Access to full project description and check Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/fantasy-sports-clustering-analysis)
[![Read the Notebook](https://img.shields.io/badge/📓_Read_the_Notebook-056B67?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/maxsantana-data2strategy/fantasy-sports-clustering-analysis/blob/main/unsupervised-learning-fantasy-sports-clustering.ipynb)

🚧 **Status: Work in progress** — EDA, PCA, K-Means, and K-Medoids are complete; Hierarchical, GMM, and DBSCAN are still pending, as is the final algorithm comparison.

<details markdown="1">

<summary markdown="1">
🔍 See full case study
</summary>

## 🔧 What I Did (so far)
1. **EDA & Outlier Review** — Univariate and bivariate analysis of 10 performance stats across ~476 players, plus a deliberate decision to retain outliers (elite scorers) rather than treat them as anomalies
2. **Scaling + PCA** — Standardized the feature set and reduced it with PCA for clustering and visualization
3. **K-Means (k = 4)** — Selected k via the elbow method and silhouette score, then profiled each cluster's average stats
4. **K-Medoids (k = 4)** — Re-ran the same segmentation with real players as cluster centers instead of synthetic means, then compared cluster-by-cluster against K-Means

## 🛠️ Technologies
Python (pandas, numpy, scikit-learn, scikit-learn-extra) | PCA | K-Means | K-Medoids | matplotlib, seaborn | Jupyter Notebook

## 📊 Preliminary Result: K-Means vs. K-Medoids
Both algorithms converge on the same four tiers — elite offensive playmakers, durable defensive anchors, rotational/mid-tier regulars, and low-minute enablers — but K-Medoids anchors each one to a real player (e.g. Gylfi Sigurdsson, Ben Godfrey) instead of a statistical mean, which is more robust to outliers and easier to justify in a pricing conversation.

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/fantasy-sports-clustering-analysis/main/kmeans_vs_kmedoids.png" alt="K-Means vs K-Medoids cluster comparison: PCA scatter plots and feature-mean heatmaps for both algorithms" width="700">
</p>

## 💡 Key Insight (preliminary)
**The choice of algorithm barely moves the player tiers — it moves how defensible they are.** Since K-Medoids reaches the same four-tier story anchored to real players, it is the stronger candidate for a pricing decision stakeholders need to trust, pending the remaining methods (Hierarchical, GMM, DBSCAN) and a full silhouette-score comparison before a final recommendation.

</details>

</div>

<!-- ==========================================
4. Contenedor: Foresight
========================================== -->
<div class="project-wrapper foresight" markdown="1">

<img class="section-banner" src="https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy/main/banner-foresight.gif" alt="Animated banner: a three-dimensional futures cone branching into four named scenarios, with a wild card breaking outside the cone">

<p class="section-intro">Not forecasting. The goal is not to predict the future but to see its possibilities and shape it. Driver analysis, scenario building, and horizon scanning used to stress-test strategy under deep uncertainty.</p>

# Can AI Group Geopolitical Risk Signals Like an Expert — Mexico · Python NLP

![In Progress](https://img.shields.io/badge/Status-In_Progress-FB2E89?style=for-the-badge)

## 🎯 Objective
Identify and classify geopolitical risk signals for Mexico using AI-assisted NLP horizon scanning — transforming 43 raw signals into structured risk drivers for executive decision-making.

[![View Repository Files](https://img.shields.io/badge/📂_View_Repository_Files-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/horizon-scanning-geopolitical-risk-mx)

<details markdown="1">

<summary markdown="1">
🔍 See full case study
</summary>

## 🔧 What I Did
1. **Signal Collection** — Gathered 43 geopolitical signals from OSINT sources relevant to Mexico's strategic risk environment
2. **AI Classification** — Applied NLP-based zero-shot classification to group signals into thematic risk drivers
3. **Expert Validation** — Compared AI-generated groupings against expert-defined taxonomy; alignment reached ~78%
4. **Visual Analysis** — Mapped signals by impact/uncertainty and plotted drivers by risk vs. novelty scores

## 🛠️ Technologies
Python (pandas, transformers, zero-shot classification) | matplotlib, seaborn | OSINT research | Jupyter Notebook

## 📊 Results
43 signals → 7 drivers identified. AI classification aligned with expert grouping in ~78% of cases. Security-related drivers dominate; regulatory fragmentation and supply chain risk are secondary clusters.

![Impact/Uncertainty Matrix — 43 geopolitical signals plotted by impact and uncertainty](https://github.com/maxsantana-data2strategy/horizon-scanning-geopolitical-risk-mx/blob/main/figures/fig1_miu.png?raw=true)

![Risk vs. Novelty by Driver — highest-novelty drivers have lowest risk scores, revealing the novelty penalty](https://github.com/maxsantana-data2strategy/horizon-scanning-geopolitical-risk-mx/blob/main/figures/fig2_drivers.png?raw=true)

## 💡 Key Insight
**AI classification matched expert grouping in 78% of cases** — validating automated horizon scanning as a viable first-pass tool for geopolitical risk analysis. The "novelty penalty" pattern (highest-novelty drivers score lowest on risk) suggests that emerging threats are systematically underweighted in traditional risk frameworks.

**Implication:** Analysts and decision-makers should actively adjust for novelty bias when prioritizing risk responses.

</details>

# Four Futures for Humanitarian Aid to 2040 — IARAN · Scenarios & CLA

## 🎯 Objective
Explore four plausible futures for the global humanitarian aid system by 2040, translating foresight into strategy for organizations navigating funding cuts, politicization, and systemic uncertainty.

<details markdown="1">

<summary markdown="1">
🔍 See full case study
</summary>

## 🧭 Scenario Matrix

Four scenarios mapped across two axes: network cooperation vs. survival of the fittest, and multipolar blocs vs. empires and conflict.

<p align="center"><img src="https://github.com/user-attachments/assets/14ccf88d-eb73-421d-bc81-8c4fd0893e8d" alt="2040 Aid Scenarios Matrix — four future scenarios for global humanitarian aid" width="700"></p>

## 🔧 What I Did
1. **Trend Research** — Led documentary research on global trends (incl. AI) as lead analyst for LATAM
2. **Stakeholder Facilitation** — Facilitated consultations in Mexico and coordinated multiple stakeholders (donors, strategic partners, consulted organizations) within project governance
3. **Multi-Phase Delivery** — Contributed across the project's three phases: foundations (Causal Layered Analysis), scenarios, and transformation pathways

## 🛠️ Key Methodologies
Strategic Foresight | Horizon Scanning | Causal Layered Analysis (CLA) | Scenario Building | Stakeholder Alignment

## 📊 Results

| Metric | Value |
|---|---|
| Consultations | 50+ |
| Contributors | 877 |
| From the Global South | 77% |
| From local NGOs / CSOs | 44% |
| With lived crisis experience | ~40% |

<p align="center">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/7c0c2c4b-f214-4e3e-949c-77cd23ebf370/39050001_neamoscou+redux.jpg" alt="Future of Aid 2040: Navigating the Next Humanitarian Horizon" width="180">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/1760035233995-XO5JPU0R82RQKIQM0SJ3/IMG_0087_neamoscou.jpeg" alt="Unpacking the Aid System" width="180">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/1778567955102-E81RF7563TNEDZJ31XOV/1.JPG" alt="Pathways to Transformation — P2T Guide" width="180">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/1778567241580-LWEGEV0TLR4BWCYQCVRC/b01850018.jpg" alt="Pathways to Transformation — From Analysis to Action" width="180">
</p>

[![Scenarios Report](https://img.shields.io/badge/📄_Scenarios_Report-0A0E14?style=for-the-badge&logo=readthedocs&logoColor=00E9D8)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/future-of-aid/FutureOfAid2040_Scenarios_Report.pdf)
[![Unpacking the Aid System](https://img.shields.io/badge/📄_Unpacking_the_Aid_System-FB2E89?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/future-of-aid/FutureOfAid2040_UnpackingAidSystem_CLA.pdf)
[![Pathways to Transformation](https://img.shields.io/badge/📄_Pathways_to_Transformation-056B67?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/future-of-aid/FutureOfAid2040_P2T_AnalysisToAction.pdf)

## 💡 Key Insight
Synthesizing 877+ voices from 50+ organizations — most from the Global South — into four scenario frameworks and an organizational toolkit for humanitarian resilience under high uncertainty.

</details>

---

# Policy Framework for the Creative Economy Under Disruption — Nuevo León · Foresight

## 🎯 Objective
Build a foresight-based framework to turn uncertainty into opportunity for Nuevo León's creative and cultural industries, facing accelerated digital disruption, AI integration, and post-pandemic pressure.

[![View Project at CONL](https://img.shields.io/badge/🔗_View_Project_at_CONL-0A0E14?style=for-the-badge&logo=googlechrome&logoColor=00E9D8)](https://conl.mx/proyectos/tierra-incognita-insertar-a-las-industrias-creativas-en-cadenas-de-valor-complejas-en-nl/)
[![One Pager](https://img.shields.io/badge/📄_One_Pager-FB2E89?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/tierra-incognita/TierraIncognita_OnePager.pdf)
[![Full Report](https://img.shields.io/badge/📄_Full_Report-056B67?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/tierra-incognita/TierraIncognita_DocumentoCompleto.pdf)

<details markdown="1">

<summary markdown="1">
🔍 See full case study
</summary>

## 🔧 What I Did
1. **Workshop Design & Facilitation** — Designed and led strategic foresight workshops with creative-sector actors and key decision-makers
2. **Policy Translation** — Translated the foresight exercise into an actionable public policy framework (Logical Framework Approach)

## 🛠️ Key Methodologies
Horizon Scanning | Scenario Building | Strategic Facilitation | Logical Framework Approach

## 📊 Deliverables

Horizon scanning report for the creative economy | 4 future scenarios for Nuevo León's creative industries | Public policy framework (Logical Framework Approach) | Published strategic policy report

</details>

</div>

</div>

<div class="i18n-es-block" markdown="1">

¡Hola! 👋, bienvenido a mi portafolio

### 👨‍💻 Un poco sobre mí

* 📊 Utilizo **análisis de datos riguroso** e **inteligencia estratégica** para transformar datos complejos y desordenados en inteligencia de negocios 📈 y decisiones estratégicas de largo plazo 🎯.
* 🌐 Licenciado en Relaciones Internacionales, especializado en análisis de datos y prospectiva estratégica 🔮 — transformando el caos en claridad ✨ y la incertidumbre en oportunidades 💡.
* 🚀 Actualmente avanzando en **análisis de datos** y **soluciones de IA aplicada** y **ciencia de datos** 🤖.
* ⚡ Dato curioso: me encantan los perros salchicha (Dachshunds); espero algún día cumplir el sueño de tener uno o dos que me acompañen mientras programo.

### 📬 Contacto y Colaboración

* 📧 **Correo:** msantana.r@outlook.com
* 📱 **Teléfono:** +52 220 501 4335

### 🛠️ Stack Técnico y Capacidades

* **Análisis de Datos y BI:** SQL, Python (`pandas`, `numpy`, `seaborn`, `matplotlib`), R (`tidyverse`, `ggplot2`), Power BI, Tableau, RStudio, Jupyter, Google Colab.

* **Enfoque Técnico Principal:** Pipelines de datos de extremo a extremo, limpieza de datasets crudos (100k+ registros), modelado de datos, pronósticos estadísticos y diseño de dashboards dinámicos.

* **Negocio y Estrategia:** Análisis orientado a preguntas de negocio, diseño de marcos de KPI, comunicación ejecutiva (marco de consultoría CFI), apoyo a la toma de decisiones y alineación con stakeholders, gestión de proyectos, resolución de conflictos.

* **Prospectiva Estratégica y Análisis de Riesgo:** Facilitación estratégica, planeación de escenarios, horizon scanning, análisis de riesgo geopolítico, mapeo de actores, construcción de escenarios de largo plazo bajo incertidumbre, HUMINT y OSINT.

* **Ciencias Sociales e Investigación:** Investigación cualitativa (consultas a expertos, entrevistas, encuestas, grupos focales), análisis de política pública y economía política.

### 📁 Proyectos

<div class="filter-buttons">
<button class="filter-btn active" data-category="bi" onclick="filterProjects('bi')">Análisis de Datos / BI</button>
<button class="filter-btn" data-category="ds" onclick="filterProjects('ds')">Ciencia de Datos</button>
<button class="filter-btn" data-category="foresight" onclick="filterProjects('foresight')">Prospectiva</button>
</div>

<div class="project-wrapper bi active" markdown="1">

<img class="section-banner" src="https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy/main/banner-data-analysis.gif" alt="Banner animado: un diagrama de dispersión que se resuelve en una línea de regresión, una gráfica de barras y una métrica de correlación">

<p class="section-intro">Trabajo que parte de una pregunta de negocio y termina en una decisión que alguien pueda defender. Limpieza, modelado y diseño de dashboards aplicados a comportamiento de clientes, rentabilidad territorial, experimentación e indicadores del sector público.</p>

# Dónde Concentrar el Gasto en Marketing en Seis Mercados — Retail de Ciclismo · SQL

## 🎯 Objetivo
Determinar dónde asignar el gasto de marketing para maximizar el ROI entre territorios, analizando ingresos, costos e inversión en marketing.

[![Acceso a la descripción completa del proyecto y archivos del repositorio](https://img.shields.io/badge/📂_Ver_Archivos_del_Repositorio-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/adventure-works-profitability-analysis-SQL)
[![Descargar infografía en PDF](https://img.shields.io/badge/📥_Descargar_Infografia_PDF-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/adventure-works-profitability-analysis-SQL/main/outputs/assets/Infographic_AdventureWorks_EN_v2.pdf)

<details markdown="1">

<summary markdown="1">
🔍 Ver estudio de caso completo
</summary>

## 🔧 Qué Hice
1. **Integración de Esquema** — Uní 6 tablas (ventas, productos, categorías, territorios, campañas) usando `clave_territorio` y `clave_producto`
2. **Limpieza de Datos** — Calculé `ingreso_total` y `costo_total` por orden, manejando NULLs con COALESCE
3. **Cálculo de KPIs** — Agregué ingresos, utilidad bruta, % de margen y % de ROI por territorio
4. **Validación** — Reconcilié los totales entre los joins y confirmé que no había anomalías en los datos

## 🛠️ Tecnologías
SQL (JOINs, GROUP BY, agregaciones, COALESCE, NULLIF) | Base de datos relacional con 6 tablas | Validación y control de calidad de datos

## 📊 Resultados

| País | Ingresos | Margen % | ROI % |
|---------|---------|----------|-------|
| 🇺🇸 EE. UU. | $3.35M | 43.4% | **75.8%** ⭐ |
| 🇦🇺 Australia | $2.53M | 41.7% | **49.2%** |
| 🇬🇧 Reino Unido | $1.19M | 42.7% | **22.1%** |
| 🇩🇪 Alemania | $1.07M | 42.9% | **20.3%** |
| 🇫🇷 Francia | $0.92M | 42.9% | **17.9%** |
| 🇨🇦 Canadá | $0.71M | 44.8% | **17.4%** |

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/adventure-works-profitability-analysis-SQL/main/outputs/assets/Revenue_by_Country_EN_whitebg.png" alt="Ingresos por país" width="600">
</p>

## 💡 Insight Clave
**EE. UU. lidera con 75.8% de ROI** con un gasto de $1.92M. **Australia (49.2% de ROI) rinde por encima de su peso.** **El Reino Unido tiene bajo desempeño**, con solo 22.1% de ROI a pesar de una inversión de $2.3M. Todos los márgenes son saludables (41–45%), pero la divergencia en ROI está impulsada por la **eficiencia del gasto en marketing.**

**Recomendación:** Reasignar ~$500K de los mercados de bajo desempeño en la UE/Canadá hacia EE. UU./Australia, para una mejora de ROI de 30–40%.

</details>

---

# Qué Clientes Generan Más Valor en Datos de Uso Desordenados — Telecom · Python

## 🎯 Objetivo
Determinar qué clientes generan más valor para una telecom latinoamericana, limpiando datos de uso, resolviendo problemas de calidad de datos y segmentando clientes por intensidad de uso y edad.

[![Acceso a la descripción completa del proyecto y archivos del repositorio](https://img.shields.io/badge/📂_Ver_Archivos_del_Repositorio-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/connectatel-customer-behavior-analysis)
[![Descargar infografía en PDF](https://img.shields.io/badge/📥_Descargar_Infografia_PDF-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/connectatel-customer-behavior-analysis/main/assets/Infographic_ConnectaTel_EN.pdf)

<details markdown="1">

<summary markdown="1">
🔍 Ver estudio de caso completo
</summary>

## 🔧 Qué Hice
1. **Diagnóstico de Calidad de Datos** — Detecté valores centinela (`age` = -999, `city` = '?'), fechas imposibles (40 registros con fecha 2026), y confirmé que los nulos de `duration`/`length` eran Missing At Random según el `type` de uso
2. **Limpieza** — Sustituí los valores centinela, estandaricé fechas, y preservé los nulos MAR como señal significativa en lugar de imputarlos
3. **Ingeniería de Variables** — Agregué 40,000 registros de uso en un perfil por usuario (mensajes, llamadas, minutos de llamada)
4. **Análisis de Outliers y Segmentación** — Usé IQR y Z-scores para identificar usuarios de alto consumo, y segmenté a los 4,000 clientes por uso (`Low`/`Medium`/`High use`) y edad

## 🛠️ Tecnologías
Python (pandas, numpy) | seaborn, matplotlib | Detección de outliers con IQR y Z-score | Segmentación basada en reglas | Google Colab

## 📊 Resultados
`Medium use` es el segmento de uso más grande; una minoría constante de 21–47 usuarios por métrica son "power users" de alto volumen, que se conservaron como objetivo de upsell en lugar de limpiarse como ruido. `Basic plan` domina en todos los segmentos, incluso entre los usuarios más intensivos, lo que señala power users sub-monetizados.

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/connectatel-customer-behavior-analysis/main/assets/usage_and_age_segments_by_plan.png" alt="Clientes por segmento de uso y segmento de edad, divididos por plan (Básico vs Premium)" width="700">
</p>

## 💡 Insight Clave
**Los outliers fueron la oportunidad, no el ruido.** Los 21–47 usuarios más intensivos por métrica de uso se conservaron —no se recortaron— porque representan el segmento de upsell más claro de ConnectaTel.

**Recomendación:** Diseñar un nivel ultra-premium para estos power users y dirigir a los clientes de `Medium use`, ya el segmento más grande, hacia incentivos de migración a `High use`/Premium.

</details>

---

# Qué Comportamientos de Cliente se Relacionan con el Ingreso Anual — E-Commerce · Python & SciPy

## 🎯 Objetivo
Identificar qué comportamientos de cliente están más fuertemente asociados con el ingreso anual que genera cada uno de 15,000 clientes de e-commerce — emparejando el coeficiente de correlación correcto con el tipo de variable, y separando la significancia estadística de la relevancia práctica.

[![Acceso a la descripción completa del proyecto y archivos del repositorio](https://img.shields.io/badge/📂_Ver_Archivos_del_Repositorio-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/novaretail-revenue-correlation-analysis)
[![Descargar infografía en PDF](https://img.shields.io/badge/📥_Descargar_Infografia_PDF-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/novaretail-revenue-correlation-analysis/main/assets/Infographic_NovaRetail_EN.pdf)

<details markdown="1">

<summary markdown="1">
🔍 Ver estudio de caso completo
</summary>

## 🔧 Qué Hice
1. **Tipificación de Variables** — Clasifiqué 12 columnas en familias numéricas, binarias y categóricas, ya que el tipo de variable determina qué coeficiente es válido
2. **Perfilado de Distribuciones** — Diagnostiqué sesgo a la derecha y colas largas en `monthly_visits`, `monthly_purchases` y `targeted_ad_spend` — la razón por la que el análisis no se basa únicamente en Pearson
3. **Selección de Coeficiente** — Spearman como coeficiente principal, con diferenciación Pearson–Spearman en los seis pares clave para *medir* el impacto de los outliers en lugar de asumirlo; point-biserial para las variables binarias y V de Cramér para el par categórico
4. **Significancia vs. Tamaño del Efecto** — Reporté cada valor p junto con su tamaño de efecto, y documenté explícitamente lo que un diseño correlacional no puede afirmar

## 🛠️ Tecnologías
Python (pandas, numpy) | `scipy.stats` (`spearmanr`, `pointbiserialr`, `chi2_contingency`) | seaborn, matplotlib | Jupyter Notebook

## 📊 Resultados

| Relación | Coeficiente | Valor | Lectura |
|---|---|---|---|
| Compras ↔ Ingreso | Spearman ρ | **0.968** ⭐ | Señal dominante |
| Visitas ↔ Gasto en ads | Spearman ρ | 0.559 | Los ads compran tráfico |
| Visitas ↔ Ingreso | Spearman ρ | 0.321 | Secundaria |
| Gasto en ads ↔ Ingreso | Spearman ρ | 0.185 | Débil |
| Miembro premium ↔ Ingreso | Point-biserial r | 0.093 (p ≈ 3e-30) | Significativo, insignificante en magnitud |
| Tipo de dispositivo × Región | V de Cramér | 0.012 (p = 0.60) | Sin asociación |

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/novaretail-revenue-correlation-analysis/main/assets/figure_5_secondary_drivers_regression.png" alt="Factores secundarios del ingreso anual con líneas de regresión" width="700">
</p>

## 💡 Insight Clave
**La frecuencia de compra domina (ρ = 0.97); la membresía premium no mueve el ingreso.** Con n = 15,000, una r de 0.09 supera cualquier umbral de significancia sin dejar de ser comercialmente irrelevante — el tamaño del efecto, no el valor p, es la cantidad relevante para la decisión. El churn no muestra ninguna firma conductual (todos los coeficientes dentro de ±0.01).

**Recomendación:** Optimizar para conversión en lugar de tráfico, evaluar las campañas por retorno basado en conversión en vez de gasto o visitas, y validar la construcción compras–ingreso (ρ = 0.97 es una señal de alerta de colinealidad) antes de usar ambas variables en cualquier modelo predictivo.

</details>

---

# Qué Versión del Homepage Lanzar — Prueba A/B de E-Commerce · Python & statsmodels

## 🎯 Objetivo
Decidir qué versión de homepage debería implementar una plataforma de e-commerce, usando un experimento de 40,000 usuarios y 28 días — emparejando cada comparación con una prueba cuyos supuestos realmente se cumplen.

[![Acceso a la descripción completa del proyecto y archivos del repositorio](https://img.shields.io/badge/📂_Ver_Archivos_del_Repositorio-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/landing-page-ab-test-analysis)
[![Descargar infografía en PDF](https://img.shields.io/badge/📥_Descargar_Infografia_PDF-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/landing-page-ab-test-analysis/main/assets/Infographic_LandingAB_EN.pdf)

<details markdown="1">

<summary markdown="1">
🔍 Ver estudio de caso completo
</summary>

## 🔧 Qué Hice
1. **Validación y Balance** — Se verificaron 40,000 filas en busca de nulos, duplicados e IDs de usuario repetidos; se compararon los grupos por región, dispositivo, canal y tipo de usuario (mayor brecha: 0.8 pp)
2. **Selección de Prueba Basada en Supuestos** — La prueba de Levene (p = 6.9e-08) descartó varianzas iguales, por lo que se usó la **prueba t de Welch** para el gasto en lugar de la de Student
3. **Análisis de Sensibilidad** — El IQR marcó a 2.8% de los compradores en cada grupo como de alto gasto; se verificó que eran compras genuinas y **se conservaron**, y se volvió a correr la prueba sin ellos para confirmar que la cola no estaba generando el efecto
4. **Proporciones e Independencia** — Prueba z de dos proporciones para conversión; chi-cuadrada sobre tablas de contingencia de conteos para fuente de tráfico y tipo de usuario, con validación de frecuencias esperadas
5. **Tamaños de Efecto en Todo** — Se reportaron la d de Cohen y la V de Cramér junto con cada resultado significativo, porque con n = 40,000 la significancia es barata

## 🛠️ Tecnologías
Python (pandas, numpy) | `scipy.stats` (`levene`, `ttest_ind` de Welch, `chi2_contingency`) | `statsmodels` (`proportions_ztest`) | d de Cohen y V de Cramér | Jupyter Notebook

## 📊 Resultados

| Pregunta | Prueba | Resultado | Tamaño del efecto |
|---|---|---|---|
| Tasa de conversión | z de dos proporciones | 15.96% vs 12.57% — **+3.38 pp (+26.9%)**, p = 3.8e-22 | El efecto decisivo ⭐ |
| Gasto por usuario convertido | t de Welch | 68.75 vs 61.09 — **+12.5%**, IC 95% [+6.08, +9.24] | d de Cohen = 0.25 (pequeño) |
| Sensibilidad a outliers | IQR + re-ejecución | La diferencia pasa de +7.66 a +7.61 | d sube a 0.30 |
| Conversión por fuente de tráfico | χ² | p = 0.034 (significativo) | V de Cramér = 0.015 (insignificante) |
| Conversión por tipo de usuario | χ² | p = 0.474 | V = 0.004 — nada |

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/landing-page-ab-test-analysis/main/assets/figure_2_conversion_rate_by_version.png" alt="Tasa de conversión por versión de landing page, A versus B" width="700">
</p>

## 💡 Insight Clave
**La Versión B gana en ambas métricas — pero solo una de ellas debería decidir.** La ganancia relativa de conversión de +26.9% vale considerablemente más que una diferencia de gasto de +12.5% con una d de 0.25. El canal está *estadísticamente* asociado con la conversión y es *prácticamente* irrelevante: V = 0.015 en una dispersión de 1.2 pp.

**Recomendación:** Implementar la Landing Page B en toda la plataforma; no reasignar presupuesto por canal ni segmentar el despliegue por tipo de usuario con esta evidencia; monitorear reembolsos, contactos a soporte y costo de adquisición como salvaguardas que el experimento no puede ver.

</details>

---

# Dónde Debería Invertir un Banco de Desarrollo en Transporte — 15 Ciudades de LatAm · Python

## 🎯 Objetivo
Determinar dónde debería invertir un banco de desarrollo en infraestructura de transporte, analizando cómo se relaciona la movilidad urbana (congestión, demoras) con la productividad económica (PIB per cápita, desempleo) en 15 ciudades latinoamericanas.

[![VER ARCHIVOS DEL REPOSITORIO](https://img.shields.io/badge/VER%20ARCHIVOS%20DEL%20REPOSITORIO-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity)
[![DESCARGAR INFOGRAFIA](https://img.shields.io/badge/DESCARGAR%20INFOGRAFIA-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity/blob/main/assets/Infographic_UrbanMobility_LatAm_HighRes_1.png)

<details markdown="1">

<summary markdown="1">
🔍 Ver estudio de caso completo
</summary>

- **Integración de Datos** — Se combinaron registros de tráfico de TomTom con indicadores económicos urbanos de la OCDE usando claves de ciudad y año
- **Limpieza de Datos** — Se estandarizaron formatos de columna, se interpretó el formato numérico europeo, se convirtieron timestamps, y se filtró a 2024
- **Agregación** — Se agruparon los registros de tráfico por ciudad para calcular demora media, congestión y métricas de tiempo de viaje por ciudad-año
- **Análisis** — Se calculó una razón congestión-productividad y se corrió un análisis de correlación entre PIB, congestión, desempleo y población

## 🛠️ Tecnologías
Python (pandas, numpy) | seaborn, matplotlib | Limpieza de datos y análisis de correlación | Jupyter Notebook

## 📊 Resultados

| Ciudad | PIB/Cápita | Razón | Perfil |
|---|---|---|---|
| 🇨🇴 Bogotá | $11,442 | 0.100 | Mayor urgencia ⭐ |
| 🇵🇪 Lima | $13,472 | 0.078 | Mayor urgencia ⭐ |
| 🇲🇽 Ciudad de México | $21,111 | 0.134 | Congestión de gran escala |
| 🇧🇷 São Paulo | $14,703 | 0.118 | Congestión de gran escala |
| 🇧🇷 Brasilia | $16,251 | 0.006 | Referencia eficiente |
| 🇺🇾 Montevideo | $26,176 | 0.002 | Referencia eficiente |

![Demoras por tráfico y PIB per cápita por ciudad](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity/blob/main/assets/figure_1.png?raw=true)

## 💡 Insight Clave
La matriz de correlación sugiere que el tráfico está impulsado principalmente por el tamaño de la población (r = 0.88), no por el PIB per cápita (r = 0.28) como se esperaba inicialmente. Bogotá y Lima combinan alta fricción de tráfico con menor producción económica — el caso más claro para inversión. Ciudad de México y São Paulo muestran la congestión absoluta más alta, pero está impulsada por escala, no por ineficiencia. Montevideo y Brasilia destacan como referencias eficientes.

![Matriz de correlación](https://github.com/maxsantana-data2strategy/urbanmobility_economicproductivity/blob/main/assets/figure_2.png?raw=true)

**Recomendación:** Priorizar la inversión en transporte en Bogotá y Lima por el mayor retorno económico esperado por dólar invertido.

</details>

---

# Qué Instituciones Federales Cargan Mayor Riesgo de Contratación — Sector Público · R & Tableau

## 🎯 Objetivo
Identificar el riesgo de corrupción en la contratación pública entre más de 260 instituciones federales mexicanas, evaluando el cumplimiento de tres principios: competencia, transparencia y Estado de derecho.

[![Ver Archivos del Repositorio](https://img.shields.io/badge/📂_Ver_Archivos_del_Repositorio-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/risk-corruption-index-IMCO)
[![Descargar Infografía](https://img.shields.io/badge/📥_Descargar_Infografia-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/risk-corruption-index-IMCO/main/assets/Infographic_IRC_IMCO_EN.jpg)

<details markdown="1">

<summary markdown="1">
🔍 Ver estudio de caso completo
</summary>

## 🔧 Qué Hice
1. **Apoyo en Investigación** — Apoyé el proyecto IRC en capacidad de investigación, enfocado en interpretar los hallazgos de riesgo en contratación pública
2. **Presentación de Resultados** — Ayudé a traducir los resultados analíticos en insights claros y materiales de presentación para audiencias de política pública
3. **Reporte a Stakeholders** — Contribuí al reporte de avances a USAID como financiador del proyecto

## 🛠️ Tecnologías
R (análisis de datos) | Tableau (dashboard interactivo) | Investigación en política pública y gobernanza

## 📊 Resultados
[![Ver Reporte IRC](https://img.shields.io/badge/📄_Ver_Reporte_IRC-0A0E14?style=for-the-badge&logo=readthedocs&logoColor=00E9D8)](https://imco.org.mx/indice-de-riesgos-de-corrupcion/)
[![Ver Dashboard Interactivo](https://img.shields.io/badge/📊_Ver_Dashboard_Interactivo-FB2E89?style=for-the-badge&logo=tableau&logoColor=white)](https://imco.org.mx/riesgosdecorrupcion)

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/imco-irc-dashboard.png" alt="Dashboard IRC — riesgo de contratación pública por institución" width="700">
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/risk-corruption-index-IMCO/main/assets/IRC_2020_High_Spending_Institutions.png" alt="Puntaje IRC 2020 — instituciones con gasto anual superior a MXN 3,000M (IMCO)" width="700">
</p>

## 💡 Insight Clave
Entre 2018 y 2020, el riesgo de corrupción aumentó en 147 de 247 instituciones federales (59%), impulsado por competencia débil, baja transparencia e incumplimiento. La herramienta fue adoptada como referencia en los debates de política pública mexicana sobre transparencia e integridad institucional.

</details>
</div>

<div class="project-wrapper ds" markdown="1">

<img class="section-banner" src="https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy/main/banner-data-science.gif" alt="Banner animado: un clasificador buscando una frontera de decisión, con curva de pérdida y matriz de confusión">

<p class="section-intro">Donde la descripción da paso al modelado — estimando qué es probable, qué es incierto y cuánto pueden sostener realmente los datos. Métodos elegidos para ajustarse al problema, validados contra datos que no han visto, y reportados con sus límites en lugar de sin ellos.</p>

# ¿La Estructura de la Curva Supera a un Pronóstico Naive? — Deuda Soberana · Python (PCA + VAR)

## 🎯 Objetivo
Probar si la estructura común de la curva de rendimientos nominal de México — nueve plazos de CETES y MBONOS, 240 meses — pronostica mejor que simplemente asumir que las tasas se mantienen donde están.

[![Acceso a la descripción completa del proyecto y archivos del repositorio](https://img.shields.io/badge/📂_Ver_Archivos_del_Repositorio-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/forecasting-mexican-yield-curve)
[![Leer el Notebook](https://img.shields.io/badge/📓_Leer_el_Notebook-056B67?style=for-the-badge&logo=jupyter&logoColor=white)](https://maxsantana-data2strategy.github.io/forecasting-mexican-yield-curve/analisis_curva_banxico_notebook.html)
[![Descargar Infografía](https://img.shields.io/badge/📥_Descargar_Infografia-FB2E89?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/forecasting-mexican-yield-curve/main/assets/Infographic_YieldCurve_EN.jpg)

<details markdown="1">

<summary markdown="1">
🔍 Ver estudio de caso completo
</summary>

## 🔧 Qué Hice
1. **Auditoría de Datos Faltantes** — Transformé 1,936 registros en formato largo a una matriz mensual y encontré que los vacíos aparecen solo por alineación: únicamente **40 de 240 meses** observan los nueve plazos (30% faltante a 30 años)
2. **Relleno Causal Hacia Adelante** — Cada vacío toma la última observación *pasada*, nunca información futura, aplicado antes de recortar la muestra; un script dedicado compara ambos órdenes y documenta la diferencia
3. **PCA sobre Niveles** — Estimado sin estandarizar, para preservar diferencias genuinas de variabilidad entre plazos en lugar de normalizarlas
4. **Selección de Benchmark** — Se compararon persistencia, media histórica expansiva y promedio móvil de 12 meses, y ambos modelos se midieron contra **el más exigente de los tres**
5. **Evaluación con Ventana Expansiva** — El entrenamiento termina en septiembre de 2022; 45 orígenes en h = 3 y 36 en h = 12, con el PCA reestimado en cada origen para que los factores nunca se contaminen con datos no disponibles

## 🛠️ Tecnologías
Python (pandas, numpy) | `sklearn.decomposition.PCA` | `statsmodels.tsa.api.VAR` | Evaluación fuera de muestra con ventana expansiva (RMSE/MAE) | matplotlib, PIL | Jupyter Notebook

## 📊 Resultados

| Componente | Varianza explicada | Interpretación |
|---|---|---|
| CP1 | **94.09%** | Nivel — mismo signo en todos los plazos |
| CP2 | 4.60% | Pendiente — corto contra largo |
| CP3 | 0.69% | Curvatura — medio contra los extremos |
| **Tres componentes** | **99.38%** | Reconstruye nueve tasas con **15.07 pb** de error |

| Horizonte | Mejor modelo | RMSE | vs. persistencia |
|---|---|---|---|
| h = 3 | **VAR(1) directo** | 0.5103 | −7.2% ⭐ |
| h = 12 | **PCA(3) + VAR(1)** | 1.1630 | −8.6% ⭐ |
| h = 12 | VAR(1) directo | 1.2808 | +0.7% *peor* |

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/forecasting-mexican-yield-curve/main/assets/figure_model_rmse.png" alt="RMSE fuera de muestra por modelo y horizonte, contra el benchmark de persistencia" width="700">
</p>

## 💡 Insight Clave
**La curva mide solo tres números de ancho — pero la compresión solo paga en el horizonte largo.** Modelar los cambios directamente gana a 3 meses y *pierde contra el benchmark* a 12, donde la representación factorial entrega la mayor brecha de la tabla. Ninguna especificación domina por sí sola, y la persistencia vence a uno de los dos modelos en cada horizonte.

**Recomendación:** Elegir el modelo según el horizonte en lugar de buscar un único ganador. Los resultados se etiquetan como **exploratorios**: el relleno hacia adelante puede fabricar cambios mensuales de cero, no se corrió ninguna prueba de significancia entre modelos, y el tratamiento de disponibilidad de subastas es la limitación más probable de cambiar el ranking.

</details>

# Segmentando Jugadores de Fantasy Premier League para Precios Dinámicos — OnSports · Python (Aprendizaje No Supervisado)

## 🎯 Objetivo
Agrupar a los jugadores de fantasy de la Premier League inglesa según su desempeño de la temporada pasada (goles, asistencias, minutos, creatividad, influencia, amenaza, bonos, porterías en cero) para que una plataforma de deportes de fantasía pueda fijar precios escalonados por jugador para la nueva temporada.

[![Acceso a la descripción completa del proyecto y archivos del repositorio](https://img.shields.io/badge/📂_Ver_Archivos_del_Repositorio-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/fantasy-sports-clustering-analysis)
[![Leer el Notebook](https://img.shields.io/badge/📓_Leer_el_Notebook-056B67?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/maxsantana-data2strategy/fantasy-sports-clustering-analysis/blob/main/unsupervised-learning-fantasy-sports-clustering.ipynb)

🚧 **Estado: trabajo en progreso** — EDA, PCA, K-Means y K-Medoids están completos; Hierarchical, GMM y DBSCAN siguen pendientes, así como la comparación final de algoritmos.

<details markdown="1">

<summary markdown="1">
🔍 Ver estudio de caso completo
</summary>

## 🔧 Qué Hice (hasta ahora)
1. **EDA y Revisión de Outliers** — Análisis univariado y bivariado de 10 estadísticas de desempeño en ~476 jugadores, más la decisión deliberada de conservar los outliers (goleadores de élite) en lugar de tratarlos como anomalías
2. **Escalamiento + PCA** — Estandaricé el conjunto de variables y lo reduje con PCA para clustering y visualización
3. **K-Means (k = 4)** — Seleccioné k mediante el método del codo y el puntaje de silueta, y luego perfilé las estadísticas promedio de cada cluster
4. **K-Medoids (k = 4)** — Repetí la misma segmentación usando jugadores reales como centros de cluster en lugar de medias sintéticas, y comparé cluster por cluster contra K-Means

## 🛠️ Tecnologías
Python (pandas, numpy, scikit-learn, scikit-learn-extra) | PCA | K-Means | K-Medoids | matplotlib, seaborn | Jupyter Notebook

## 📊 Resultado Preliminar: K-Means vs. K-Medoids
Ambos algoritmos convergen en los mismos cuatro niveles — creadores de juego ofensivo de élite, anclas defensivas duraderas, titulares regulares de nivel medio, y jugadores habilitadores de pocos minutos — pero K-Medoids ancla cada uno a un jugador real (p. ej., Gylfi Sigurdsson, Ben Godfrey) en lugar de una media estadística, lo cual es más robusto ante outliers y más fácil de justificar en una conversación sobre precios.

<p align="center">
<img src="https://raw.githubusercontent.com/maxsantana-data2strategy/fantasy-sports-clustering-analysis/main/kmeans_vs_kmedoids.png" alt="Comparación de clusters K-Means vs K-Medoids: diagramas de dispersión PCA y mapas de calor de medias por variable para ambos algoritmos" width="700">
</p>

## 💡 Insight Clave (preliminar)
**La elección del algoritmo apenas mueve los niveles de jugadores — lo que mueve es cuán defendibles son.** Como K-Medoids llega a la misma historia de cuatro niveles anclada a jugadores reales, es el candidato más sólido para una decisión de precios que los stakeholders necesitan confiar, en espera de los métodos restantes (Hierarchical, GMM, DBSCAN) y una comparación completa de puntajes de silueta antes de una recomendación final.

</details>

</div>

<div class="project-wrapper foresight" markdown="1">

<img class="section-banner" src="https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy/main/banner-foresight.gif" alt="Banner animado: un cono de futuros tridimensional que se ramifica en cuatro escenarios nombrados, con un wild card rompiendo fuera del cono">

<p class="section-intro">No se trata de predecir. El objetivo no es pronosticar el futuro, sino ver sus posibilidades y darle forma. Análisis de drivers, construcción de escenarios y horizon scanning usados para poner a prueba la estrategia bajo incertidumbre profunda.</p>

# ¿Puede la IA Agrupar Señales de Riesgo Geopolítico Como un Experto? — México · Python NLP

![En Progreso](https://img.shields.io/badge/Estado-En_Progreso-FB2E89?style=for-the-badge)

## 🎯 Objetivo
Identificar y clasificar señales de riesgo geopolítico para México mediante horizon scanning asistido por IA — transformando 43 señales crudas en drivers de riesgo estructurados para la toma de decisiones ejecutivas.

[![Ver Archivos del Repositorio](https://img.shields.io/badge/📂_Ver_Archivos_del_Repositorio-0A0E14?style=for-the-badge&logo=github&logoColor=00E9D8)](https://github.com/maxsantana-data2strategy/horizon-scanning-geopolitical-risk-mx)

<details markdown="1">

<summary markdown="1">
🔍 Ver estudio de caso completo
</summary>

## 🔧 Qué Hice
1. **Recolección de Señales** — Reuní 43 señales geopolíticas de fuentes OSINT relevantes para el entorno de riesgo estratégico de México
2. **Clasificación con IA** — Aplique clasificación zero-shot basada en NLP para agrupar las señales en drivers de riesgo temáticos
3. **Validación de Expertos** — Comparé las agrupaciones generadas por IA contra una taxonomía definida por expertos; la alineación alcanzó ~78%
4. **Análisis Visual** — Mapeé las señales por impacto/incertidumbre y grafiqué los drivers por riesgo vs. puntaje de novedad

## 🛠️ Tecnologías
Python (pandas, transformers, clasificación zero-shot) | matplotlib, seaborn | Investigación OSINT | Jupyter Notebook

## 📊 Resultados
43 señales → 7 drivers identificados. La clasificación por IA coincidió con la agrupación de expertos en ~78% de los casos. Los drivers relacionados con seguridad dominan; la fragmentación regulatoria y el riesgo de cadena de suministro son clusters secundarios.

![Matriz de Impacto/Incertidumbre — 43 señales geopolíticas graficadas por impacto e incertidumbre](https://github.com/maxsantana-data2strategy/horizon-scanning-geopolitical-risk-mx/blob/main/figures/fig1_miu.png?raw=true)

![Riesgo vs. Novedad por Driver — los drivers de mayor novedad tienen los puntajes de riesgo más bajos, revelando la penalización por novedad](https://github.com/maxsantana-data2strategy/horizon-scanning-geopolitical-risk-mx/blob/main/figures/fig2_drivers.png?raw=true)

## 💡 Insight Clave
**La clasificación por IA coincidió con la agrupación de expertos en el 78% de los casos** — validando el horizon scanning automatizado como una herramienta viable de primera pasada para el análisis de riesgo geopolítico. El patrón de "penalización por novedad" (los drivers de mayor novedad puntúan más bajo en riesgo) sugiere que las amenazas emergentes se subponderan sistemáticamente en los marcos de riesgo tradicionales.

**Implicación:** Analistas y tomadores de decisiones deberían ajustar activamente por el sesgo de novedad al priorizar respuestas de riesgo.

</details>

# Cuatro Futuros para la Ayuda Humanitaria al 2040 — IARAN · Escenarios y CLA

## 🎯 Objetivo
Explorar cuatro futuros plausibles para el sistema global de ayuda humanitaria al 2040, traduciendo prospectiva en estrategia para organizaciones que navegan recortes de financiamiento, politización e incertidumbre sistémica.

<details markdown="1">

<summary markdown="1">
🔍 Ver estudio de caso completo
</summary>

## 🧭 Matriz de Escenarios

Cuatro escenarios mapeados en dos ejes: cooperación en red vs. supervivencia del más fuerte, y bloques multipolares vs. imperios y conflicto.

<p align="center"><img src="https://github.com/user-attachments/assets/14ccf88d-eb73-421d-bc81-8c4fd0893e8d" alt="Matriz de Escenarios de Ayuda 2040 — cuatro escenarios futuros para la ayuda humanitaria global" width="700"></p>

## 🔧 Qué Hice
1. **Investigación de Tendencias** — Lideré la investigación documental sobre tendencias globales (incl. IA) como analista líder para LATAM
2. **Facilitación con Stakeholders** — Facilité consultas en México y coordiné a múltiples stakeholders (donantes, socios estratégicos, organizaciones consultadas) dentro de la gobernanza del proyecto
3. **Entrega Multi-fase** — Contribuí en las tres fases del proyecto: fundamentos (Análisis de Capas Causales), escenarios, y rutas de transformación

## 🛠️ Metodologías Clave
Prospectiva Estratégica | Horizon Scanning | Análisis de Capas Causales (CLA) | Construcción de Escenarios | Alineación de Stakeholders

## 📊 Resultados

| Métrica | Valor |
|---|---|
| Consultas | 50+ |
| Contribuyentes | 877 |
| Del Sur Global | 77% |
| De ONGs/OSC locales | 44% |
| Con experiencia vivida de crisis | ~40% |

<p align="center">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/7c0c2c4b-f214-4e3e-949c-77cd23ebf370/39050001_neamoscou+redux.jpg" alt="Future of Aid 2040: Navegando el Próximo Horizonte Humanitario" width="180">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/1760035233995-XO5JPU0R82RQKIQM0SJ3/IMG_0087_neamoscou.jpeg" alt="Desglosando el Sistema de Ayuda" width="180">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/1778567955102-E81RF7563TNEDZJ31XOV/1.JPG" alt="Rutas hacia la Transformación — Guía P2T" width="180">
<img src="https://images.squarespace-cdn.com/content/v1/593eb9e7b8a79bc4102fd8aa/1778567241580-LWEGEV0TLR4BWCYQCVRC/b01850018.jpg" alt="Rutas hacia la Transformación — Del Análisis a la Acción" width="180">
</p>

[![Reporte de Escenarios](https://img.shields.io/badge/📄_Reporte_de_Escenarios-0A0E14?style=for-the-badge&logo=readthedocs&logoColor=00E9D8)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/future-of-aid/FutureOfAid2040_Scenarios_Report.pdf)
[![Desglosando el Sistema de Ayuda](https://img.shields.io/badge/📄_Desglosando_el_Sistema_de_Ayuda-FB2E89?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/future-of-aid/FutureOfAid2040_UnpackingAidSystem_CLA.pdf)
[![Rutas hacia la Transformación](https://img.shields.io/badge/📄_Rutas_hacia_la_Transformacion-056B67?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/future-of-aid/FutureOfAid2040_P2T_AnalysisToAction.pdf)

## 💡 Insight Clave
Síntesis de más de 877 voces de 50+ organizaciones — la mayoría del Sur Global — en cuatro marcos de escenarios y un kit de herramientas organizacional para la resiliencia humanitaria bajo alta incertidumbre.

</details>

---

# Marco de Política Pública para la Economía Creativa en Disrupción — Nuevo León · Prospectiva

## 🎯 Objetivo
Construir un marco basado en prospectiva para convertir la incertidumbre en oportunidad para las industrias creativas y culturales de Nuevo León, frente a la disrupción digital acelerada, la integración de IA y la presión pospandemia.

[![Ver Proyecto en CONL](https://img.shields.io/badge/🔗_Ver_Proyecto_en_CONL-0A0E14?style=for-the-badge&logo=googlechrome&logoColor=00E9D8)](https://conl.mx/proyectos/tierra-incognita-insertar-a-las-industrias-creativas-en-cadenas-de-valor-complejas-en-nl/)
[![Hoja Informativa](https://img.shields.io/badge/📄_Hoja_Informativa-FB2E89?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/tierra-incognita/TierraIncognita_OnePager.pdf)
[![Reporte Completo](https://img.shields.io/badge/📄_Reporte_Completo-056B67?style=for-the-badge&logo=readthedocs&logoColor=white)](https://raw.githubusercontent.com/maxsantana-data2strategy/maxsantana-data2strategy.github.io/main/docs/tierra-incognita/TierraIncognita_DocumentoCompleto.pdf)

<details markdown="1">

<summary markdown="1">
🔍 Ver estudio de caso completo
</summary>

## 🔧 Qué Hice
1. **Diseño y Facilitación de Talleres** — Diseñé y lideré talleres de prospectiva estratégica con actores del sector creativo y tomadores de decisiones clave
2. **Traducción a Política Pública** — Traduje el ejercicio de prospectiva en un marco de política pública aplicable (Enfoque de Marco Lógico)

## 🛠️ Metodologías Clave
Horizon Scanning | Construcción de Escenarios | Facilitación Estratégica | Enfoque de Marco Lógico

## 📊 Entregables

Reporte de horizon scanning para la economía creativa | 4 escenarios futuros para las industrias creativas de Nuevo León | Marco de política pública (Enfoque de Marco Lógico) | Reporte estratégico de política pública publicado

</details>

</div>

</div>

<script>
function filterProjects(category) {
var buttons = document.querySelectorAll('.filter-btn');
for (var i = 0; i < buttons.length; i++) {
if (buttons[i].getAttribute('data-category') === category) {
buttons[i].classList.add('active');
} else {
buttons[i].classList.remove('active');
}
}

var wrappers = document.querySelectorAll('.project-wrapper');
for (var j = 0; j < wrappers.length; j++) {
if (wrappers[j].classList.contains(category)) {
wrappers[j].classList.add('active');
} else {
wrappers[j].classList.remove('active');
}
}
}

function toggleLanguage() {
var body = document.body;
var btn = document.getElementById('langToggleBtn');
var isEs = body.classList.contains('lang-es');
if (isEs) {
body.classList.remove('lang-es');
if (btn) { btn.textContent = '🇲🇽 Ver en Español'; }
try { localStorage.setItem('site-lang', 'en'); } catch (e) {}
} else {
body.classList.add('lang-es');
if (btn) { btn.textContent = '🇺🇸 View in English'; }
try { localStorage.setItem('site-lang', 'es'); } catch (e) {}
}
}

(function () {
try {
var saved = localStorage.getItem('site-lang');
if (saved === 'es') {
document.body.classList.add('lang-es');
var btn = document.getElementById('langToggleBtn');
if (btn) { btn.textContent = '🇺🇸 View in English'; }
}
} catch (e) {}
})();
</script>
