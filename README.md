#  Customer Churn Prediction with AutoML

##  Overview

This project builds a customer churn prediction system using machine
learning and AutoML (PyCaret). It demonstrates a full pipeline from data
preprocessing to model evaluation.

------------------------------------------------------------------------

##  Problem Statement

Customer churn prediction helps businesses: - Reduce revenue loss -
Identify at-risk customers - Improve retention strategies

------------------------------------------------------------------------

##  Dataset

-   Customer demographics
-   Service usage
-   Contract details
-   Payment information

Target: Churn (0 = No, 1 = Yes)

------------------------------------------------------------------------

##  Workflow

1.  Data Cleaning
2.  Feature Engineering
3.  Encoding (CatBoostEncoder)
4.  Handling imbalance (SMOTE)
5.  Model selection (PyCaret)
6.  Model tuning
7.  Evaluation

------------------------------------------------------------------------

##  Best Model

Extra Trees Classifier\
F1 Score: \~0.87

------------------------------------------------------------------------

##  Evaluation

-   Confusion Matrix
-   ROC Curve
-   Learning Curve

------------------------------------------------------------------------

##  Trade-offs

-   AutoML: speed vs control
-   SMOTE: recall vs noise
-   Extra Trees: performance vs interpretability

------------------------------------------------------------------------

##  Tech Stack

-   Python
-   Pandas
-   PyCaret
-   Scikit-learn
-   Imbalanced-learn

------------------------------------------------------------------------

##  How to Run

pip install pandas scikit-learn pycaret imbalanced-learn
category_encoders\
Open notebook: 1.Customer_Churn_Prediction_with_AutoML.ipynb

------------------------------------------------------------------------

##  Key Insight

Churn prediction is not just modeling --- it is a business decision
problem.

------------------------------------------------------------------------

##  Future Work

-   Deploy API
-   Add SHAP explainability
-   Build dashboard

------------------------------------------------------------------------

