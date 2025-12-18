# Developing-a-Multi-Tool-Predictive-Framework-for-Customer-Churn-in-Telecommunications

## 📌 Project Overview

**"Developing a Multi-Tool Predictive Framework for Customer Churn in Telecommunications: An Integrated Approach Using Machine Learning, Survey Analytics, and Business Intelligence Visualization"**

The project focuses on predicting customer churn in the telecommunications sector by combining **machine learning models**, **primary survey data**, and **business intelligence dashboards**. The aim is not only to achieve strong predictive performance but also to ensure **model interpretability** and **business applicability**.

---

## 🎯 Objectives

* Predict customer churn using supervised machine learning techniques
* Identify key churn drivers using feature importance and explainability methods (SHAP)
* Compare multiple ML models to balance accuracy and interpretability
* Integrate **primary survey data** to enhance business understanding
* Visualize churn insights using **Power BI dashboards**

---

## 🧠 Methodology

### Data Sources

* **Secondary Data**: Telco Customer Churn Dataset (Kaggle)

  * 7,043 customer records
  * Demographics, services, billing, and churn labels
* **Primary Data**: Survey data collected via Google Forms

  * 100+ responses
  * Customer satisfaction, service perception, churn intention

### Tools & Technologies

* **SQL** – Data extraction and preprocessing
* **Python** – Data analysis and machine learning
* **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn, SHAP
* **Power BI** – Interactive dashboards and business insights

### Machine Learning Models

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost
* K-Nearest Neighbors (KNN)
* Gaussian Naive Bayes

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

---

## 📊 Key Findings

* **Best Performing Model**: XGBoost (highest ROC-AUC and F1-score)
* **Strong Churn Predictors**:

  * Tenure
  * Monthly Charges
  * Total Charges
  * Contract Type (Two-year contracts reduce churn)
  * Fiber Optic Internet Service
* **Interpretability**: SHAP values provided clear insights into feature impact
* **Survey Insights**: Customer satisfaction and service perception strongly align with churn behavior

```

## ▶️ How to Run the Project


1. Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run Jupyter Notebook

```bash
jupyter notebook
```

4. Open notebooks from the `notebooks/` directory and execute cells sequentially

---

## 📈 Business Value

* Enables **early identification of high-risk customers**
* Supports **data-driven retention strategies**
* Bridges the gap between **technical models and managerial decision-making**
* Improves transparency through explainable AI

---

## ⚖️ Ethical Considerations

* GDPR-compliant data handling
* No personally identifiable information (PII) used
* Fairness-aware modeling and class imbalance handling (SMOTE)
* Transparent model interpretation using SHAP

---

## ⭐ Acknowledgements

* Kaggle – Telco Customer Churn Dataset
* Scikit-learn & SHAP open-source communities
* Academic supervisors and peers for guidance and feedback

---

