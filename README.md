# 🐶🐱 Cats vs. Dogs Image Classification using CNN

## 📘 Project Overview

This project implements a **Convolutional Neural Network (CNN)** using **TensorFlow and Keras** to classify images as either **cat** or **dog**. The model is trained on a dataset from Kaggle and demonstrates how deep learning can be applied to binary image classification problems.

---

## 🎯 Objective

- Develop an end-to-end image classification pipeline using CNN.
- Automate pet image classification with high accuracy.
- Enable predictions on unseen, real-world images.
- Visualize the learning process and evaluate performance using real metrics.

---

## 🧠 Use Case

This model can be used in:

- **Pet identification apps**
- **Veterinary clinics** to automatically tag photos
- **Animal shelter software** for quick pet type classification
- **Educational purposes** to demonstrate CNNs in action

---

## 📂 Dataset

- **Source**: [Kaggle - Dogs vs. Cats (by salader)](https://www.kaggle.com/datasets/salader/dogs-vs-cats)
- Dataset contains thousands of labeled images of dogs and cats.
- Downloaded using Kaggle API:

```bash
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!kaggle datasets download -d salader/dogs-vs-cats
!unzip dogs-vs-cats.zip
