# 🌍🏫 World University Rankings 2026 — Machine Learning Analysis

##  Project Overview

This project analyzes the **QS World University Rankings 2026 dataset** and builds a Machine Learning model to **predict university scores** based on key performance indicators.

The goal is to uncover:

* What factors influence university rankings
* How accurately we can predict QS scores
* Which features matter the most

---

##  Problem Statement

Can we predict a university's **QS Score** using features like:

* Academic Reputation
* Employer Reputation
* Faculty-Student Ratio
* Citations per Faculty
* International Students

---

##  Machine Learning Approach

###  Steps Performed:

* Data Cleaning & Handling Missing Values
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Encoding Categorical Variables
* Model Building & Evaluation

---

##  Models Used

* Random Forest Regressor
* XGBoost Regressor (Final Model )

---

##  Model Performance

| Metric   | Score    |
| -------- | -------- |
| R² Score | **0.73** |
| MAE      | **2.77** |
| RMSE     | **4.13** |

 *Model performance improved from R² = 0.67 → 0.73 after optimization*

---

##  Key Insights

* Academic Reputation is the **strongest predictor** of QS Score
* QS Rank has a strong inverse relationship with Score
* International factors have **moderate impact**
* Feature engineering + XGBoost significantly improved performance

---

##  Visualizations

* Top 15 Universities (QS Rankings 2026)
* Region-wise Score Distribution
* Correlation Heatmap
* Feature Importance Plot

---

##  Tech Stack

* Python 🐍
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* XGBoost

---

##  Future Improvements

* Hyperparameter tuning for better accuracy
* SHAP explainability for model interpretation
* Deploy as a Streamlit web app
* Add more real-world ranking features

---

##  Conclusion

This project demonstrates how Machine Learning can be applied to **analyze global education rankings** and uncover key drivers behind university performance.


