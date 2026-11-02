# Data Analysis Portfolio

**Author:** Plinio Durango
**Tools:** MySQL · Python · pandas · matplotlib · seaborn · Jupyter

A collection of data analysis projects using SQL and Python to explore real-world datasets — covering public safety, environmental quality, consumer behavior, historical records, healthcare, and energy economics.

---

## Projects

### 1. SF Crime Analysis — 2024 vs 2025
> MySQL · Window Functions · EDA · 225K+ Records

Analyzes 225,000+ SFPD incident reports across two years. Compares crime volume, category shifts, district hotspots, resolution rates, and seasonal patterns to assess citywide safety trends.

**Repo:** [sf_crime_2024_2025](https://github.com/plinio9302/sf_crime_2024_2025)
**Key skills:** UNION ALL, window functions (RANK, LAG, SUM OVER), CREATE VIEW, time-series aggregation

---

### 2. Air Quality Analysis — UCI Dataset
> MySQL · EDA · WHO Thresholds · Seasonal Trends

Analyzes 390 days of hourly air quality measurements from an Italian city. Covers WHO exceedance rates, seasonal pollution patterns, peak hours, and temperature vs. pollutant correlations.

**Repo:** [Air-Quality](https://github.com/plinio9302/Air-Quality)
**Key skills:** NULLIF, STR_TO_DATE, CREATE VIEW, data cleaning, threshold analysis

---

### 3. Beer Reviews — Chemistry & Taste Perception
> Python · EDA · pandas · seaborn · Jupyter

Explores beer reviews at the intersection of chemistry (ABV, IBU) and taste perception. Investigates whether bitterness affects ratings, flavor descriptor patterns, and brewery performance.

**Repo:** [beer-reviews-chemistry-analysis](https://github.com/plinio9302/beer-reviews-chemistry-analysis)
**Key skills:** EDA, correlation analysis, data visualization, groupby aggregation

---

### 4. Titanic Survival Analysis
> MySQL · SQL Analytics · Survival Modeling

SQL survival analysis of Titanic passengers — exploring the impact of gender, class, cabin, family size, and social title on survival outcomes.

**Repo:** [Titanic_dataset](https://github.com/plinio9302/Titanic_dataset)
**Key skills:** GROUP BY, CASE WHEN, aggregation, conditional filtering

---

### 5. Green Hydrogen vs. SMR: Levelized Cost in California
> Python · Techno-Economic Analysis · Discounted Cash Flow · Sensitivity Analysis · Excel

Builds a transparent LCOH (levelized cost of hydrogen) model comparing PEM (proton exchange membrane) electrolysis on a dedicated solar PPA (power purchase agreement) against SMR (steam methane reforming). The base case costs $3.96/kg for green hydrogen versus $2.17/kg for SMR at current California gas prices. Includes crossover analysis, a tornado sensitivity chart, a check of the federal 45V tax credit, a formula driven Excel model, and a one page client style memo.

**Repo:** [green-hydrogen-lcoh](https://github.com/plinio9302/green-hydrogen-lcoh)
**Key skills:** DCF (discounted cash flow) modeling, scenario and sensitivity analysis, breakeven analysis, Excel modeling, policy analysis

---

### 6. ASA DataFest 2026: Patient Encounter Analysis
> Python · pandas · EDA · Healthcare Data · 7.7M Records

Team analysis of Stormont Vail Health's four year patient encounter dataset (about 7.7M encounters across rural Northeast Kansas) for ASA (American Statistical Association) DataFest 2026. Maps which of the 20 most frequent diagnosis groups co-occur within 60 days for the same patient (normalized heatmap), then profiles high utilization patient clusters by length of stay, diagnoses, and departments. Cross referencing with the social determinants questionnaire surfaced transportation access as a driver of return visits, which won the Best Insight award at the University of San Francisco site. Raw data is not included under the data use agreement.

**Repo:** [Data_Fest_2026](https://github.com/plinio9302/Data_Fest_2026)
**Key skills:** Large scale pandas joins, co-occurrence analysis, heatmaps, cohort profiling, healthcare data, communicating insights

---

### 7. Data Wrangling with pandas: A Complete Guide
> Python · pandas · Data Cleaning · Reshaping · Jupyter

An end to end reference notebook organized in four stages: collect, clean, reshape, and repair. Covers reading data efficiently (dtypes, categoricals, many files into one frame), renaming and type conversion, datetime handling, filtering and indexing, pivot, melt, stack and unstack, and profiling and repairing damaged data.

**Repo:** [my-pandas-notebook](https://github.com/plinio9302/my-pandas-notebook)
**Key skills:** pandas, data cleaning, datetime handling, pivot and melt, MultiIndex, data profiling

---

## Skills Demonstrated

| Area | Technologies |
|------|-------------|
| SQL Analysis | MySQL, window functions, CREATE VIEW, UNION ALL, CTEs |
| Data Cleaning | NULLIF, STR_TO_DATE, type casting, NULL handling |
| Python EDA | pandas, matplotlib, seaborn, Jupyter Notebooks |
| Data Wrangling | Collect, clean, reshape, repair with pandas; pivot, melt, datetime handling |
| Domain Areas | Public safety, environmental science, consumer data, historical records, healthcare, energy economics |
| Financial Modeling | DCF, levelized cost, crossover analysis, tornado sensitivity, Excel models |

## Tools & Technologies

![MySQL](https://img.shields.io/badge/MySQL-Database-blue)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-green)

---

*For machine learning projects, see [ml-portfolio](https://github.com/plinio9302/ml-portfolio)*
