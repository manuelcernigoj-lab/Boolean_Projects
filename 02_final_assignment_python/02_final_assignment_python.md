# Software Professionals Salary & Indian Startup Funding — Data Analysis with Python

## Objective
Final assignment of the Python module, split into two parts. **Part 1** explores the Software Professionals Salary dataset (~22,770 records, 8 variables) covering job roles, salaries in INR, company ratings and locations across the Indian tech industry. **Part 2** works with three annual datasets on Indian startup funding (2019–2021), individually provided as separate .csv files. Both datasets were sourced from Kaggle and adapted by the instructor.

## Platform & Tools
**Language:** Python | **Environment:** VS Code | **Format:** Jupyter Notebook (.ipynb)
**Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Requests, OS

## Results

**Part 1 — Software Professionals Salary**
Performed data exploration (shape, unique values, substring filtering) and aggregations via `groupby`. Integrated a **live currency conversion API** (ExchangeRate-API) to derive a real-time `Salary USD` column. Identified the highest-paying and most-reported companies. Generated a scatterplot of avg. Salary vs. avg. Rating, detecting a significant **outlier** caused by a data entry anomaly.

**Part 2 — Indian Startup Funding (2019–2021)**
Used a **for loop** with `pd.concat` to programmatically load and stack the three annual files into a single DataFrame, adding a `Year` tag at each iteration. Applied a custom reusable **string-cleaning function** to handle inconsistent formatting and convert columns to correct numeric types. Performed investor ranking analysis across years. In the final task, both datasets were **merged via inner join** on city/location to cross-analyse salary, company ratings and funding metrics. Concluded with a labelled scatterplot identifying **Mumbai** as the standout city for both employee salary and total startup funding received.

---
*Tools: Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook | Dataset: Kaggle (adapted)*
