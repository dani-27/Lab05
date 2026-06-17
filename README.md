# Lab 5: Feature Analysis

This lab introduces feature transformations and dimensionality reduction using two synthetic biomedical datasets. Students will practise changing numeric scales, discretizing continuous variables, encoding categorical variables, and using Principal Component Analysis (PCA) to represent a high-dimensional dataset with two principal components.

## Learning objectives

By the end of the lab, students should be able to:

- apply min-max scaling and z-score standardization
- compare equal-width and equal-frequency discretization
- apply a logarithmic transformation to a skewed feature
- distinguish ordinal encoding from one-hot encoding
- standardize data before PCA
- reduce a high-dimensional dataset to two principal components and visualize the result
- optionally generate and select useful features

## Packages used

- pandas
- numpy
- matplotlib
- scikit-learn

## Lab checklist

- [ ] Load and inspect the patient dataset.
- [ ] Round a numeric feature and discuss what information is lost.
- [ ] Apply min-max scaling.
- [ ] Apply z-score standardization.
- [ ] Compare equal-width and equal-frequency discretization.
- [ ] Apply a log transformation to a skewed feature.
- [ ] Encode an ordinal categorical feature.
- [ ] One-hot encode nominal categorical features.
- [ ] Standardize the gene-expression features.
- [ ] Use PCA to reduce the gene-expression dataset to two components.
- [ ] Plot the PCA result and describe the separation between groups.
- [ ] Try the optional feature generation and feature selection tasks.
