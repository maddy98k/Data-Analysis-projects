# Telco Customer Churn Analysis

## Project Overview

This repository contains an exploratory data analysis (EDA) project for Telco customer churn using the `telco_churn.csv` dataset.

The notebook `cutomer_churn.ipynb` performs data cleaning, transformation, and visualization to uncover churn drivers and support business recommendations.

## Files

- `cutomer_churn.ipynb` - Jupyter notebook with EDA, data cleaning, visualizations, and insights.
- `telco_churn.csv` - Telco churn dataset used for analysis.

## Key Insights

- The churn rate is approximately **26.5%**, meaning around one in four customers left the service.
- **Month-to-month contracts** show the highest churn rates, while one-year and two-year contracts have stronger retention.
- Customers paying by **electronic check** are more likely to churn.
- **Short tenure** is a major churn signal: customers are most likely to leave within the first months.
- Customers without **tech support** or **online security** are more likely to churn.
- **Senior citizens** churn at higher rates than non-senior customers.

## Recommended Analysis Flow

1. Load and inspect the dataset
2. Clean numeric columns such as `TotalCharges`
3. Convert categorical features for analysis
4. Visualize churn distribution and key drivers
5. Summarize insights for stakeholders

## How to Run

1. Clone or download this folder to your local machine.
2. Open the `cutomer_churn.ipynb` notebook in Jupyter Notebook or Jupyter Lab.
3. Run the notebook cells sequentially.

## Required Libraries

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`



