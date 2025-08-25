## Optimizing Health Risk Predictions with AI and Data Accuracy
# Project Overview

This project focuses on enhancing healthcare risk prediction by improving the quality of data in Electronic Health Records (EHRs). By integrating advanced machine learning models with robust preprocessing methods, the project demonstrates how AI can support clinical decision-making, hospital discharge planning, and patient-centered care.

# Key Contributions:

Improved EHR data preprocessing (imputation, outlier handling, scaling).

Applied Logistic Regression, Decision Trees, and Neural Networks for prediction.

Addressed class imbalance using SMOTE.

Achieved up to 98.6% accuracy with strong recall/precision scores.

Developed interpretable Power BI dashboards and visualizations.

# Project Structure

final code.ipynb → Main Jupyter Notebook containing data preprocessing, feature engineering, modeling, and evaluation.

EHR.csv → Dataset of patient health records used for training and validation.

Final Presentation.pptx → Project presentation slides summarizing methodology, results, and findings.

README.md → Documentation of the project (this file).

#  Installation & Setup
Requirements

Make sure you have the following installed:

Python 3.8+

Jupyter Notebook

# Libraries:

pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn

# Dataset

The dataset EHR.csv should be placed in the project directory.

Missing values and outliers are handled automatically in preprocessing steps.

# Running the Project

Open Jupyter Notebook:

jupyter notebook


Run the notebook final code.ipynb.

The notebook will:

Load and preprocess the dataset.

Perform feature engineering.

Train and evaluate multiple machine learning models.

Generate evaluation metrics (accuracy, precision, recall, F1, ROC/AUC).

# Results

Logistic Regression: 98.6% accuracy, perfect recall for “True” cases.

Decision Tree: Perfect accuracy (risk of overfitting).

Neural Network: 97.2% accuracy with high precision but lower recall.

ROC/AUC scores range between 0.83 – 0.84.

These models highlight the potential of AI-driven risk prediction for hospital discharge planning and clinical support systems.
