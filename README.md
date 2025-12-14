
# Brain Tumor Detection Using Deep Learning

## 📌 Project Overview

This project focuses on **detecting brain tumors from MRI images using Deep Learning techniques**. A Convolutional Neural Network (CNN) is trained to classify MRI scans into tumor-related categories, assisting in early diagnosis and medical decision support.

The implementation is provided in a Jupyter Notebook and demonstrates data preprocessing, model training, evaluation, and prediction.

---

## 🎯 Objectives

* Automate brain tumor detection from MRI images
* Reduce manual diagnostic effort
* Improve accuracy using deep learning models

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* OpenCV
* Jupyter Notebook

---

## 📂 Project Structure

```
├── Brain Tumor Detection using DEEP LEARNING.ipynb
├── dataset/
│   ├── yes/
│   └── no/
├── models/
├── outputs/
└── README.md
```

---

## ⚙️ Algorithm / Working Steps

1. **Data Collection**

   * MRI images are collected and categorized into tumor and non-tumor classes.

2. **Data Preprocessing**

   * Resize images
   * Normalize pixel values
   * Convert images into arrays

3. **Model Architecture**

   * Convolutional layers for feature extraction
   * Max pooling layers for dimensionality reduction
   * Fully connected layers for classification

4. **Model Training**

   * Split data into training and testing sets
   * Train CNN using backpropagation
   * Optimize using Adam optimizer

5. **Model Evaluation**

   * Accuracy and loss are calculated
   * Performance is visualized using graphs

6. **Prediction**

   * New MRI images are passed to the trained model
   * Output predicts whether a tumor is present or not

---

## 📥 Sample Input

* Input: MRI image of the brain (JPEG/PNG format)

Example:

```
Input Image → brain_mri_01.jpg
```

---

## 📤 Sample Output

```
Prediction: Positive Tumor
Confidence: 96.4%
```

OR

```
Prediction: No Tumor
Confidence: 94.8%
```

---

## 🚀 How to Run the Project

1. Clone the repository

   ```bash
   git clone <repository-url>
   ```
2. Install required libraries

   ```bash
   pip install tensorflow numpy pandas matplotlib opencv-python
   ```
3. Open Jupyter Notebook

   ```bash
   jupyter notebook
   ```
4. Run **Brain Tumor Detection using DEEP LEARNING.ipynb** step by step

---

## ✅ Results

* The model achieves high accuracy in detecting brain tumors.
* Deep learning proves effective for medical image classification.

---

## 🔮 Future Enhancements

* Multi-class tumor classification
* Integration with a web or mobile application
* Use of transfer learning (ResNet, VGG, etc.)

---
