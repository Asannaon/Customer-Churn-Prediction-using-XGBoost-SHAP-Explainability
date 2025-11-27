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

<img width="803" height="940" alt="image" src="https://github.com/user-attachments/assets/f2c9f71e-89ce-4b0f-a936-78c45953d640" />


<img width="790" height="940" alt="image" src="https://github.com/user-attachments/assets/de6f5658-8515-4488-b2e0-b8403f407e7c" />

<img width="648" height="453" alt="image" src="https://github.com/user-attachments/assets/019d324c-00f6-4ebc-8989-ebd919575b6b" />

<img width="675" height="146" alt="Screen Shot 2025-11-27 at 11 28 38" src="https://github.com/user-attachments/assets/7c01f6be-ddf7-4112-a09e-e9d2b3843f85" />


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
