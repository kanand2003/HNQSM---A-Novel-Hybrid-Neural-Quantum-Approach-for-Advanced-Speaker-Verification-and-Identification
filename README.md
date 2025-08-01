# HNQSM---A-Novel-Hybrid-Neural-Quantum-Approach-for-Advanced-Speaker-Verification-and-Identification
This repository contains the official implementation of **HNQSM (Hybrid Neural Quantum Speaker Model)** — a novel hybrid deep learning and quantum-inspired architecture for **Speaker Identification (SI)** and **Speaker Verification (SV)**. HNQSM combines the strengths of **Convolutional Neural Networks (CNN)**, **Quantum Convolutional Neural Networks (QCNN)**, and **Siamese Neural Networks (SNN)** to achieve high accuracy and robustness in noisy environments.

## 🚀 Features

- ✅ **Quantum-Enhanced Classification** using QCNN for deeper feature abstraction
- ✅ **Siamese Verification Layer** for robust pairwise speaker comparison
- ✅ **Dimensionality Reduction** to address the curse of dimensionality and improve runtime
- ✅ **Real-World Dataset Support**: Tested on **RAVDESS** and **VoxCeleb1**
- ✅ **Low EER and High Accuracy**, outperforming traditional DL models
- ✅ **SHAP-based Feature Importance** visualization
- ✅ **Ablation Study** included to assess individual module contributions

## 📁 Repository Structure

```bash
├── data/                   # Dataset loaders and preprocessors
├── models/                 # CNN, QCNN, SNN architectures
├── utils/                  # Helper functions and feature extraction
├── notebooks/              # Jupyter notebooks for SHAP and results
├── experiments/            # Training and evaluation scripts
├── results/                # Evaluation metrics, plots, and figures
└── README.md               # This file
