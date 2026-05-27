# Telecom Customer Churn Prediction

## Project Overview

This project develops a machine learning model to predict customer churn in a telecommunications company. Using customer demographics, service usage, and expense data, the model identifies customers at risk of leaving, enabling proactive retention strategies.

## Business Problem

**Challenge**: A telecom firm experiences customer attrition and needs to:
- Identify high-risk churn customers
- Understand which factors drive churn
- Develop targeted retention programs
- Improve customer lifetime value

**Solution**: Logistic regression model predicting churn probability with feature importance analysis.

## Dataset Overview

### Features

**Demographics**:
- Age
- Gender
- Family status

**Services Availed**:
- Internet packages purchased
- Special offers taken
- Service types subscribed

**Expenses**:
- Monthly recharge amounts
- Total spending patterns

**Target Variable**: 
- `Churn`: Customer left the service (Yes/No)

See `Telecom Churn Data Dictionary.csv` for complete variable descriptions.

## Project Methodology

### Step 1: Data Cleaning & Preparation
   - Load and inspect data
   - Handle missing values
   - Data type conversions
   - Duplicate removal

### Step 2: Exploratory Data Analysis
   - Univariate analysis of features
   - Bivariate analysis with target variable
   - Visualization of churn patterns
   - Correlation analysis

### Step 3: Model Development
   - Logistic regression model building
   - Feature selection via Recursive Feature Elimination (RFE)
   - Model training and cross-validation

### Step 4: Model Evaluation
   - Confusion Matrix analysis
   - Accuracy, Precision, Recall, F1-Score
   - ROC-AUC curve
   - Classification report

### Step 5: Feature Elimination & Optimization
   - Manual feature removal (non-significant variables)
   - Model refinement
   - Final model selection

## Installation & Setup

```bash
# Install required packages
pip install pandas numpy scikit-learn matplotlib seaborn

# Launch Jupyter notebook
jupyter notebook "Logistic Regression - Telecom Churn Case Study.ipynb"
```

## Usage

Execute notebook sections in order:
1. Load and explore data
2. Clean and prepare data
3. Build initial logistic regression model
4. Apply RFE for feature selection
5. Analyze confusion matrix and metrics
6. Eliminate non-significant features
7. Generate final predictions

## Data Files

- `churn_data.csv` - Main customer churn dataset
- `customer_data.csv` - Customer demographic information
- `internet_data.csv` - Internet service usage data
- `churn_prob.csv` - Predicted churn probabilities
- `Telecom Churn Data Dictionary.csv` - Data dictionary

## Model Performance

**Final Model Metrics**:
- Accuracy: [Value]%
- Precision: [Value]%
- Recall: [Value]%
- F1-Score: [Value]
- AUC-ROC: [Value]

## Key Insights

- **Top Churn Factors**: [List key variables driving churn]
- **Customer Segments**: [High-risk customer profiles]
- **Retention Recommendations**: [Actionable insights for reducing churn]

## Deliverables

- Predictive model for churn identification
- Feature importance ranking
- Customer churn probability scores
- Business recommendations for retention

## Technologies

- Python 3.x
- Scikit-learn (Logistic Regression, RFE)
- Pandas (Data manipulation)
- Matplotlib/Seaborn (Visualization)
- Jupyter Notebook

## License

[License Information]

## Author

Abhilasha Garg

## References

[Any relevant research papers or methodologies]
