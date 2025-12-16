# Tech Layoffs Analysis (2020–2024)

## Project Overview
This project presents an exploratory and business-focused analysis of global layoffs in the technology industry between 2020 and 2024. Using a real-world dataset, the analysis aims to uncover temporal trends, geographic patterns, and structural insights behind workforce reductions in tech companies.

The project is designed as a portfolio case study, simulating a real analytical workflow from data ingestion to insight generation and visualization.

---

## Objectives
- Analyze the evolution of tech layoffs over time (yearly and monthly)
- Identify peak periods and cyclical patterns in workforce reductions
- Compare layoffs across geographic regions
- Understand how layoffs are distributed across the global tech ecosystem
- Practice a complete data analysis workflow using real data

---

## 🗂 Dataset
**Source:** Tech Layoffs 2020–2024 (Kaggle)

The dataset includes:
- Company name and headquarters location
- Date of layoffs
- Number and percentage of employees laid off
- Company size before and after layoffs
- Industry and funding stage
- Geographic information (country and continent)

> Note: The data is compiled from publicly available sources and may contain missing or incomplete values. Figures should be interpreted as indicative rather than exact.

---

## Methodology

### 1. Data Preparation
- Loading and validating datasets
- Handling missing values in numeric and categorical fields
- Standardizing date formats
- Verifying data consistency

### 2. Feature Engineering
- Extracted year and month from layoff dates
- Created aggregated time variables for trend analysis (year-month)

### 3. Exploratory Data Analysis (EDA)
- Yearly and monthly aggregation of layoffs
- Identification of temporal peaks and downturns
- Geographic aggregation by continent
- Industry-level exploratory analysis

### 4. Visualization
- Time series line charts for layoffs over time
- Bar charts for geographic comparisons

---

## Key Findings
- Tech layoffs show **clear cyclical behavior**, with sharp peaks rather than gradual trends.
- **2023 represents the highest number of layoffs**, indicating a prolonged industry correction following the post-pandemic expansion.
- **North America accounts for the majority of layoffs**, reflecting its dominance in the global technology sector.
- Layoffs tend to occur in concentrated waves, often aligned with broader macroeconomic and financial conditions.

---

## Geographic Insights
- North America leads in total layoffs by a significant margin.
- Europe and Asia show comparable levels of workforce reductions.
- Other regions experience lower absolute numbers, reflecting smaller concentrations of large tech companies.

---

## Limitations
- Missing values in company size and funding data
- Incomplete data for 2025, which was excluded from most analyses
- Layoff counts do not account for rehiring or net employment changes

---

## Future Work
- Industry-specific trend analysis
- Company-level deep dive analyses
- Correlation analysis between funding stages and layoffs
- Integration with macroeconomic indicators (interest rates, venture capital trends)

---

## Tools & Technologies
- Python (pandas, numpy)
- Data Visualization: matplotlib
- Jupyter Notebook
- Git & GitHub

---

## 📎 Author
Data Analyst Portfolio Project  
Focused on business-oriented data analysis and real-world datasets.