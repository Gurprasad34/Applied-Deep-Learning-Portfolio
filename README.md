# 🧠 Applied Deep Learning Portfolio

## Overview

This project is a collection of deep learning applications across **banking, natural language processing, computer vision, and medical imaging**.

The portfolio explores several neural network architectures using **Python, TensorFlow, and Keras**, including Artificial Neural Networks, CNN-LSTM models, Transfer Learning, and Autoencoders. Each project covers data preprocessing, model development, training, evaluation, and prediction on a different type of real-world data.

---

## Projects

### 🏦 Customer Churn Prediction

Built an **Artificial Neural Network (ANN)** to predict whether a banking customer is likely to churn.

The workflow includes preprocessing customer data, encoding categorical variables, splitting the data into training and testing sets, training a sequential neural network, and evaluating classification performance.

**Techniques:**
- Artificial Neural Networks
- Binary Classification
- Feature Encoding
- Train/Test Splitting
- Confusion Matrix & Accuracy Evaluation

**Notebook:** `ChurnModel.ipynb`

---

### 😷 Face Mask Detection

Developed an image classification model using **Transfer Learning** to identify whether a person is wearing a face mask.

Images were prepared for training, validation, and testing before applying pretrained deep learning architectures with pooling, dropout, and classification layers. Model predictions were then compared against true image labels.

**Techniques:**
- Transfer Learning
- Image Classification
- Image Preprocessing
- Dropout & Pooling
- Softmax Classification

**Notebook:** `FaceDetectionModel.ipynb`

---

### 💬 Customer Review Sentiment Classification

Built a **CNN-LSTM hybrid neural network** to classify customer product reviews based on sentiment.

Review text was converted into a binary target, tokenized, padded, and processed through a model combining convolutional layers for feature extraction with LSTM layers for sequential text understanding.

**Techniques:**
- Natural Language Processing
- Text Tokenization & Padding
- Word Embeddings
- Conv1D
- LSTM
- Sentiment Classification

**Notebook:** `CNN-LSTM.ipynb`

---

### 🦷 Dental X-Ray Denoising

Developed a **Convolutional Autoencoder** to reconstruct cleaner dental X-ray images from noisy inputs.

Gaussian noise was added to normalized images to create corrupted samples. The autoencoder was then trained to reconstruct the original images using convolutional and transposed convolutional layers.

**Techniques:**
- Autoencoders
- Unsupervised Learning
- Image Denoising
- Convolutional Neural Networks
- Gaussian Noise
- Image Reconstruction

**Notebook:** `autoencoderDentalXRays.ipynb`

---

## 🛠️ Technologies

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **Jupyter Notebook**

---

## Key Concepts Demonstrated

This portfolio demonstrates practical experience with:

- Artificial Neural Networks
- Convolutional Neural Networks
- LSTM Networks
- Transfer Learning
- Autoencoders
- Binary & Multiclass Classification
- Natural Language Processing
- Computer Vision
- Image Reconstruction
- Model Training & Evaluation

---

## Repository Structure

```text
Applied-Deep-Learning-Portfolio/
│
├── data/
├── ChurnModel.ipynb
├── CNN-LSTM.ipynb
├── FaceDetectionModel.ipynb
├── autoencoderDentalXRays.ipynb
├── Churn_Modeling.csv
└── .gitignore
```

> Large datasets used for model training are excluded from the repository due to file size limitations.

---

## Purpose

The goal of this portfolio is to demonstrate the application of different **deep learning architectures to multiple data types and real-world problems**, ranging from structured banking data and customer reviews to image classification and medical image reconstruction.
