# ewas
EWAS aim at looking for associations between x variable and metilation levels in a bunch of CpGs.
How to conduct epigenome wide association studies.

OPTION A
1. Multiple canonical correlation analysis. Contrast 3 sets of variables: independent, CpGs and covariates.

OPTION B
1. PCA to find components of x variable. Determine que components (as weighted mean) that explai anmportant % of the variability.
2. MLR (multiple linear regression or robust multiple linear regression). Conduct a regressión between each principal component and the whole set of CpGs.
