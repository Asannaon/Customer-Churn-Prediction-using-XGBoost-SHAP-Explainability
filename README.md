---

# Customer Churn Prediction using XGBoost + SHAP Explainability

This repository contains a complete end-to-end project for analyzing and predicting **Customer Churn** using the **XGBoost Classifier**, enhanced with **SHAP explainability** to understand the key features influencing churn behavior.

The entire workflow — from EDA, preprocessing, modeling, evaluation, to SHAP interpretation — is conducted in a **single Jupyter Notebook**.

---

## Project Objectives

* Clean and prepare the IBM Telco Customer Churn dataset.
* Build a predictive model using **XGBoost Classifier**.
* Handle class imbalance using several approaches.
* Evaluate model performance using accuracy, precision, recall, F1-score, and confusion matrix.
* Use **SHAP** to interpret model predictions and identify the most influential features.
* Generate business insights to support customer retention strategies.

---

## Technologies Used

* Python 3.x
* Pandas, NumPy
* Scikit-Learn
* XGBoost
* SHAP
* Matplotlib & Seaborn
* Jupyter Notebook

---

##  Key Model Results

* **Accuracy:** ~0.76 – 0.79
* **Precision (Churn):** ~0.56
* **Recall (Churn):** ~0.58
* **Confusion Matrix** shows strong performance on the majority class and improved recall after tuning.

---

##  Key Insights from SHAP

* **Tenure** is the most influential feature — customers with shorter tenure are more likely to churn.
* Higher **MonthlyCharges** increase the probability of churn.
* **Contract Type** (especially month-to-month) strongly affects churn behavior.
* Features such as **TechSupport** and **InternetService** significantly contribute to customer satisfaction.

SHAP visualizations — including summary plot, beeswarm, and decision plot — clearly show how each feature contributes to model decisions and make the results interpretable for non-technical stakeholders.

---

## ▶ How to Run the Notebook

1. Clone the repository:

   ```
   git clone https://github.com/username/Customer-Churn-Prediction-XGBoost-SHAP.git
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Launch the notebook:

   ```
   jupyter notebook
   ```

---

##  Why This Project Matters

* Demonstrates full end-to-end data analysis skills.
* Utilizes a production-grade machine learning model (XGBoost).
* Applies explainable AI techniques using SHAP — highly valuable in the industry.
* Ideal as a portfolio project for Data Analyst / Data Scientist roles.

---

## Author

**Tarsan Asan**
Data Analyst & Machine Learning Enthusiast
 LinkedIn: *(Tarsan Asan)*

---
