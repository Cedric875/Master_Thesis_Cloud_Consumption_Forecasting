# Master_Thesis_Cloud_Consumption_Forecasting

## Code Style
- Python --> Jupyter-Notebooks files (ipynb)
- Used Databricks with clusters

## Folders
- Data_Queries
  - Create_Datasets (2 Main ones and saved raw datasets with enhancements)
    -  df_aggregated_month_populated_btp_core --> final dataset with all features and all months
    -  df_filtered_active_customers --> subset of df_aggregated_month_populated_btp_core with only customers having at least 1 active contract throughout whole period
  
- Data_Analysis
  - Data_Analysis_BTP_Core --> Analysis of data

- Data_Modeling
  - Naive_Forecasting_Model --> baseline model/naive forecasting models for both datasets and 3 horizons
  - Linear_Regression_Global --> 'global' linear regression forecasting models for both datasets and 3 horizons
  - Linear_Regression_Per_Customer --> linear regression forecasting models per customer for both datasets and 3 horizons
  - XGBoost --> XGboost forecasting models for both datasets and 3 horizons
  - Prophet --> Prophet forecasting models per customer for both datasets and 3 horizons
  - Model_Evaluation --> performance metrics for both datasets and 3 horizons for all models except Prophet for visualization
