# Boolean Data Analytics Master — Final Assignments Repository

## Overview
Comprehensive Master's program in Data Analytics focused on end-to-end data workflows, from data extraction and transformation to analysis and visualization. Core areas include advanced SQL for relational databases, Python for data processing and statistical analysis, and Power BI for professional reporting (PL-300 oriented).

---

## Repository Structure
```
Boolean_Projects/
├── 01_final_assignment_sql/
│   ├── data/
│   ├── 01_Final Assignment SQL.docx
│   ├── 01_final_assignment_sql.md
│   └── erd_schema.png
│
├── 02_final_assignment_python/
│   ├── data/
│   │   ├── fnd/
│   │   └── sps/
│   ├── plots/
│   ├── 02_Final Assignment Python 1.ipynb
│   ├── 02_Final Assignment Python 2.ipynb
│   └── 02_final_assignment_python.md
│
├── 03_final_assignment_python_statistics/
│   ├── data/
│   ├── plots/
│   ├── 03_Final Assignment Python Statistics.ipynb
│   └── 03_final_assignment_python_statistics.md
│
├── 04_final_assignment_power_bi/
│   ├── data/
│   ├── documents/
│   ├── media/
│   ├── 04_final_assignment_powerbi.md
│   └── Climate Data Dashboard.pbix
│
├── 05_final_assignment_ml_and_web_scraping/
│   ├── data/
│   ├── plots/
│   ├── 05_final_assignment_ml_web_scraping.md
│   ├── 05_final_assignment_p1_ml.ipynb
│   └── 05_final_assignment_p2_web_scraping.ipynb
│
└── README.md
```

---

## Assignment Projects

### 1. European Soccer Database Analysis
- **Objective:** Analyze team and player performance across European leagues  
- **Tools:** SQL (Google BigQuery)  
- **Results:** Generated team rankings, player BMI insights, and match-level statistics from ~26K games using advanced querying (JOINs, CTEs, window functions)

### 2. Software Salaries & Indian Startup Funding
- **Objective:** Identify salary and funding patterns across Indian cities  
- **Tools:** Python (Pandas, NumPy, Matplotlib, Seaborn), API integration  
- **Results:** Delivered cross-dataset insights on compensation and startup funding; improved consistency via cleaning, currency normalization, and outlier handling  

### 3. Food Consumption & Emissions Analysis
- **Objective:** Assess relationships between food consumption and CO₂ emissions  
- **Tools:** Python (SciPy, Seaborn)  
- **Results:** Identified consumption patterns across 11 food categories; validated statistical significance via permutation testing  

### 4. EU Climate Change Opinion Dashboard
- **Objective:** Analyze public opinion on climate change across EU countries  
- **Tools:** Power BI (Power Query, DAX)  
- **Results:** Built a 3-page interactive dashboard (40K+ respondents, 24 countries) enabling cross-country comparison of climate perception, concern levels, and energy preferences  

### 5. Happiness Modeling & Literacy-Salary Analysis
- **Objective:** Model drivers of happiness and explore literacy-income relationships  
- **Tools:** Python (Scikit-learn, Statsmodels, web scraping)  
- **Results:** Developed regression models evaluated via R² and MAE; produced a multi-variable visualization linking literacy, salary, and population across cities  

---

## Notes
- Each folder contains:
  - Raw datasets (`data/`)
  - Analysis notebooks, SQL work or pbix files
  - Supporting visualizations (`plots/`)
  - A `.md` file documenting methodology, assumptions, and results  
- The repository reflects a modular progression from data extraction to modeling and visualization.

