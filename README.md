# Pneumonia-Detection-Using-CNN-and-Transfer-Learning 

This project uses deep learning to automatically detect pneumonia from chest X-ray images.
It combines powerful CNN-based and transfer learning architectures with a simple Streamlit web interface, allowing users to upload an image and instantly get AI-powered diagnostic insights.

## 🚀 Project Overview

Pneumonia is a serious lung infection that can be identified through radiological imaging such as chest X-rays.
This project leverages Convolutional Neural Networks (CNNs) and transfer learning to build an image classification model that distinguishes between normal and pneumonia-infected lungs.

The model was trained and evaluated using the publicly available Chest X-Ray Images (Pneumonia) dataset
.

## 🧠 AI Model Development

The AI component was developed in Python (TensorFlow/Keras) and trained using Google Colab.
It includes:

Custom CNN architecture

Transfer Learning models, including:

DenseNet121

Xception

MobileNetV2 (final best-performing model)

Data augmentation for robust generalization

Early stopping, learning rate reduction, and model checkpointing

Visualization tools for:

Training and validation performance

Class distribution

Confusion matrices

Comparative analysis across multiple architectures

After training and evaluation, the MobileNetV2 model achieved the highest accuracy and AUC, and was exported as
pneumonia_model.keras for deployment.

## 💻 Streamlit Web Application

The project includes a lightweight Streamlit web UI that allows users to interact with the trained model.

#### 🧩 Features:

Upload a chest X-ray image (JPG or PNG)

The AI model analyzes the image in real-time

Displays:

Predicted result (Normal / Pneumonia Detected)

Confidence score

Includes a sample images section for quick testing

Simple, responsive, and intuitive interface

Built-in safety disclaimer emphasizing research-only use
