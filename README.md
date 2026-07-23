# Detection of Natural Disasters Using Machine Learning Technique

## 📌 Project Overview

This project presents a deep learning-based system for detecting and classifying natural disasters from satellite imagery. The model utilizes Transfer Learning with MobileNetV2 to classify multiple disaster categories accurately. To improve model interpretability, Grad-CAM is used to visualize the regions of the image that contribute to the prediction. The project also estimates disaster severity based on prediction confidence.

---

## 🎯 Objectives

- Detect natural disasters using satellite images.
- Improve classification accuracy using Transfer Learning.
- Visualize model predictions with Grad-CAM.
- Estimate disaster severity based on prediction confidence.
- Predict disaster types for new satellite images.

---

## 🚀 Features

- Multi-class disaster classification
- Transfer Learning using MobileNetV2
- Image preprocessing and augmentation
- Class imbalance handling
- Model training and validation
- Confusion Matrix
- Precision, Recall and F1-Score evaluation
- Classification Report
- Grad-CAM visualization
- Disaster severity estimation
- Single image prediction

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## 🧠 Model Architecture

- Base Model: MobileNetV2 (Pre-trained on ImageNet)
- Transfer Learning
- Fully Connected Classification Layers
- Softmax Output Layer

---

## 📊 Evaluation Metrics

The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 🔥 Explainable AI

Grad-CAM (Gradient-weighted Class Activation Mapping) is used to generate heatmaps that highlight the regions of satellite images influencing the model's predictions. This improves the transparency and interpretability of the deep learning model.

---

## 📂 Project Workflow

```
Satellite Images
        │
        ▼
Image Preprocessing
        │
        ▼
Data Augmentation
        │
        ▼
Transfer Learning (MobileNetV2)
        │
        ▼
Model Training
        │
        ▼
Prediction
        │
        ▼
Grad-CAM Visualization
        │
        ▼
Severity Estimation
```

---

## 📸 Project Screenshots

### Training Accuracy

(Add `accuracy.png` here)

### Training Loss

(Add `loss.png` here)

### Confusion Matrix

(Add `confusion_matrix.png` here)

### Grad-CAM Visualization

(Add `gradcam.png` here)

### Prediction Output

(Add `prediction.png` here)

---

## 📁 Project Structure

```
Detection-of-Natural-Disasters-Using-Machine-Learning-Technique
│
├── Disaster_Detection.ipynb
├── README.md
├── requirements.txt
└── screenshots
      ├── accuracy.png
      ├── loss.png
      ├── confusion_matrix.png
      ├── gradcam.png
      └── prediction.png
```

---

## 🔮 Future Enhancements

- Real-time disaster monitoring
- Deployment as a web application
- Live satellite image integration
- Support for additional disaster categories
- Cloud deployment

---

## 👩‍💻 Author

**Adhisubalakshmi K A K**

Electronics and Communication Engineering

Machine Learning | Deep Learning | Computer Vision