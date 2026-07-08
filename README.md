# quantium-data-analytics
Data analytics simulation based on Quantium's retail analytics work — customer segmentation, trend analysis, and commercial insights.
# Quantium Data Analytics — Retail Category Review

## Overview
This project analyses retail transaction data for a supermarket chain to uncover customer purchasing trends and behaviours in the chips category, supporting a strategic recommendation for an upcoming category review.

The analysis focuses on understanding **who buys chips, how much they spend, and what drives that spend** across different customer segments — using `LIFESTAGE` (life stage, e.g. young singles, families with children) and `PREMIUM_CUSTOMER` (price/quality tier: budget, mainstream, premium) as the key segmentation variables.

## Objective
To identify high-value customer segments and purchasing drivers, and translate these into clear, commercially actionable recommendations for a Category Manager.

## Approach
1. **Data cleaning & validation** — high-level summary checks, outlier detection and removal, data format correction across transaction and customer behaviour datasets
2. **Feature engineering** — derived pack size and brand name from product name fields
3. **Exploratory analysis** — examined purchasing metrics (spend, frequency, unit price) across `LIFESTAGE` and `PREMIUM_CUSTOMER` segments
4. **Insight generation** — identified which segments drive category sales and why
5. **Commercial recommendation** — summarised findings into a clear, actionable strategy

## Tools
Python (pandas, matplotlib/seaborn) — analysis and visualisation

## Files
- `quantium_chips_analysis.ipynb` — full analysis notebook
- `quantium_chips_analysis.pdf` — submitted findings (PDF export)
- Data files not included (proprietary Quantium simulation data)

## Skills Demonstrated
Data cleaning, outlier detection, feature engineering, exploratory data analysis, customer segmentation analysis, commercial insight generation, Python (pandas)
