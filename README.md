# Air-Quality-anlysis-Prediction-using-ML
#Project Objectives
-->Predict the Air Quality Index (AQI) based on pollutant levels.

-->Apply and compare multiple regression algorithms to determine the best-performing model.

-->Perform data analysis to understand the relationship between pollutant levels and AQI.

-->Visualize pollutant distribution, trends, and AQI predictions for better environmental insight.

#Dataset Overview
Total Records: 29,531 rows × 16 columns

Target Variable: AQI

Main Features:

SO₂ (Sulfur Dioxide)

NO₂ (Nitrogen Dioxide)

RSPM (Respirable Suspended Particulate Matter)

SPM (Suspended Particulate Matter)

#Data Split
Training Set: 70%

Testing Set: 30%

 #Machine Learning Models Implemented
The following models were trained and evaluated:

Linear Regression

Lasso Regression

Decision Tree Regressor

Random Forest Regressor ✅ (Best Performance)

Best Performing Model: Random Forest
After comparing all models using R² Score, MAE, and RMSE, the Random Forest Regressor was found to be the most accurate and reliable for predicting AQI. Its ability to handle non-linear relationships and reduce overfitting contributed to its success in this project.


# Tech Stack
Python

Jupyter Notebook

Libraries Used:

pandas

numpy

matplotlib

seaborn

scikit-learn

joblib 

