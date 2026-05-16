# AI-Based Crop Disease Detection System

## Overview

The AI-Based Crop Disease Detection System is a deep learning project developed using Python and Convolutional Neural Networks (CNN).
This system helps in detecting crop diseases from leaf images and provides faster identification for farmers and agricultural researchers.

The project uses image processing and machine learning techniques to classify diseases based on uploaded crop leaf images

---

## Features

* Image-based disease detection using CNN
* Deep learning model for accurate prediction
* Data preprocessing and augmentation
* Disease classification and prediction
* Flask web application interface
* Practical implementation using agricultural datasets

---

## Technologies Used

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Flask
* Matplotlib
* Scikit-learn

---

## Project Structure

```bash
AI_Crop_Disease_Detection_System/
│
├── app.py
├── train_model.py
├── predict.py
├── requirements.txt
├── README.md
│
├── dataset/
│
├── model/
│   └── crop_disease_model.h5
│
├── static/
│
└── templates/
    └── index.html
```

---

## System Requirements

* Python 3.8 or above
* TensorFlow
* Flask
* OpenCV
* NumPy

---

## Installation

### Step 1: Install Required Packages

```bash
pip install -r requirements.txt
```

### Step 2: Train the Model

```bash
python train_model.py
```

### Step 3: Run the Application

```bash
python app.py
```

---

## Working Procedure

1. Upload a crop leaf image through the web application.
2. The image is preprocessed and resized.
3. The CNN model analyzes the image.
4. The system predicts the disease category.
5. The prediction result is displayed to the user.

---

## CNN Model Features

* Convolution Layers for feature extraction
* Max Pooling Layers for dimensionality reduction
* Dropout Layer to reduce overfitting
* Softmax activation for classification

---

## Advantages

* Faster disease identification
* Reduces manual inspection
* Improves agricultural productivity
* Supports smart farming techniques
* User-friendly interface

---

## Future Enhancements

* Real-time mobile application
* IoT sensor integration
* Multi-crop disease detection
* Cloud deployment
* Higher accuracy using advanced deep learning models

---

## Conclusion

The AI-Based Crop Disease Detection System demonstrates the practical implementation of Artificial Intelligence in agriculture.
By using CNN-based image classification techniques, the system can accurately detect crop diseases and support farmers in taking preventive measures at an early stage.
