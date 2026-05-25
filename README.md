# Signature Forgery Detection using PyTorch

A deep learning project for handwritten signature verification using Convolutional Neural Networks (CNNs) in PyTorch.  
The model classifies signatures as **Genuine** or **Forged** using image-based learning techniques.

---

## Overview

This project focuses on offline signature verification by training a CNN model on handwritten signature datasets.  
It includes preprocessing, training, validation, and prediction pipelines for forgery detection.

---

## Features

- Signature Forgery Detection
- CNN-based Deep Learning Model
- Genuine vs Forged Classification
- Image Preprocessing
- Model Training & Validation
- Accuracy Evaluation
- Real-time Prediction
- PyTorch Implementation

---

## Tech Stack

- Python
- PyTorch
- Torchvision
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn
- PIL

---

## Dataset Structure

```bash
dataset/
│
├── train/
│   ├── genuine/
│   └── forged/
│
├── valid/
│   ├── genuine/
│   └── forged/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/signature-forgery-detection-pytorch.git
```

Move into the project directory:

```bash
cd signature-forgery-detection-pytorch
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Requirements

```txt
torch
torchvision
numpy
matplotlib
pillow
opencv-python
scikit-learn
tqdm
jupyter
```

---

## Training

Run the notebook:

```bash
jupyter notebook
```

Open:

```bash
signature.ipynb
```

---

## Prediction

Upload a signature image and run prediction to determine whether the signature is genuine or forged.

Example:

```python
model.predict(image)
```

---

## Model Information

- Framework: PyTorch
- Optimizer: Adam
- Loss Function: CrossEntropyLoss
- Image Size: 224x224
- Best Model Saving Supported

---

## Project Structure

```bash
├── dataset/
├── best_signature_model.pth
├── signature.ipynb
├── requirements.txt
└── README.md
```

---

## Future Improvements

- Siamese Neural Networks
- Better Data Augmentation
- Web Application Deployment
- REST API Integration
- Mobile App Support

---

## Author

Developed by Suchay Joshi
