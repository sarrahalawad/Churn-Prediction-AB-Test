# Churn-Prediction-AB-Test

This project demonstrates a complete churn modeling pipeline and A/B testing workflow using synthetic telecom-like data. It reflects my experience working as a **Marketing Intelligence Analyst at Sudatel Telecommunication**, where I focused on **churn analysis, customer segmentation, and KPI monitoring**.

**Note**: This project does **not** use any real customer data from Sudatel or any other company. All data used here is **synthetically generated** to mimic real-world telecom customer behavior for educational and demonstration purposes.

---

##  Project Goals

- Simulate realistic customer and campaign data
- Perform A/B testing to evaluate marketing interventions
- Build churn prediction models with imbalanced data handling
- Explore threshold tuning to optimize classification performance

---

##  Structure

churn-prediction-ab-test/
│
├── notebooks/
│   ├── 01_data_generation.ipynb         # Generate synthetic churn dataset
│   ├── 02_ab_testing.ipynb              # Simulate A/B test and analyze results
│   └── 03_churn_prediction_model.ipynb  # Churn model with SMOTE, threshold tuning
│
├── results/
│   └── precision_recall_curve.png       # Evaluation plot
│
├── requirements.txt
└── README.md

