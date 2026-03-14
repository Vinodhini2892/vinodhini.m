# vinodhini.m
job-acceptance-ml-project
# Job Acceptance Prediction & HR Analytics Dashboard

## Project Overview

This project builds a **Machine Learning system to predict whether a candidate will accept a job offer** based on various academic, technical, and experience-related features.

The project demonstrates a **complete data analytics and machine learning workflow**, including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and an interactive dashboard.

The final system also includes a **Streamlit-based dashboard** that allows HR teams to explore key metrics and predict job acceptance outcomes.

---

## Objectives

The main objectives of this project are:

* Clean and preprocess real-world candidate data
* Perform exploratory data analysis (EDA)
* Engineer useful features for prediction
* Train a supervised machine learning classification model
* Evaluate model performance using standard metrics
* Build an interactive dashboard for HR analytics and prediction

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Streamlit
* MySQL (optional for storage)

---

## Project Structure

```
job_acceptance_project
│
├── data
│   ├── raw_data.csv
│   ├── cleaned_data.csv
│   └── feature_engineered_data.csv
│
├── database
│   └── store_to_mysql.py
│
├── model
│   └── job_acceptance_model.pkl
│
├── src
│   ├── data_cleaning.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   └── evaluation.py
│
├── dashboard
│   └── streamlit_app.py
│
├── requirements.txt
└── README.md
```

---

## Dataset Description

The dataset contains information about job candidates including:

* Age
* Gender
* Academic performance (SSC, HSC, Degree)
* Technical score
* Aptitude score
* Communication score
* Skills match percentage
* Internship experience
* Years of experience
* Previous and expected salary
* Company tier
* Notice period
* Employment gap
* Relocation willingness

Target Variable:

**status**

* 1 → Candidate accepts the job offer
* 0 → Candidate does not accept the job offer

---

## Machine Learning Workflow

### 1. Data Cleaning

* Handled missing values using mean, median, or mode
* Removed
