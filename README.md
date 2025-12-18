# Customer Churn Prediction Using Machine Learning

##  Project Overview

This project implements an end-to-end **Customer Churn Prediction system** using supervised machine learning. The objective is to identify customers who are likely to discontinue a service, enabling businesses to take **proactive retention actions** and reduce revenue loss.

The project follows industry-standard practices including data preprocessing, class imbalance handling, model training, evaluation, and deployment-ready model persistence.

---

##  Dataset

**Telco Customer Churn Dataset**

The dataset contains customer-level information including:

* Demographic details
* Subscription and service usage patterns
* Contract and billing information

Target Variable:

* `Churn` (Yes / No)

---

##  Project Workflow

1. Data Cleaning and Preprocessing
2. Encoding of Categorical Features
3. Handling Class Imbalance using **SMOTE**
4. Model Training using **Random Forest Classifier**
5. Model Evaluation using Multiple Performance Metrics
6. Model and Encoder Persistence using **Pickle**
7. Prediction on Unseen Customer Data

---

##  Machine Learning Model

* **RandomForestClassifier**

Chosen for its robustness, ability to handle non-linear relationships, and strong performance on structured tabular data.

---

## 📈 Model Evaluation Metrics

The model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score

These metrics ensure balanced evaluation, especially for imbalanced classification problems.

---

##  Technologies & Tools

* Python
* Pandas, NumPy
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Jupyter Notebook

---

##  Key Highlights

* Built a complete machine learning pipeline from data preprocessing to prediction
* Effectively handled class imbalance using SMOTE
* Saved trained model and encoders for reuse and deployment
* Successfully predicted churn on new, unseen customer data
* Used industry-relevant algorithms and evaluation techniques

---

##  Business Insights

* Customers on **month-to-month contracts** show higher churn probability
* Higher **monthly charges** correlate with increased churn risk
* Long-term contracts significantly reduce churn likelihood

These insights can help businesses design targeted retention strategies.

---

##  Future Enhancements

* Implement Pipeline and ColumnTransformer for production robustness
* Add feature importance visualization
* Perform cross-validation for better generalization
* Compare multiple models (Logistic Regression, XGBoost)
* Deploy the model using Flask or FastAPI

---

##  One-Line Project Summary (Interview Ready)

"Developed an end-to-end customer churn prediction system using Random Forest, addressing class imbalance with SMOTE and deploying the model for real-time prediction on unseen customer data."

---

##  Repository Structure (Suggested)

```
├── data/
├── notebooks/
├── models/
├── encoders/
├── src/
├── README.md
```

---

 This project demonstrates strong fundamentals in machine learning, data preprocessing, and model deployment concepts, making it suitable for **Data Analyst / Data Scientist entry-level roles**.
