# Superstore Profitability Analysis - Portfolio Project

## Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](problem-statement)
- [Data Source](data-source)
- [Key Performance Indicators](key-performance-indicators)
- [Data Cleaning](data-cleaning)
- [Analysis Overview](analysis-overview)
- [Regression Model](regression-model)
- [Tableau Dashboard](tableau-dashboard)
- [Limitations](limitations)
- [Recommendations](recommendations)
- [Tools Used](tools-used)
- [Author](author)

## Project Overview

 Analyze Superstore's historical sales data to uncover profit trends across regions, product sub-categories, and customer segments. Provide actionable insights to guide strategy.

 ## Problem Statement

 Retail businesses face volatile markets. Superstore wants to improve its profitability through data-driven decision-making.

This project analyzes 4 years of U.S. sales and profit data to:

- Uncover underperforming regions and products

- Measure discount effectiveness

- Recommend better pricing and inventory strategies

## Data Source

Source: Kaggle – Superstore Dataset

Records: 9,994 rows × 21 columns

File: Superstore_Sales_Analysis.xlsx

## Key Performance Indicators (KPIs)

- Total Sales

- Quantity Sold

- Profit

- Profit Margin

- Profit per Unit

## Data Cleaning

Performed in Excel:

- Removed unneeded columns

- Created Order Year, Order Month, Profit per Unit, and Profit Margin

- No missing values or duplicates

  ## Analysis Overview

- Region Analysis: West outperformed; South underperformed

- Sub-Category Analysis: Tables & Bookcases lost money

- Discount Analysis: Weak negative correlation with profit (R² low)

  ## Regression Model

- Model: Linear Regression – Profit vs. Discount

- Result: Low correlation (discounting not a strong driver of profit)

- Interpretation: Other factors (demand, cost, seasonality) likely more important

  ## Tableau Dashboard

Interactive dashboard includes:

- Filters by Region, State, Sub-Category

- Profit & Sales trendlines

- Heatmaps and bar char
  ### [Link](https://public.tableau.com/app/profile/jean.tinialaou/viz/SuperstoreSalesProfitAnalysis_17521953763290/Dashboard1)

  ## Limitations

- Limited modeling due to high categorical data

- Outliers skewed profit/sales values

- Focused on profit; ignored external economic factors

  ## Recommendations

- Cap discounts at 5–10%

- Review loss-making categories

- Add multivariate analysis with external data

- Use time-series forecasting and customer segmentation

 ## Tools Used

 Excel – cleaning, feature engineering, and regression analysis [Download from this repo](./Superstore%20Sales%20%26%20Profit%20Analysis%20-%20Portfolio%20Project.xlsx) | [Source on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

Tableau – visual dashboard

Markdown – documentation

## Author

Jean Tinialaou

MITA Program at Rutgers Business School

jean.tinis@gmail.com | www.linkedin.com/in/jean-tinialaou  



