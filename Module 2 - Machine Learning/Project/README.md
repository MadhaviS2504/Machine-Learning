# Final Project — Personal Loan Campaign (Capstone — Module 2)

## Overview

This capstone applies an end-to-end machine learning workflow to a retail banking marketing problem: predict which deposit customers are most likely to accept a personal loan offer. The project uses the `Loan_Modelling (1).csv` dataset and demonstrates the full modelling lifecycle — from data exploration and feature work through model building, hyperparameter tuning, evaluation, and business recommendations.

## Business context

AllLife Bank ran a previous campaign with a positive conversion rate and wants to scale future campaigns more efficiently by targeting customers with the highest propensity to accept a loan. The model built in this project helps the marketing team prioritize customers and improve campaign ROI.

## Objectives

- Build a predictive model to identify customers likely to accept a personal loan.
- Understand which customer attributes drive conversions.
- Provide actionable recommendations for a targeted marketing campaign.

## Dataset

- File: `Loan_Modelling (1).csv` (used in the notebook)
- Shape: 5000 rows × 14 columns
- Key columns: Age, Experience, Income, ZIPCode, Family, CCAvg (credit card avg spend), Education, Mortgage, Personal_Loan (target), Securities_Account, CD_Account, Online, CreditCard

## What I did (step-by-step)

1. Project setup
   - Installed and imported industry-standard Python libraries (pandas, numpy, matplotlib, seaborn, scikit-learn, plotly).
2. Data loading & quick sanity checks
   - Loaded the CSV into a pandas DataFrame, inspected shape, sample rows and summary statistics to confirm data integrity.
3. Exploratory data analysis (EDA)
   - Visualized distributions and relationships (univariate and bivariate plots).
   - Examined the target distribution and key predictors to understand how features relate to Personal_Loan acceptance.
   - Looked for outliers, odd values and data quality issues (e.g., negative or inconsistent Experience values).
4. Data cleaning & preprocessing
   - Addressed obvious data issues discovered during EDA (missing values, inconsistent entries).
   - Converted or encoded categorical variables (Education, accounts flags) as required by models.
   - Considered dropping or transforming features not useful for modeling (e.g., raw ZIPCode) and scaling numeric features where helpful.
5. Feature engineering and selection
   - Created/selected predictive features based on domain intuition and EDA (Income, CCAvg, Education, Mortgage, Family, Age, account flags).
   - Explored correlations and feature importance to prioritize variables.
6. Train / test split
   - Split the data into training and test sets to measure generalization.
7. Model building
   - Implemented baseline classifiers and focused on a Decision Tree classifier.
   - Used GridSearchCV for hyperparameter tuning to find better model settings (max_depth, min_samples_split, etc.).
8. Model evaluation
   - Evaluated models using classification metrics: confusion matrix, accuracy, precision, recall, F1-score (and ROC/AUC when appropriate).
   - Interpreted model results in a business context — balancing precision vs recall depending on campaign goals (reduce wasted outreach vs miss potential customers).
9. Interpretation & business recommendations
   - Analyzed the most important features and derived customer profiles with high propensity to accept the loan.
   - Recommended targeted outreach strategies and monitoring steps for production use.
10. Reporting
    - Exported the analysis to an HTML report for sharing and interviewer review.

## Key findings & business insights (summary)

- Customers with higher Income and higher CCAvg tend to have greater propensity to accept the loan — these are strong predictors.
- Ownership of other bank products (Securities account, CD account) and active online banking were correlated with acceptance in exploratory analysis.
- Education level, mortgage presence and family size also influence propensity — these features help segment customers for targeted offers.
- By prioritizing a scored shortlist of high-propensity customers, the bank can increase campaign efficiency and ROI while reducing cost-per-acquisition.

## What I learned

- How to run an end-to-end ML workflow: data ingestion → EDA → preprocessing → modeling → tuning → evaluation → business interpretation.
- Practical EDA techniques to uncover data quality issues and meaningful feature relationships.
- How to prepare real-world tabular data for machine learning (encoding, handling outliers, feature selection).
- Model selection and hyperparameter tuning with scikit-learn (GridSearchCV) and how tuning affects overfitting/generalization.
- Interpreting classifier metrics (precision/recall/F1) from a business perspective to choose trade-offs for campaigns.
- How to communicate technical results to non-technical stakeholders via visualizations and a reproducible notebook / HTML report.

## Tools & skills demonstrated

- Python: pandas, numpy
- Visualization: seaborn, matplotlib, plotly
- Machine learning: scikit-learn (DecisionTreeClassifier, GridSearchCV, metrics)
- Notebook-based reproducible analysis: Jupyter / Colab
- Model evaluation and interpretation for business use
- Report export (HTML) for sharing results with stakeholders

## How to run

1. Clone the repo and open the notebook:
   - Notebook: `Module 2 - Machine Learning/Project/Machine_Learning_Project_Personal_Loan_Campaign (1).ipynb`
   - Dataset: `Module 2 - Machine Learning/Project/Loan_Modelling (1).csv`
2. Install dependencies (example):
   - pip install numpy pandas matplotlib seaborn scikit-learn plotly
3. Open and run the notebook cells in order. The HTML file `Machine_Learning_Project_Personal_Loan_Campaign (2).html` is an exported, static version suitable for quick review.

## Highlights to mention to recruiters

- End-to-end project experience on a real-world banking dataset.
- Strong emphasis on exploratory analysis, feature engineering and model validation.
- Practical use of hyperparameter tuning and model evaluation metrics tailored to business goals.
- Clear communication: generated a shareable HTML report and actionable recommendations for campaign targeting.

## Next steps (optional improvements)

- Try more models (Random Forest, XGBoost, Logistic Regression) and compare using cross-validated ROC/AUC.
- Use stratified sampling or resampling techniques if the target is imbalanced.
- Deploy model scoring as a lightweight API or batch scoring job and measure campaign lift in production.
- Implement SHAP or other explainability tools for deeper feature-level explanations.

## Contact

If you'd like this README adjusted further (shorter resume-friendly version, or a one-page project summary for LinkedIn), I can update it for you.
