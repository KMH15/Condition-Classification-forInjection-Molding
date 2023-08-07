
# Condition Classification for Injection Molding

## Introduction

### Injection Moulding Process

- Injection moulding is the most commonly used manufacturing process for the fabrication of plastic parts. A wide variety of products are manufactured using injection moulding, which vary greatly in their size, complexity, and application.

- The injection moulding process requires the use of an injection moulding machine, raw plastic material, and a mould. The plastic is melted in the injection moulding machine and then injected into the mould, where it cools and solidifies into the final part.

### Problem Statement

- How can data analytics be utilized for early detection and quality control in production processes to minimize rejections and improve efficiency through automated monitoring and control systems?

### Objectives

- Develop a data analytics framework that can effectively analyse real-time process data to detect and identify unacceptable variables or anomalies during production.

- Implement an automated system that can promptly respond to the detected issues, triggering necessary actions such as automatic rejection of the affected piece, thereby minimizing rejections and improving overall production efficiency.

## Data Understanding and Preprocessing

### Data Preprocessing

- Handling Missing Data
  - KNN Imputation 
- Handling Outliers
  - Z-score method
  - Median Replacement
- Encoding Categorical Variables
  - Label Encoding
  
## Exploratory Data Analysis

- Statistical Analysis 
  - Mean, Median, Range, Standard Deviation
  
- Correlation Analysis
  - Pearson Correlation Coefficient
  
- Data Visualization
  - Pair Plots, Heatmaps

## Model Development

- Machine Learning Models
  - Logistic Regression
  - SVM
  - Decision Tree
  - MLP
  
- Model Evaluation
  - Accuracy, Precision, Recall
  
- Hyperparameter Tuning
  - Grid Search CV
  
- Best Model
  - Logistic Regression
  
## Conclusion

- The analysis provides insights into factors influencing injection molding condition
- Logistic regression emerged as the best model for predicting the condition
- Influential parameters identified using correlation analysis
- The approach can help optimize processes and quality control

