#  Heart Disease Prediction using Machine Learning

This project aims to predict the risk of heart disease in individuals using a supervised machine learning model trained on the UCI Heart Disease dataset.

## Objective

Build a binary classification model to identify whether a patient is at risk of heart disease based on medical and personal health data.

##  Features

- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Model training: Logistic Regression & Decision Tree
- Model evaluation using accuracy, confusion matrix, and ROC-AUC score
- Feature importance analysis

## Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Steps

1. Load and inspect the dataset
2. Clean and preprocess the data
3. Perform EDA to identify trends and patterns
4. Encode categorical variables (e.g. converting strings to 0/1)
5. Train classification models
6. Evaluate model performance
7. Highlight important features

## Results

- Achieved high accuracy in predicting heart disease
- ROC curve and AUC score used for performance evaluation
- Identified key predictors like age, cholesterol, chest pain type, and exercise-induced angina

## How to Run

```bash
# Clone the repo
git clone https://github.com/mushafmirdev/Heart-Disease-Preiction.git
cd Heart-Disease-Preiction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook code.ipynb
