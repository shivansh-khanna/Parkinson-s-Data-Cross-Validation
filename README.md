# Parkinsons-Data-Cross-Validation
Demonstrate different kinds of cross-validation suitable for different datasets and observe the potential for overfitting with incorrect cross-validation.

Dataset 1: This is a synthetic dataset with random features and class labels.

Dataset 2: This is a similar dataset, but it also includes group ID metadata. In this scenario data comes from 10 different groups (e.g., companies, users, locations), and each group has 10 instances.

Dataset 3: https://archive.ics.uci.edu/ml/datasets/Parkinsons
Note that this dataset has a .data file, which is a CSV, and a .names file which is a description of
the dataset and features in it.

Task 1: Testing on the training set

Task 2: Cross-validating at the group level

Task 3: Custom cross-validation on Parkinson’s data

In this dataset, the goal is to classify whether somebody has Parkinson’s disease or not based on
speech data.
