# Heart Attack Prediction Using Machine Learning

This project predicts the risk of a heart attack using multiple Machine Learning algorithms such as **KNN, Logistic Regression, SVM, Naïve Bayes, and XGBoost**. The dataset contains various patient health indicators including age, blood pressure, cholesterol levels, chest pain type, ECG results, and more.

## 🚀 Project Overview

This system is designed to support early diagnosis of heart disease by analyzing key medical features and predicting whether a person is at high risk or not. It helps healthcare professionals make quick, data-driven decisions.

## 🧠 Machine Learning Models Used

* **K-Nearest Neighbors (KNN)**
* **Logistic Regression**
* **Support Vector Machine (SVM)**
* **Naïve Bayes Classifier**
* **XGBoost Classifier** (Best performing model)

XGBoost achieved an accuracy of **~96%**, making it the most reliable model for prediction.

## 📊 Dataset

The dataset includes attributes such as:

* Age
* Sex
* Chest Pain Type
* Blood Pressure
* Cholesterol
* Heart Rate
* Exercise-induced Angina
* Oldpeak
* Heart Attack Output (0/1)

## 🔧 Tech Stack

* **Python**
* **NumPy, Pandas** for data processing
* **Matplotlib, Seaborn** for visualization
* **Scikit-learn** for ML models
* **XGBoost** for advanced classification
* **Streamlit** for user interface

## 🏗️ System Workflow

1. **Data Collection** from medical repositories
2. **Data Preprocessing** (cleaning, encoding, scaling)
3. **Model Training** using multiple algorithms
4. **Model Evaluation** through Accuracy, Precision, Recall, F1-Score, ROC-AUC
5. **Model Deployment** using Streamlit
6. **Prediction Output** (Heart Attack / No Heart Attack)

## 📈 Results

XGBoost achieved the best performance:

* **Accuracy:** 0.89
* **F1 Score:** 0.91
* **Precision:** 0.89
* **Recall:** 0.93
* **AUC Score:** 0.96

## 🎯 Conclusion

This project successfully demonstrates how machine learning techniques can be used to predict heart attack risk with high accuracy. It supports early detection, helps doctors make better decisions, and enhances patient care.

## 📁 How to Run the Project

```bash
pip install -r requirements.txt
python app.py
```

## 👩‍💻 Author

**Alaboina Sai Priya**
B.Tech CSE (AI & ML)
KG Reddy College of Engineering & Technology
