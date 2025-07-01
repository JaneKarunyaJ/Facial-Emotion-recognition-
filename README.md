# Facial Emotion Recognition 

This project implements a Facial Emotion Recognition system using deep learning techniques. The goal is to accurately detect and classify human emotions from facial expressions in images or real-time video feeds.

##  Overview

Facial Emotion Recognition (FER) plays a critical role in human-computer interaction, psychology, and security applications. This project leverages Convolutional Neural Networks (CNNs) to classify emotions such as:

- Angry 😠
- Disgust 🤢
- Fear 😨
- Happy 😄
- Sad 😢
- Surprise 😲
- Neutral 😐

---

## 📁 Project Structure

```bash
Facial-Emotion-recognition-/
├── dataset/              # FER2013 dataset
├── models/               # Saved trained model (HDF5 format)
├── src/
│   ├── train.py          # Training script
│   ├── predict.py        # Prediction/inference logic
│   ├── model.py          # CNN architecture definition
│   └── utils.py          # Helper functions
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation

Model Architecture
Framework: TensorFlow / Keras

Architecture: Custom CNN

Input: 48x48 grayscale facial images

Output: 7 emotion classes

Loss Function: Categorical Cross-Entropy

Optimizer: Adam

Dataset
FER-2013: The dataset contains 35,887 grayscale images of 48x48 pixels, each labeled with one of the seven emotions.

Source: Kaggle FER2013
