
# Sales Prediction with Advertising Data

## Project Overview
This project involves analyzing the impact of advertising budgets across different channels (TV, Radio, Newspaper) on sales. It uses a simple linear regression model to understand relationships, predict sales, and provide marketing recommendations.

## Problem Statement
The goal is to determine which advertising channels are most effective in driving sales and to provide data-driven recommendations for budget allocation to optimize return on investment.

## Data Source
The analysis uses the `Advertising.csv` dataset, which contains records of advertising spend for TV, radio, and newspaper, along with corresponding sales figures.

## Analysis Overview
1.  **Data Loading & Initial Exploration:** Loaded the dataset, checked for missing values, and reviewed descriptive statistics.
2.  **Univariate Linear Regression (TV vs Sales):** Explored the relationship between TV advertising and sales, built a linear regression model, interpreted its coefficients, and made sales predictions.
3.  **Model Visualization:** Visualized the regression line on a scatter plot to illustrate the model's fit.
4.  **Multi-channel Comparison:** Built separate linear regression models for TV, radio, and newspaper against sales to compare their individual effectiveness.

## Key Findings
*   **Positive Relationships:** All three advertising channels (TV, Radio, Newspaper) show a positive correlation with sales.
*   **Radio's Strong Impact:** Radio advertising has the strongest relationship with sales, yielding the highest sales increase per unit of budget spent.
*   **TV's Consistent Impact:** TV advertising also shows a significant and consistent positive impact on sales.
*   **Newspaper's Weak Impact:** Newspaper advertising has the weakest and least consistent relationship with sales.

## Recommendations
Based on the analysis, it is recommended to prioritize **Radio advertising** for budget allocation due to its superior return on investment. While TV advertising is also effective, further optimization should focus on channels with the highest impact. Newspaper advertising should be re-evaluated or de-prioritized.

## How to Run the Notebook
This analysis was performed in a Google Colaboratory notebook.
1.  Open the `Advertising_Budget_vs_Sales_Prediction_Emmanuel_Ok.ipynb` file in Google Colab.
2.  Run all cells to replicate the analysis and visualizations.

## Technologies Used
*   Python
*   pandas (for data manipulation)
*   numpy (for numerical operations)
*   matplotlib (for plotting)
*   seaborn (for enhanced visualizations)
*   scikit-learn (for linear regression modeling)

## Author
[Emmanuel Okeowo](https://github.com/EMMANUELM0147)
