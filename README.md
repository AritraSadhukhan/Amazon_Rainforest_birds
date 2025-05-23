# 🦜 Illegal Hunting and Poaching Detection Using AI in Amazon Rainforest Birds

This research project leverages **Artificial Intelligence (AI)** and **Machine Learning (ML)** to detect and classify illegal hunting and poaching activities targeting endangered bird species in the **Amazon Rainforest**. The system uses **bioacoustic signals** (bird calls and sounds) and spectrogram-based analysis to build predictive models for identifying threats in real time.

---

## 📌 Problem Statement

Illegal poaching of birds in the Amazon rainforest threatens biodiversity and disrupts ecological balance. Manual surveillance is not scalable. This project explores how **machine learning models can be trained on audio data** to detect unusual bird activity and signs of poaching.

---

## 🎯 Objectives

- ✅ Collect and preprocess bird audio recordings
- ✅ Extract **MFCC** and other spectral features
- ✅ Train supervised ML classifiers to detect anomalies
- ✅ Evaluate model performance and deploy as a detection tool

---

## 🛠️ Tools & Technologies

| Technology         | Purpose                             |
|--------------------|--------------------------------------|
| **Python**         | Programming language                 |
| **Librosa**        | Audio processing and feature extraction |
| **NumPy / Pandas** | Data manipulation                   |
| **Scikit-learn**   | ML modeling (Random Forest, SVM)     |
| **Matplotlib / Seaborn** | Data visualization            |
| **SMOTE**          | Imbalanced data handling             |
| **MFCC**           | Audio feature representation         |

---

## 🔍 Features Extracted

- **MFCC (Mel-Frequency Cepstral Coefficients)**
- **Spectral Centroid**
- **Chroma Frequencies**
- **Zero Crossing Rate**
- **Root Mean Square Energy**

These features help distinguish between normal bird calls and distress or human-triggered activity.

---

## 📊 Model Performance

| Model            | Accuracy  | Precision | Recall |
|------------------|-----------|-----------|--------|
| Random Forest    | 94.7%     | 95.2%     | 94.5%  |
| SVM              | 91.2%     | 91.0%     | 90.8%  |
| KNN              | 89.3%     | 88.7%     | 89.0%  |

> 🧠 Random Forest gave the best accuracy for multi-class classification across bird species and threat detection.

---

## Results

![Image](https://github.com/user-attachments/assets/31d05053-87aa-4eff-a4a2-45587d2433ce)
![Image](https://github.com/user-attachments/assets/e7e1e00a-0652-41a5-92de-f7186394efc8)
