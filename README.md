# Predictive Modelling of Used-Car Prices (AutoTrader UK, ~400k Records)

### Author: **Paramesh Kumar Bukya**  
*MSc Data Science (Distinction), Manchester Metropolitan University*

---

## 📘 Project Overview

This project builds a complete end-to-end **machine learning regression pipeline** to predict used-car prices using a real dataset supplied by **AutoTrader UK** as part of a confidential academic partnership with **Manchester Metropolitan University**.

The notebook includes:

- Comprehensive Exploratory Data Analysis (EDA)  
- Data cleaning (missing values, outliers, formatting issues)  
- Feature engineering (e.g., `age_of_car`)  
- Model training using:  
  - **Decision Tree Regressor**  
  - **k-Nearest Neighbour (kNN) Regressor**  
  - **Linear Regression**  
- Hyperparameter tuning using **GridSearchCV**  
- Evaluation using **MAE**, **RMSE**, and **R²**  
- Basic feature importance and model comparison  

This notebook runs end-to-end **without modifying any code**, provided the dataset is placed in the same folder.

---

## 🔒 Dataset Access (Important)

The dataset used in this project (`adverts.csv`) is **confidential** and was provided exclusively for academic use under a **MMU × AutoTrader UK** partnership agreement.

### Therefore:
- The dataset **cannot be uploaded publicly**
- It is **NOT included** in this repository

### To run the notebook yourself:

1. Place your authorised copy of `adverts.csv` in the **same directory** as the notebook  
2. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn seaborn matplotlib
