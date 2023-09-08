# XGBoost_Tuning_with_HyperOpt_and_MLflow_Tracking

## Intro:

This project aims to develop a binary classification model using XGBoost, a powerful gradient boosting algorithm, to predict a target variable with two distinct classes. The model will be tuned using Hyperopt to find the best combination of hyperparameters that maximizes the model's performance. HyperOpt is a Python library for hyperparameter optimization that can balance model performance and computational resource limitations by searching for optimal parameters in a non-exhaustive way. MLflow will be utilized to track the experimentation process and manage the model's lifecycle.

Databricks is a unified, open analytics platform for building, deploying, sharing, and maintaining enterprise-grade data, analytics, and AI solutions at scale.

The optimization method used is the Tree-structured Parzen Estimator (TPE) which is widely used in recent parameter tuning frameworks. TPE is a sequential model-based optimization (SMBO) approach that sequentially constructs models to approximate the performance of hyperparameters based on historical measurements and then subsequently chooses new hyperparameters to test based on this model.

## Data: 

The original dataset can be found here:

https://archive.ics.uci.edu/ml/datasets/credit+approval

## Requirements:


```XGBoost:``` XGBoost is a popular machine learning library that provides scalable and efficient implementations of gradient boosting algorithms. It is designed to be highly customizable and provides a number of hyperparameters that can be tuned to improve performance.

```MLflow:``` MLflow is an open-source platform for the complete machine learning lifecycle, which includes tracking experiments, packaging code into reproducible runs, and sharing and deploying models. It provides a simple interface for logging and tracking machine learning experiments and is designed to work with any machine learning library.

```Hyperopt:``` Hyperopt is a popular open-source hyperparameter tuning library. It provides a range of algorithms for searching over a hyperparameter space, including random search, Bayesian optimization and tree-structured Parzen estimators.

```pandas:``` Data analysis and manipulation tool.
