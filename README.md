# Analysis-on-steel-industry-using-ML

Energy Consumption Prediction in the Steel Industry
Overview:

This project predicts energy consumption in the steel industry using machine learning.
The steel sector is vital for economic development, but it also contributes heavily to carbon emissions.
Our work aims to support eco-friendly production methods by building predictive models that can guide sustainable operations.

 Objective:

Predict energy consumption in steel manufacturing.

Enable better decision-making for sustainability and efficiency.

Highlight the best-performing model for accurate predictions.

Dataset:

Size: 35,040 records

Features: 11 variables (4 categorical, 7 continuous)

Preprocessing:

Encoded categorical features (WeekStatus, Day_of_week, Load_Type)

Removed outliers using the IQR method

Ensured data quality with no missing values

EDA Highlights:

Positive correlation between electricity usage and CO₂ emissions

Time-series plots revealed fluctuating energy demand with sharp spikes

Outlier analysis improved model stability

Best Model :– XGBoost

After experimenting with various models, XGBoost emerged as the top performer:

Train-Test Split: 80-20

R² Score: 0.9911


Delivers high accuracy

Robust for large datasets
