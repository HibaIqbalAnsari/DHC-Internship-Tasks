# DHC-Internship-Tasks

# TASK-1
Task Objective: Perform Exploratory Data Analysis (EDA) on the Iris dataset.

Dataset Used: Iris dataset (seaborn.load_dataset('iris'))

Models Applied: No machine learning models were used; the task was purely EDA.

Key Results and Findings:
- Pair Plot: Iris-setosa is clearly distinct. Versicolor and Virginica overlap but are separable by petal dimensions. Strong positive correlations for petal length/width within species.
- Histograms: Showed feature distributions; sepal_width is somewhat normal, petal_length and petal_width are multi-modal due to species differences.
- Box Plots: Highlighted distinct ranges per species, with Iris-setosa having smaller feature values. Some sepal_width outliers observed.

# TASK-2
Task Objective: Predict next day's stock closing price.

Dataset Used: Apple Inc. ('AAPL') historical stock data (2021-2024) via yfinance. Features: 'Open', 'High', 'Low', 'Volume'. Target: 'Next_Close'.

Models Applied: Linear Regression.

Key Results and Findings:
- Mean Squared Error (MSE): 4.94
- R-squared (R2 Score): 0.96
The model shows high predictive accuracy for short-term stock prices.

# TASK-3
Task Objective: Predict heart disease risk using a classification model.

Dataset Used: heart_disease_uci.csv.

Models Applied: Logistic Regression.

Key Results and Findings:
- Data Preprocessing: Cleaned data by dropping irrelevant columns, converting 'num' to 'target', imputing missing numerical (median) and categorical (mode) values, and one-hot encoding.
- Model Performance: 84.24% accuracy, 0.91 ROC AUC score.
- Top 10 Features: cp_atypical angina, ca_2.0, sex_Male, cp_non-anginal, ca_1.0, exang_True, ca_3.0, cp_typical angina, slope_flat, oldpeak.
