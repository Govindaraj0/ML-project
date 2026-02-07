Gradient Boosting from Scratch
Overview

This project is a from-scratch implementation of a Gradient Boosting Machine (GBM) for regression tasks using only NumPy. The goal is to understand the fundamentals of GBM without relying on external libraries.

Requirements

Python 3.x

NumPy for numerical computations

Objectives

Implement a Decision Tree Regressor from scratch.

Build a Gradient Boosting Regressor using the custom decision tree.

Generate a synthetic dataset for testing.

Compare the custom GBM’s performance with scikit-learn’s implementation.

Project Structure

Imports: Only NumPy is imported for numerical operations.

Decision Tree Implementation: A simple Decision Tree Regressor was coded from the ground up, focusing on basic splitting criteria and mean squared error (MSE) minimization.

Gradient Boosting Machine: Using the decision tree as a base learner, a GBM regressor was built that iteratively fits to the residuals of the previous model.

Dataset Generation: A synthetic regression dataset was created to test the implementation.

Performance Comparison: The custom GBM was compared with scikit-learn’s GradientBoostingRegressor to evaluate its accuracy and efficiency.

Algorithms Used

Decision Tree Regressor: For the base learner in each boosting iteration.

Gradient Boosting: For iteratively fitting new trees to correct the errors of the previous ensemble.

How to Run

Clone the repository.

Run the main script to see the GBM in action.
