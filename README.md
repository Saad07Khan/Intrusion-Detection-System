Cyber Attack Detection on CIC-IDS2017 Dataset
This project compares the performance of CNN, LSTM, and Hybrid CNN-LSTM models for network intrusion detection using the CIC-IDS2017 dataset.

Features
Data Preparation: Cleans, balances, and preprocesses the dataset.
Dimensionality Reduction: Uses an autoencoder for feature extraction.
Modeling: Implements CNN, LSTM, and Hybrid CNN-LSTM architectures.
Evaluation: Compares models using Accuracy, ROC AUC, and PR AUC metrics.
Usage
Download the dataset using KaggleHub.
Run the notebook step-by-step in Jupyter or Google Colab.
Review model comparison results and visualizations.
Requirements
Python 3.x
pandas, numpy, seaborn, matplotlib
scikit-learn, imbalanced-learn
tensorflow, keras
kagglehub, optuna
Results
LSTM achieves the best performance.
CNN is a strong alternative with faster training.
Hybrid CNN-LSTM does not outperform standalone models.
See ids.ipynb for full code and analysis.
