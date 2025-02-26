# Toyformers

This repository contains a bunch of "toy" set modelling tasks with synthetic data.
We train transformers on this data and see how well they do.

In general, these tasks involve training sequences of uniform random length up to 100, and then evaluating on sequences up to length 200.

## Getting Started

```sh
# create and activate whatever environment you want
pip install -r requirements.txt
```

Each experiment exists entirely inside a self-contained notebook, with outputs already saved.
To reproduce the experiments, you can re-run the notebook.

## Tasks

### Classification

These experiments use a sequence of labelled classification data.

- [(easy) predicting the feature vector of linearly-separable binary classification](./classification/binary_classification_easy.ipynb)

### Regression

These experiments use a sequence of labelled regression data.

- [(easy) predicting the feature vector of linear regression](./regression/linear_regression_easy.ipynb)
- [(easy) directly predicting the response for unseen data, in linear regression](./regression/direct_linear_regression_easy.ipynb)
- [(medium) directly predicting the response for unseen data](./regression/direct_regression_medium.ipynb)

### Selection

These experiments focus on finding an element in the sequence based on some criteria.

- [(easy) selecting the maximum Euclidean distance from mean](./selection/outlier_detection_easy.ipynb)
- [(medium) selecting the most isolated point](./selection/outlier_detection_medium.ipynb)
