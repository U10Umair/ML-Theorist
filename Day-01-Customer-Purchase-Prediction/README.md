# Day 1 – Customer Purchase Prediction

## Project Overview
This project focuses on predicting whether a customer will make a purchase based on their demographic and behavioral data.

The goal of this project is to practice:
- End-to-end machine learning workflow
- Model training and evaluation
- Interpreting model coefficients

---

## Dataset
- Source: Kaggle  
- Link: https://www.kaggle.com/datasets/rabieelkharoua/predict-customer-purchase-behavior-dataset

The dataset contains customer-related features such as age, income, website activity, and loyalty status.

---

## Workflow
1. Load and explore the dataset
2. Check for missing values (none found)
3. Split data into training and testing sets
4. Train a classification model
5. Evaluate performance using accuracy
6. Analyze feature importance

---

## Model Performance
- Accuracy: **~77%**

The model performs reasonably well for a first baseline implementation.

---

## Feature Weights (Insights)

| Feature | Weight |
|------|------|
| Age | -0.078 |
| Gender | -0.248 |
| AnnualIncome | 0.000012 |
| NumberOfPurchases | 0.045 |
| ProductCategory | -0.126 |
| TimeSpentOnWebsite | 0.049 |
| LoyaltyProgram | **2.156** |
| DiscountsAvailed | 0.423 |

### Key Insight:
Customers enrolled in the **loyalty program** have the strongest influence on purchase behavior.

---

## Tools Used
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## Learning Outcome
This project helped reinforce:
- Train-test split
- Model training (`fit`)
- Prediction (`predict`)
- Evaluation using accuracy
- Interpreting model coefficients

---

## Status
Baseline model completed.  
Future improvements may include feature engineering and trying other algorithms.

