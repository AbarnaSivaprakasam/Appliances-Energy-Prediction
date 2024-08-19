# Appliances-Energy-Prediction
The project titled "Appliances Energy Prediction" provides a comprehensive analysis of energy consumption data collected from a house in Belgium over 4.5 months.


## Introduction
The objective is to understand and predict energy consumption patterns using data analysis and predictive modeling.
## Exploratory Data Analysis (EDA)
Dataset Overview: The dataset contains temperature and humidity readings collected every 10 minutes from a house with 7 rooms and 1 bathroom.
Data Cleaning: Steps include converting date columns, splitting them into separate components, creating new columns for total energy consumption, and removing redundant or uninformative columns.
Outlier Analysis: Identified outliers were analyzed but not removed, as they provided valuable insights.
Missing Value & Duplicate Analysis: The dataset had no missing values or duplicates.
Statistical Descriptive Analysis: Measures like mean, median, standard deviation, and quartile ranges were calculated.
Data Visualizations: Included daily and weekly power consumption analysis and correlation analysis.
## Train-test Dataset Creation
The dataset was split into 80% training and 20% testing sets to evaluate model performance.
## Predictive Models
Various regression models were applied to predict energy consumption:
Linear Regression: Performed poorly due to the lack of linearity in the data.
Support Vector Machines (SVM): Tried different kernels but results were unsatisfactory.
Random Forest: Showed the best performance with the highest R-squared value.
XGBoost: The 'dart' booster provided competitive results, though not as good as Random Forest.
K-Nearest Neighbors (KNN): Performed better than linear models but not as well as Random Forest or XGBoost.
## Conclusion
Random Forest and XGBoost with 'dart' were the top-performing models. The importance of selecting models suited to the data's characteristics was emphasized.
