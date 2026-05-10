# Deep-Learning-Framework-for-Blind-Underwater-Image-Quality-Assessment
Overview

This project implements MobileViT, a lightweight hybrid deep learning architecture that combines the strengths of Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs) for efficient image classification tasks. The model is designed to deliver high accuracy while maintaining low computational cost, making it suitable for mobile and edge devices.

Features
Hybrid CNN + Transformer architecture
Efficient and lightweight model design
Image preprocessing and augmentation
Model training and evaluation pipeline
Accuracy and performance visualization
PyTorch implementation
Tech Stack
Python
PyTorch
NumPy
Matplotlib
Scikit-learn
Project Structure
├── mobilevit.ipynb
├── dataset/
├── models/
├── outputs/
├── README.md
Installation



Install dependencies:

pip install -r requirements.txt
Usage

Run the Jupyter Notebook:

jupyter notebook mobilevit.ipynb

Train the model and evaluate performance directly from the notebook.

Model Highlights

MobileViT combines:

Local feature extraction from CNNs
Global context learning from Transformers

This improves:

Computational efficiency
Feature representation
Classification performance
Results

The model demonstrates strong performance on image classification tasks with reduced parameters and lower computational complexity compared to traditional transformer models.

Future Improvements
Hyperparameter tuning
Deployment on edge devices
Transfer learning support
Real-time inference optimization
