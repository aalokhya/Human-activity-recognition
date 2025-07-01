# 🧍 Human Activity Recognition with CNN-LSTM

This repository presents a deep learning approach for classifying human activities using a hybrid **CNN-LSTM model**. The model is trained on data collected from smartphones' embedded accelerometer and gyroscope sensors, based on the **UCI Human Activity Recognition (HAR) Dataset**.

> 🔬 Note: This project focuses exclusively on model training and evaluation. No real-time prediction or UI integration is included.

---

## 📊 Dataset

- **Source**: [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)
- **Description**: Sensor data collected from 30 volunteers performing six daily activities while carrying a waist-mounted smartphone.
- **Activities Recognized**:
  - `WALKING`
  - `WALKING_UPSTAIRS`
  - `WALKING_DOWNSTAIRS`
  - `SITTING`
  - `STANDING`
  - `LAYING`

---

## 🧠 Model Overview

- **Type**: CNN-LSTM (1D Convolution + Long Short-Term Memory)
- **Purpose**:  
  - CNN layers extract spatial patterns from sensor signals.
  - LSTM layers model the temporal dependencies in activity sequences.
- **Frameworks Used**:  
  - TensorFlow  
  - Keras

---

## 📁 Files Included

- `human_activity_recognition Activity 12.ipynb`:  
  Main Jupyter Notebook containing the entire pipeline — from data preprocessing to model training and evaluation.

---

## 📚 Reference

Anguita, D. et al. (2013).  
*Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine.*  
Proceedings of the International Workshop on Ambient Assisted Living.

---

## 📝 License

- **Code**: MIT License  
- **Dataset**: Public Domain (CC0)
