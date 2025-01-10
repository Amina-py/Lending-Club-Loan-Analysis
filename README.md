# Lending-Club-Loan-Analysis and Prediction
## Overview
This project involves a comprehensive analysis of the Lending Club loan dataset, utilizing SQL, Python, and Power BI to extract insights and build predictive models. The goal is to understand the factors contributing to loan defaults and leverage predictive analytics to improve decision-making processes. This repository includes SQL queries, Python code for predictive modeling, and Power BI dashboards for data visualization.

## Objectives
Data Analysis: Explore borrower and loan attributes to identify key factors affecting loan defaults.
Predictive Modeling: Build machine learning models to predict loan default likelihood.
Data Visualization: Create interactive dashboards to present insights dynamically.
Recommendations: Provide actionable insights to reduce default rates and improve lending strategies.

## Analysis Highlights
### 1. SQL Analysis
A detailed SQL analysis uncovered critical insights into loan defaults:
1. Default Rate: Charged-off loans account for 19.74% of the dataset.
2. High-Risk Borrower Profiles: Borrowers with the following attributes exhibit the highest default rates:
a. Employment Titles: Manager, Supervisor, Teacher, Owner.
b. Employment Length: 10+ years.
c. Home Ownership: Mortgage and Rent.
3. Loan Attributes:
Loans with terms of 36 or 60 months and moderate-to-high loan amounts show the highest default rates.
Debt consolidation loans have the highest default rates across all grades, followed by credit card and home improvement loans.
4. Interest Rates: Charged-off loans have an average interest rate of 54.8%, higher than fully paid loans.
5. Seasonal Trends:
October and July record the highest defaults, while December has the lowest.
6. Credit Lines and Public Records:
Borrowers with high open credit lines default less.
Borrowers with none or low public records default more frequently.

### 2. Predictive Analysis Using Python
A machine learning model was developed to predict loan defaults, achieving an accuracy of 80%. The key steps included:
Feature Engineering:
Created new features and transformed columns such as loan term, home ownership, employment length, verification status, and loan purpose.
Data Visualization:
Visualized categorical features against the target variable.
Used a correlation heatmap to analyze numerical features.
Model Building:
Developed a Voting Classifier combining Random Forest, XGBoost, and Logistic Regression.
Integrated a column transformer for preprocessing and scaling.
Evaluation:
Achieved a prediction accuracy of 80%, demonstrating the model’s effectiveness in identifying potential loan defaults.

## Key Recommendations
Based on the analysis, the following recommendations were made to stakeholders:
1. Enhance Risk Assessment:
Focus on high-risk borrower profiles and loan purposes with stringent evaluation criteria.
2. Optimize Loan Policies:
Limit long-term, high-value loans and adjust interest rates to reduce default risks.
3. Leverage Predictive Models:
Integrate machine learning models into loan approval processes for better risk prediction.
4. Monitor Seasonal Trends:
Implement targeted interventions during months with high default rates (October, July).
5. Support Borrowers:
Offer financial literacy programs and flexible repayment plans to reduce defaults.

## Conclusion
This project demonstrates the power of data analytics and machine learning in understanding and predicting loan defaults. By combining insights gotten stakeholders can make data-driven decisions to optimize lending strategies, reduce risks, and improve profitability.
