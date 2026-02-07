PROJECT: Gradient Boosting Machine from Scratch

OBJECTIVE
To implement Gradient Boosting for regression using NumPy and understand the optimization of Mean Squared Error via negative gradients.

ALGORITHMS IMPLEMENTED
1. Decision Tree Regressor
2. Gradient Boosting Regressor
3. Residual learning using negative gradient of MSE

WORKFLOW
Step 1: Generate nonlinear synthetic dataset
Step 2: Initialize model with mean target value
Step 3: Compute residuals
Step 4: Train decision tree on residuals
Step 5: Update predictions
Step 6: Repeat for N estimators
Step 7: Compare with sklearn implementation

EVALUATION METRICS
- Mean Squared Error
- Training time
- Hyperparameter sensitivity

STOPPING CRITERIA IN TREE
- Maximum depth
- Minimum samples split
- Pure node detection

FILES
decision_tree.py → base learner  
gbm.py → boosting algorithm  
dataset.py → synthetic dataset  
main.py → execution file  
report.txt → mathematical derivation & analysis  

