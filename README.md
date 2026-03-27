# ❤️ Heart Disease Risk Screening

## 📌 Problem

In healthcare screening, one of the most critical risks is falsely reassuring patients who are actually at high risk.

This project aims to build a machine learning model to identify high-risk patients while minimizing false negatives.

---

## 🎯 Objective

- Predict heart disease risk
- Reduce false negatives (missed cases)
- Analyze model decisions and trade-offs

---

## 🧠 Approach

1. Data cleaning and handling missing values  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering and encoding  
4. Model training (Logistic Regression & Random Forest)  
5. Model evaluation using confusion matrix and recall  
6. Threshold tuning to reduce false negatives  
7. Feature importance analysis  

---

## 📊 Results

### Logistic Regression (Default)
- False Negatives: 14  

### Logistic Regression (Tuned Threshold)
- False Negatives: 9 ✅  

### Random Forest
- False Negatives: 13  

---

## 🔥 Key Insight

Lowering the decision threshold significantly reduced false negatives, improving patient safety.

---

## ⚠️ Important Takeaway

In healthcare applications, minimizing dangerous errors (false negatives) is more important than maximizing accuracy.

---

## 🧪 Technologies Used

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 🚀 Future Work

- Improve model performance  
- Apply cross-validation  
- Explore advanced models (XGBoost)  
- Deploy as a decision-support tool  

---

## 👤 Author

Ali Haider  
