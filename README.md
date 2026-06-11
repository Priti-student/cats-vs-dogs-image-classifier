# Cats vs Dogs Image Classification using Deep Learning

## 📌 Project Overview

This project implements and compares multiple deep learning approaches for binary image classification of cats and dogs using the Dogs vs Cats dataset from Kaggle.

The project explores the effectiveness of:

* Custom Convolutional Neural Networks (CNNs)
* Transfer Learning using EfficientNetB0
* Fine-Tuning of pretrained models

The primary goal is to classify images as either **Cat** or **Dog** while evaluating the impact of advanced deep learning techniques on model performance.

---

## 🎯 Results

| Model                              | Validation Accuracy |
| ---------------------------------- | ------------------- |
| Custom CNN                         | 84–85%              |
| Transfer Learning (EfficientNetB0) | 98–99%              |
| Fine-Tuned EfficientNetB0          | 99%                 |

The results demonstrate the significant improvement achieved through transfer learning and fine-tuning compared to a CNN built from scratch.

---

## 🚀 Features

* Binary image classification (Cat vs Dog)
* Custom CNN implementation
* Transfer Learning with EfficientNetB0
* Fine-Tuning of pretrained layers
* Data augmentation
* Early stopping
* Model checkpointing
* Performance evaluation
* Accuracy and loss visualization
* Confusion matrix analysis
* Classification report generation

---

## 📂 Dataset

**Dataset:** Dogs vs Cats

**Source:** Kaggle

The dataset contains images belonging to two classes:

* Cat
* Dog

Images were divided into training and validation sets for model development and evaluation.

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 🧠 Models Implemented

### 1. Custom CNN

File:cats_vs_dogs.ipynb

A Convolutional Neural Network built from scratch using:

* Convolution Layers
* Max Pooling Layers
* Dropout Layers
* Dense Layers

This model serves as the baseline for comparison.

---

### 2. Transfer Learning using EfficientNetB0

File:Classification of cats-vs-dogs using transfer learning.ipynb

A pretrained EfficientNetB0 model trained on ImageNet was used as a feature extractor.

Features:

* Frozen pretrained layers
* Faster convergence
* Better feature extraction
* Improved generalization

This model significantly outperformed the custom CNN.

---

### 3. Fine-Tuned EfficientNetB0

File:Classification of cats-vs-dogs using transfer learning.ipynb

After transfer learning:

* Selected EfficientNetB0 layers were unfrozen
* The model was retrained using a small learning rate
* Features were adapted specifically for the Dogs vs Cats dataset

This approach achieved the highest classification accuracy.

---

## 📊 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Validation Accuracy
* Loss
* Validation Loss
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📈 Training Analysis

The project includes visualizations for:

* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss
* Confusion Matrix

These visualizations help analyze learning behavior and identify overfitting or underfitting.

---

### File Description

| File                                                         | Description                                     |
| -------------------------------------------------------------| ----------------------------------------------- |
| cats_vs_dogs.ipynb                                           | Custom CNN built from scratch                   |
| Classification of cats-vs-dogs using transfer learning.ipynb | EfficientNetB0 Transfer Learning implementation |
| cats_vs_dogs_model.zip                                       | Fine-Tuned EfficientNetB0 model                 |
| README.md                                                    | Project documentation                           |

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Priti-student/cats-vs-dogs-image-classifier
```

### 2. Install Dependencies

```bash
pip install tensorflow scikit-learn matplotlib seaborn kaggle
```

### 3. Download Dataset

Download the Dogs vs Cats dataset from Kaggle and place it in the working directory.

### 4. Run the Notebooks

Execute the notebooks sequentially:

1. cats_vs_dogs.ipynb
2. Classification of cats-vs-dogs using transfer learning.ipynb

---

## 📚 Key Learnings

Through this project, I gained practical experience in:

* Convolutional Neural Networks (CNNs)
* Transfer Learning
* Fine-Tuning Deep Learning Models
* Data Augmentation
* Model Evaluation
* Computer Vision
* TensorFlow and Keras

---

## 🔮 Future Improvements

* Grad-CAM for model explainability
* MobileNetV2 and ResNet50 comparison
* Real-time image prediction interface

---

## 👩‍💻 Author

**Priti Ram**

B.Tech Student | AI & Machine Learning Enthusiast

Interested in Deep Learning, Computer Vision, and Artificial Intelligence Applications.
