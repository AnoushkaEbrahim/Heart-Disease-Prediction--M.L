# 🫀 Heart Disease Prediction Using Machine Learning

This project predicts the presence of heart disease using clinical data, based on the UCI Heart Disease dataset. I implemented and compared multiple machine learning models, including Logistic Regression, Random Forest, and Neural Networks.

---

## 📌 Problem Statement

To classify whether a patient has heart disease (`target = 1`) or not (`target = 0`) using features like age, blood pressure, cholesterol, etc.

---

## 📊 Dataset

- **Source**: [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- **Features**: 
  - Age, Sex, Chest Pain Type, Resting Blood Pressure, Cholesterol, etc.
- **Target**: 1 = Has heart disease, 0 = No heart disease

---

## 🧪 Steps Followed

### 1. 📈 Exploratory Data Analysis (EDA)
- Visualized class distribution using Plotly
- Analyzed distributions of age, cholesterol, and other features
- Used correlation heatmaps and scatter plots

### 2. 🧹 Data Preprocessing
- Handled missing values (if any)
- Encoded categorical variables
- Scaled numerical features

### 3. 🤖 Model Building
Trained and evaluated the following models:
- **Logistic Regression**
- **Random Forest**
- **Neural Network (MLPClassifier)**

### 4. 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📌 Requirements

Install the dependencies using:

```bash
pip install -r requirements.txt
