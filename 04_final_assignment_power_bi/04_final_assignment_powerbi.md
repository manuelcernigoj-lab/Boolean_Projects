# European Public Opinion on Climate Change — Interactive Dashboard in Power BI

## Objective
Final assignment of the Data Visualisation & Power BI module. The dataset is derived from the **European Social Survey (ESS) Round 8 — 2016/17**, a large-scale survey covering social attitudes across Europe (40,000+ respondents, 24 countries). Two files were provided: `Climate_Data_Clean.csv` (39 encoded variables, climate change topic) and `variables.csv` (mapping of variable codes to full questions and short labels). The task simulated a real-world brief from a European policy institute, requiring a dashboard to explore European attitudes towards climate change.

## Platform & Tools
**Tool:** Microsoft Power BI | **Data Preparation:** Power Query (M language)
**Key operations:** data cleaning, column unpivoting, variable decoding via merge with mapping table, data type formatting, data model management, DAX measures and calculated columns, cross-page interactive filtering via Country Selector slicer

## Results
Delivered a **3-page interactive dashboard**, each page dedicated to a thematic area of the survey:

**Page 1 — General Opinion:** 93.21% of respondents believe climate is changing; 45.52% attribute it to human activity. Visualised via KPI cards, donut chart and stacked bar charts by country.

**Page 2 — Worry & Responsibilities:** 74.02% report worry about climate change; 71.49% feel personal responsibility to act. Includes a worry-level breakdown table across energy-related concerns.

**Page 3 — Energy:** Treemap of support levels for 6 energy sources (Solar 77%, Wind 73%, Nuclear 17%); stacked bar charts filterable by energy source and country. Italy-specific view highlights above-average solar support (90%).

All pages share a **Country Selector** slicer enabling dynamic cross-country comparison throughout the report.

---
*Tools: Power BI · Power Query · DAX | Dataset: European Social Survey Round 8, 2016/17*
