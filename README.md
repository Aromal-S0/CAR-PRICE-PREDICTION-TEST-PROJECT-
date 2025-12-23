
# 🚗 Car Price Prediction – Regression Models

## 📌 Overview
This project analyzes the factors affecting car prices in the US market and builds regression models to predict car prices using technical and market features.

---

## 🎯 Objective
- Understand key variables influencing car price  
- Build and compare multiple regression models  
- Improve performance using hyperparameter tuning  

---

## 🛠️ Methodology
- Dropped irrelevant columns (`car_ID`, `CarName`)
- One-hot encoded categorical variables
- Performed train–test split (67% / 33%)
- Removed highly correlated features using correlation matrix
- Applied feature scaling where required

---

## 🤖 Models Implemented
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- **Support Vector Regressor (SVR)**  

---

## 📊 Evaluation Metrics
- **R² Score** (model comparison)
- **MAE** (average prediction error)
- **MSE** (penalizes large errors)

---

## ⚙️ Hyperparameter Tuning
Hyperparameters were adjusted to improve model performance.  
After tuning, **SVR achieved the best performance**, showing the highest R² score and lowest prediction error compared to other models.

---

## ✅ Conclusion
Among all implemented models, **Support Vector Regressor (SVR)** performed the best after hyperparameter tuning.  
SVR effectively captured complex relationships in the data and provided the most accurate car price predictions.

---

## 🧰 Libraries Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 👤 Author
**Aromal**  
MSc Data Science
