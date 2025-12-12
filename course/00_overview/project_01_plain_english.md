# Project 1 (Anchor Project): Tabular Healthcare ML  

This document describes the first project that anchors this learning program. The goal is to build a machine‑learning model that makes predictions from healthcare‑style table data.  

## What this project is about  

You will work with tabular data—rows and columns like a spreadsheet or database table. Each row represents a patient, visit or claim. Each column contains information about that row (age, diagnosis codes, number of visits, etc.). The aim is to teach a computer to find patterns in this data and predict something useful.  

## Types of data involved  

Tabular data means structured data in rows and columns. Examples include:  

- Patient demographic fields (age, sex)  
- Clinical codes (diagnoses, procedures, medications)  
- Utilization metrics (number of visits, length of stay)  
- Financial metrics (costs, charges)  

We start with structured tabular data because this is the most common data type in healthcare analytics.  

## Example prediction tasks  

We will select one clear prediction task, such as:  

- **Readmission classification**: Predict whether a patient will be readmitted within 30 days (yes or no).  
- **Cost threshold classification**: Predict whether a claim will exceed a certain cost threshold (yes or no).  
- **Cost regression**: Predict the total cost for the next period (a number).  

For learning, binary classification (yes/no) is simpler; regression tasks can be attempted later.  

## Success criteria  

Success is not measured by perfect accuracy or fancy algorithms. Instead, success means:  

- You understand what the model is doing.  
- You can explain why it performs the way it does.  
- You know how to detect and prevent situations where the model “cheats” by using information it should not have (this is called data leakage).  

## Tools used  

For this project you will use:  

- **Python** for programming.  
- **pandas** to load and manipulate tabular data.  
- **scikit‑learn** for data preparation, model training and evaluation.  
- **LightGBM or XGBoost** for building strong models on tabular data.  
- **SHAP** to explain model predictions in human terms.  

Each tool will be introduced only when needed.  

## Skills you will gain  

By completing this project you will learn how to:  

- Convert raw tables into model‑ready datasets.  
- Design validation strategies that avoid data leakage.  
- Train baseline and improved models.  
- Evaluate whether a model is useful using appropriate metrics.  
- Explain model decisions to non‑technical stakeholders.  

These skills are directly applicable to real healthcare analytics work.  

## How to use Coursera materials  

The Coursera Advanced Machine Learning specialization provides many notebooks and assignments. Rather than following them in order, you will pull in specific notebooks when they help with your current task. For example, when you need to understand cross‑validation and leakage, you will consult the relevant notebook from the data science competition module. This approach keeps learning focused and avoids overload.  

## First thinking exercise  

Imagine a spreadsheet with 10 000 rows where each row is a patient visit and you want to predict whether the patient is readmitted within 30 days. Think about:  

- Which columns might be important for this prediction.  
- Which columns might accidentally include information that leaks the outcome.  
- What could go wrong if the model looks at future information.  

This mental exercise sets the stage for building your first model.
