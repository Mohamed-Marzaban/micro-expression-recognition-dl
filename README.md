# 🎭 Micro-Expression Recognition using Deep Learning

Ever tried catching an emotion that lasts less than half a second?  
That’s exactly what this project is about.

This repository contains my **Bachelor Graduation Project**, where I explore **micro-expression recognition** using **deep learning** techniques on the **SAMM micro-expression dataset**.

Micro-expressions are extremely brief, involuntary facial expressions that reveal genuine emotions — making them one of the hardest problems in computer vision and affective computing.

---

## 🚀 Project Overview

The goal of this project is to **detect and classify subtle facial micro-expressions from video sequences** by combining:

- **Spatial feature extraction** (what the face looks like)
- **Temporal modeling** (how facial movements evolve over time)

The pipeline is designed to capture tiny, short-duration facial changes that are often invisible to the human eye.

---

## 🧠 Methodology

The system follows a spatio-temporal deep learning pipeline:

1. **Preprocessing**
   - Face alignment and normalization
   - Selection of relevant frames around micro-expression intervals

2. **Feature Extraction**
   - Deep visual features extracted using CNN-based architectures

3. **Temporal Modeling**
   - Sequential modeling of facial dynamics using recurrent networks (e.g., BiLSTM)

4. **Classification**
   - Emotion category prediction based on learned representations

---

## 📊 Dataset

This project uses the **SAMM (Spontaneous Actions and Micro-Movements)** dataset:

- High frame-rate facial videos
- Precisely annotated onset, apex, and offset frames
- Widely used in academic micro-expression research

SAMM is known for being **challenging and realistic**, making it ideal for evaluating micro-expression models.

---

## 📈 Results & Evaluation

The model is evaluated using standard classification metrics such as:

- Accuracy
- Confusion matrix

The results show that **combining spatial and temporal representations** significantly improves the recognition of subtle facial movements.

*(See the notebook for full experiments, visualizations, and outputs.)*

---

## 🛠️ Tech Stack

- **Python**
- **Deep Learning:** CNNs, BiLSTM
- **Libraries:** NumPy, OpenCV, PyTorch / TensorFlow *(depending on implementation)*
- **Visualization:** Matplotlib
- **Environment:** Jupyter Notebook

---

## 📓 Notebook

The full implementation, experiments, and outputs are available in the notebook:

📘 `SAMM_Micro_Expressions.ipynb`

All outputs are preserved to ensure full transparency and reproducibility.

---

## 🎓 Academic Context

This project was developed as part of my **Bachelor Project** in Computer Engineering , focusing on:

- Computer Vision  
- Deep Learning  

---

## 👤 Author

**Mohamed Shady**  
Computer Engineering Student  
German University in Cairo (GUC)

If you found this project interesting, feel free to ⭐ the repo!
