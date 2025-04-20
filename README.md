# 🏡 Zillow House Price Prediction using Machine Learning

This project aims to improve the **Zillow Zestimate** by applying **machine learning algorithms** to predict log errors between actual and estimated house prices. Focused on California home sales from **2016–2017**, the study leverages various regression models to analyze property characteristics and improve pricing accuracy.

---

## 📌 Project Overview

- **Objective:** Predict log error in Zillow's house price estimates and uncover key contributors to estimation inaccuracy.
- **Scope:** Houses sold in California (2016–2017).
- **Approach:** Comparative model analysis using linear regression, Lasso, Gradient Boosting, and others.
- **Target Variable:** Log Error (difference between Zillow's predicted price and actual sale price)

---

## 📁 Dataset Description

Key Features Used:
- **bedroomcnt:** Number of bedrooms  
- **bathroomcnt:** Number of bathrooms  
- **calculatedfinishedsquarefeet:** Total living area  
- **taxvaluedollarcnt:** Assessed property value  
- **regionidcounty:** County identifier  
- **yearbuilt:** Year the home was constructed  
- **poolcnt:** Pool count

---

## 🧠 Models Used

| Model                    | Description                                |
|-------------------------|--------------------------------------------|
| **Linear Regression**   | Baseline regression model                  |
| **Lasso-Lars**          | Regularized linear model                   |
| **Polynomial Features** | Captures non-linearity                     |
| **Gradient Boosting**   | Ensemble model with high performance       |
| **Generalized Linear**  | Linear model with better distribution fit  |
| **RFE (Recursive Feature Elimination)** | For optimal feature selection   |

---

## 🧪 Evaluation Metrics

- **MSE (Mean Squared Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**
- **Log Error Analysis**

---

## 📊 Key Findings

- Strong positive correlation between **square footage** and **assessed value**
- **Pools** and **number of bedrooms/bathrooms** significantly influence valuations
- **Older properties** generally have lower assessed values
- County-wise variation: **Orange County** has higher average values than **LA County**
- **Gradient Boosting** achieved the lowest MSE and best predictive performance

---

## ⚙️ Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- Statsmodels

---

## 💡 Insights & Recommendations

- Regional disparities must be factored into automated price estimators.
- Pools and home age significantly affect pricing – Zillow can improve estimates by factoring in these elements.
- Ensemble models (like Gradient Boosting) outperform traditional regression in pricing prediction tasks.

---

## 👨‍💻 Author

**Aswin S Krishna**  
B.Tech, Computer Science and Engineering  
Lovely Professional University  
