# 💳 Credit Card Fraud Detection using Linear Regression

## 🧠 Overview

This project aims to detect fraudulent credit card transactions using a **Linear Regression** model. The goal is to analyze transaction data, extract relevant features, and build a predictive model that can classify transactions as **fraudulent** or **legitimate**.

While Linear Regression is not typically the best model for classification tasks (Logistic Regression or tree-based models usually perform better), this project demonstrates the **implementation, training, and evaluation** of a regression-based approach for educational purposes.

---


## 📊 Dataset

* **Source**: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
* **Description**: Contains transactions made by cardholders
* **Target Variable**:

  * `Class` → 0 = legitimate, 1 = fraud

## 🧩 Model Development

### Steps:

1. **Data Preprocessing**

   * Handle missing values (if any)
   * Scale numerical features (`StandardScaler`)
   * Split dataset into training and testing sets

2. **Model Training**

   * Train a **Linear Regression** model using `scikit-learn`
   * Predict transaction labels (rounded predictions to 0 or 1)

3. **Evaluation Metrics**

   * Accuracy
   * Precision
   * Recall
   * F1-Score
   * Confusion Matrix

---

## 📈 Results

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 0.99  |
| Precision | 0.90  |
| Recall    | 0.95  |
| F1-Score  | 0.92  |

---

## 🧰 Technologies Used

* **Python 3.10+**
* **NumPy**
* **Pandas**
* **Scikit-learn**
* **Matplotlib / Seaborn**
* **Google collab**

---

## 🚀 Future Improvements

* Replace Linear Regression with **Logistic Regression** or **Random Forest** for better classification.
* Deploy the model via a **Flask** or **FastAPI** REST API.
