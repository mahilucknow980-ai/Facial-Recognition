# 😊 DeepFER - Facial Emotion Recognition Using Deep Learning

A Deep Learning based Facial Emotion Recognition System that detects human emotions in real-time using a webcam. This project uses a Convolutional Neural Network (CNN) trained on the FER2013 dataset and OpenCV for face detection.

---

## 📌 Project Overview

Facial Emotion Recognition (FER) is a Computer Vision application that identifies a person's emotional state from facial expressions.

This project recognizes the following seven emotions:

- 😀 Happy
- 😢 Sad
- 😠 Angry
- 😨 Fear
- 😲 Surprise
- 😐 Neutral
- 🤢 Disgust

The trained model predicts emotions from live webcam video in real time.

---

## 🚀 Features

- Real-Time Emotion Detection
- Face Detection using OpenCV
- CNN-based Emotion Classification
- FER2013 Dataset
- TensorFlow/Keras Implementation
- Data Augmentation
- Model Training & Evaluation
- Accuracy and Loss Visualization
- Confusion Matrix
- Classification Report
- Saved Trained Model (.keras)

---

## 🛠 Technologies Used

- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
DeepFER/
│
├── dataset/
│   ├── train/
│   └── test/
│
├── models/
│   ├── DeepFER_Best_Model.keras
│   └── DeepFER_Final_Model.keras
│
├── notebooks/
│   └── DeepFER.ipynb
│
├── results/
│   ├── Accuracy.png
│   ├── Loss.png
│   └── Confusion_Matrix.png
│
├── README.md
│
└── requirements.txt
```

---

## 📊 Dataset

This project uses the **FER2013** dataset.

Dataset contains:

- 35,887 grayscale facial images
- Image Size: 48 × 48
- 7 Emotion Classes

Dataset Structure

```
train/

angry/

disgust/

fear/

happy/

neutral/

sad/

surprise/

test/

angry/

...
```

---

## 🧠 CNN Architecture

The CNN model consists of:

- Conv2D
- Batch Normalization
- MaxPooling
- Dropout
- Flatten
- Dense Layer
- Softmax Output Layer

---

## 🔄 Project Workflow

```
Dataset Collection
        ↓
Image Preprocessing
        ↓
Data Augmentation
        ↓
CNN Model
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Save Model
        ↓
Real-Time Webcam Detection
```

---

## 📈 Model Evaluation

The trained model is evaluated using:

- Accuracy
- Loss
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 🎥 Real-Time Emotion Detection

The application performs the following steps:

1. Open Webcam
2. Detect Face
3. Extract Face Region
4. Resize Image (48×48)
5. Normalize Image
6. Predict Emotion
7. Display Emotion Label
8. Display Confidence Score

---

## 💻 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/DeepFER.git
```

Move to project directory

```bash
cd DeepFER
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Project

Open Jupyter Notebook

```bash
jupyter notebook
```

Run

```
DeepFER.ipynb
```

---

## 📸 Sample Output

```
Emotion : Happy 😊

Confidence : 97.84%
```

---

## 📚 Applications

- Healthcare
- Mental Health Monitoring
- Driver Monitoring System
- Human Computer Interaction
- Smart Classroom
- Security Systems
- Customer Behaviour Analysis
- Online Examination Monitoring

---

## 🔮 Future Scope

- Mobile Application
- Web Application
- Higher Accuracy Models
- Transfer Learning
- Multi-face Emotion Detection
- Emotion Analytics Dashboard
- Cloud Deployment

---

## 📄 Requirements

```
tensorflow
opencv-python
numpy
matplotlib
pandas
scikit-learn
jupyter
```

---

## 👨‍💻 Author

**Mahesh Kumar**

B.Tech Computer Science & Engineering (AI & DS)

Khwaja Moinuddin Chishti Language University

Lucknow, Uttar Pradesh, India

---

## 📜 License

This project is developed for educational and research purposes.

---

## ⭐ If you like this project

Please consider giving this repository a ⭐ on GitHub.
