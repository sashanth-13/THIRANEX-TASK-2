Project Title: Credit Risk Assessment & Classification Using Decision Trees

Overview
This project builds a predictive pipeline to classify loan applications into risk categories. Utilizing demographic and financial inputs, the model attempts to accurately flag potential defaults before a credit line is extended.

Key Features Implemented:

Synthetic Feature Engineering: Structured standard distributions for numeric risk indicators including debt burden ratios and credit indexing.

Algorithmic Modeling: Deployed a constrained Decision Tree Classifier (DecisionTreeClassifier), limiting structure depth to maintain strong interpretability and generalizability on unseen validation pools.

Strategic Diagnostic Plots:

Created a Confusion Matrix to separate operational errors (False Positives vs. False Negatives).

Generated an ROC Curve mapping sensitivity against specific fallout levels to identify the optimum decision threshold.

Interactive Model Explorer
To help understand how changes to machine learning models alter these exact diagnostic metrics, use the interactive simulator below. You can adjust the decision thresholds and hyperparameter constraints to observe how the True/False matrix and Area Under the Curve adapt dynamically.
