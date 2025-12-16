# Tech Layoffs Analysis (2020–2024)

## 📖 Project Overview
This project analyzes global layoffs in the technology sector between 2020 and 2024.  
The objective is to identify trends, patterns, and insights related to workforce reductions across time, geography, and company characteristics.

The analysis provides a data-driven view of how major events such as the COVID-19 pandemic and the post-2022 tech correction impacted employment in the tech industry.

---

## 🎯 Objectives
- Analyze the evolution of tech layoffs over time (yearly and monthly trends).
- Identify which continents and regions were most affected.
- Explore relationships between layoffs, company size, funding, and industry.
- Provide actionable insights supported by data visualization.

---

## 📊 Dataset
Source: Kaggle – *Tech Layoffs 2020–2024*

The project uses multiple datasets, including:
- Layoff events by company and date
- Company attributes (industry, stage, funding)
- Geographic information (country, continent)

All datasets are stored in the `Data/` directory.

---

## 🛠️ Tech Stack
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**
- **Git & GitHub**

---

## 🧪 Data Processing
Key steps in the analysis:
- Data loading and integration from multiple sources
- Handling missing values and inconsistent formats
- Date parsing and feature engineering (year, month, year-month)
- Aggregations and group-by analysis
- Exploratory Data Analysis (EDA)

---

## 📈 Key Insights
- Layoffs peaked significantly during **2022–2024**, reflecting post-pandemic corrections.
- **North America** accounts for the majority of tech layoffs globally.
- Funding level and company size show strong relationships with layoff magnitude.
- Certain industries were disproportionately impacted during specific periods.

*(Detailed visualizations and explanations are available in the notebook.)*

---

## 📂 Project Structure
tech_layoffs_analysis/
│
├── Data/
│ ├── tech_layoffs_til_Q4_2024.csv
│ ├── tech_layoffs_location.csv
│ └── ...
│
├── Notebooks/
│ └── analysis_tech_layoffs.ipynb
│
├── README.md
└── requirements.txt

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Frencher3000/Tech-Layoffs-Analysis-2020-2024-.git

   Author

Felipe Arguello
Data Analyst | Marketing & Analytics
GitHub: https://github.com/Frencher3000