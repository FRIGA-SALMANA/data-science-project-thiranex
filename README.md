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

# 3. Exploratory Data Analysis (EDA) on Restaurant Tips Dataset

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a restaurant tipping dataset to discover patterns, trends, and relationships between variables such as total bill, tip amount, customer gender, smoking status, day, time, and group size.

The analysis uses statistical summaries and data visualizations to better understand customer tipping behavior.

## Dataset Description
The dataset contains information about restaurant customers and their tipping behavior.

Features in the dataset:
- total_bill – Total bill amount
- tip – Tip amount given by the customer
- sex – Gender of the customer
- smoker – Whether the customer is a smoker or non-smoker
- day – Day of the visit
- time – Meal time (Lunch or Dinner)
- size – Number of people in the group

## Objectives
- Perform exploratory data analysis on the dataset
- Generate statistical summaries
- Visualize data distributions and relationships
- Identify correlations between variables
- Discover factors influencing tip amounts

## Tools and Libraries Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis Steps
1. Data Loading and Inspection
2. Data Cleaning and Missing Value Check
3. Statistical Summary of Data
4. Univariate Analysis
5. Bivariate Analysis
6. Correlation Analysis
7. Visualization of Patterns and Trends

## Key Insights
- Tip amount generally increases as the total bill increases.
- Larger group sizes often result in higher total tips.
- Tipping behavior may vary depending on day, time, and customer characteristics.
- Visualizations help reveal patterns and relationships within the dataset.

## Project Structure

```
EDA
│
├── Exploratory_Data_Analysis.ipynb
├── cleaned_tips.csv
└── README.md

```

## Conclusion
This exploratory data analysis provides insights into tipping behavior in restaurants. Understanding these patterns helps identify key factors that influence customer tipping and demonstrates the importance of data visualization and statistical exploration in data analysis.


# 4.Real world data project(Healthcare Data Analysis and Prediction)

## Project Overview
This project focuses on analyzing healthcare data to identify patterns related to patient health and predict potential health risks using machine learning techniques. The project demonstrates an end-to-end data science workflow including data preprocessing, exploratory data analysis (EDA), visualization, and predictive modeling.

The goal is to apply data science skills to a real-world healthcare dataset and extract meaningful insights that could assist in healthcare decision-making.

---

## Dataset
The dataset contains patient health-related information such as:

- Age
- Gender
- Body Mass Index (BMI)
- Blood Pressure
- Cholesterol Level
- Glucose Level
- Smoking Status
- Heart Rate

These features are used to analyze health patterns and build a machine learning model to predict potential health risks.

---

## Project Objectives

- Perform exploratory data analysis on healthcare data
- Identify relationships between health indicators
- Visualize important patterns and trends
- Build a machine learning model for prediction
- Evaluate the performance of the predictive model
- Demonstrate a complete data science workflow

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```
Data_science(Real world)/
│
├── data/
│ └── hospital_healthcare_dataset.csv
│
├── notebooks/
│ └── Healthcare(Data Science).ipynb
│
├── reports/
│ └── Health_Care.pdf
│
├── outputs/
│ ├── visualizations/
│ └── model_results/

```

### Folder Description

**data/**  
Contains the raw dataset used for analysis and model training.

**notebooks/**  
Contains Jupyter notebooks used for:
- Data cleaning
- Exploratory data analysis
- Visualization
- Machine learning model development

**reports/**  
Contains written summaries or reports explaining analysis results and findings.

**outputs/**  
Stores generated outputs such as:
- Visualizations
- Model evaluation results
- Prediction outputs

---

## Project Workflow

### 1. Data Loading
The dataset is loaded using Pandas and inspected to understand its structure, data types, and initial statistics.

### 2. Data Cleaning
Data preprocessing steps include:

- Handling missing values
- Checking for duplicate records
- Verifying data types
- Preparing features for analysis

### 3. Exploratory Data Analysis (EDA)
EDA helps to understand the relationships between different health variables.

Key analyses include:

- Age distribution
- BMI distribution
- Blood pressure analysis
- Cholesterol level patterns
- Smoking habits
- Feature correlation analysis

---

### 4. Data Visualization

Several visualizations are created to explore patterns in the data:

- Distribution plots
- Histograms
- Correlation heatmap
- Feature comparison plots

These visualizations help identify potential health risk indicators.

---

### 5. Feature Engineering

- Encoding categorical variables
- Selecting relevant features
- Preparing data for machine learning

---

### 6. Model Building

A **Logistic Regression model** is used to predict health risk based on patient features.

Steps involved:

- Train-test split
- Model training
- Prediction generation

---

### 7. Model Evaluation

The model performance is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

These metrics help measure the effectiveness of the predictive model.

---

## Key Insights

- Age plays an important role in determining health risks.
- Higher BMI levels may increase the chances of health complications.
- Cholesterol and glucose levels are strong indicators of potential health issues.
- Blood pressure patterns can help identify cardiovascular risks.

---

## Results

The machine learning model successfully identifies patterns in the healthcare dataset and predicts health risk levels based on patient attributes. This demonstrates how data science techniques can support healthcare analysis and predictive decision-making.

---




