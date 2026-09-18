# Global Malaria Burden: Trends, Mortality and Incidence

<img width="599" height="333" alt="Image" src="https://github.com/user-attachments/assets/cf06cfab-cf1b-4409-a31a-69ccda990a52" />

## Project Overview

This project presents an Excel- and Power BI-based analysis of the global malaria burden across 103 countries from 2000 to 2019.

The analysis examines malaria incidence, mortality rates, deaths by age group, country-level mortality burden, high-incidence countries, and variations in malaria burden across regions and continents.

The project demonstrates a practical end-to-end data analysis workflow, from data preparation and integration through descriptive analysis, visualization, and interactive dashboard development.

The analysis is descriptive and trend-focused. 

---

## Research Questions

The project addresses six research questions:

1. **What trends can be observed in malaria incidence and mortality across the countries represented in the dataset from 2000 to 2019?**

2. **How are malaria deaths and death rates distributed across different age groups, and which age groups are most affected?**

3. **Which countries record the highest malaria mortality burden based on the number of deaths and mortality rates?**

4. **Which countries record the highest malaria incidence, and how do incidence patterns vary over the study period?**

5. **How do malaria incidence, total deaths, and mortality rates compare among the countries with the greatest malaria burden?**

6. **How does malaria burden vary across regions and continents among the countries represented in the dataset?**

---

## Data Preparation

The original datasets contained differences in structure, coverage, and data consistency. Data preparation was therefore an important part of the project.

The main preparation steps included:

1. Reviewing the available malaria datasets.
2. Identifying datasets relevant to the research questions.
3. Removing unsuitable and inconsistent records.
4. Cleaning entity and year fields.
5. Aligning datasets by country/entity and year.
6. Merging the selected datasets using **Power Query**.
7. Validating the resulting records for completeness.
8. Removing aggregate entities from the final country-level dataset.
9. Creating a country lookup for region and continent classification.
10. Populating region and continent fields in the final master dataset.
11. Verifying that the final dataset contained 103 countries covering 2000–2019.

The resulting master dataset was then used as the basis for the Excel analysis and Power BI dashboard.

---

## Analytical Approach

The project uses descriptive and comparative analysis to examine malaria burden.

### Key analytical techniques

- Data cleaning
- Data transformation
- Data integration
- Power Query
- PivotTables and PivotCharts
- Trend analysis and comparisons
- Interactive dashboard visualization

---

# Key Findings

## RQ1 — Malaria Incidence and Mortality Trends

The analysis showed a substantial overall decline in both malaria incidence and mortality during the study period.

Average malaria incidence declined by approximately **46.0%** between 2000 and 2019.

Average malaria mortality, based on the all-age death rate, declined by approximately **47.0%** over the same period.

Overall, the findings indicate a downward trend in both malaria incidence and mortality across the countries represented in the final dataset.

---

## RQ2 — Mortality by Age Group

The analysis examined both the number of deaths and death rates across five age groups:

- Under 5
- 5–14
- 15–49
- 50–69
- 70+

The **under-5 age group recorded the largest share of malaria deaths**, accounting for approximately **63% of cumulative deaths** in the final analysis.

The under-5 group also recorded the highest average death rate among the age groups analysed.

This highlights the substantial contribution of malaria mortality among young children within the countries and period covered by the dataset.

---

## RQ3 — Countries with the Highest Mortality Burden

Two measures were used to examine country-level malaria mortality:

1. **Cumulative number of deaths**
2. **Average mortality rate**

The results showed different patterns depending on the measure used.

### Highest cumulative deaths

**Nigeria** recorded the highest cumulative number of malaria deaths during the study period, with approximately **4.61 million deaths**.

Other countries with high cumulative death counts included:

- Democratic Republic of the Congo
- India
- Uganda
- Burkina Faso
- Côte d'Ivoire
- Ghana
- Niger
- Mozambique
- Mali

### Highest average mortality rate

When mortality was assessed using the average standardized mortality rate, **Sierra Leone** recorded the highest average value at approximately **244.14**.

Other countries with high average standardized mortality rates included:

- Burkina Faso
- Côte d'Ivoire
- Liberia
- Nigeria
- Niger
- Benin
- Cameroon
- Mozambique
- Mali

The comparison demonstrates why both absolute deaths and mortality rates are useful when assessing malaria burden.

---

## RQ4 — Countries with the Highest Malaria Incidence

Countries with the highest average malaria incidence during the study period included:

| Country | Average Incidence |
|---------|------------------:|
| Burkina Faso | 508.18 |
| Benin | 426.93 |
| Sierra Leone | 417.10 |
| Côte d'Ivoire | 409.64 |
| Mali | 403.19 |
| Democratic Republic of the Congo | 396.11 |
| Central African Republic | 394.75 |
| Mozambique | 391.91 |
| Uganda | 385.25 |
| Guinea | 384.46 |

The analysis also examined changes in incidence between 2000 and 2019.

For example:

- Burkina Faso: approximately **39.3% decline**
- Benin: approximately **5.2% decline**
- Sierra Leone: approximately **26.1% decline**
- Côte d'Ivoire: approximately **44.9% decline**
- Mali: approximately **17.9% decline**
- Democratic Republic of the Congo: approximately **31.7% decline**
- Central African Republic: approximately **26.9% decline**
- Mozambique: approximately **37.5% decline**
- Uganda: approximately **46.1% decline**

These results show that countries with high average incidence did not necessarily experience the same magnitude of change over the study period.

---

## RQ5 — Comparison Among Countries with the Greatest Malaria Burden

The fifth research question brought together the major malaria indicators to provide a broader comparison of countries with high malaria burden.

The analysis compared:

- Malaria incidence
- Total malaria deaths
- Mortality rates

The results showed that countries can occupy different positions depending on the measure used.

For example, **Nigeria recorded the highest cumulative number of deaths**, while **Sierra Leone recorded the highest average standardized mortality rate**. **Burkina Faso recorded the highest average malaria incidence** among the countries analysed.

This demonstrates that malaria burden is multidimensional and that total deaths, incidence, and mortality rates provide different perspectives on country-level burden.

---

## RQ6 — Regional and Continental Variation

The analysis also examined malaria burden across the regions and continents represented by the 103 countries.

The regional and continental analysis showed that **Africa accounted for the largest malaria burden** among the geographical groupings represented in the final dataset.

The analysis used the final 103-country master dataset rather than relying on a separate regional aggregate dataset. This ensured that regional and continental comparisons were based on the same cleaned country-level records used throughout the project.

---

# Excel Analysis

Microsoft Excel was used extensively throughout the project and PivotTables were used to summarize the data. These summaries formed the basis for the project's analytical findings and visualizations.

---

# Power BI Dashboard

The cleaned master dataset was also imported into Power BI to create an interactive malaria dashboard.

The dashboard presents key indicators and allows users to explore malaria burden across countries and geographical groupings.

The Power BI dashboard complements the Excel analysis by allowing users to interact with the data and examine different aspects of malaria burden dynamically.

---

# Project Workflow

```text
Kaggle Malaria Datasets
          │
          ▼
    Data Review
          │
          ▼
   Data Cleaning
          │
          ▼
 Power Query Transformation
          │
          ▼
     Dataset Merge
          │
          ▼
 Country / Region / Continent Mapping
          │
          ▼
 Final Master Dataset
  103 Countries × 20 Years
          │
          ├───────────────┐
          ▼               ▼
      Excel            Power BI
          │               │
    PivotTables       Data Model
    PivotCharts          DAX
    Descriptive       Interactive
      Analysis         Dashboard
          │               │
          └───────┬───────┘
                  ▼
           Key Findings
