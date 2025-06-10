
# 🧠 CS5720 – Home Assignment 2  
**Course:** Neural Networks and Deep Learning  
**University:** University of Central Missouri  
**Semester:** Summer 2025  
**Student Name:** ALCHURI NIKHITHA

---

## 📌 Assignment Description

This assignment demonstrates fundamental operations in Convolutional Neural Networks (CNNs) and data preprocessing techniques in deep learning. It is divided into three key sections:

### ✅ Q1. Convolution Operations with Different Parameters
- Performed convolution on a 5×5 input matrix using a 3×3 kernel.
- Implemented 4 different configurations using TensorFlow:
  - Stride = 1, Padding = 'VALID'
  - Stride = 1, Padding = 'SAME'
  - Stride = 2, Padding = 'VALID'
  - Stride = 2, Padding = 'SAME'
- Printed the resulting feature maps for each case.

---

### ✅ Q2. CNN Feature Extraction with Filters and Pooling

#### 🧩 Task 1: Sobel Edge Detection
- Loaded a grayscale image (`my_image.jpg`).
- Applied **Sobel-X** and **Sobel-Y** filters using OpenCV.
- Displayed:
  - Original image
  - Edge-detected image (X-direction)
  - Edge-detected image (Y-direction)

#### 🧩 Task 2: Max and Average Pooling
- Created a random **4×4 matrix** as input.
- Applied:
  - **2×2 Max Pooling**
  - **2×2 Average Pooling**
- Displayed the original, max-pooled, and average-pooled matrices using TensorFlow.

---

### ✅ Q3. Data Preprocessing: Normalization vs. Standardization
- Loaded the **Iris dataset** using `sklearn.datasets`.
- Applied:
  - **Min-Max Normalization**
  - **Z-score Standardization**
- Visualized feature distributions using histograms.
- Trained **Logistic Regression** models on:
  - Original data
  - Normalized data
  - Standardized data
- Compared model accuracy across preprocessing methods.
- Discussed scenarios where **Normalization** or **Standardization** is more suitable.

---

## 📁 Project Structure

```bash
├── Q1_Convolution.py               # Convolution with stride and padding variations
├── Q2_Edge_Pooling.py             # Sobel filter and pooling demo
├── Q3_DataPreprocessing.py        # Normalization, standardization, logistic regression
├── my_image.jpg                   # Input grayscale image for edge detection
├── README.md                      # Assignment documentation
