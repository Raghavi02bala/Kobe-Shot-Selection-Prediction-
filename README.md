# Kobe-Shot-Selection-Prediction-
This project describes how using One-Hot Encoding reduces the performance of RandomForest Algorithm.
One-Hot encoding causes the RF algorithm to produce a tree that grows in one direction.
We're including sparsity into the dataset which we don't want.
The base algorithm in the RF model splits data based on the purity of data. 
If the tree decides to make a split on one of the dummy variables, the gain in purity per split is very less.
As a result, the tree is very unlikely to select one of the dummy variables closer to the root.

