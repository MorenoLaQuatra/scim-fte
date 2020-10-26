# Understanding the value of full-text article exploration in citation analysis

This repository contains the binary classification output of different machine learning models for the task of scientific citation classification.

We propose a classification approach to automatically predicting whether the article full-text contains a relevant amount of similar content beyond abstract and title. The proposed approach could support researchers in understanding the added value of full-text article exploration, compared to a quick glance of the very preliminary sections of the paper. 

# Repository documentation

| Shortname | Classifier             |
|-----------|------------------------|
| AB        | AdaBoost               |
| DT        | Decision Tree          |
| GB        | Gradient Boosting      |
| GNB       | Gaussian Naive Bayes   |
| MLP       | Multi-Layer Perceptron |
| RF        | Random Forest          |

Each classifier is associated to 3 corresponding files:
- `Shortname_train.csv` contains the samples used to train the classification system.
- `Shortname_test.csv` contains the ground truth values for testing samples.
- `Shortname_predicted.csv` contains the predicted output for the classification system.

# Paper citation 

Cagliero, L., La Quatra, M. & Baralis, E. *Understanding the value of full-text article exploration in citation analysis*, **currently under review**

