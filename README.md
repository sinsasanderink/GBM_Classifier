# Employee Attrition Prediction

This project aims to predict employee attrition based on various employee data, including demographic, job, and performance information. The model utilizes data preprocessing, feature engineering, and machine learning algorithms to classify employees likely to leave.

## Project Overview

1. **Exploratory Data Analysis (EDA)**:
   - Initial data inspection with Pandas, handling missing values, and creating visualizations using Seaborn and Matplotlib.
   - Correlation heatmaps to examine relationships between variables.

2. **Feature Engineering**:
   - Converting categorical features to numerical representations using one-hot encoding.
   - Combining numerical and encoded categorical features for model readiness.

3. **Model Training**:
   - Splitting data into training and test sets.
   - Using machine learning models, including Gradient Boosting and Random Forest, to predict attrition.
   - Evaluating models with metrics such as accuracy and log loss.

4. **Hyperparameter Tuning**:
   - Fine-tuning model parameters for Gradient Boosting with cross-validation.

5. **Feature Importance Visualization**:
   - Generating feature importance plots using Plotly to understand impactful features.

## Requirements

Install the following packages if not already available:

```python
!pip install numpy pandas seaborn matplotlib plotly scikit-learn imbalanced-learn xgboost
