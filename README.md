# Interpreting Complex Models in Healthcare

A machine-learning interpretability case study using breast-cancer diagnostic data and a gradient-boosting classifier.

## Objective
Demonstrate how predictive performance and model interpretation can be examined together rather than treating a classifier as a black box.

## Workflow
The notebook loads a 569-row diagnostic dataset, identifies the diagnosis target, maps malignant/benign labels to a binary target, prepares numeric features, trains a `HistGradientBoostingClassifier`, and uses scikit-learn interpretation tools such as permutation importance and partial dependence.

## Primary artifact
- `Interpreting Complex Models in Healthcare.ipynb`

## Tools
Python · pandas · NumPy · scikit-learn · Matplotlib · Gradient Boosting · Permutation Importance · Partial Dependence

## Reproducibility limitation
The notebook expects `/content/data.csv`, but the dataset is not committed to this repository. The current code is therefore best treated as a documented experiment rather than a one-command reproducible project.

## Responsible interpretation
This is an educational machine-learning exercise, not a clinical diagnostic system. Model outputs should not be represented as medical advice or validated clinical performance.

## Next improvements
Document the dataset source and license, add dependency management, remove ID-like fields from predictors where appropriate, add cross-validation and calibration analysis, save interpretation figures, and package the workflow into reusable modules.

## Author
Martin Ngare
