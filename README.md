A data-driven analysis exploring the key factors influencing national happiness scores worldwide using multiple linear regression and statistical modeling in R.

🚀 Project Overview
This project investigates the relationship between economic, demographic, and social factors and happiness levels across different countries. Using data from the World Happiness Report (2021) and World Data by Country (2020), the study applies data cleaning, exploratory data analysis (EDA), correlation analysis, and predictive modeling to determine the most influential variables in predicting happiness scores.

🎯 Objective
Identify key factors that contribute to a nation's happiness.
Develop a predictive model for happiness scores using multiple linear regression.
Compare different models to evaluate accuracy and interpretability.
Use statistical hypothesis testing to validate assumptions about happiness determinants.

📊 Data Sources
World Happiness Report 2021 – Contains happiness scores for various countries.
World Data by Country 2020 – Includes socioeconomic indicators such as GDP per capita, urbanization rates, life expectancy, and more.

🛠️ Tools and Technologies
Programming Language: R

Key Libraries:
📊 ggplot2, tidyverse, corrplot, GGally – Data visualization and EDA
🔢 stats, caTools – Statistical modeling and regression analysis
🗺️ maps, ggsci – Geospatial analysis and mapping
📈 reshape2, corrgram – Correlation analysis and heatmaps

📌 Methodology
Data Cleaning & Preparation

Merging datasets from different sources
Handling missing values and renaming columns
Assigning countries to continents for comparative analysis
Exploratory Data Analysis (EDA)

Correlation heatmaps to identify key factors influencing happiness
Geospatial visualization of global happiness distribution
Comparative analysis of happiness across continents
Statistical Modeling & Hypothesis Testing

Building multiple linear regression models to predict happiness scores
Evaluating the significance of variables (GDP per capita, life expectancy, urbanization, etc.)
Performing residual diagnostics to validate model assumptions
Model Comparison & Performance Evaluation

Comparing Adjusted R² scores to determine the best model
Analyzing the impact of log transformations on model accuracy
Visualizing predicted vs. actual happiness scores

🔍 Key Findings
Life Expectancy and GDP per Capita are the strongest predictors of happiness.
Urbanization rate has a weaker correlation with happiness compared to GDP and life expectancy.
South Asia and Africa have the lowest happiness scores, while North America, Europe, and Australia rank highest.
Linear regression models achieved ~67% accuracy in predicting happiness scores.

🏆 Best Model for Prediction
After testing multiple models, Model-2 (GDP per capita + Life Expectancy) was identified as the most accurate and interpretable predictor of happiness scores.

Model	Adjusted R²	Key Variables
Model-1 (GDP + Urbanization + Life Expectancy)	0.6618	GDP, Life Expectancy
Model-2 (GDP + Life Expectancy)	0.6550	GDP, Life Expectancy
Model-3 (GDP + Urbanization + Life Expectancy + Suicide Rate + Population Growth)	0.6550	GDP, Life Expectancy

🏗️ Future Enhancements
Implement machine learning models (Random Forest, XGBoost) to improve prediction accuracy.
Use feature engineering to extract additional insights from demographic variables.
Explore clustering techniques (e.g., K-Means) to categorize countries based on happiness determinants.

🤝 Contribution
If you're interested in expanding this analysis, feel free to fork the repository and submit pull requests. Suggestions for incorporating deep learning, NLP, or alternative datasets are welcome!

