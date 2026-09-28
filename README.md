# credit-risk-predictive-analytics
An end-to-end credit-risk analytics project using 30,000 credit-card customer records to predict next-month default. The project uses Databricks/PySpark for data preparation and feature engineering and compares logistic regression with XGBoost for predictive modeling.
| Metric | Logistic Regression | XGBoost |
|---|---:|---:|
| Accuracy | 80.35% | **81.12%** |
| Precision | 61.71% | **62.16%** |
| Recall | 29.39% | **37.38%** |
| F1 | 39.82% | **46.68%** |
| ROC-AUC | 0.7433 | **0.7599** |


XGBoost outperformed the logistic-regression baseline across all evaluation metrics, increasing recall from 29.39% to 37.38% while maintaining slightly higher precision. This suggests that nonlinear relationships and interactions provide additional predictive value for identifying customers at risk of default.
