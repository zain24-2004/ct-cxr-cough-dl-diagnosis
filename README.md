# ct-cxr-cough-dl-diagnosis
Deep learning–based multimodal system for respiratory disease detection using CT scans, chest X-rays (CXR), and cough sound analysis.
# Multimodal Respiratory Disease Diagnosis Using Deep Learning

This project presents a **multimodal deep learning system** for detecting respiratory diseases by combining **CT scans**, **Chest X-rays (CXR)**, and **cough sound signals**. The system leverages computer vision and audio deep learning techniques to improve diagnostic accuracy.

---

## 📌 Project Overview

Respiratory diseases such as pneumonia, COVID-19, tuberculosis, and chronic lung conditions require accurate and early diagnosis. Traditional diagnosis relies on isolated modalities. This project integrates **medical imaging** and **audio signals** into a unified AI system to provide more robust predictions.

The project explores **CNN-based image models**, **audio feature extraction**, and **multimodal fusion strategies**.

---

##  Objectives

- Detect respiratory diseases using CT and CXR images
- Classify cough sounds using deep learning
- Fuse multiple modalities for improved diagnosis
- Compare unimodal vs multimodal performance
- Build a scalable AI-based diagnostic framework

---

##  Modalities Used

###  CT Scans
- Lung CT slices
- CNN-based classification

### Chest X-rays (CXR)
- Frontal chest X-ray images
- Transfer learning (ResNet, DenseNet, EfficientNet)

###  Cough Sounds
- Audio recordings (.wav)
- Feature extraction:
  - MFCC
  - Spectrograms
- CNN / LSTM-based audio classifiers

---

##  Datasets

- CT Scan Dataset (public medical datasets)
- Chest X-ray Dataset (e.g., NIH / COVIDx)
- Cough Sound Dataset (e.g., Coswara)

> All datasets are publicly available and used for research purposes only.

---

##  Models & Architectures

- CNNs (ResNet, EfficientNet)
- Audio CNN (Spectrogram-based)
- LSTM (for temporal cough patterns)
- Multimodal Fusion Network:
  - Feature-level fusion
  - Decision-level fusion

---

##  Methodology

1. Data Collection & Cleaning
2. Image Preprocessing & Augmentation
3. Audio Signal Processing
4. Feature Extraction
5. Model Training (Single Modality)
6. Multimodal Feature Fusion
7. Evaluation & Comparison

---

##  Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

##  Tools & Technologies

- Python
- PyTorch / TensorFlow
- OpenCV
- Librosa (Audio Processing)
- NumPy, Pandas
- Matplotlib, Seaborn
- Jupyter Notebook

---

##  Project Structure
multimodal-respiratory-diagnosis/
│
├── data/
│ ├── ct/
│ ├── cxr/
│ └── cough_audio/
│
├── models/
│ ├── ct_model.py
│ ├── cxr_model.py
│ ├── audio_model.py
│ └── fusion_model.py
in one note book 

