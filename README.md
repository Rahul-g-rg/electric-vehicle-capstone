# 🚗 Electric Vehicle Type Classification

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)

---

## 📌 Project Overview

This capstone project uses machine learning to classify electric vehicles (EVs) into two major types:
- **BEV**: Battery Electric Vehicle  
- **PHEV**: Plug-in Hybrid Electric Vehicle

The project utilizes Washington State's EV Population dataset to analyze and predict EV adoption patterns.

---

## 🎯 Objective

To develop a classification model that can accurately identify the type of EV based on features like:
- Model Year
- Make
- Electric Range
- Base MSRP
- CAFV Eligibility

---

## 🧰 Tools & Technologies

- **Language**: Python
- **Libraries**: pandas, numpy, seaborn, matplotlib, scikit-learn, joblib
- **Environment**: Jupyter Notebook

---

## 🔍 Project Workflow

1. **Data Cleaning**
   - Removed missing values and duplicates
   - Handled outliers using IQR

2. **Exploratory Data Analysis (EDA)**
   - Visualized distribution of model year, range, MSRP, and make

3. **Feature Engineering**
   - Label encoding and One-Hot encoding
   - Removed high-cardinality columns

4. **Modeling**
   - Trained Logistic Regression, Random Forest, and Gradient Boosting models
   - Evaluated using Accuracy, F1 Score, and ROC-AUC

5. **Model Deployment**
   - Saved best model using `joblib`

---

## 🧠 Key Insights

- Tesla dominates EV registrations in Washington
- BEVs are more common than PHEVs
- Significant EV adoption occurred post-2018

---

## 📁 Project Files

| File                        | Description                           |
|----------------------------|---------------------------------------|
| `EV_Capstone_Project.ipynb` | Full Jupyter Notebook                 |
| `best_ev_model.pkl`         | Trained Random Forest model           |
| `EV_X_features.csv`         | Cleaned and encoded features (optional) |
| `EV_y_target.csv`           | Encoded target column (optional)      |
| `*.png`                     | EDA visualizations                    |

---

## 🧪 How to Run This Project

1. Clone the repo or download files
2. Open `EV_Capstone_Project.ipynb` in Jupyter
3. Run all cells to retrain or load the model
4. (Optional) Use `joblib.load()` to load the saved model

---

## 📧 Contact

Made with ❤️ by [RAHUL G]  
[Your LinkedIn](https://www.linkedin.com/in/rahulrahulgangadharan/)  
[Your GitHub](https://github.com/Rahul-g-rg)

