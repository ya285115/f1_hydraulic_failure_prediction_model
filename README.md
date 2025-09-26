## Predictive Reliability Tool — Hydraulic Systems (UCI)

This repo contains a professional Predictive Reliability pipeline built on the UCI Hydraulic dataset.
It includes:
- data fetch & inspect
- robust preprocessing utilities
- model training (RandomForest, XGBoost) with CV and SMOTE for class imbalance
- SHAP explainability (global + local)
- Monte Carlo stress simulation for failure probability
- Streamlit demo for upload / single-row prediction / SHAP / Monte Carlo
