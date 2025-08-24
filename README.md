Cyber Attack Detection on CIC-IDS2017 Dataset

Deep-learning comparison of CNN, LSTM, and Hybrid CNN-LSTM for network intrusion detection using the CIC-IDS2017 dataset.

Table of Contents

Project Overview

Features

Results (summary)

Requirements

Installation

Dataset

Usage

Repository structure

How to reproduce experiments

Notes & tips

License & Contact

Project Overview

This repository implements data preparation, dimensionality reduction, modeling, and evaluation pipelines to compare CNN, LSTM, and Hybrid CNN-LSTM architectures on the CIC-IDS2017 intrusion detection dataset. The goal is to benchmark model performance using classification metrics and precision/recall-oriented metrics.

Features

Data preparation — cleaning, balancing, and preprocessing of CIC-IDS2017.

Dimensionality reduction — autoencoder-based feature extraction.

Modeling — implementations of CNN, LSTM, and Hybrid CNN-LSTM models (TensorFlow / Keras).

Evaluation & visualization — Accuracy, ROC AUC, PR AUC, confusion matrices and comparative plots.

Notebook-based — step-by-step ids.ipynb for reproducibility.

Results (summary)

Best performer: LSTM achieved the best overall performance in our experiments.

Runner-up: CNN delivered strong performance with faster training times.

Hybrid: The CNN-LSTM hybrid did not outperform the standalone models in our runs.
(See ids.ipynb for detailed tables and plots.)
