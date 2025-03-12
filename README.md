# MNIST-Classification
MNIST Classification using MLE, PCA, FDA,  and Discriminant Analysis.
Handwritten Digit Classification (0, 1, 2)

Overview

This project explores classification techniques on a subset of the MNIST dataset. The objective is to classify digits 0, 1, and 2 using statistical and dimensionality reduction methods.

Dataset

Subset of MNIST containing only digits 0, 1, and 2.

Training set: 100 randomly selected samples per class (Total: 300 samples).

Test set: 100 randomly selected samples per class (Total: 300 samples).

Approach

1. Data Preprocessing

Filter out digits 0, 1, and 2.

Normalize image pixel values to [0,1].

Convert images into feature vectors.

2. MLE Estimation

Estimate class-wise mean and covariance assuming a Gaussian distribution.

Compute likelihood using:



3. Dimensionality Reduction

PCA: Reduce features while preserving 95% variance.

FDA: Optimize class separability by computing between-class and within-class scatter matrices.

4. Classification

Implement Linear Discriminant Analysis (LDA) and Quadratic Discriminant Analysis (QDA).

Evaluate classification accuracy on test data.

Experiments

Compare LDA and QDA performance.

Analyze PCA’s effect on classification.

Experiment with different PCA variance thresholds (e.g., 90%).

Visualize PCA and FDA transformed feature spaces.

