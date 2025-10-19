# Machine-Learning_Classification

## 📘 Overview

This repository gathers **machine learning classification projects** developed in Google Colab, addressing real-world business and health problems. Each project involves **data analysis, model training, evaluation, and validation** using diverse classification techniques.

### Projects Included

1. **Investment Adherence Prediction**
2. **Customer Churn Classification**
3. **Diabetes Risk Classification**
4. **Loan Default Detection and Metrics Validation**

Each notebook explores different approaches to **model evaluation, hyperparameter tuning, and cross-validation** to ensure robust predictive performance.

---

## 🚀 1. Investment Adherence Prediction

**Objective:** Predict whether clients will adhere to a new investment offer based on demographic and financial attributes.

**Main Steps:**

* Exploratory Data Analysis (EDA) and visualization of categorical variables.
* Feature encoding with `OneHotEncoder`.
* Model comparison and performance evaluation.

**Models Used:**

* Decision Tree Classifier
* Logistic Regression (baseline)

**Metrics Evaluated:**

* Accuracy
* Confusion Matrix
* Feature Importance

---

## 🔁 2. Customer Churn Classification

**Objective:** Predict customer churn in a banking dataset.

**Main Steps:**

* Feature transformation with `OneHotEncoder`.
* Baseline model using `DummyClassifier`.
* Hyperparameter optimization with `GridSearchCV`.

**Models Used:**

* Decision Tree Classifier (tuned)
* Dummy Classifier (baseline)

**Metrics Evaluated:**

* Accuracy
* Precision
* Recall
* F1-Score

**Validation Method:** Cross-validation with Grid Search

---

## 🩺 3. Diabetes Risk Classification

**Objective:** Identify patients at risk of diabetes using clinical data.

**Main Steps:**

* Data splitting (train, validation, test)
* Model evaluation and visualization (confusion matrix, ROC, Precision-Recall curves)
* Statistical reliability analysis through cross-validation

**Models Used:**

* Decision Tree Classifier (max_depth=2)
* Random Forest Classifier (max_depth=3)

**Metrics Evaluated:**

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Average Precision (AP)

**Validation Method:** KFold and StratifiedKFold cross-validation with confidence intervals

---

## 💳 4. Loan Default Detection and Metrics Validation

**Objective:** Detect potential loan defaulters and validate multiple model performance metrics.

**Main Steps:**

* Exploratory data analysis and preprocessing
* Comparison of overfitted vs. optimized models
* Evaluation of all major classification metrics
* Computation of confidence intervals for model reliability

**Models Used:**

* Decision Tree Classifier (max_depth=10)
* Random Forest Classifier

**Metrics Evaluated:**

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Average Precision

**Validation Method:** KFold cross-validation with mean ± 2×std confidence intervals

---

## 🧩 Tools and Libraries

* **Python 3**
* **Pandas**, **NumPy** – data manipulation
* **Scikit-Learn** – model building, encoding, and validation
* **Plotly**, **Matplotlib** – data visualization

---

## 📊 Performance Summary

| Project                | Best Model                   | Accuracy | Key Metric           | Validation Method |
| ---------------------- | ---------------------------- | -------- | -------------------- | ----------------- |
| Investment Adherence   | Decision Tree                | ~0.85    | Precision            | Hold-out          |
| Customer Churn         | Decision Tree (GridSearchCV) | 0.85     | F1-Score             | Cross-validation  |
| Diabetes Risk          | Random Forest                | 0.71     | ROC-AUC              | StratifiedKFold   |
| Loan Default Detection | Decision Tree (max_depth=10) | 0.91     | Confidence Intervals | KFold             |

---

## 🧠 Conclusion

These projects demonstrate the practical use of **supervised classification algorithms** for decision-making in finance, healthcare, and marketing. Beyond accuracy, they assess **model stability** through statistical validation and confidence intervals, promoting a more trustworthy and transparent evaluation process.

---

📍 Developed in **Google Colab (Python 3)** using **Scikit-learn**, **Pandas**, and **Matplotlib**.
