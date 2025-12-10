# Personalized-Healthcare-Recommendations

Project Overview

This project builds a Machine Learning–based Personalized Healthcare Recommendation System using blood biomarker data. The system analyzes patient blood test values, predicts whether a person is at low risk or elevated risk, and provides easy-to-understand health recommendations.

---

Project Goals

-Explore and understand the blood dataset,
-Build supervised ML models for health-risk prediction,
-Use model outputs to produce personalized recommendations,
-Generate clear visualizations: distribution plots, correlation heatmap, confusion matrix, ROC,
-Ensure transparency with SHAP explainability,
-Deliver final documentation/report summarizing findings and insights.

---

Dataset

The dataset used is blood.csv, containing features such as:
Recency,
Frequency,
Monetary,
Time,
Class.

---

Exploratory Data Analysis (EDA)

-Missing value heatmap,
-Histogram + KDE distributions for numeric biomarkers,
-Correlation heatmap.

---

Preprocessing

-Missing value handling,
-Standardization of numeric features,
-One-Hot Encoding for categorical variables,
-Train–test split,
-Pipeline-based transformations for reproducibility.

---

Feature Engineering

-Creation of risk_label if not present,
-Encoding categorical variables,
-Scaling numeric variables,
-Extraction of feature names for later SHAP analysis.

---

Machine Learning Models

Random Forest Classifier:
-High interpretability,
-Strong performance.
XGBoost Classifier:
-Handles complex feature interactions,
-Often higher predictive power.
Cross-validation was used to select the better-performing model.

---

Model Evaluation

-Accuracy,
-Precision, recall, F1-score,
-Confusion matrix,
-ROC curve and AUC.

---

Explainability

SHAP (SHapley Additive exPlanations):
-Provides global and individual-level explanations,
-Shows how each feature contributes to risk,
-Easy for clinicians and stakeholders to interpret.

---

Personalized Recommendations

If Low Risk (0):
-Maintain healthy routine,
-Get annual checkups.

If Elevated Risk (1):
-Schedule a medical evaluation,
-Monitor cholesterol/glucose,
-Adjust diet/exercise,
-Consider preventive treatment options.

---

Technologies Used

-Python 3.8+,
-Pandas, NumPy,
-Matplotlib, Seaborn,
-Scikit-Learn, XGBoost,
-Joblib,
-SHAP.
