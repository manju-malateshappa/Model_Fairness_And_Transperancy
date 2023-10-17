# Model Fairness And Transperancy: What-If Tool and SHAP on COMPAS Keras Model

## Table of Contents

1. [Introduction](#introduction)
2. [Background](#background)
3. [Model Training](#model-training)
4. [Explanation with SHAP](#explanation-with-shap)
5. [ML Fairness](#ml-fairness)
6. [Copyright](#copyright)

## Introduction

This notebook demonstrates the use of the What-If Tool and SHAP library with a Keras model trained on the COMPAS dataset. The notebook covers the following key aspects:

- Training a Keras model on the COMPAS dataset.
- Providing explanations for inference results using SHAP.
- Utilizing the What-If Tool to analyze the trained model, including the use of SHAP values.

## Background

For background on machine learning fairness with COMPAS, you can refer to the following resources:

- [Machine Bias: Risk Assessments in Criminal Sentencing](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)
- [How We Analyzed the COMPAS Recidivism Algorithm](https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm)
- [Machine Bias: There’s Software Used Across the Country to Predict Future Criminals. And it’s Biased Against Blacks.](http://www.crj.org/assets/2017/07/9_Machine_bias_rejoinder.pdf)

This notebook builds a model that emulates the behavior of the COMPAS recidivism classifier and utilizes the SHAP library to provide feature importance for each prediction made by the model. The model's performance and fairness are then analyzed using the What-If Tool, and the importance of each feature for each prediction is explored through SHAP values.

The specific binary classification task for this model is to determine if a person belongs to the "Low" risk class according to COMPAS (negative class) or the "Medium" or "High" risk class (positive class). The analysis is conducted using the What-If Tool to assess the model's ability to predict recidivism within two years of arrest.

For a simpler version of this notebook that doesn't make use of the SHAP explainer, you can find it [here](#link-to-simpler-version).

## Model Training

Information about training the Keras model on the COMPAS dataset.

## Explanation with SHAP

Details on how SHAP (SHapley Additive exPlanations) is used to provide feature explanations for the model's predictions.

## ML Fairness

An overview of the analysis of model fairness and its implications.

## Copyright

Copyright 2019 Google LLC. SPDX-License-Identifier: Apache-2.0
