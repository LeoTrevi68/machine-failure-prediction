# Machine Failure Prediction (Predictive Maintenance)

This project analyzes industrial machine data to identify patterns associated with equipment failure.

The objective is to understand the factors that lead to failures and evaluate the ability of machine learning models to detect them.

---

## Business Problem

Unexpected machine failures generate downtime, increase maintenance costs, and impact production efficiency.

Predicting failures in advance allows companies to move from reactive to preventive maintenance strategies.

---

## Key Insights

- **Failure events are difficult to separate clearly**  
  The available process variables do not strongly distinguish failure from normal operation.

- **Failure mechanisms are likely heterogeneous**  
  Different types of failures may have different root causes, but are grouped into a single category.

- **Data limitations impact model performance**  
  Important variables related to failure may not be captured in the dataset.

---

## Modeling Approach

- Data preprocessing and feature scaling  
- Supervised learning models for classification  
- Model evaluation using ROC AUC and classification metrics  
- Exploration of model limitations  

---

## Model Performance

The model shows moderate predictive performance, indicating that some signal exists in the data but is not strong enough for reliable classification.

This suggests that improving data quality and feature representation is critical for better performance.

---

## Key Takeaway

This project demonstrates that model performance is strongly constrained by data quality.

Even well-implemented models cannot achieve high accuracy if key explanatory variables are missing or if failure mechanisms are not properly represented.

---

## Dataset

AI4I 2020 Predictive Maintenance Dataset  
https://www.kaggle.com/datasets/shivamb/ai4i-2020-predictive-maintenance-dataset

The dataset is not included due to size and licensing considerations.
