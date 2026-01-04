# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview
Credit card fraud is a critical financial problem where detecting fraudulent transactions accurately and early can prevent significant monetary loss.  
This project implements an **end-to-end machine learning pipeline** to identify fraudulent credit card transactions using statistical analysis, data preprocessing, feature engineering, and multiple machine learning models.

The notebook follows **industry-standard data science practices** and emphasizes **business-critical evaluation metrics** suitable for highly imbalanced datasets.

---

## 🎯 Objectives
- Detect fraudulent credit card transactions with high precision and recall  
- Handle severe class imbalance effectively  
- Compare multiple machine learning models  
- Build a **production-ready, scalable ML workflow**

---

## 🗂️ Dataset
- Contains anonymized credit card transaction data  
- Highly imbalanced target variable (`Class`)
  - `0` → Legitimate transaction  
  - `1` → Fraudulent transaction  

---

## 🔍 Key Steps & Methodology

### 1️⃣ Data Quality & Exploratory Analysis
- Checked missing and null values  
- Dataset structure and feature inspection  
- Target variable distribution analysis  
- Correlation heatmap for feature relationships  

---

### 2️⃣ Statistical Analysis
- **Chi-Square Test** to identify relationships between categorical variables and the target variable  
- Ensures statistically relevant feature inclusion  

---

### 3️⃣ Feature Engineering
- Encoding categorical variables  
- Dropping unnecessary features after encoding  
- Feature scaling using **StandardScaler**  
- Feature transformation for model compatibility  

---

### 4️⃣ Handling Class Imbalance
- Implemented **SMOTE (Synthetic Minority Oversampling Technique)**  
- Ensures models learn meaningful fraud patterns  

---

### 5️⃣ Machine Learning Models
- Logistic Regression (baseline / high bias model)  
- Random Forest Classifier (low bias, high capacity model)  

---

### 6️⃣ Model Evaluation Metrics
- Classification Report  
- Confusion Matrix  
- ROC-AUC Curve  
- Precision-Recall Curve  

---

### 7️⃣ Cross-Validation & Hyperparameter Tuning
- **GridSearchCV** with 5-fold cross-validation  
- Optimized using **F1-Score**  

---

### 8️⃣ Bias–Variance Trade-Off
- Comparison between simple and complex models  
- Balanced generalization through tuning  

---

### 9️⃣ Production-Ready ML Pipeline
- Implemented **Scikit-Learn Pipeline**  
- Prevents data leakage  
- Ready for deployment  

---

## 🛠️ Tools & Technologies

### Programming & Libraries
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- SciPy  
- Imbalanced-learn  

### Visualization
- Matplotlib  
- Seaborn  

---

## 📈 Results & Insights
- Ensemble models outperform baseline classifiers  
- Precision–Recall is more effective than accuracy for fraud detection  
- SMOTE significantly improves minority class detection  

---

## 💼 Business Impact
- Reduced false negatives (missed fraud cases)  
- Improved fraud detection reliability  
- Supports financial risk mitigation strategies  

---

## 🚀 Future Improvements
- XGBoost / LightGBM  
- Cost-sensitive learning  
- Real-time fraud detection pipeline  
- Model explainability using SHAP  

---

## 👤 Author
[**Aniket Mishra**](https://www.linkedin.com/in/aniketmishra622/) 
Data Analyst | Machine Learning Enthusiast

