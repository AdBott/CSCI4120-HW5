# CSCI4120-HW5

members:
adam bott - botta19@students.ecu.edu,
jared rogers - rogersjar21@students.ecu.edu

quick start:
run ipynb file in jupyter note book with the following requirements

requirements:
Python,
Numpy,
Scikit-Learn,
Scipy,
Pandas

hyperparameters:
n_estimators: Number of trees in the forest, Values tried: [100, 150],
max_depth: Maximum depth of the tree, Values tried: [None, 30],
min_samples_split: Minimum number of samples required to split an internal node, Value used: 2,
criterion: The function to measure the quality of a split, Value used: gini

average accuracy: 0.9613 = 96.13%

accuracy per feature: 0.9613/18(number of features) = 0.053 = 05.3%
