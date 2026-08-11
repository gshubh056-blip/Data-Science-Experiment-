# Data-Science-Experiment-
Kaggle based Data science experiment . 
# Diabetes Prediction using the Pima Indians Diabetes Dataset

## Overview
This is my first hands-on machine learning experiment, where I built a model to predict whether a patient is likely to have diabetes based on key diagnostic measurements. The goal was to get comfortable with the end-to-end ML workflow — from data cleaning to model evaluation.

## Objective
Given a set of medical diagnostic features, predict whether a patient has diabetes (binary classification: `1` = diabetic, `0` = non-diabetic).

## 📊 Dataset
- **Source:** [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/jamaltariqcheema/pima-indians-diabetes-dataset) on Kaggle
- **Original source:** National Institute of Diabetes and Digestive and Kidney Diseases (via UCI Machine Learning Repository)
- **Records:** 768 patient records, all female, age 21+, of Pima Indian heritage
- **Features (8 inputs + 1 target):**
  - `Pregnancies` — number of times pregnant
  - `Glucose` — plasma glucose concentration
  - `BloodPressure` — diastolic blood pressure (mm Hg)
  - `SkinThickness` — triceps skinfold thickness (mm)
  - `Insulin` — 2-hour serum insulin (mu U/ml)
  - `BMI` — body mass index
  - `DiabetesPedigreeFunction` — diabetes likelihood based on family history
  - `Age` — age in years
  - `Outcome` — target variable (0 = non-diabetic, 1 = diabetic)

##  Tech Stack
`[Fill in — e.g. Python, pandas, NumPy, scikit-learn, Matplotlib/Seaborn]`

##  Approach
1. Loaded and explored the dataset (EDA)
2. Handled missing/invalid values (e.g. zeros in Glucose, BloodPressure, BMI)
3. Split data into training and test sets
4. Trained a `[Fill in — e.g. Logistic Regression / Random Forest / KNN]` model
5. Evaluated performance using accuracy, precision, recall, and confusion matrix

## 📈 Results
`[Fill in — e.g. Achieved XX% accuracy on the test set]`

## 🚀 How to Run
```bash
git clone <your-repo-link>
cd <repo-folder>
pip install -r requirements.txt
python model.py
```

## 📚 What I Learned
`[Fill in — e.g. handling missing data disguised as zeros, feature scaling, evaluating classifiers beyond accuracy]`

## 🔗 References
- Dataset: [Kaggle — Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/jamaltariqcheema/pima-indians-diabetes-dataset)
