# Week 2 — Decision Trees & Classification

## Overview

This week focuses on decision tree algorithms and classification techniques. You'll learn how to build and optimize decision tree models, understand tree-based feature importance, and explore classification metrics specific to binary and multi-class problems.

## Topics Covered

- **Decision Tree Fundamentals**
  - Understanding tree structure: nodes, splits, and leaves
  - Information gain and impurity measures (Gini, Entropy)
  - Decision boundaries and tree depth

- **Building Decision Trees**
  - Recursive binary splitting algorithm
  - Handling both classification and regression tasks with trees
  - Feature importance ranking from trees

- **Hyperparameter Tuning & Optimization**
  - Tree depth (`max_depth`) and leaf size (`min_samples_leaf`) tuning
  - Cost complexity pruning to prevent overfitting
  - Grid search and parameter optimization strategies

- **Model Validation & Evaluation**
  - Cross-validation techniques for robust performance estimation
  - Classification metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
  - Confusion matrix interpretation and threshold analysis
  - Overfitting detection and mitigation strategies

- **Business Applications**
  - Feature importance interpretation for decision-making
  - Model transparency and explainability in trees
  - Real-world case studies: Machine failure prediction, Loan delinquency

- **Logistic Regression** (Additional Material)
  - Introduction to probabilistic classification
  - Sigmoid function and decision boundaries
  - Binary classification with logistic regression

## Key Projects & Datasets

- **Hands_on_Decision_Tree_Notebook.ipynb** — Step-by-step decision tree examples and evaluation
- **credit_card_approval.csv** — Credit approval prediction dataset for classification
- **MLS (Multiple Learning Scenarios)** — `MLS2_Decision_Tree_Machine_Failure_Prediction_Notebook.ipynb` (predicting machine failures using sensor data)
- **Decision Tree - Additional Case Study** — `W2_Additional_CaseStudy_Loan_Delinquent_Notebook.ipynb` (business-context problem on loan delinquency prediction)
- **W2 - Additional Material - Logistic Regression** — Supplementary content on logistic regression and probability-based classification
- **Decision Trees.pdf** — Theoretical reference material

## Skills & Tools

- **Languages & Libraries**: Python, pandas, NumPy, scikit-learn
- **Algorithms**: Decision Trees, Logistic Regression
- **Validation**: Cross-validation, hyperparameter tuning (GridSearchCV, RandomizedSearchCV)
- **Visualization**: matplotlib, seaborn, tree visualization tools
- **Environment**: Jupyter Notebooks

## How to Run

1. Create a virtual environment and install required packages (same as Week 1):

```bash
python -m venv venv
venv\Scripts\activate  # On macOS/Linux: source venv/bin/activate
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
```

2. Launch Jupyter and explore the notebooks:

```bash
jupyter notebook
```

3. Follow the learning sequence:
   - Start with `Hands_on_Decision_Tree_Notebook.ipynb` for fundamentals
   - Review the machine failure case study in `MLS/`
   - Apply concepts to the loan delinquency problem in `Decision Tree - Additional Case Study/`
   - Explore logistic regression in `W2 - Additional Material - Logistic Regression/`

## Key Learnings & Takeaways

- ✅ Built and tuned decision tree models with optimal hyperparameters
- ✅ Demonstrated cross-validation and pruning techniques to prevent overfitting
- ✅ Interpreted feature importance and translated results into business recommendations
- ✅ Applied classification metrics to evaluate model performance comprehensively
- ✅ Solved real-world problems: Machine failure prediction, Loan delinquency assessment
- ✅ Understood the trade-offs between model complexity and interpretability

## Highlights to Mention to Recruiters

- Developed end-to-end classification pipelines using decision trees
- Applied advanced techniques: hyperparameter tuning, cross-validation, and pruning
- Interpreted feature importance for business decision-making
- Worked with imbalanced datasets and class-specific metrics
- Built transparent, explainable models for critical business domains (finance, manufacturing)
- Demonstrated understanding of both tree-based and probabilistic classification methods

## Next Steps

After mastering decision trees and classification, you'll explore **Week 3 - Clustering**, which introduces unsupervised learning and customer segmentation techniques.
