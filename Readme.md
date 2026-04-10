# Diabetes Prediction

## Repository Description

This project implements a machine learning model to predict whether a patient is likely to have diabetes based on various medical features. The dataset contains several numerical attributes such as glucose level, blood pressure, BMI, insulin level, and age.

The goal is to build a predictive model capable of identifying diabetic patients from non-diabetic ones. The project includes data preprocessing, exploratory data analysis, feature scaling, model training, and evaluation.

This project can be useful in healthcare applications to support early detection and decision-making.
---

## Key Features

- Data cleaning and normalization  
- Feature analysis and visualization  
- Implementation of classification model: **Support Vector Machine (SVM)**  
- Model evaluation using accuracy  
- Simple and beginner-friendly structure  

---

## Project Structure
```bash
.
├── datasets
    ├── diabetes.csv
├── diabetes.ipynb # Main Jupyter Notebook (core project)
├── requirements.txt # Dependencies
└── README.md
```

> Note: Only the **Jupyter Notebook (`diabetes.ipynb`)** is included in this repository.

---

## Setup Project

### 1. Create and activate virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### 2. Options:

#### Option 1: Run with Jupyter Notebook (Recommended)
##### Install Jupyter:
```bash
pip install notebook
```
##### Launch Jupyter:
```bash
jupyter notebook
```

##### Then open: 
diabetes.ipynb

#### Option 2: Convert to Python Script

If you prefer running a .py file:

##### Convert notebook to script:
```bash
jupyter nbconvert --to script diabetes.ipynb
```
##### This will generate:
diabetes.py
##### Run the script:
```bash
python3 diabetes.py
```