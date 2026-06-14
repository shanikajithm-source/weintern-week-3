# Sales Analysis and Prediction Project

## Overview
This project was completed as part of the WeIntern Data Science Internship Week 3 Assignment. The objective was to perform data cleaning, exploratory data analysis (EDA), and build a machine learning model to predict sales using the Superstore dataset.

---

## Project Tasks

### Task 1: Data Cleaning
- Loaded the raw Superstore dataset.
- Checked dataset structure using `head()`, `info()`, and `describe()`.
- Identified and handled missing values.
- Checked and removed duplicate records.
- Standardized column names to snake_case format.
- Converted date columns to datetime format.
- Validated data quality and exported the cleaned dataset.

### Output
- `cleaned_superstore.csv`

---

### Task 2: Exploratory Data Analysis (EDA)
Performed statistical analysis and visualizations to understand the dataset.

#### Visualizations Created
1. Sales Distribution Histogram
2. Sales by Category Bar Chart
3. Correlation Heatmap
4. Discount vs Sales Scatter Plot
5. Profit by Category Box Plot

#### Key Insights
- Technology products contribute significantly to total sales.
- Sales data is highly skewed with a few large transactions.
- Discounts have a weak relationship with sales.
- Profit varies across product categories.
- Most orders contain relatively small quantities.

---

### Task 3: Sales Prediction Model
Built and evaluated machine learning models to predict sales.

#### Models Used
- Linear Regression
- Random Forest Regressor

#### Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-Squared (R²)

#### Additional Analysis
- Feature Importance Visualization
- Actual vs Predicted Plot
- Hyperparameter Tuning using GridSearchCV

#### Best Parameters
- max_depth = 10
- n_estimators = 100

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Files Included

- Task_1.ipynb
- Task_2.ipynb
- Task_3.ipynb
- cleaned_superstore.csv
- raw_dataset.zip
- README.md

---

## Dataset
Sample Superstore Dataset

---

## Conclusion
This project demonstrates the complete data science workflow including data preprocessing, exploratory analysis, visualization, machine learning model development, evaluation, and optimization. The Random Forest model produced better predictive performance and was selected as the final model for sales prediction.
