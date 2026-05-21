# Employee-Burnout-Detector
# Employee Burnout Prediction

**Domain:** HR Analytics · Regression
**Programme:** 3MTT/ Data Science Cohort 3

---

## Overview

A machine learning regression model that predicts employee
burn rate using HR data. Includes SHAP-based explainability
to identify the key drivers of burnout and support
proactive workplace interventions.

---

## Problem

Rising employee burnout reduces productivity and increases
turnover. This model estimates a continuous burn rate score
(0–1) for each employee, enabling HR teams to identify and
support at-risk staff before performance deteriorates.

---

## Workflow

1. Loaded HR training and test datasets
2. Explored distributions, correlations, and missing values
3. Imputed missing values and encoded categorical variables
4. Trained Linear Regression, Random Forest, and Gradient
   Boosting models
5. Applied SHAP to explain feature importance
6. Saved best model using joblib

---

## Key Findings

Top burnout predictors: mental fatigue score, WFH
availability, company type, and employee designation.

---

## Tools

Python · pandas · scikit-learn · SHAP · joblib
Matplotlib · Seaborn · Google Colab

---

## Dataset

HR dataset with employee demographics, work conditions,
and mental health indicators.
Target variable: Burn Rate (continuous, 0–1)

---

## Author

Adewole Toluwalope Olumide
Agricultural Economist & Data Scientist
Lagos, Nigeria
github.com/Adewole-Toluwalope
