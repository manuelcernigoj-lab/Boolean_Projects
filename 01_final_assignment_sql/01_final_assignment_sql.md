# European Soccer Database — Relational Data Analysis with SQL

## Objective
Final assignment of the Databases & SQL module. The dataset, adapted from Kaggle and provided as four .csv files (leagues, match, team, player — totalling ~37,000 records), was loaded into Google BigQuery for relational analysis. A relational schema (ER diagram) was designed to map primary and foreign key relationships across the four tables.

## Platform & Tools
**Language:** SQL (Standard SQL) | **Environment:** Google BigQuery
**Key features used:** JOINs, GROUP BY aggregations, CTEs (WITH clauses), CREATE TABLE AS, CASE WHEN, window functions (RANK OVER PARTITION BY), DATE_DIFF, POW

## Results
**Q3** — Calculated the dataset's time span: **2,868 days** of match data across 8 seasons.

**Q4–Q5** — Aggregated home goals (min, avg, mid-range, max, sum) by season and league via multi-table JOINs. Identified the **England Premier League 2009/2010** as the highest-scoring season (645 goals). Also flagged a data quality issue in league naming conventions.

**Q6–Q7** — Created a derived table (PlayerBMI) with unit-converted weight/height and calculated BMI. Filtered for optimal BMI range (18.5–24.9): **10,197 players** within range, **863** outside.

**Q8–Q9** — Used CASE WHEN aggregation and RANK window functions to identify top-scoring teams per season. **FC Barcelona** led the most recent season (112 goals); **Real Madrid CF** ranked first across the most seasons (4).

**Q10** — Built a TopScorer table and applied a self-join to generate all unique pair combinations among the top 10 teams: **45 pairs**, consistent with C(10,2).

---
*Tools: SQL · Google BigQuery · Lucid.app | Dataset: European Soccer Database (Kaggle, adapted)*
