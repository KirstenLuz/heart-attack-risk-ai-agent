# Intelligent Agent for Heart Attack Risk Prediction in Women

This project was developed for the Artificial Intelligence course at Universidade do Vale do Itajaí (UNIVALI).

The objective of the project is to develop an intelligent agent capable of identifying women with high risk of heart attack using Machine Learning techniques applied to clinical, behavioral and health-related data.

---

# Project Objective

Create an intelligent agent capable of analyzing patient information and classifying heart attack risk based on multiple health indicators.

The project explores:
- Data preprocessing
- Outlier treatment
- Data transformation and encoding
- Statistical analysis
- Dataset balancing with SMOTE
- Model training and evaluation

---

# Dataset

Dataset source:
- Kaggle — Heart Attack Prediction Dataset

Original dataset:
- 8763 records
- Male and female patients

Filtered dataset used in the project:
- 2652 female patients only

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Imbalanced-Learn (SMOTE)
- Matplotlib
- Seaborn

---

# Machine Learning Models

The following algorithms were tested:

- Decision Tree
- Naive Bayes
- Random Forest

Both categorical and continuous versions of the dataset were evaluated.

---

# Main Results

| Model | Dataset | Test Accuracy |
|---|---|---|
| Decision Tree | Categorical | 55.03% |
| Naive Bayes | Categorical | 57.29% |
| Naive Bayes | Continuous | 54.02% |
| Random Forest | Continuous | 55.78% |

The experiments showed that the main limitation was not the algorithms themselves, but the synthetic nature of the dataset, which lacked strong real-world correlations between variables.

---

# Project Structure

```bash
├── data/
├── notebooks/
├── src/
├── images/
├── report/
└── README.md
```

---

# Features Analyzed

Some of the analyzed variables include:

- Age
- Cholesterol
- Blood Pressure
- Heart Rate
- Diabetes
- Smoking
- Obesity
- Alcohol Consumption
- Physical Activity
- Stress Level
- Sleep Hours
- BMI
- Triglycerides

---

# Methodology

## Data Preparation
- Removal of irrelevant columns
- Correction of import errors
- Categorization and encoding of variables

## Outlier Treatment
- IQR (Interquartile Range) method

## Train/Test Split
- Holdout method
- 70% training
- 15% validation
- 15% testing
- Stratified split

## Balancing
- SMOTE applied to training data

---

# Conclusions

The models achieved relatively low performance due to the synthetic characteristics of the dataset. Feature importance analysis demonstrated the absence of highly predictive variables, limiting the models’ ability to distinguish between classes effectively.

Even so, the project was valuable for understanding the complete Machine Learning pipeline applied to healthcare data.

---

# Authors

- Kirsten Luz Concepcion
- Pedro Henrique Schneider

---

# Academic Project

Artificial Intelligence — UNIVALI  
Professor Anita Maria da Rocha Fernandes
