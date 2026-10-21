# Max Santana
### Data Analyst, Business Intelligence & Strategic Foresight Specialist

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
---

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
<button class="filter-btn active" onclick="filterProjects('bi', this)">Data Analysis / BI</button>
<button class="filter-btn" onclick="filterProjects('ds', this)">Data Science</button>
<button class="filter-btn" onclick="filterProjects('foresight', this)">Foresight</button>
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

<!-- ==========================================
5. Lógica JavaScript (Corregida para Jekyll)
========================================== -->

<script>
function filterProjects(category, btnElement) {
var buttons = document.querySelectorAll('.filter-btn');
for (var i = 0; i < buttons.length; i++) {
buttons[i].classList.remove('active');
}
btnElement.classList.add('active');

var wrappers = document.querySelectorAll('.project-wrapper');
for (var j = 0; j < wrappers.length; j++) {
if (wrappers[j].classList.contains(category)) {
wrappers[j].classList.add('active');
} else {
wrappers[j].classList.remove('active');
}
}
}
</script>
