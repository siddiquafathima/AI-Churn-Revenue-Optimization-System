AI-Driven Customer Churn Prediction & Revenue Optimization System
 
 Project Overview:
This project builds an end-to-end AI system to:
Predict customer churn using Machine Learning
Improve churn detection using threshold optimization
Generate automated retention strategies
Estimate real business revenue impact
Provide an AI-style assistant for customer-level explanations
The system moves beyond prediction and integrates business decision intelligence.

Problem Statement:
Customer churn leads to major revenue loss in subscription-based businesses.
Traditional ML projects stop at prediction accuracy.
This project focuses on:
Maximizing recall for churn detection
Translating predictions into actionable business strategies
Estimating financial impact

System Architecture:
Data Preprocessing
→ Model Training (Logistic Regression, Random Forest)
→ Threshold Optimization
→ Feature Importance Analysis
→ Retention Strategy Engine
→ Revenue Impact Estimation
→ AI Business Assistant Layer

 Dataset:
Telco Customer Churn Dataset
7043 rows
21 original features
After encoding: 30 features
Target variable: Churn (0/1)

 Machine Learning Models Used:
1️.Logistic Regression (Baseline)
Accuracy: 80%
Recall (Churn): 56%

2️.Random Forest
Accuracy: 79%
Used for feature importance analysis

3️.Threshold Optimization (0.5 → 0.3)
Recall improved from 56% → 76%
Business-focused optimization

Key Business Insights:
Top churn drivers:
Total Charges
Tenure
Monthly Charges
Contract Type
Fiber Optic Internet

Insights:
Short-tenure customers churn more
Month-to-month contracts are high risk
Higher monthly charges increase churn probability

Retention Strategy Engine:
The system categorizes customers into:
Critical Risk
High Risk
Medium Risk
Low Risk

Based on:
Churn probability
Tenure
Total spending
It automatically assigns:
Discount offers
Loyalty packages
Engagement emails
Appreciation messages

Revenue Impact Estimation:
Estimated Results (Test Sample):
Revenue loss without model: ₹67,32,000
Revenue saved using model: ₹51,12,000
Retention campaign cost: ₹5,42,000
Net Business Gain: ₹45,70,000
This transforms the project from ML prediction to AI-powered revenue protection system.

AI Business Assistant Layer:
Built a simulated AI assistant that:
Explains churn probability
Shows risk level
Recommends retention action
Provides reasoning behind decisions

Example Query:
“Why is customer 2280 high risk?”

Output:
Churn Probability: 0.68
Risk Level: High
Tenure: 8 months
Recommended Action: 20% discount
Explanation based on behavioral factors

Tech Stack:
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Jupyter Notebook

Key Achievements:
✔ Improved churn recall to 76%
✔ Integrated ML with business decision system
✔ Built revenue impact estimator
✔ Designed AI-style assistant architecture

Future Improvements:
Deploy using Streamlit
Integrate with OpenAI API
Add SHAP explainability
Real-time churn monitoring dashboard

#Project Outputs:

## Revenue Impact
![Revenue Impact](revenue_impact.png)

## Feature Importance
![Feature Importance](feature_importance.png)

## AI Assistant Output
![AI Assistant](ai_assistant_output.png)

Author:
Siddiqua Fathima
MCA Student | Aspiring ML Engineer

Includes an AI decision assistant layer
It demonstrates both technical depth and business thinking.
