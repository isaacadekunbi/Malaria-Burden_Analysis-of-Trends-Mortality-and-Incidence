# Global Malaria Burden: Trends, Mortality and Incidence

## Project Overview

This project presents an Excel and Power BI analysis of the global malaria burden, focusing on trends in malaria incidence, mortality, and deaths across 103 countries between 2000 and 2019.

The project was developed as a practical data analysis and visualization exercise using publicly available malaria datasets obtained from Kaggle. The analysis focuses on descriptive statistics, comparisons, and trends rather than predictive or inferential modelling.

The project demonstrates the application of data cleaning, data transformation, aggregation, analysis, and visualization techniques to convert multiple raw datasets into meaningful business-style insights and interactive dashboards.

---

## Objectives

The project aims to:

- Examine trends in malaria incidence from 2000 to 2019.
- Examine trends in malaria mortality rates over the study period.
- Compare malaria deaths across different age groups.
- Identify countries with the highest malaria mortality burden.
- Identify countries with high malaria incidence.
- Examine differences in malaria burden across regions and continents.
- Present key findings through interactive Excel and Power BI dashboards.

---

## Research Questions

### RQ1
How did malaria incidence and mortality rates change between 2000 and 2019?

### RQ2
Which age groups recorded the highest malaria mortality rates?

### RQ3
Which countries recorded the highest malaria mortality burden based on the number of deaths and mortality rates?

### RQ4
Which countries recorded the highest malaria incidence during the study period, and how did incidence change between 2000 and 2019?

---

## Dataset

The original project dataset consisted of multiple malaria-related CSV files obtained from Kaggle.

After reviewing and cleaning the available datasets, five datasets were selected for the final analysis based on data consistency, completeness, and relevance to the research questions.

The final master dataset contains:

- **103 countries**
- **20 years (2000–2019)**
- **2,060 country-year records**
- Malaria incidence data
- Mortality rates
- Deaths by age group
- Standardized mortality rates
- Region
- Continent

Aggregate entities and records that did not represent individual countries were excluded from the final country-level analysis.

---

## Data Preparation and Cleaning

The raw datasets required preparation before analysis.

The main data preparation activities included:

1. Reviewing the available CSV datasets.
2. Identifying datasets suitable for the research questions.
3. Removing unsuitable or inconsistent records.
4. Aligning datasets using country/entity and year.
5. Merging the selected datasets using Power Query.
6. Checking for missing and inconsistent records.
7. Removing aggregate entities from the final country-level dataset.
8. Adding region and continent classifications using a country lookup table.
9. Validating the final dataset to ensure that each country contained records for the required study years.

The final dataset contains a complete 20-year period for each of the 103 countries.

---

## Tools Used

### Microsoft Excel

Excel was used for:

- Data cleaning and preparation
- Power Query
- Data transformation
- PivotTables
- PivotCharts
- Descriptive statistics
- Percentage calculations
- Trend analysis
- Dashboard development

### Microsoft Power BI

Power BI was used for:

- Data modelling
- DAX measures
- Interactive visualizations
- Slicers and filters
- KPI cards
- Trend analysis
- Country and regional comparisons
- Interactive dashboard development

---

## Key Findings

### 1. Incidence and Mortality Trends

Average malaria incidence across the countries in the final dataset declined from **152.12 per 1,000 population at risk in 2000** to **82.27 in 2019**, representing an approximate **45.92% decline**.

Average malaria mortality rate also declined over the study period, from **45.20 in 2000** to **23.98 in 2019**.

The findings therefore show an overall downward trend in both malaria incidence and mortality during the study period.

---

### 2. Mortality by Age Group

The analysis showed that the **under-5 age group accounted for the largest number of malaria deaths** in the dataset.

The distribution of deaths by age group was:

| Age Group | Number of Deaths | Share |
|-----------|-----------------:|------:|
| Under 5 | 82,389,229 | 64% |
| 5–14 | 9,961,223 | 8% |
| 15–49 | 17,067,555 | 13% |
| 50–69 | 14,307,146 | 11% |
| 70+ | 5,572,326 | 4% |

---

### 3. Countries with High Mortality Burden

Based on the total number of deaths recorded during the study period, the countries with the largest death counts included:

- Nigeria — 4,610,044
- Democratic Republic of the Congo — 1,683,887
- India — 1,137,121
- Uganda — 779,740
- Burkina Faso — 714,360

When mortality was assessed using the average standardized mortality rate, countries with high values included:

- Sierra Leone — 244.14
- Burkina Faso — 220.44
- Côte d'Ivoire — 190.19
- Liberia — 160.74
- Nigeria — 148.95

These measures provide different perspectives on malaria burden: total deaths reflect the number of deaths, while standardized mortality rates allow mortality levels to be compared using a rate-based measure.

---

### 4. Countries with High Malaria Incidence

Countries with high average malaria incidence during the study period included:

- Burkina Faso — 508.18
- Benin — 426.93
- Sierra Leone — 417.10
- Côte d'Ivoire — 409.64
- Mali — 403.19
- Democratic Republic of the Congo — 396.11
- Central African Republic — 394.75
- Mozambique — 391.91
- Uganda — 385.25
- Guinea — 384.46

Several of these countries also experienced substantial reductions in incidence between 2000 and 2019.

---

## Dashboard

The project includes both **Excel and Power BI dashboards** designed to communicate the main findings interactively.

The dashboard focuses on:

- Malaria incidence trends
- Mortality trends
- Mortality by age group
- Country-level mortality comparisons
- Incidence comparisons
- Regional and continental patterns
- Interactive filtering and exploration

The Power BI version provides additional interactivity through slicers, cross-filtering, KPI cards, and dynamic visual exploration.

---

## Project Workflow

```text
Raw CSV Datasets
       ↓
Data Review
       ↓
Dataset Selection
       ↓
Data Cleaning
       ↓
Power Query Transformation
       ↓
Dataset Merging
       ↓
Country / Region / Continent Mapping
       ↓
Final Master Dataset
       ↓
PivotTable & Descriptive Analysis
       ↓
Excel Dashboard
       ↓
Power BI Data Model & DAX
       ↓
Interactive Power BI Dashboard
