An advanced machine learning approach to predicting national happiness scores worldwide using tree-based models, ensemble learning, and deep learning in Python & R.

📌 Project Overview
This project explores the relationship between economic, demographic, and social factors and happiness levels across different countries. Using data from the World Happiness Report (2021) and World Data by Country (2020), we apply statistical analysis and machine learning models to determine the most influential variables in predicting happiness scores.

The project originally used multiple linear regression, but we have now upgraded it with advanced ML models, including Random Forest, Gradient Boosting (XGBoost, LightGBM), and Artificial Neural Networks (ANNs) to improve prediction accuracy.

🎯 Objective
Identify key factors contributing to national happiness.
Compare traditional regression models vs modern ML models.
Develop an optimized predictive model for happiness scores.
Use SHAP values & feature importance for model interpretability.

🛠️ Tools & Technologies
Programming Languages: R, Python
Machine Learning Models:
Linear Regression (Baseline)
Random Forest Regressor
XGBoost & LightGBM
Artificial Neural Network (ANN)
Key Libraries:
R: tidyverse, ggplot2, corrplot, GGally
Python: pandas, scikit-learn, xgboost, lightgbm, tensorflow, shap
Visualization Tools: matplotlib, seaborn, plotly

📊 Data Sources
World Happiness Report 2021
World Data by Country 2020

📌 Methodology
Data Cleaning & Feature Engineering

Merge datasets, handle missing values, rename variables
Assign continents for regional comparisons
Exploratory Data Analysis (EDA)

Correlation heatmaps to identify key predictors
Geospatial visualization of happiness distribution
Machine Learning Modeling

Baseline: Linear Regression
Advanced ML Models:
Random Forest Regressor
XGBoost & LightGBM
Artificial Neural Networks (ANNs)
Model Evaluation & Comparison

RMSE, R², MAE scores
SHAP value analysis for interpretability
Final Model Deployment

Best-performing model selected
Interactive dashboard for prediction (Future Work)

🔍 Key Findings
Life Expectancy & GDP per Capita remain the most important happiness predictors.
XGBoost performed best, outperforming linear regression by 10%+ accuracy.
SHAP values confirm feature importance, enhancing model interpretability.

🚀 Next Steps
Deploy an interactive web app with Streamlit.
Experiment with deep learning models (LSTMs, Transformers).
Fine-tune models using Optuna for hyperparameter optimization.

🤝 Contributions
This project is open for collaboration! Feel free to fork the repo, improve models, or add new data sources for more insights.

