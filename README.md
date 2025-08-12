# 💼 Salary Prediction Project

A machine learning project for predicting employee salaries based on various features such as age, experience, job title, department, education level, and location.

---

## 🔍 What This Project Does

This notebook demonstrates how to:

- ✅ Prepare and preprocess employee data
- ✅ Train and evaluate **Linear Regression** and **XGBoost Regressor** models
- ✅ Compare their performance using **MSE** and **R²**
- ✅ Build **interactive widgets** to predict salary from user input
- ✅ Visualize salary distribution across locations with interactive **Plotly buttons**

---

## 📊 Models Compared

| Model             | MSE (Mean Squared Error) | R² (Coefficient of Determination) | Training Time (approx.) |
|------------------|--------------------------|----------------------------------|--------------------------|
| XGBRegressor      | 17,974,718               | 0.9915                           | ~0.8 sec                 |
| Linear Regression | 17,375,021               | 0.9918                           | ~0.27 sec                |

- 🔧 *XGBoost was optimized using a parameter grid search.*
- ⚡ *Linear Regression was faster and slightly more accurate on this dataset.*

---

## 🎛️ Interactive Features

The notebook includes:

- 📦 **Widgets** using `ipywidgets` to input:
  - Age
  - Gender
  - Department
  - Job Title
  - Experience (years)
  - Education Level
  - Location
- 🧠 Real-time salary prediction based on the model
- 📈 **Dynamic Plotly visualizations**:
  - Salary distribution histogram
  - Built-in filter buttons for selecting cities

---


## 🚀 How to Run

1. Open the notebookю
2. Run all cells
3. Use the interactive sliders and dropdowns to predict salaries
4. Explore the salary distribution plots with interactive filters

---
