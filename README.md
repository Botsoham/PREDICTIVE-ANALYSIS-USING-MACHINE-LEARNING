# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

COMPANY - CODTECH IT SOLUTION

NAME - SOHAM MAHAJAN

INTERNID - CT04DY2129

DOMAIN - DATA ANALYST

DURATION - 4 WEEKS

MENTOR - NEELA SANTOSH

# 🧠 Predictive Analysis using Machine Learning  
### Internship Project – Breast Cancer Prediction  

---

## 📌 Project Overview
This project demonstrates **predictive analysis using machine learning** to classify breast cancer tumors as **Malignant (cancerous)** or **Benign (non-cancerous)**.  

The notebook includes:
- Data exploration & preprocessing  
- Feature selection  
- Model training (Logistic Regression, Random Forest, Gradient Boosting)  
- Model evaluation with metrics and plots  
- Saving the best trained model  

---


## ⚙️ Steps Performed

### 1. 📊 Data Exploration
- Loaded dataset using `sklearn.datasets.load_breast_cancer()`.  
- Checked dataset shape `(569, 31)`.  
- Verified no missing values.  
- Plotted distributions of key features.  
- Created a **correlation heatmap**.  

### 2. 🔍 Feature Selection
- **Variance Threshold** → Removed features with very low variance.  
- **SelectKBest (ANOVA F-test)** → Selected top 10 features.  
- **Recursive Feature Elimination (RFE)** → Selected 10 best features using Logistic Regression.  

### 3. 🤖 Model Training
- Trained multiple models using pipelines:  
  - Logistic Regression  
  - Random Forest  
  - Gradient Boosting  
- Used **Cross-Validation** to compare performance.  

### 4. 🎯 Hyperparameter Tuning
- Tuned **Random Forest** using `GridSearchCV`.  
- Best parameters:  

### 5. 📤 Output 

