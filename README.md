# Global Layoffs Analysis (2020–2023)

### Project Overview

This project analyzes global layoffs data from 2020 to 2023 to understand trends, industry impact, and key factors contributing to workforce reductions during and after the COVID-19 pandemic.

The analysis includes data cleaning, transformation, and exploratory data analysis (EDA) using SQL.

### Dataset

The dataset contains information about company layoffs across different countries and industries.


### Key columns:

- company
- location
- industry
- total_laid_off
- percentage_laid_off
- date
- stage
- country
funds_raised_millions



### Tools & Technologies

SQLite
SQL
GitHub
DB Browser for SQLite



### Data Cleaning Steps

- Created a staging table to preserve the original dataset.

- Identified and removed duplicate records.

- Standardized text columns (company, industry, country, stage).

- Fixed inconsistent date formats and converted them to a uniform format (YYYY-MM-DD).

- Hanled null and blank values in key columns.

- Converted numeric columns (total_laid_off, percentage_laid_off, funds_raised_millions) to proper data types.

- Created a clean final table for analysis.



### Exploratory Data Analysis (EDA)

The following insights were explored:

Total layoffs by year

Monthly layoff trends

Industries most affected by layoffs

Countries with the highest layoffs

Companies with the largest layoffs

Layoffs by company funding stage

### Key Insights

The highest number of layoffs occurred in 2022.

The United States recorded the most layoffs globally.

The Consumer and Retail industries were among the most affected sectors.

Major tech companies such as Amazon, Google, Meta, and Microsoft had the largest layoffs.

Post-IPO and Series C/D companies experienced significant workforce reductions.

Detailed insights are available in the insights.md file.

### Root Cause Summary

Global layoffs were driven by:

COVID-19 business disruption (2020–2021)

Post-pandemic overhiring and workforce correction (2022–2023)

Economic slowdown and inflation

Reduced startup funding

Business restructuring and automation

### Project Structure

global-layoffs-analysis/
│
├── data/
│   └── layoffs.csv
│
├── sql/
│   └── data_cleaning.sql
│   └── eda.sql
│
├── insights.md
├── README.md

### Future Work

Build dashboards using Power BI or Tableau
Add visualizations for trends and comparisons
Perform predictive analysis on layoff trends
Extend analysis with more recent data
