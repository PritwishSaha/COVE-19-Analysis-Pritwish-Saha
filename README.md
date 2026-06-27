# 🦠 COVID-19 Analysis Dashboard (Power BI)

![COVID-19 Analysis Dashboard](Screenshot%202026-06-27%20133400.png)

## 📌 Project Overview

This Power BI dashboard provides an interactive analysis of global COVID-19 data using the Our World in Data (OWID) dataset. It helps users explore worldwide case trends, death statistics, continent-level comparisons, and demographic insights through dynamic visualizations and KPI indicators.

---

## 🎯 Objectives

- Analyze the global spread of COVID-19
- Compare cases and deaths across countries and continents
- Track pandemic trends over time
- Explore the relationship between median age and COVID-19 impact
- Build an interactive dashboard using Power BI

---

## 📊 Dashboard Features

### KPI Cards
- 🌍 **Total Cases** – Global confirmed COVID-19 cases
- 📈 **New Cases** – Total newly reported cases
- ⚠️ **Total Deaths** – Global confirmed COVID-19 deaths

### Visualizations

#### 1️⃣ Total Cases by Country
Displays the countries with the highest cumulative COVID-19 cases.

#### 2️⃣ Total Cases by Continent
Pie chart showing the percentage contribution of each continent to global case counts.

#### 3️⃣ Total Deaths by Continent
Donut chart visualizing the distribution of deaths across continents.

#### 4️⃣ Total Cases by Year and Country
Stacked area chart showing the progression of COVID-19 cases between 2020 and 2021.

#### 5️⃣ Median Age Analysis
Scatter chart comparing median age across countries and continents to identify demographic patterns.

---

## 📷 Dashboard Preview

The dashboard provides:

- Interactive filtering and exploration
- Country and continent-level insights
- Time-series analysis of pandemic growth
- Clean and professional visualization layout

---

## 🗂️ Dataset Information

| Attribute | Details |
|------------|-----------|
| Dataset | OWID COVID-19 Dataset |
| Source | Our World in Data |
| Format | CSV / Excel |
| Time Period | 2020 – 2021 |
| Records | Global COVID-19 Statistics |

### Fields Used

- `location`
- `continent`
- `date`
- `total_cases`
- `new_cases`
- `total_deaths`
- `median_age`
- `population`

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|---------|
| Power BI Desktop | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | Data Modeling & Calculations |
| Excel / CSV | Data Source |

---

## ⚙️ Project Workflow

### Data Preparation
- Imported OWID COVID-19 dataset
- Removed unnecessary columns
- Handled missing values
- Converted date fields into proper format
- Filtered invalid and aggregate records

### Data Modeling
- Established relationships where required
- Created DAX measures for:
  - Total Cases
  - Total Deaths
  - New Cases
  - Latest cumulative values

### Dashboard Design
- Built KPI cards
- Created interactive charts
- Added legends and filters
- Designed a clean and user-friendly layout

---

## 📈 Key Insights

✅ The United States, India, and Brazil recorded some of the highest case counts globally.

✅ Europe and Asia contributed the largest share of total reported cases and deaths.

✅ COVID-19 cases increased dramatically during 2021 compared to 2020.

✅ Demographic factors such as median age show varying relationships with COVID-19 impact across continents.

---

## 📂 Repository Structure

```text
COVID-19-Analysis-Dashboard/
│
├── README.md
├── Screenshot 2026-06-27 133400.png
├── owid-covid-data.xlsx
└── COVID-19 Analysis.pbix
```

---

## 🔗 Data Source

- Our World in Data (OWID)
- https://ourworldindata.org/covid-deaths

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Visualization
- Dashboard Design
- Power BI
- Power Query
- DAX
- Analytical Thinking

---

## 👨‍💻 Author

**Pritwish**

Aspiring Data Analyst passionate about transforming raw data into actionable insights through interactive dashboards and visual storytelling.

⭐ If you found this project useful, consider giving the repository a star.