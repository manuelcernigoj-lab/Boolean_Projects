# World Happiness & Literacy vs. Salary — Machine Learning and Web Scraping with Python

## Objective
Final assignment of the Machine Learning & Web Scraping module, split into two parts. **Part 1** explores the World Happiness dataset (143 countries, 8 variables) to build and evaluate linear regression models predicting happiness scores. **Part 2** scrapes a live Indian census web page to extract city-level literacy and population data, then then links literacy rates to average salaries across Indian cities by merging with the `sps_fnd_loc` DataFrame from a previous assignment.

## Platform & Tools
**Language:** Python | **Environment:** VS Code | **Format:** Jupyter Notebook (.ipynb)
**Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Statsmodels, Scikit-learn
**Key techniques:** OLS simple linear regression (Statsmodels), multiple linear regression with train/test split (Scikit-learn), mean imputation, web scraping via `pd.read_html()`, bubble chart with annotations

## Results

**Part 1 — World Happiness & Linear Regression**
Explored variable distributions and built a **correlation heatmap** to identify predictors. Applied **mean imputation** to handle missing values. Fitted a simple OLS regression (Statsmodels) to quantify the effect of life expectancy on happiness score. Built a **multiple linear regression** model (Scikit-learn) using 4 predictors; R² and MAE on both splits confirmed no overfitting. 
**Part 2 — Web Scraping & Cross-Dataset Analysis**
Scraped a live census table via `pd.read_html()` and resolved a city name mismatch (`Delhi` → `New Delhi`) identified via set difference logic. Merged the resulting table with `sps_fnd_loc` and produced a **bubble chart** (literacy × salary × population) with city labels, identifying **Kolkata** as the city breaking the expected positive literacy–salary relationship.

---
*Tools: Python · Scikit-learn · Statsmodels · Pandas · Seaborn · Jupyter Notebook | Dataset: Kaggle (adapted), Census 2011 India (web)*
