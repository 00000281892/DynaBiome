# DynaBiome
Research Project: Anomaly Detection in Longitudinal Microbiome Data using LSTM Autoencoders and Ensemble Learning.
This research project implements an anomaly detection framework using LSTM Autoencoders to identify anomalous patterns in longitudinal microbiome data. The reconstruction error from the autoencoder is then used as a feature for various downstream classification models (Logistic Regression, MLP, One-Class SVM, K-Nearest Neighbors, XGBoost, Random Forest) and ensemble learning techniques (Averaged Probabilities, Weighted Averaging, Stacking) to improve anomaly detection performance.

The project includes:
- Data loading and preprocessing for time-series analysis.
- Training of an LSTM Autoencoder on normal data sequences.
- Evaluation of the autoencoder using reconstruction error analysis and optimal thresholding.
- Training and evaluation of individual classifiers on reconstruction errors.
- Implementation and evaluation of ensemble learning methods.
- Statistical testing and bootstrap analysis to compare model performances.
- Visualisation of results including reconstruction error distribution, ROC and PR curves, confusion matrices, and SHAP explanations.

## Table of Contents

1. [Setup](#setup)
2. [Data](#data)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Interpretation](#interpretation)
6. [Ensemble Learning](#ensemble-learning)
7. [Statistical Analysis](#statistical-analysis)
8. [Usage](#usage)
9. [License](#license)
10. [Contact](#contact)
