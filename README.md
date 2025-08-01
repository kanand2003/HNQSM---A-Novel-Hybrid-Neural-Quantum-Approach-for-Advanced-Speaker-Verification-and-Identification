# 🔊 HNQSM: Hybrid Neural-Quantum Speaker Model for Speaker Verification & Identification

This repository contains the **Jupyter notebook implementation** of **HNQSM (Hybrid Neural Quantum Speaker Model)**, a novel architecture for **speaker verification and identification** that combines classical deep learning with quantum-inspired computation.

HNQSM integrates:
- 🧠 **CNN** for extracting refined acoustic features
- ⚛️ **QCNN** (Quantum Convolutional Neural Network) for efficient feature transformation
- 🧬 **Siamese Neural Network (SNN)** for speaker verification via pairwise matching

> 📓 The entire workflow — from preprocessing to evaluation — is implemented in the notebook:  
📄 `Speaker_verification+identification.ipynb`

---

## 📌 Highlights

- ✅ Real-world speech datasets: **RAVDESS** and **VoxCeleb1 (subset)**
- ✅ Speaker classification and verification from raw WAV files
- ✅ SHAP-based feature importance to interpret model behavior
- ✅ Ablation study to evaluate contributions of CNN, QCNN, and SNN
- ✅ Runtime and Equal Error Rate (EER) analysis
- ✅ Robust to noisy environments and high speaker variability

---

## 📁 Files

- `Speaker_verification+identification.ipynb`: Main notebook with full pipeline
- `README.md`: Project overview and usage guide

> Additional modules (e.g., preprocessing scripts or audio folders) can be added later to extend functionality.

---

## 🗃️ Datasets

- **RAVDESS**: Emotionally balanced dataset with clean speech
- **VoxCeleb1 (subset)**: Noisy, unconstrained real-world speaker recordings  
Both datasets are publicly available and must be downloaded separately.

---

## 📊 Evaluation Metrics

- Equal Error Rate (EER)  
- Precision, Recall, F1-score  
- ROC Curve, SHAP plots  
- Runtime benchmarks

---

## ⚙️ Setup Instructions

Install the required packages before running the notebook:

```bash
pip install pandas numpy librosa matplotlib scikit-learn tensorflow pennylane shap
