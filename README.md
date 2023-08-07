# anomaly_detection_ECG
Anomaly Detection using LSTM Auto Encoders

# ECG Anomaly Detection using Recurrent Autoencoder

This repository contains an implementation of ECG (Electrocardiogram) anomaly detection using a Recurrent Autoencoder model. The goal is to identify abnormal heartbeats in ECG time series data.

## Overview

This project aims to detect abnormal heartbeats (anomalies) in ECG signals using a Recurrent Autoencoder model. An Autoencoder is an unsupervised machine learning model that learns to encode input data into a compressed representation and then decode it back to the original input. By training an Autoencoder on normal ECG signals, we can use the model to reconstruct new instances and compare the reconstruction error to identify anomalies.

## Key Features

- Data Setup: Preprocess and prepare the ECG dataset for training and testing.
- Model Architecture: Implement an Encoder and Decoder architecture for the Recurrent Autoencoder.
- Training: Train the model on the prepared ECG dataset and monitor training progress.
- Anomaly Detection: Identify abnormal heartbeats in both normal and anomaly datasets.
- Visualization: Visualize original, predicted, and reconstructed time series for abnormal and normal instances.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ecg-anomaly-detection.git

