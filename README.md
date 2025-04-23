# ☕ Filtering the Grind: Machine Learning on Noisy Sales Data from a Café

This repository contains a machine learning project that transforms noisy, real-world café sales data into actionable business insights. The project tackles challenges like missing values, outliers, and categorical inconsistencies using advanced preprocessing and regression models like **Random Forest**, **XGBoost**, and **Gradient Boosting**.

---

## 📌 Project Goals

- 📊 Predict customer **Total Spent** using transactional data  
- 🕐 Identify **peak business hours** and **popular products**  
- 📈 Use ML models to uncover patterns in customer behavior  
- 🧹 Clean and process messy real-world data for accurate predictions

---

## 🧠 Models Used

| Model              | MAE  | RMSE | R² Score |
|-------------------|------|------|----------|
| Random Forest      | 3.61 | 5.04 | 0.91     |
| XGBoost            | 3.58 | 4.95 | 0.91     |
| Gradient Boosting  | 3.72 | 5.11 | 0.91     |

📌 **XGBoost** had the best performance with the lowest RMSE. All models showed excellent predictive power (R² ≈ 0.91).

---

## 📁 Folder Descriptions

### `/src/`
Contains source code for the entire ML pipeline including:
- Data cleaning
- Feature engineering
- Model training
- Visualizations

📄 `ML_GROUP_I_FINAL_CODE.ipynb` — main notebook with code and results.

---

### `/report/`
Holds the final PDF report submitted as part of the academic project.

📄 `ML_REPORT_GRPI.pdf` — complete documentation of problem statement, methodology, results, and future work.

---

### `/data/` 
This folder stores:
- `dirty_cafe_sales.csv` — the raw café sales data.

---

### `/`
Root folder containing:
- `README.md` — this file!

---

## 📊 Visualizations

- 📉 Actual vs Predicted Spend (Scatter plot)
- 🧮 Correlation Heatmap
- 📦 Boxplots of Numerical Features
- 📊 Frequency Bar Charts for Categorical Columns

---

## 👥 Team Members

- **Satvika S S** 
- **Toshima Jaiswal**  
- **Ronal Thomas**  
- **Venmugil Sruthi**   
- **Hannah Elsa Anish**

---

## 📘 Report

📄 [View Full Report](./report/ML_REPORT_GRPI.pdf)

---

## 🚀 Future Scope

- Real-time prediction using APIs and POS integration  
- Add customer-level personalization and loyalty prediction  
- Use LSTMs or Transformer models for sequential data  
- Implement explainable AI with SHAP/LIME  
- Deploy dashboard using Streamlit for business use

---

> ✨ This project highlights the power of machine learning in converting **messy sales data into meaningful business insights**, especially for small retail businesses like cafés.

---


