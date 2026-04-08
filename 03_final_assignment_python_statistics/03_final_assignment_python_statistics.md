# Food Consumption & Probability Distributions — Statistics with Python

## Objective
Final assignment of the Statistics with Python module, split into two parts. **Part 1** explores the Food Consumption dataset (~1,430 records) covering food consumption and CO2 emissions by country and food category (Kaggle, adapted). **Part 2** works with an unlabelled dataset of 7 columns (~1,000 records each), where each column contains data drawn from an unknown probability distribution to be identified.

## Platform & Tools
**Language:** Python | **Environment:** VS Code | **Format:** Jupyter Notebook (.ipynb)
**Libraries:** NumPy, Pandas, Matplotlib, Seaborn, SciPy

## Results

**Part 1 — Food Consumption & CO2 Emissions**
Applied `groupby` with `.describe()` to compute descriptive statistics (mean, median, IQR) by food category. Generated a multi-boxplot chart ordered by median CO2 emission, identifying **beef** as the category with both the highest median CO2 emission and the highest IQR — indicating the greatest variability across countries. Conducted a **permutation test** (2,000 iterations) to assess whether the difference in mean consumption between poultry (21.22) and fish (17.29) was statistically significant. With a p-value below the significance threshold (α = 0.05), **H0 was rejected**, confirming statistical significance.

**Part 2 — Probability Distribution Identification**
Loaded 7 unlabelled numerical columns and visualised each using **KDE (Kernel Density Estimation) plots** via a for loop. By comparing the empirical shapes against reference distributions generated with NumPy, each column was matched to its distribution: **Bernoulli, Normal, Continuous Uniform, Binomial, Poisson, Discrete Uniform** and **Exponential**. A side-by-side plot layout was used for visual confirmation of each match.

---
*Tools: Python · Pandas · NumPy · SciPy · Matplotlib · Seaborn · Jupyter Notebook | Dataset: Kaggle (adapted)*
