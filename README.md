📊 Credit Score Classification & Analysis
🔍 Project Overview

This project predicts customer credit scores (Good, Standard, Poor) based on financial and behavioral data. It helps financial institutions assess creditworthiness and reduce risk.

🎯 Objective
Predict customer credit score using machine learning
Identify key factors affecting creditworthiness
Support better financial decision-making

📁 Dataset Features
Age
Annual Income
Monthly Inhand Salary
Number of Bank Accounts
Number of Credit Cards
Interest Rate
Outstanding Debt
Credit Mix
Payment Behaviour
Credit History Age

⚙️ Technologies Used
Python (Pandas, NumPy, Scikit-learn)
XGBoost
Power BI
Matplotlib & Seaborn

🔄 Project Workflow
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Handling Missing Values & Outliers
Handling Imbalanced Data (SMOTE & NearMiss)
Model Training & Evaluation
Model Comparison & Selection
Dashboard Creation (Power BI)

🤖 Models Implemented
Logistic Regression
Decision Tree
Random Forest
XGBoost (Best Performer)

📈 Results
XGBoost achieved the best performance
Accuracy: ~72%
Balanced evaluation using F1-score (weighted)
Better performance on original data compared to sampling techniques

📊 Dashboard Insights
Higher income → better credit score
Higher outstanding debt → poor credit score
Payment behaviour strongly impacts credit rating
Majority customers fall under Standard category

💾 Model Deployment
Model saved using Pickle (.pkl file) for reuse without retraining

🚀 How to Run
Load dataset
Run Jupyter Notebook
Train models or load saved model
Visualize insights using Power BI dashboard

👩‍💻 Author
Sakshi Davkhar
