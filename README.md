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

<img width="542" height="321" alt="Image" src="https://github.com/user-attachments/assets/db29a129-dd62-4a30-add4-fd2e5053de12" />

<img width="898" height="781" alt="Image" src="https://github.com/user-attachments/assets/8a8ee18f-7272-4cda-85bf-263be249f371" />

<img width="1248" height="143" alt="Image" src="https://github.com/user-attachments/assets/ccff63aa-b688-4885-9955-d8ac95aab718" />

<img width="340" height="92" alt="Image" src="https://github.com/user-attachments/assets/35752313-3a7e-4988-a8c7-777b65146eed" />

<img width="390" height="89" alt="Image" src="https://github.com/user-attachments/assets/91407ae3-001e-45f0-800d-4a299d944065" />

<img width="501" height="79" alt="Image" src="https://github.com/user-attachments/assets/1c56b38b-27b2-4314-8bd3-55de0814e0b9" />

<img width="486" height="254" alt="Image" src="https://github.com/user-attachments/assets/45039d51-8189-426b-bd79-0062cd0072b3" />

<img width="432" height="312" alt="Image" src="https://github.com/user-attachments/assets/1d521ac8-7871-4eb3-ad80-c51a3d583f60" />
