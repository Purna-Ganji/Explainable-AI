# Explainable-AI
Explainable AI (XAI) — LIME &amp; SHAP Experiments  This repository contains Jupyter notebooks demonstrating Explainable AI (XAI) techniques such as LIME and SHAP across different datasets and models. Each notebook includes training, explanation generation, and visualizations for comparison.
Contents
1. lime_classification_diabetes.ipynb

Dataset: Diabetes dataset

Models: Logistic Regression, SVM, MLP

Tasks:

Train three classifiers

Generate LIME local explanations for 5 test samples

Compare influential features with global model behavior

Experiment with kernel width sensitivity

2. shap_classification_breast_cancer.ipynb

Dataset: Breast Cancer dataset (scikit-learn)

Models: Logistic Regression, SVM, MLP

Tasks:

Explain predictions for 5 samples with SHAP

Plot SHAP summary and dependence plots

Analyze feature importance

3. lime_shap_mnist.ipynb

Dataset: MNIST handwritten digits

Model: Custom CNN

Tasks:

Train CNN for digit classification

Generate explanations with LIME and SHAP for 5 test images

Compare similarities and differences between LIME and SHAP explanations

4. lime_shap_pretrained_cifar10.ipynb

Dataset: CIFAR-10

Model: Pretrained ResNet50 (or InceptionV3)

Tasks:

Classify 5 CIFAR-10 images with pretrained ImageNet models

Generate explanations with LIME and SHAP (GradientExplainer)

Critically evaluate which method provides mo
