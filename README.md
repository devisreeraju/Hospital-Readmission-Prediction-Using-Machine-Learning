

# 🏥 Hospital Readmission Prediction Using Machine Learning

## 📌 Project Overview

Hospital readmissions within 30 days are a major challenge in healthcare systems. This project builds a machine learning model to predict whether a patient will be readmitted within 30 days after discharge.

The goal is to help healthcare providers identify high-risk patients and improve patient care management.

---

## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA)
* Clean and preprocess healthcare dataset
* Convert categorical target variable into binary format
* Train classification models
* Evaluate model performance using metrics
* Analyze feature importance

---

## 📂 Dataset Information

* Dataset: Diabetic Patient Readmission Dataset
* Records: ~101,766 patients
* Features: 50+ medical attributes
* Target Variable: `readmitted`

  * `<30` → Readmitted within 30 days
  * `>30` → Readmitted after 30 days
  * `NO` → Not readmitted

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook (VS Code)

---

## 🔍 Data Preprocessing Steps

* Removed unnecessary ID columns (`encounter_id`, `patient_nbr`)
* Checked for missing values
* Converted target variable into binary:

  * 1 → Readmitted within 30 days
  * 0 → Otherwise
* Train-Test Split (80/20)

---

## 🤖 Machine Learning Models Used

### 1️⃣ Logistic Regression

### 2️⃣ Random Forest Classifier

---

## 📊 Model Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve
* AUC Score
* Feature Importance Analysis

---

## 📈 Results

* Accuracy: ~58%
* AUC Score: ~0.50
* Random Forest performed better than Logistic Regression
* Important Features:

  * Number of lab procedures
  * Number of medications
  * Inpatient visits
  * Time in hospital

---

## 📌 Key Insights

* Readmission prediction is challenging due to class imbalance.
* Medical history and hospital stay duration significantly influence readmission.
* Feature importance analysis provides interpretability for healthcare decision-making.

---

## 🚀 Future Improvements

* Apply SMOTE for class imbalance
* Hyperparameter tuning
* Try advanced models (XGBoost, Gradient Boosting)
* Deploy model using Flask/Streamlit

---

## 👩‍💻 Author

Haritha (MCA Student)
Machine Learning & Data Science Enthusiast

---



Tell me what you want next 💪
