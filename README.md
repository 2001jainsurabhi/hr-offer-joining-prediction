# HR Offer–Joining Prediction  
Predicting Candidate Joining Probability Using Logistic Regression, SMOTE, RFECV & Threshold Optimization  
Author: **Surbhi Jain**

---

## 🧠 Project Overview

This project predicts the **probability that a candidate will join a company after accepting the job offer**.  
It enables HR teams to:

- Reduce last-minute dropouts  
- Improve hiring planning  
- Allocate resources more efficiently  
- Make data-driven offer decisions  

The model outputs both:
- The **probability** of joining  
- The final **classification** (Join / Not Join)

---

## 🚀 Key Features of This Project

### **✔ End-to-End Data Pipeline**
- Data cleaning  
- Encoding  
- Feature engineering  
- Handling missing values  

### **✔ Exploratory Data Analysis (EDA)**
- Distribution analysis  
- Countplots  
- Correlation heatmaps  

### **✔ Class Imbalance Handling**
- Used **SMOTE** to balance “Joined vs Not Joined”

### **✔ Feature Selection (RFECV)**
Selected **33 high-impact features** including:
- Notice period  
- Percent hike expected / offered  
- Location  
- LOB  
- Offered band  
- Gender, age, relocation, etc.

### **✔ Logistic Regression Modeling**
Built two models:
1. **Model 1:** All features  
2. **Model 2:** Selected RFECV features (better performance)

### **✔ Threshold Optimization (MLE)**
Identified the best cutoff probability:
### ⭐ **Final Cut-Off = 0.59596**

### **✔ Evaluation Metrics**
- Accuracy  
- Sensitivity  
- Specificity  
- AUC / ROC  
- Confusion matrix  

---

## 📊 Summary of Results

| Metric | Score |
|--------|--------|
| **Optimal Threshold** | **0.59596** |
| Accuracy | ~82% |
| Sensitivity | Good |
| Specificity | High |
| AUC | Strong model performance |

The model performs reliably and provides interpretable joining predictions for HR operations.

---

## 📄 Questions Solved (Q1–Q6)

This notebook includes complete explanations and code for:

- **Q1:** Analytics project lifecycle  
- **Q2:** Logistic Regression development & feature selection  
- **Q3:** Predictive algorithm explanation  
- **Q4:** Sensitivity, Specificity & Accuracy  
- **Q5:** Final cutoff probability  
- **Q6:** Cook’s Distance & standardized residuals (theory)  

---

## ▶ How to Run This Project

1. Clone the repo  
2. Install dependencies using `pip install -r requirements.txt`  
3. Open the Jupyter notebook  
4. Run all cells top-to-bottom  

Everything in the notebook is structured and ready to execute.

---

## 👩‍💻 Author

### **Surbhi Jain**

**Data Analyst | SQL | Python | Power BI | Machine Learning**

---

## ⭐ If you found this project helpful, please give it a star!
