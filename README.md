# EWAS

Epigenome Wide Association Study aiming at looking for associations between a set of variables variable and metilation levels in a set of CpGs. Two methodological approaches are employed:

1. Multiple Canonical Correlation Analysis. Contrasting 3 sets of variables: independent variables (food intake), CpGs and covariates.

2. Perform Principal Component Analysis to find the most important contributors to the food intake variables. Then, perform Robust Multiple Linear Regression between each principal component and the whole set of CpGs.
