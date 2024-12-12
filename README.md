# Predicting Stroke Risk Using Patient Health Data

**Overview**

Stroke is a leading cause of death and long-term disability worldwide. Early prediction of stroke risk can enable timely intervention and treatment, improving patient outcomes. This project leverages machine learning to build a predictive model for stroke likelihood based on patient demographic and health data.

**Project Goals**

Develop a Predictive Model: Use machine learning algorithms to classify stroke occurrence.

Explore Various Models: Compare Logistic Regression, Random Forest, Gradient Boosting, and XGBoost.

Hyperparameter Tuning: Optimize models to enhance performance.

Evaluate Performance: Identify the best model based on metrics like accuracy, precision, recall, and F1 score.

**Dataset Description**

The Stroke Prediction Dataset includes:

Demographics: Age, gender

Health Conditions: Hypertension, heart disease, BMI

Lifestyle Factors: Smoking status

Target Variable: Stroke occurrence (1 = stroke, 0 = no stroke)

**Data Preprocessing**

Handling Missing Values: Imputed missing values for BMI and smoking status.

Encoding: One-hot encoded categorical variables like gender and smoking status.

Scaling: Standardized numerical features (e.g., age, BMI).

Train-Test Split: Split data into 80% training and 20% testing subsets.

**Exploratory Data Analysis (EDA)**

Class Imbalance: Severe imbalance with far fewer stroke cases.

Key Features Correlation: Age, hypertension, and heart disease are significant predictors.

Visualizations:

Histograms: Age, BMI, and glucose level distributions.

Correlation Heatmap: Relationships among features.

Scatter Plot: BMI vs. stroke occurrence.

Box Plot: Age vs. stroke occurrence.

Pair Plot: Interaction effects between key features.

**Modeling Process**

Implemented Models

Logistic Regression (baseline)

Random Forest

Gradient Boosting

XGBoost (with and without tuning)

Key Techniques

Addressed class imbalance using class_weight='balanced' and scale_pos_weight.

Performed hyperparameter tuning (e.g., learning rate, max depth, number of estimators).

**Model Evaluation**

Model: Logistic Regression

Accuracy: 0.695

Precision: 0.147

Recall: 0.839

F1 Score: 0.250

Model: Random Forest

Accuracy: 0.939

Precision: 0.000

Recall: 0.000

F1 Score: 0.000

Model: Gradient Boosting

Accuracy: 0.938

Precision: 0.000

Recall: 0.000

F1 Score: 0.000

Model: XGBoost

Accuracy: 0.917

Precision: 0.220

Recall: 0.145

F1 Score: 0.175

Model: Tuned XGBoost

Accuracy: 0.800

Precision: 0.186

Recall: 0.677

F1 Score: 0.292

**Final Model Selection**

Tuned XGBoost was selected for its balance between precision, recall, and F1 score, crucial for minimizing false negatives in stroke prediction.

**Results and Recommendations**

Final Model Metrics

Accuracy: 0.800

Precision: 0.186

Recall: 0.677

F1 Score: 0.292

Recommendations

Adopt Tuned XGBoost: Ideal for identifying stroke cases with high recall.

Monitor Performance: Regularly evaluate the model with new data.

Expand Features: Incorporate additional health metrics like cholesterol levels.

**Future Work**

Investigate advanced models (e.g., deep learning).

Address class imbalance with enhanced resampling techniques.

Explore feature engineering for improved model performance.

**Conclusion**

The Tuned XGBoost model provides a robust approach to predicting stroke likelihood using patient data. With a focus on maximizing recall, this model supports early intervention strategies, showcasing the potential of machine learning in healthcare.
