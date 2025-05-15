# covid19-data-pipeline-fabric
# COVID-19 Data Pipeline in Microsoft Fabric

This repository contains a series of notebooks and insights demonstrating end-to-end data engineering and analytics using **Microsoft Fabric** and **PySpark Notebooks**, built on top of a real-world COVID-19 dataset.

## 🔧 Tools & Technologies
- Microsoft Fabric
- OneLake + Lakehouse
- PySpark (inside Fabric notebooks)
- Delta Tables
- Data Analysis & Aggregation
- (Upcoming) Power BI

---

## 📚 Project Phases

### ✅ Day 1 – Cleaning & Structuring the Dataset
- Loaded raw COVID-19 data (100MB CSV) into OneLake Files
- Converted all numeric fields to appropriate types using PySpark
- Handled missing/null values in critical fields
- Created derived metrics like `death rate` and `vaccinated per 100 people`
- Saved cleaned output as a Delta Table

📂 [`day01-cleaning-and-preparation`](./day01-cleaning-and-preparation/)

---

### ✅ Day 2 – Aggregations & Country/Continent Insights
- Generated **monthly summaries** by country and continent
- Created an **all-time country leaderboard** for cases, deaths, and vaccinations
- Computed **death-to-case ratios** and other health indicators
- Saved all results as structured Delta Tables
- Extracted key insights for further visualizations

📂 [`day02-aggregations-and-insights`](./day02-aggregations-and-insights/)

---

## 📌 Next Steps
- Phase 3: Time-Series Analysis with rolling averages and visualizations
- Phase 4: Correlation & socio-economic equity metrics
- Phase 5: Visualization in Power BI or Fabric charts

---

## 📈 Dataset
- Source: [Our World in Data – COVID-19 Dataset](https://ourworldindata.org/covid-vaccinations)

---

## 👋 About Me
I'm a Power BI developer transitioning into the world of **data engineering** and **analytics** using Microsoft Fabric. This repository is part of my learning-in-public journey toward DP-600 certification and beyond!

