# Environmental-Monitoring-Pollution-Control
#project : plastic waste detection project
-------------------------------------------------------------------------------------------------------------------------
Week-1 (what I did)

Dataset: “Plastic Waste Around the World.”

Task: Exploratory Data Analysis (EDA) + Preprocessing.

I explored the dataset by looking at its features, distributions, and checking for missing values. I then preprocessed the data using WEKA, where I handled the missing values and applied cleaning and normalization. After preprocessing, I submitted the cleaned dataset as my Week-1 work.

-------------------------------------------------------------------------------------------------------------------------
Week-2: Model Training

In Week-2, the focus was on training machine learning models to predict total plastic waste (mt) using the preprocessed dataset from Week-1. The following steps were performed:

Data Split: The dataset was split into training (80%) and testing (20%) sets with a fixed random seed (42) to ensure reproducibility.

Models Trained: Three regression models were applied:

Linear Regression (baseline)
M5P (Model Tree)
Random Forest Regressor

Evaluation Metrics: Each model was evaluated using Correlation Coefficient, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

Model Comparison:
Linear Regression showed weak correlation (0.1654).
M5P improved correlation slightly (0.386) but with higher error.
Random Forest achieved the best performance with the highest correlation (0.4575) and the lowest MAE (0.0407).

Final Model Selection: Based on the results, Random Forest was chosen as the best-performing model. The trained model was saved as RandomForest_BestModel.model for further evaluation in Week-3.

-------------------------------------------------------------------------------------------------------------------------
week 3 - Weka Regression Project

This repository contains a Weka-based regression analysis using a dataset of **Actual vs Predicted values**.

## Overview
- Prepared a CSV file with **Actual and Predicted values**.
- Loaded the CSV in **Weka** and visualized the data using the **Visualize tab**.
- Generated a **scatter plot** to observe how predictions compare with actual values.
- Examined key regression metrics: Correlation coefficient, MAE, RMSE, Relative errors, and Total instances.

## Observations
- The scatter plot appears **scattered rather than diagonal**.
- Reason: Predicted values are almost constant, while Actual values vary, resulting in a **low correlation coefficient (0.1279)**.
- Despite small MAE/RMSE, the model does not follow the trend of actual values.

## Files in this Repository
- `Actual_Predicted.csv` – Dataset with Actual and Predicted values.
- `ActualvsPredicted.png` – Scatter plot visualization from Weka.
- `Weka_Visualize_Session.arff` – Saved Weka session for reproducibility.

## Conclusion
- Demonstrates how Weka can be used for **visualizing regression results** and analyzing model performance.
- Scatter plot and metrics provide insights into the **accuracy and limitations of the model**.

  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------
