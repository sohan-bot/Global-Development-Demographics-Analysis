# Global Development & Demographics Analysis

## Executive Summary

This project demonstrates an **end-to-end Data Analyst workflow** using **SQL + Pandas**, with a strong emphasis on **performance-aware data extraction**, **analytical feature engineering**, and **business-focused visualization**.

Using global country, city, and language datasets, the analysis answers high-impact questions around **economic development, population distribution, and risk identification**. SQL is used for scalable aggregation and joins, while Pandas and Python visualization libraries are used for analytical modeling and storytelling.

**Key outcomes:**

* Identified strong correlation between **GNP per capita and life expectancy**
* Built a **development index** to rank and flag high-risk countries
* Highlighted countries facing challenges from **high population density**
* Compared **language diversity across continents**

This repository is designed to reflect how analytics work is performed in real organizations—not just isolated queries or charts.

---

## Project Objectives

* Demonstrate correct **SQL vs Pandas tool selection**
* Apply **window functions, joins, and aggregations** on realistic datasets
* Perform **feature engineering and segmentation** in Pandas
* Create **publication-quality and interactive visualizations**
* Communicate insights clearly for non-technical stakeholders

---

## Dataset Description

The project uses three relational tables (similar to the MySQL `world` database):

### `country`

* Demographics: Population, SurfaceArea
* Economic indicators: GNP, LifeExpectancy
* Geography: Continent, Region

### `city`

* City-level population data
* Linked to country via CountryCode

### `countrylanguage`

* Languages spoken per country
* Percentage of speakers and official language flag

---

## Tech Stack

* **Database:** MySQL
* **Query Language:** SQL (CTEs, Window Functions)
* **Analysis:** Python, Pandas
* **Visualization:** Matplotlib, Seaborn, Plotly

---

## Analytical Workflow

### 1. Data Extraction (SQL)

* Filtered and aggregated data at the database level
* Reduced data volume before loading into Python
* Used window functions for ranking and cumulative metrics

### 2. Data Transformation (Pandas)

* Feature engineering (GNP per capita, population density)
* Development tier classification
* Composite development index creation

### 3. Visualization & Insights

* Static charts (Seaborn) for reports
* Interactive charts (Plotly) for exploration
* Business-focused interpretation of trends and outliers

---

## Key Visual Insights

### Income vs Life Expectancy

Higher GNP per capita is strongly associated with higher life expectancy, with diminishing returns at very high income levels.

### Development Risk Identification

Countries with low income and low life expectancy were flagged using a composite development index to identify potential high-risk regions.

### Population Density Challenges

A small group of countries experience extremely high population density, creating unique infrastructure and development pressures.

### Language Diversity

Africa and Asia exhibit the highest linguistic diversity, reflecting cultural complexity and policy challenges.

---

## Repository Structure

```
global-development-analysis/
│
├── sql/                  # Optimized SQL queries
├── notebooks/            # Analysis & visualization notebooks
├── images/charts/        # Publication-quality visuals
├── README.md
└── requirements.txt
```

---

## Why This Project Matters

This project demonstrates:

* Analytical thinking, not just coding
* Performance-aware decision making
* Clear communication of insights
* Readiness for real-world Data Analyst roles

---
