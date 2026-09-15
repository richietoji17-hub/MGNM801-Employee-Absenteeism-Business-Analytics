# MGNM801 – Employee Absenteeism Business Analytics

## Project Overview

This repository contains the complete project for **MGNM801 – Business Analytics**.

The project investigates workplace absenteeism using the genuine **UCI Machine Learning Repository – Absenteeism at Work** dataset. Python is used to perform data exploration, data preparation, descriptive analysis, visualization, classification modelling, model evaluation, and business interpretation.

The objective is to understand patterns associated with higher absenteeism and examine how analytics can support workforce planning and operational decision-making.

---

## Business Problem

Employee absenteeism can create challenges for staffing, workload allocation, scheduling, and workforce planning.

This project addresses the following business question:

> How can employee and workplace data be analyzed to identify factors and circumstances associated with higher workplace absenteeism and support better workforce planning?

---

## Dataset

**Dataset:** Absenteeism at Work

**Source:** UCI Machine Learning Repository  
**Dataset ID:** 445  
**Official URL:** https://archive.ics.uci.edu/dataset/445/absenteeism+at+work  
**DOI:** https://doi.org/10.24432/C5X882

The dataset contains workplace absenteeism records collected from **July 2007 to July 2010** in the context of a courier company in Brazil.

The original dataset contains **740 records** and includes employee, workplace, scheduling, commuting, and absence-related variables.

---

## Analysis Performed

The project includes:

- Data acquisition using Python
- Initial data exploration
- Missing-value and duplicate checks
- Data preparation
- Feature engineering
- Absenteeism-hours analysis
- Analysis by reason for absence
- Monthly analysis
- Day-of-week analysis
- Seasonal analysis
- Workload analysis
- Commuting and distance analysis
- Employee characteristic analysis
- Lower- vs. higher-absence comparison
- Matplotlib visualizations
- Binary classification of higher absenteeism
- Logistic Regression
- Random Forest Classification
- Accuracy, Precision, Recall, F1-score and AUC
- Confusion matrix
- Random Forest feature importance
- Business interpretation and recommendations

---

## Classification Target

The original target variable is:

```text
Absenteeism time in hours
