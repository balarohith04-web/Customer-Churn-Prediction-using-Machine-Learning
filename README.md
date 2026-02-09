Interpretable Machine Learning for Customer Churn Prediction using SHAP Values

This project builds, evaluates, and interprets an ensemble machine learning model for binary customer churn prediction.
The focus is not only on achieving strong predictive performance but also on providing clear, data-driven explanations using SHAP (SHapley Additive exPlanations).

This ensures model transparency, supports business decision-making, and aligns with real-world needs for explainable AI systems in customer retention strategies.

📌 Project Overview

The goal of this project is to develop an interpretable churn prediction model using XGBoost or LightGBM.

The workflow includes:

Preprocessing of a customer churn dataset

Handling categorical variables (encoding techniques)

Addressing class imbalance using resampling

Training and tuning an ensemble model

Evaluating performance (AUC, Precision, Recall, F1)

Extracting model-native feature importance

Generating SHAP global explanations

Producing SHAP local explanations for selected customers

Creating an executive summary with business insights

The notebook produces all required plots and metrics needed for model interpretation and reporting.
