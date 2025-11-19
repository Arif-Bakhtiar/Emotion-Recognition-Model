# Speech Emotion Recognition (RAVDESS Dataset)

This project implements a **Speech Emotion Recognition (SER)** system using **Mel-Frequency Cepstral Coefficients (MFCC)** and a **Long Short-Term Memory (LSTM)** neural network.  
It detects emotions such as **happy, sad, angry, calm, fear, disgust, surprise,** and **neutral** from audio recordings of human speech.

---

## Overview

The ability to detect emotions from speech is essential for applications in:
- Human-computer interaction
- Sentiment analysis
- Mental health monitoring
- Customer service analytics

This project leverages the **RAVDESS dataset** and extracts **MFCC features** from each audio file to train an **LSTM-based deep learning model** capable of recognizing emotions with high accuracy.

---

## Features

- Audio-based emotion detection using MFCCs  
- Deep learning with LSTM architecture  
- Training and evaluation metrics visualization  
- Configurable preprocessing (audio duration, padding, sampling rate)  
- Easily extendable to other emotion datasets  

---

## Model Architecture

**Model Type:** Sequential LSTM  
**Input:** 40 MFCC features × 216 time steps  
**Layers:**
1. LSTM (128 units)
2. Dropout (0.3)
3. LSTM (64 units)
4. Dense (8 neurons, Softmax activation)

**Loss Function:** Categorical Crossentropy  
**Optimizer:** Adam  
**Evaluation Metric:** Accuracy
**Metric	    Value**
Test Accuracy:	84.20%

---


