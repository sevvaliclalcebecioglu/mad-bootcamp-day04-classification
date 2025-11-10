# 🏢 Day 04 - Employee Attrition Prediction with Classification Models
Project from the "Mastering Applied Data Science Bootcamp"  

This repository contains my study project on predicting whether employees will leave a company using classification models. The goal was to analyze HR data, preprocess it, engineer features, and build models that can accurately predict attrition.

---

## 🔹 Project Overview
The project follows a structured workflow:

### Exploratory Data Analysis (EDA)
- Load and inspect HR dataset (`hr_data.csv`)  
- Analyze distributions, correlations, and missing values  
- Visualize target variable distribution (`Attrition`)  
- Handle missing values and preprocess features  

### Feature Engineering
- Transform categorical variables into numeric format using `get_dummies`  
- Map target variable (`Attrition`) from Yes/No to 1/0  
- Normalize or scale features if required  

### Modeling
- Split data into training and test sets (`train_test_split`)  
- Train multiple classification models:  
  - Gaussian Naive Bayes  
  - Bernoulli Naive Bayes  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Gradient Boosting  
  - K-Nearest Neighbors (KNN)  
  - AdaBoost  
  - Multinomial Naive Bayes  

- Evaluate models using:  
  - Accuracy Score  
  - Precision, Recall, F1-Score  
  - Confusion Matrix  
  - ROC-AUC curve  

### Model Comparison
- Compare model performance using a custom `algo_test(x, y)` function  
- Identify the best-performing model based on F1-score and overall metrics  
- Visualize results and confusion matrices for interpretability  

---

## 🔹 Key Results
- **Best Model:** Gradient Boosting Classifier  
- **Accuracy:** 88.79%  
- The model accurately predicts employee attrition and can help HR teams take proactive measures  
