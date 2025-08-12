---
layout: single
title: "Deep Learningg Projects"
permalink: /deep-learning/
author_profile: true

---

## 🧠 Deep Learning Project #1 – MNIST Digit Classification

This project applies **Artificial Neural Networks (ANN)** using **TensorFlow/Keras** to classify handwritten digits (0–9) from the **MNIST dataset** (70,000 grayscale images, 28×28 pixels each).

**Key Steps:**
- Preprocessed and normalized image data
- One-hot encoded labels
- Built a Sequential ANN with:
  - Flatten input layer
  - Dense hidden layers (128 & 64 neurons, ReLU activation)
  - Dropout for regularization
  - Softmax output layer
- Compiled with Adam optimizer & categorical cross-entropy
- Trained for 10 epochs (batch size: 128, validation split: 0.1)
- Visualized training/validation accuracy & loss
- Evaluated on test set and generated:
  - Final accuracy score
  - Confusion matrix
  - Classification report
- Saved trained model in Keras format

📊 **Outcome:** Achieved high accuracy on handwritten digit recognition with clear performance visualizations.

 📂 [Google Colab Notebook](https://colab.research.google.com/drive/1_SbMdaxfJKi1nHner1zzfGaKtz6F33G6?usp=sharing)
 
 ---
 🔙 [**Back to Projects Categories**](/projects.md)
 
---
