📊 Telecom Churn Prediction using IBM SPSS Modeler
🧠 Project Overview

This project focuses on predicting customer churn in the telecommunications industry using IBM SPSS Modeler. The goal is to analyze customer data, identify factors contributing to churn, and build a predictive model to help telecom companies retain valuable customers.

🎯 Objectives

Identify key indicators influencing customer churn.

Develop a predictive model using historical customer data.

Evaluate model performance and generate actionable insights for retention strategies.

🧰 Tools & Technologies

IBM SPSS Modeler (for data mining and predictive modeling)

Dataset: Telecom customer data (containing demographic, usage, and service features)

Techniques Used:

Data cleaning and preparation

Feature selection and transformation

Classification algorithms (e.g., Decision Tree, Logistic Regression, Neural Network)

Model evaluation with accuracy, ROC curve, and confusion matrix

🔍 Project Workflow

Data Import & Exploration
Imported telecom customer dataset into SPSS Modeler and explored churn patterns.

Data Preparation

Handled missing values and outliers

Encoded categorical variables

Normalized numeric features

Model Building

Used Decision Tree (C5.0), Logistic Regression, and Neural Network models

Compared models using accuracy and lift charts

Model Evaluation

Measured performance on a test set

Analyzed feature importance and customer churn drivers

Deployment & Visualization

Generated churn probability scores

Exported results for business interpretation

📈 Key Insights

Contract type, monthly charges, and customer tenure are major churn predictors.

Decision Tree models provided the best interpretability for business insights.

Data-driven insights can improve retention strategies by targeting at-risk customers early.

📂 Repository Structure
├── telecom_analysis.str     # SPSS Modeler stream file (project workflow)
├── README.md                # Project summary (this file)
├── dataset/                 # (Optional) sample or reference dataset
└── reports/                 # Model evaluation results and charts

🚀 How to Use

Open IBM SPSS Modeler.

Load telecom_analysis.str into the workspace.

Connect to your dataset and run the stream to reproduce the analysis.
