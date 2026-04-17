Home Loan Risk Management
Financial institutions face significant capital risk when borrowers default on loans. This project implements a machine learning framework to predict loan default probability (TARGET) based on complex demographic, financial, and credit-related datasets.

Project Objective
The primary goal is to build a robust predictive model that identifies high-risk customers, enabling banks to make data-driven, risk-aware lending decisions and reduce potential financial losses.

Data Architecture
The project utilizes a multifaceted dataset structure to build a holistic borrower profile:

Application Data: Core demographic and financial attributes for 307,511 applicants.

Bureau Data: Historical credit data from the Credit Bureau.

Financial Histories: Includes POS/CASH balances, installment payments, and credit card histories to capture repayment behavior.

Key Technical Variables
AMT_INCOME_TOTAL: Total annual income.

AMT_CREDIT: Total loan amount requested.

DAYS_BIRTH / DAYS_EMPLOYED: Feature engineering for age and employment stability.

TARGET: Binary classification target (0: No Default, 1: Default).

Technical Stack & Methodology
Exploratory Data Analysis (EDA): Performed with Pandas, NumPy, Matplotlib, and Seaborn to identify correlations and data skews.

Predictive Modeling: Implemented several supervised learning algorithms including:

Logistic Regression for baseline performance.

Random Forest for non-linear feature interactions.

XGBoost (Gradient Boosting) for optimized predictive accuracy.

Performance Metrics: Models were evaluated using ROC-AUC, Accuracy, and Classification Reports to ensure reliability in high-stakes financial environments.
