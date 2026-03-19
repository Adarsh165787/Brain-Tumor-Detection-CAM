# 🧠 Brain Tumor Detection using CNN + Class Activation Maps (CAM)

## 📌 Overview

This project focuses on **brain tumor detection** from MRI images using a **Convolutional Neural Network (CNN)**. In addition to classification, the model uses **Class Activation Maps (CAM)** to visualize which regions of the brain contributed to the prediction.

The goal is not only to achieve high accuracy but also to provide **interpretability**, which is crucial in medical applications.

---

## 🎯 Objectives

* Build a CNN model for **brain tumor classification**
* Apply **filters and feature extraction** techniques
* Generate **Class Activation Maps (CAM)** for visualization
* Evaluate **localization quality**
* Provide **medical interpretation** of results

---

## 📂 Dataset

* MRI brain scan images
* Classes:

  * Tumor
  * No Tumor

*(Mention dataset source here if required, e.g., Kaggle)*

---

## ⚙️ Model Architecture

* Convolutional Layers (Feature Extraction)
* ReLU Activation
* MaxPooling Layers
* Fully Connected Layers
* Softmax Output Layer

---

## 🧪 Implementation Steps

### 1. Data Preprocessing

* Image resizing
* Normalization
* Train-test split

### 2. CNN Model Training

* Loss Function: CrossEntropy
* Optimizer: Adam
* Evaluation Metrics: Accuracy, Loss

### 3. Feature Filtering

* CNN filters automatically learn:

  * Edges
  * Textures
  * Tumor patterns

### 4. Class Activation Map (CAM)

* Extract feature maps from last convolution layer
* Weight them using final dense layer weights
* Overlay heatmap on original MRI image

---

## 🔥 CAM Visualization

CAM helps identify **important regions** used by the model.

* Red/Hot regions → High importance (possible tumor)
* Blue/Cool regions → Low importance

---

## 📊 Results

* Training Accuracy: XX%
* Validation Accuracy: XX%
* Loss Curve Analysis

*(Replace XX with your actual results)*

---

## 📍 Localization Quality

* CAM correctly highlights tumor regions in most cases
* Helps validate model decisions
* Improves trust in predictions

---

## 🏥 Medical Interpretation

* Model identifies abnormal tissue regions
* CAM provides visual explanation for diagnosis
* Useful as a **decision-support tool** for radiologists
* Not a replacement for medical professionals

---

## 💡 Key Insights

* CNN performs well for image classification tasks
* CAM adds **interpretability**
* Localization improves model reliability in healthcare

---

## 🚀 Future Improvements

* Use **Grad-CAM** for better visualization
* Apply **transfer learning (ResNet, VGG)**
* Increase dataset size
* Deploy as a web app

---

## 🛠️ Technologies Used

* Python
* TensorFlow / PyTorch
* OpenCV
* Matplotlib
* NumPy

---

## 📁 Project Structure

```
├── dataset/
├── model/
├── notebooks/
│   └── Brain_Tumor_Detection.ipynb
├── results/
├── README.md
```

---

## 👨‍💻 Author

**Adarsh Kumar**
B.Tech CSE (AI)
KIET Group of Institutions

---

## ⚠️ Disclaimer

This project is for **educational purposes only**. It should not be used for real-world medical diagnosis without expert validation.

---
