# Bank Customer Churn Prediction

Data mining course project (ISTE-600, RIT Dubai, Fall 2025), done in a team of three.

**Goal:** predict which bank customers are likely to leave and segment them by churn risk.

**Data:** Churn Modelling dataset from Kaggle, 10,000 customers (9,626 after cleaning).

**Methods:** data cleaning, log transform of Balance, IQR outlier filtering, 80/20 stratified split. Models: Logistic Regression, Random Forest, GBM, XGBoost.

**Result:** XGBoost performed best (accuracy 86.5%, precision 0.81, recall 0.80). Customers were split into low, medium and high churn-risk segments.

📄 [Full project report (PDF)](./ISTE600_project_report_Fall2025_azhar_tilekova_hamda_alhashmi_shaikha_hassan.pdf)
