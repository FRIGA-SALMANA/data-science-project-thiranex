# Data Cleaning and Visualization Project

## Overview
This project focuses on cleaning and analyzing a raw dataset to extract useful insights. The dataset is processed using Python libraries and visualized to understand patterns and trends.

## Objectives
- Handle missing values
- Remove duplicate records
- Detect and manage outliers
- Visualize data insights

## Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```
data-cleaning-visualization-project
│
├── data
│   ├── tips.csv
│   └── cleaned_tips.csv
│
├── notebook
│   └── data_cleaning_step.ipynb
│
├── visuals
│   └── bill_distribution.png
│
├── report
│   └── data_cleaning_report.pdf
│
└── README.md
```

## Data Cleaning Steps
1. Loaded the raw dataset
2. Checked for missing values
3. Filled missing values
4. Removed duplicate entries
5. Identified outliers
6. Saved cleaned dataset

## Visualization

Bill distribution visualization:

<img width="766" height="458" alt="image" src="https://github.com/user-attachments/assets/29927eeb-c715-4fea-a865-6641410bae77" />

## Key Insights
- Most bills fall between a moderate range.
- Some high-value bills appear as outliers.
- Tip amount increases with total bill.

# Predictive Modeling Using Machine Learning

This project demonstrates a complete machine learning pipeline starting from **data cleaning** to **predictive modeling** and **model evaluation**.

The objective is to build a machine learning model that can predict outcomes using supervised learning algorithms and evaluate the model performance.

---

# Project Structure

```
data_science_project/
│
├── data_cleaning/
│   ├── data_cleaning.ipynb
│   └── cleaned_dataset.csv
│
├── predictive_modeling/
│   ├── predictive_model.ipynb
│   └── outputs/
│       ├── bill_distribution.png
│       ├── confusion_matrix.png
│       └── roc_curve.png
│
└── README.md
```

---

# 1. Data Cleaning

The **data_cleaning** folder contains the notebook used to preprocess and prepare the dataset for machine learning.

## Steps Performed

- Importing the dataset
- Handling missing values
- Removing duplicate records
- Data formatting and type conversion
- Feature selection
- Saving the cleaned dataset

## Output

After cleaning, the processed dataset is saved as:

```
cleaned_dataset.csv
```

This cleaned dataset is used as input for predictive modeling.

---

# 2. Predictive Modeling

The **predictive_modeling** folder contains the notebook responsible for building and evaluating machine learning models.

## Algorithms Used

- Linear Regression
- Decision Tree
- Random Forest

## Workflow

1. Load the cleaned dataset
2. Split the dataset into training and testing sets
3. Train machine learning models
4. Evaluate model performance
5. Visualize results

---

# Model Evaluation

The models are evaluated using different performance metrics and visualizations.

## Confusion Matrix

The confusion matrix helps evaluate the classification performance of the model.

<img width="800" height="500" alt="confusion_matrix" src="https://github.com/user-attachments/assets/755d29bd-c72f-401a-b660-ceacd03fc540" />

## ROC Curve

The ROC curve shows the ability of the model to distinguish between classes.

<img width="800" height="500" alt="roc_curve" src="https://github.com/user-attachments/assets/97cea971-d70f-46e8-a2c6-d7c38bb1065e" />

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Expected Outcome

This project provides hands-on experience in:

- Data preprocessing
- Supervised machine learning
- Model training and testing
- Model evaluation techniques
- Performance visualization using confusion matrices and ROC curves
