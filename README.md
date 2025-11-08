# FlowerClassification


# 🌸 Flower Classification using CNN (TensorFlow/Keras)

This project builds a **Convolutional Neural Network (CNN)** to classify images of flowers using the **TensorFlow Flowers dataset** (`tf_flowers`).  
It demonstrates data loading, preprocessing, model building, training, evaluation, and prediction — all within a single Jupyter Notebook.

---

## 📘 Overview

The notebook walks through:
- Loading and splitting the `tf_flowers` dataset
- Preprocessing and normalizing images
- Building a CNN architecture using Keras Sequential API
- Training and evaluating the model
- Visualizing accuracy and loss
- Making predictions on unseen data

---

## 🧠 Model Architecture

The CNN model is composed of:
- Multiple **Conv2D** + **MaxPooling2D** layers for feature extraction  
- **Dropout** layers to reduce overfitting  
- **Flatten** and **Dense** layers for classification  
- **Softmax** activation in the output layer for multi-class prediction  

**Optimizer:** Adam  
**Loss Function:** Sparse Categorical Crossentropy  
**Metrics:** Accuracy  

---

## 📊 Dataset

**Dataset:** [TensorFlow Flowers](https://www.tensorflow.org/datasets/catalog/tf_flowers)

The dataset contains 5 flower categories:
- Daisy 🌼  
- Dandelion 🌻  
- Roses 🌹  
- Sunflowers 🌞  
- Tulips 🌷  

It is automatically downloaded and prepared using `tensorflow_datasets`.

---

## ⚙️ Requirements

To run this notebook, install the following dependencies:

```bash
pip install tensorflow tensorflow-datasets matplotlib numpy
