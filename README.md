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

To use this project, follow these steps:

- Setup: Ensure you have the necessary dependencies installed as described in the Setup section in the Notebook.
- Data: Place the asv_interpretability_dataset.csv file in the /content/ directory or update the data loading code to point to your data location.
- Run the Notebook: Execute the code cells in the notebook sequentially. The notebook is designed to perform the data preprocessing, model training, evaluation, and interpretation steps.
- Analyse Results: Review the generated plots and the summary table to understand the model performance and feature importance. The output files (PDFs and CSVs) will be saved in the specified directories.
- Adapt the Code: Modify the code as needed for your specific dataset or research questions.
