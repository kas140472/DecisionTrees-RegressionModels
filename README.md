# Decision Trees and Advanced Regression Analysis

## Project Overview
This project explores two main areas of machine learning: interpretable decision trees and advanced regression techniques including LASSO and Boosting. The analysis includes comprehensive data preparation, feature selection, and model evaluation using multiple approaches.

## Key Components
* **Decision Tree Analysis**:
  * Multi-label classification implementation
  * Cost-complexity pruning
  * Rule extraction and interpretation
  * Visualization of decision boundaries

* **Advanced Regression**:
  * Data imputation for missing values
  * Feature selection using coefficient of variation
  * Multiple regression model implementations
  * Comparative performance analysis

## Technical Details

### Decision Tree Implementation
* **Data Processing**:
  * Multi-label dataset handling
  * Decision rule extraction
  * Tree visualization
  * Pruning optimization

* **Rule Generation**:
  * IF-THEN rule conversion
  * Interpretability enhancement
  * Minimal tree identification

### Regression Analysis
* **Data Preparation**:
  * Missing value imputation
  * Feature selection using CV
  * Correlation analysis
  * Data standardization

* **Models & Evaluation**:
  * Linear regression baseline
  * Ridge regression with cross-validation
  * LASSO with feature selection
  * Principal Component Regression
  * L1-penalized gradient boosting trees

## Technologies Used
* Python
* Scikit-learn
* XGBoost
* Pandas
* Matplotlib/Seaborn

## Datasets
### Acute Inflammations Dataset
* Multi-label classification task
* Medical diagnosis application
* Complete dataset analysis

### Communities and Crime Dataset
* 1495 training samples
* Multiple numerical features
* Regression task
* Contains missing values

## Implementation Details
* **Feature Selection**:
  * CV calculation for all features
  * Top floor(sqrt(128)) features analysis
  * Correlation matrix visualization
  * Scatter and box plot analysis

* **Model Evaluation**:
  * Cross-validation error analysis
  * Test set performance comparison
  * Feature importance assessment
  * Regularization impact analysis

This project was completed as part of USC's DSCI 552 course under the guidance of Professor Mohammad Reza Rajati.

## Resources
* [Decision Tree Interpretation Guide](https://www.kdnuggets.com/2017/05/simplifying-decision-tree-interpretation-decision-rules-python.html)
* [XGBoost Windows Installation](http://www.picnet.com.au/blogs/guido/2016/09/22/xgboost-windows-x64-binaries-for-download/)
* [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/)
