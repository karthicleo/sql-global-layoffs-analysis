# sql-global-layoffs-analysis
End-to-End SQL Data Cleaning &amp; Exploratory Data Analysis on a Global Layoffs Dataset using MySQL.
# Global Layoffs Data Cleaning & Exploratory Data Analysis using SQL

## Project Overview

In this project, I worked with a real-world Global Layoffs dataset to perform end-to-end data cleaning and exploratory data analysis (EDA) using MySQL.

The dataset contained duplicate records, inconsistent values, missing data, and formatting issues. I cleaned the data to make it reliable for analysis and then explored it to identify trends and patterns in global layoffs. The goal of this project was to gain hands-on experience with the complete data analysis workflow, from raw data to meaningful insights.

---

## Dataset

The dataset contains information about layoffs across companies around the world, including:

- Company
- Industry
- Country
- Location
- Date
- Total Layoffs
- Percentage Laid Off
- Funding Stage
- Funds Raised (Millions)

---

## Objectives

The main objectives of this project were to:

- Clean and prepare a real-world dataset for analysis.
- Remove duplicate and inconsistent records.
- Handle missing values and standardize the data.
- Explore the dataset using SQL to identify trends and patterns.
- Generate insights that could help understand the impact of layoffs across companies, industries, and countries.

---

## Data Cleaning Process

To improve the quality of the dataset, I performed the following steps:

- Created a staging table to preserve the original dataset.
- Removed duplicate records using the `ROW_NUMBER()` window function.
- Standardized company names, industries, countries, and date formats.
- Converted dates into SQL `DATE` format.
- Identified and handled missing and blank values.
- Corrected inconsistent records wherever possible.
- Removed unnecessary records to prepare a clean dataset for analysis.

---

## Exploratory Data Analysis

After cleaning the dataset, I used SQL queries to explore different aspects of the data. The analysis focused on:

- Companies with the highest layoffs.
- Industries that experienced the largest workforce reductions.
- Countries most affected by layoffs.
- Yearly and monthly layoff trends.
- Rolling monthly layoff totals.
- Top companies by layoffs for each year.
- Layoffs across different funding stages.
- Companies that laid off 100% of their workforce.

---

## Key Insights

Some of the insights generated from this analysis include:

- Identified the companies with the highest number of layoffs.
- Found the industries that were most affected during the layoff period.
- Analyzed which countries experienced the largest workforce reductions.
- Observed how layoffs changed over different years and months.
- Calculated rolling monthly totals to better understand cumulative layoff trends.
- Ranked the top companies with the highest layoffs each year using SQL window functions.
- Compared layoffs across different funding stages to understand how company maturity influenced workforce reductions.
- Identified companies that laid off their entire workforce.

---

## SQL Concepts Used

Throughout this project, I applied several SQL concepts, including:

- SELECT, WHERE, ORDER BY
- GROUP BY
- Aggregate Functions
- CASE Statements
- Self Joins
- Common Table Expressions (CTEs)
- Window Functions (`ROW_NUMBER()`, `DENSE_RANK()`, `SUM() OVER`)
- Date Functions
- Data Cleaning Techniques

---

 ## Folder Structure

```
global-layoffs-sql-project
│
├── dataset
│   └── layoffs.csv
│
├── sql
│   ├── 01_data_cleaning.sql
│   └── 02_exploratory_data_analysis.sql
│
├── screenshots
│   ├── data_cleaning
│   └── eda
│
├── README.md
└── LICENSE
```

---

## Future Improvements

This project can be extended further by:

- Building an interactive Power BI dashboard using the cleaned dataset.
- Creating visualizations to present the key insights.
- Performing trend forecasting using Python.
- Developing a complete end-to-end analytics dashboard combining SQL and Power BI.
- Expanding the analysis with additional business questions and KPIs.

---

Thank you for taking the time to explore this project. Feedback and suggestions are always welcome.
