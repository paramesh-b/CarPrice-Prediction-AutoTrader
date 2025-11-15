Predictive Modelling of Used-Car Prices (AutoTrader UK, ~400k Records)
Author: Paramesh Kumar Bukya

MSc Data Science (Distinction), Manchester Metropolitan University

📘 Project Overview

This project builds a complete end-to-end Machine Learning regression pipeline to predict used-car prices using a large real-world dataset supplied by AutoTrader UK as part of a confidential partnership with Manchester Metropolitan University (MMU).

The work demonstrates:

Exploratory Data Analysis (EDA)

Data cleaning & preprocessing (missing values, outlier handling)

Feature engineering (age_of_car, target encoding)

Model development (Decision Tree, kNN, Linear Regression)

Hyperparameter tuning using GridSearchCV

Model evaluation using MAE, RMSE, R²

Interpretability using feature importance and SHAP

The notebook is fully runnable without modification, provided the authorised dataset is available.

🔒 Dataset Access (Important)

The AutoTrader dataset used in this project is confidential and was provided solely for academic purposes under a MMU × AutoTrader UK partnership agreement.

⚠️ Therefore:

The dataset cannot be uploaded or distributed publicly.

The CSV file (adverts.csv) is intentionally NOT included in this repository.

To run the notebook:

Place your authorised copy of adverts.csv in the same folder as the notebook.

Open the notebook in Jupyter/Colab.

Run all cells — no code changes are required.

If you are a recruiter or reviewer without access to the data,
please refer to the methods, results, and PDF report included in this repository.

📂 Repository Contents
File	Description
CarPrice_AutoTrader_Paramesh_Bukya.ipynb	Fully runnable notebook with complete pipeline, EDA → Modelling → Evaluation
Machine learning final.pdf	Original academic report submitted as part of MSc coursework
README.md	Project documentation, confidentiality note, instructions
🧪 Machine Learning Workflow
1. Data Cleaning & Preparation

Replaced missing values using mean/median strategies

Removed extreme outliers using IQR

Converted date and numerical fields

Selected and cleaned key predictive features

2. Feature Engineering

Derived age_of_car from year of registration

Target encoded high-cardinality categorical columns

Normalised/standardised numerical fields

3. Model Training

Three baseline ML models were trained:

Decision Tree Regressor

k-Nearest Neighbour Regressor

Linear Regression

Hyperparameter tuning performed via GridSearchCV.

4. Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

Residual diagnostics

Feature importance analysis

Best model:

⭐ Decision Tree Regressor — MAE ≈ £2,130
🧠 Key Results

Decision Tree consistently outperformed kNN and Linear Regression

Appropriate preprocessing & encoding significantly improved performance

Feature drivers included:

age_of_car

mileage

color

standard_make/model

Model behaviour is interpretable and stable.

🧩 Reproducibility

To reproduce this project:

Install required packages:

pip install numpy pandas matplotlib seaborn scikit-learn


Place your authorised adverts.csv in the same folder

Run the notebook from top-to-bottom

⚠️ The notebook will not run without the dataset (due to confidentiality).

🧑‍💻 Author

Paramesh Kumar Bukya
MSc Data Science (Distinction), Manchester Metropolitan University
LinkedIn: www.linkedin.com/in/paramesh-kumar-bukya-296368238

Email: parmeshkumar496@gmail.com

✔️ Notes for Recruiters / Reviewers

This repository contains all code and documentation required to demonstrate:

ML pipeline design

Data preprocessing

Evaluation methodology

Interpretability

Academic writing quality

Dataset is excluded due to confidentiality, but full details are provided in the report and notebook.
