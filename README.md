# Leveraging full-text article exploration for citation analysis

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

La Quatra, M., Cagliero, L. & Baralis, E. Leveraging full-text article exploration for citation analysis. Scientometrics 126, 8275–8293 (2021). https://doi.org/10.1007/s11192-021-04117-4

```
@article{laquatra2021leveraging,
  title={Leveraging full-text article exploration for citation analysis},
  author={La Quatra, Moreno and Cagliero, Luca and Baralis, Elena},
  journal={Scientometrics},
  volume={126},
  number={10},
  pages={8275--8293},
  year={2021},
  publisher={Springer}
}
```
