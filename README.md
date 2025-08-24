# Cyber Attack Detection on CIC-IDS2017 Dataset
-This project compares CNN, LSTM, and Hybrid CNN-LSTM models for network intrusion detection using the CIC-IDS2017 dataset. It leverages pandas, numpy, seaborn, matplotlib, scikit-learn, imbalanced-learn, TensorFlow, Keras, and Optuna.

# Features & Techniques
- Data Preparation: Cleaning, outlier handling (IQR), removal of highly correlated features, missing value imputation, label encoding, standardization, and class balancing (RandomUnderSampler).
- Dimensionality Reduction: Autoencoder with L2 regularization for feature extraction.
- Modeling: CNN, LSTM, and Hybrid CNN-LSTM architectures.
- Generalization Techniques: Dropout, L2 regularization, batch normalization, early stopping, and learning rate scheduling.
  
# Evaluation: Accuracy, ROC AUC, PR AUC, confusion matrix, ROC and PR curve visualizations.
# Usage
- Download the dataset using KaggleHub.
- Run ids.ipynb step-by-step in Jupyter or Google Colab.
- Review model comparison results and visualizations.
# Requirements
- Python 3.x
- pandas, numpy, seaborn, matplotlib
- scikit-learn, imbalanced-learn
- tensorflow, keras
- kagglehub, optuna
# Results
- LSTM achieves the best performance.
- CNN is a strong alternative with faster training.
- Hybrid CNN-LSTM does not outperform standalone models.
- See ids.ipynb for full code and analysis.
