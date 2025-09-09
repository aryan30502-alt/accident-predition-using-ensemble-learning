# accident-prediction-using-ensemble-learning
import os

# --- The Markdown content for the README file ---
readme_content = """# 🚦 Accident Risk Prediction Using Ensemble Machine Learning & Explainable AI

## 📌 Project Overview
Road traffic accidents are a leading cause of death globally, with over **1.35 million fatalities each year (WHO, 2023)**. Traditional statistical models can explain patterns but struggle to predict accidents accurately due to complex spatio-temporal and environmental interactions.

This project develops a **machine learning framework** that:
- Predicts accident risk for given **locations and times**
- Combines **Random Forest, XGBoost, and Stacking** for higher accuracy
- Uses **SHAP (Shapley Additive Explanations)** for interpretability
- Provides a **Streamlit dashboard** to visualize accident hotspots

---

## ✨ Objectives
* **Predict Accident Risk:** Develop ensemble ML models to estimate accident probability.
* **Interpret Predictions:** Use SHAP to explain global & local feature contributions.
* **Handle Imbalanced Data:** Apply SMOTE/class-weighting to improve learning.
* **Interactive Dashboard:** Allow users to upload data & visualize hotspots.
* **Evaluate Models:** Compare RF, XGBoost, and Stacked Ensemble using PR-AUC, ROC-AUC, and Brier Score.

---

## ⚙️ Methodology
1. **Data Preprocessing** – Clean and merge accident, weather, and location datasets.
2. **Feature Engineering** – Spatio-temporal (hour, weekday, month), environmental (precipitation, visibility), and contextual features (road density).
3. **Model Training** – Random Forest, XGBoost, and Stacked Ensemble.
4. **Evaluation** – Metrics for imbalanced classification: PR-AUC, ROC-AUC, Brier Score.
5. **Explainability** – SHAP values for feature importance and local explanations.
6. **Visualization** – Streamlit dashboard with hotspot maps and SHAP plots.

---

## 📂 Project Structure
