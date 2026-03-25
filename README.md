Fraud Detection System (Banking Simulation)
📌 Overview

This project simulates a real-world fraud detection system in a banking environment. It focuses on detecting fraudulent transactions using machine learning while balancing fraud detection performance with customer experience.

🎯 Objectives
Detect fraudulent transactions with high recall
Minimize false positives to reduce customer friction
Simulate a real-time fraud scoring system
🧠 Key Features
Time-based data splitting to prevent data leakage
Behavioral and temporal feature engineering
Class imbalance handling using weighted learning
XGBoost model for non-linear fraud detection
Evaluation using AUPRC, Precision-Recall trade-offs
Risk scoring system combining rules + ML
⚙️ Tech Stack
Python (Pandas, NumPy, Scikit-learn, XGBoost)
Jupyter Notebook
Google Sheets / Looker Studio (for dashboard)
📊 Model Performance
Metric	Value
AUPRC	XX
Recall (Fraud Detection Rate)	XX
Precision	XX
False Positive Rate	XX

Note: Metrics are evaluated using time-based validation to simulate real-world deployment.

⚖️ Business Trade-off
Lower thresholds improve fraud detection (Recall ↑)
But increase false positives → customer inconvenience

This project evaluates that trade-off explicitly.
