# automl-helpers

## Introduction
automl-helpers is a Python module designed to streamline the process of training and evaluating machine learning models that use multiple data types requiring pre-processing (text, categorical, etc.). Built on top of scikit-learn, numpy, pandas, and tf/keras, it offers a simple process to quickly experiment with different modeling pipelines to identify effective algorithms and pre-processing techniques for specific datasets. For more information and to download the latest version, visit the [automl-helpers PyPI page](https://pypi.org/project/automl-helpers/).

## Features
- Easy model stacking and selection of upstream model hyperparameters
- Pre-processing and feature selection techniques
- Data aggregation functions
- Easy integration with scikit-learn, numpy, pandas, and tf/keras
- Functionality to save trained models for future prediction

## Requirements
- scikit-learn (version <1.6)
- numpy (version x.x or higher)
- pandas (version x.x or higher)
- Optional: tf/keras (version x.x or higher)
- Optional: xgboost (version x.x or higher)

See requiremets.txt for working venv

## User Installation
```bash
pip install automl-helpers
```