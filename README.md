# Interpretable Credit Risk Modeling

##  Project Overview

This project develops an interpretable and cost-sensitive credit risk model using statistical inference and machine learning techniques.  
The objective is to simulate a real-world banking credit approval system that balances predictive performance, financial risk, and model explainability.

The modeling pipeline integrates:
- Statistical hypothesis testing
- Logistic regression with inference
- Cost-sensitive learning
- Threshold optimization
- Random Forest (non-linear benchmark)
- SHAP explainability
- Cross-validation and hyperparameter tuning

---

##  Business Objective

In credit risk modeling, false negatives (approving a risky applicant) are significantly more costly than false positives (rejecting a safe applicant).

This project focuses on:

- Minimizing financial loss using cost-sensitive evaluation
- Improving recall for high-risk applicants
- Maintaining model interpretability for regulatory compliance
- Ensuring robustness through cross-validation

---

##  Methodology

###  Statistical Analysis
- Independent t-tests for group differences
- Correlation matrix analysis
- Variance Inflation Factor (VIF)
- Logistic regression with p-values (statsmodels)

###  Machine Learning Baseline
- Logistic Regression (scikit-learn)
- Standard scaling
- Performance evaluation (Accuracy, Precision, Recall, ROC-AUC)

###  Handling Class Imbalance
- Class-weighted logistic regression
- Performance trade-off analysis

###  Decision Threshold Optimization
- Cost-sensitive confusion matrix
- Financial loss estimation
- Systematic threshold search

###  Non-Linear Model
- Random Forest classifier
- Comparative performance analysis

###  Full Feature Model
- One-hot encoding for categorical variables
- Regularized logistic regression

###  Model Interpretability
- SHAP summary plots
- Feature importance analysis

###  Model Robustness
- 5-fold Cross-Validation
- GridSearch hyperparameter tuning

---

##  Key Results

- Cross-validated ROC-AUC ≈ **0.79**
- Significant improvement in high-risk recall
- Cost-sensitive threshold reduced expected financial loss by nearly **50%**
- SHAP analysis confirms economic interpretability of key features

---

##  Dataset

German Credit Dataset  
UCI Machine Learning Repository  

https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)

---

##  Technologies Used

- Python
- scikit-learn
- statsmodels
- SHAP
- pandas
- numpy
- matplotlib
- seaborn
- scipy

