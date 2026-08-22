# Week 1 — Linear Regression

## Overview

This week covers the fundamentals of linear regression, one of the most essential supervised learning algorithms. You'll learn to build both simple and multiple linear regression models, perform exploratory data analysis, and evaluate model performance using statistical metrics.

## Topics Covered

- **Exploratory Data Analysis (EDA)**
  - Data loading and inspection
  - Summary statistics and data visualization
  - Identifying patterns and relationships

- **Simple Linear Regression (SLR)**
  - Understanding the linear relationship between a single independent and dependent variable
  - Fitting and interpreting regression equations
  - Visualizing fitted lines and residuals

- **Multiple Linear Regression (MLS)**
  - Building models with multiple independent variables
  - Feature selection and handling multicollinearity
  - Interpreting coefficients and their statistical significance

- **Model Evaluation & Validation**
  - Performance metrics: R², RMSE, MAE, MSE
  - Residual analysis and assumption checking
  - Train-test split and cross-validation concepts

- **Model Assumptions**
  - Linearity, independence, homoscedasticity, and normality of residuals
  - Diagnostic plots for validating model assumptions

## Key Projects & Datasets

- **Hands_on_Linear_Regression_Notebook.ipynb** — Main walkthrough with EDA and modeling on example datasets
- **Sales (1).csv** — Sales prediction dataset used for regression modeling
- **Practice Exercise 1** — Guided exercises using `boston.csv` (SLR_W1_PracticeExercise_Question.ipynb and SLR_W1_PracticeExercise_Solution.ipynb)
- **MLS - Linear Regression** — Additional case study: `ML_MLS1_Cars4u_Notebook.ipynb` (predicting car prices with multiple features)
- **Linear Regression_ Practice Quiz** — Practice problems and solutions
- **Additional Case Study** — Real-world application scenarios

## Skills & Tools

- **Languages & Libraries**: Python, pandas, NumPy, scikit-learn
- **Visualization**: matplotlib, seaborn
- **Environment**: Jupyter Notebooks

## How to Run

1. Create a virtual environment and install required packages:

```bash
python -m venv venv
venv\Scripts\activate  # On macOS/Linux: source venv/bin/activate
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
```

2. Launch Jupyter and open the `.ipynb` files:

```bash
jupyter notebook
```

3. Follow the notebooks sequentially:
   - Start with `Hands_on_Linear_Regression_Notebook.ipynb`
   - Practice with exercises in `Practice Exercise 1/`
   - Explore the case study in `MLS - Linear Regression/`

## Key Learnings & Takeaways

- ✅ Performed feature selection and interpretation of regression coefficients
- ✅ Compared model performance using multiple evaluation metrics (R², RMSE, MAE)
- ✅ Validated model assumptions with residual plots and diagnostic visualizations
- ✅ Built real-world case studies demonstrating practical application (car price prediction, sales forecasting)
- ✅ Understood the limitations of linear regression and when it applies best

## Highlights to Mention to Recruiters

- Built and interpreted both simple and multiple linear regression models from scratch
- Demonstrated proficiency in EDA, feature engineering, and model evaluation
- Applied statistical methods to validate model assumptions and interpret results
- Worked with real datasets and translated predictions into actionable insights
- Strong foundation in supervised learning fundamentals

## Next Steps

After completing Week 1, you'll be ready to explore classification algorithms in **Week 2 - Decision Trees**, which extends these concepts to categorical prediction problems.
