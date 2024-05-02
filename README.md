# Anomaly Detection Framework

This project implements an anomaly detection framework using a Transformer-based Autoencoder integrated with a Generative Adversarial Network (GAN) and Contrastive Learning. The framework is designed to detect anomalies in multivariate time series data efficiently.

## Features

- **Transformer-based Autoencoder**: Utilizes a Transformer architecture for effective time-series data encoding and reconstruction.
- **Generative Adversarial Network**: Employs GANs for generating synthetic time-series data, enhancing the robustness of the anomaly detection.
- **Contrastive Learning**: Improves the feature representation by contrasting positive and negative examples.
- **Data Augmentation**: Implements geometric distribution masks to simulate partial data occlusion, enhancing model robustness.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.8 or higher
- PyTorch 1.7 or higher
- Matplotlib (for plotting training losses and metrics)
