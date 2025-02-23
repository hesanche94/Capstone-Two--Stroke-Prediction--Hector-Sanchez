# 🏥**Predicting Stroke Risk Using Patient Health Data**

## 📌 **Project Overview**

Stroke is a leading cause of death and disability worldwide. Early prediction of stroke risk can help in timely intervention and improved patient care. This project leverages machine learning techniques to predict the likelihood of stroke occurrence based on patient demographic and health data.

## 🎯 **Objective**

Develop a machine learning model to classify whether a patient is at risk of stroke.

Compare multiple classification models to determine the best performer.

Optimize model hyperparameters and evaluate performance using key metrics.

## 📊 **Dataset Overview**

**Dataset:** Stroke Prediction Dataset

**Feature Category -->  Key Features**

Demographics -->  Age, Gender

Health Conditions -->  Hypertension, Heart Disease, BMI

Lifestyle Factors -->  Smoking Status

Target Variable -->  Stroke (1 = Stroke, 0 = No Stroke)

**Preprocessing Steps:**

Handled missing values for bmi and smoking_status.

One-hot encoding for categorical variables.

Standardization of numerical features.

Split dataset: 80% training, 20% testing.

## 🔍 **Exploratory Data Analysis (EDA)**

**Key Insights:**

Severe class imbalance: significantly more patients without stroke.

Older individuals, those with hypertension, and those with heart disease had a higher likelihood of stroke.

**Visualizations:**

📈 Histograms: Age, BMI, and Glucose Levels Distribution

📊 Correlation Heatmap: Identifies relationships between features

🎯 Scatter Plot: BMI vs. Stroke occurrence

📦 Box Plot: Age vs. Stroke

🔗 Pair Plot: Interactions between risk factors

##🤖 **Machine Learning Models**

**Implemented Models:**

✅ Logistic Regression (Baseline Model)

🌳 Random Forest (Ensemble Model)

📈 Gradient Boosting (Boosting Technique)

⚡ XGBoost (Optimized Gradient Boosting)

**Hyperparameter Tuning:**

Used GridSearchCV for XGBoost to optimize learning rate, max depth, and estimators.

## 📊 **Model Performance**

**Model                Accuracy  Precision  Recall  F1 Score**

Logistic Regression  0.695      0.147      0.839    0.250

Random Forest        0.939      0.000      0.000    0.000

Gradient Boosting    0.938      0.000      0.000    0.000

XGBoost              0.917      0.220      0.145    0.175

Tuned XGBoost        0.800      0.186      0.677    0.292

**Final Model: Tuned XGBoost**

Balanced recall and precision, crucial for handling class imbalance.

Prioritizes correctly identifying stroke cases, minimizing false negatives.

## 🔮 **Future Work & Recommendations**

✔ Adopt Tuned XGBoost for practical applications in stroke prediction.

✔ Monitor Model Performance to ensure accuracy over time.

✔ Incorporate Additional Health Features (e.g., cholesterol levels, lifestyle habits).

✔ Experiment with Advanced Models such as deep learning.

✔ Address Class Imbalance through improved resampling techniques.

✔ Expand Model Scope to predict stroke prognosis and aid early intervention strategies.

## 🚀 **Conclusion**

This project demonstrates how machine learning can be used to predict stroke risk using patient data. By prioritizing recall, our model ensures that high-risk patients are identified, enabling timely medical intervention. Future improvements can further enhance accuracy and reliability in real-world applications.

# 📬 **Connect with Me:**

💼 LinkedIn: www.linkedin.com/in/hechector-sanchez-skaggs

📧 Email: h.sanche94@gmail.com

📂 Portfolio: https://github.com/hesanche94

⭐ **If you found this project helpful, please consider giving it a star on GitHub!** ⭐
