#   MNIST Digit Classification using CNN

## Overview
---
Built a Convolutional Neural Network (CNN) to classify handwritten digits using the MNIST dataset. Implemented proper preprocessing, baseline modeling, and performance improvement using data augmentation.

## 📂 Dataset
---
The dataset is not included in this repository due to size constraints.

You can download it from:
- https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

After downloading, place the files in the following structure:
- dataset
     - mnist_train.csv
     - mnist_test.csv

## ⚙️ Workflow
---
- Data Loading & Inspection  
- Preprocessing (Normalization, Reshaping, One-hot encoding)  
- Baseline CNN Model  
- Error Analysis  
- Data Augmentation for improvement  

## 🏗️ Model Architecture
---
- Conv2D (32 filters) + ReLU  
- MaxPooling  
- Conv2D (64 filters) + ReLU  
- MaxPooling  
- Flatten  
- Dense (128) + Dropout  
- Output (Softmax)  

## 📈 Results
---
- Baseline Accuracy: ~99.1%  
- After Augmentation: ~99.3–99.4%  

## 🔍 Key Learnings
---
- Data augmentation improves generalization  
- Simpler models can outperform complex ones  
- Validation-based decisions are critical  
