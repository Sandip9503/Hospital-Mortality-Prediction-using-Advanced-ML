Hospital Mortality Prediction using Advanced Machine Learning
This project focuses on predicting patient mortality in hospitals using advanced machine learning techniques. The goal is to identify patterns in clinical data that can help forecast in-hospital deaths, aiding healthcare professionals in risk assessment and patient care prioritization.

🧠 Project Overview
Notebook: Hospital_Mortality_Prediction using PyCaret.ipynb

Toolkits Used: PyCaret, pandas, numpy, matplotlib, seaborn

Problem Type: Binary Classification

Target Variable: Indicates whether a patient died during hospitalization

🚀 Key Features
Data Preprocessing: Includes data cleaning, encoding categorical variables, handling missing values, and feature scaling.

Exploratory Data Analysis (EDA): Visual analysis to understand the distribution of features and correlations.

Model Training & Evaluation: Utilizes PyCaret to quickly compare and select the best-performing model.

Automated ML Pipeline: Efficient and quick model building using PyCaret's setup() and compare_models() functions.

Model Interpretation: Includes feature importance and classification metrics like accuracy, precision, recall, and ROC-AUC.

🛠️ Requirements
Install dependencies via pip:

pip install pycaret pandas matplotlib seaborn

or using conda

conda install -c conda-forge pycaret

🔍 How to Run
Clone the repository:

git clone <repo-url>
cd <repo-folder>

Launch the notebook:

jupyter notebook "Hospital_Mortality_Prediction using PyCaret.ipynb"

Follow the cells to preprocess data, train models, and evaluate performance.

📊 Output
Best classification model selected by PyCaret

Performance metrics including confusion matrix, AUC curve

Feature importance plot

Predictions on test data

📌 Notes
The notebook uses PyCaret for simplicity and speed in prototyping.

Ensure all required libraries are installed to avoid import errors.

Data privacy and ethical use of patient data should be strictly followed if working with real hospital datasets.
