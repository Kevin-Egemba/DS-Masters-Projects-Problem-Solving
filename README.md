# Body Fat Percentage Prediction Project

## Project Overview

This project is a comprehensive end-to-end data science case study focused on predicting body fat percentage using anthropometric measurements. It demonstrates a full machine learning workflow including data preprocessing, exploratory data analysis (EDA), feature selection, regression modeling, regularization techniques, and model evaluation. The analysis was conducted using Jupyter Notebook and Python, and serves as a demonstration of applied data science capabilities in a health-related context.

## Objective

The primary objective of this project is to develop accurate and interpretable predictive models for estimating a person’s body fat percentage using body measurements. This kind of modeling is valuable for non-invasive health assessments and can be applied in health tech, wellness, and clinical settings.

## Dataset

The dataset used in this project is `560_bodyfat.csv`, which contains 252 observations of body composition measurements for adult males. The features include age, weight, height, and various body circumference measurements (e.g., abdomen, wrist, hip). The target variable is the individual's body fat percentage.

## Key Steps in the Project

### 1. Data Import and Cleaning
- Loaded the dataset and checked for null values and data types.
- Validated data integrity and confirmed the number of samples and features.
- Verified the target variable distribution and checked for potential data leakage.

### 2. Exploratory Data Analysis (EDA)
- Generated summary statistics for each variable.
- Created histograms, boxplots, and scatter plots to visualize distributions and identify outliers.
- Conducted correlation analysis to identify strong predictors of body fat percentage.

### 3. Feature Engineering and Selection
- Standardized numerical features where necessary.
- Selected features based on domain knowledge and correlation strength with the target variable.
- Evaluated multicollinearity using correlation matrices and VIF scores.

### 4. Model Building and Evaluation
- Built and evaluated multiple models:
  - Simple Linear Regression
  - Multiple Linear Regression
  - Ridge Regression (L2 regularization)
  - Lasso Regression (L1 regularization)
  - Decision Tree Regressor
- Trained models using train-test split methodology and compared performance on test data.
- Evaluated models using R² score, RMSE, and residual plots to check for assumptions and performance.

### 5. Model Interpretation
- Analyzed coefficients of linear models to understand feature influence.
- Used feature importance scores for tree-based models to evaluate key predictors.
- Discussed potential model bias and limitations.

## Tools and Libraries Used
- Python 3.9
- Jupyter Notebook (via JupyterLab)
- pandas (for data manipulation)
- matplotlib (for data visualization)
- sklearn (for modeling and evaluation)

## Key Learnings and Outcomes

- Gained experience working with real-world structured health-related data.
- Practiced preprocessing, EDA, and regression modeling techniques in a reproducible workflow.
- Learned to evaluate and compare multiple models in terms of interpretability and accuracy.
- Applied regularization techniques to combat overfitting and improve generalization.
- Enhanced understanding of residual analysis and diagnostics for regression models.
- Produced clean, professional, and interpretable notebook documentation to communicate technical results.

## How to Run the Project

1. Clone the repository or download the notebook files.
2. Ensure you have Python 3.9+ installed.
3. Install required packages using the following command:

```
pip install -r requirements.txt
```

4. Launch JupyterLab and open `project.ipynb`.
5. Run all cells to reproduce the analysis and results.

## File Structure

- `project.ipynb`: Main Jupyter notebook containing the full analysis.
- `560_bodyfat.csv`: Dataset used for training and evaluation.
- `requirements.txt`: Python packages required to run the notebook.
- `README.md`: Project documentation (this file).

## Contact Information

Kevin Egemba  
M.S. in Data Science Candidate, Boston University  
Data Manager | Data Analyst | Aspiring Data Scientist  
Email: kevin@example.com  
LinkedIn: https://www.linkedin.com/in/your-profile  
GitHub: https://github.com/your-github

