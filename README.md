# 🧠 Brain Tumor Detection using Deep Learning (CNN)

## Overview

This project uses a Convolutional Neural Network (CNN) built with TensorFlow/Keras to classify brain MRI images into two categories: **Tumor** and **No Tumor**. The project demonstrates a complete deep learning workflow, including image preprocessing, model training, evaluation, and prediction.

---

## Project Objective

The objective of this project is to develop a deep learning model capable of detecting brain tumors from MRI images. The project demonstrates image classification using Convolutional Neural Networks (CNNs) and TensorFlow.

---

## Dataset

* **Dataset:** Brain MRI Images for Brain Tumor Detection
* **Source:** Kaggle
* **Classes:**

  * Tumor (Yes)
  * No Tumor (No)

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab

---

## Project Workflow

1. Load MRI image dataset
2. Image preprocessing
3. Data augmentation
4. Build CNN model
5. Train model
6. Evaluate model
7. Predict tumor/no tumor
8. Save trained model

---

## Model

* Convolutional Neural Network (CNN)
* Binary Classification
* Activation Function: ReLU & Sigmoid
* Optimizer: Adam
* Loss Function: Binary Crossentropy

---

## Results

* Successfully classified MRI images into:

  * Tumor
  * No Tumor
* Generated training and validation accuracy graphs
* Generated training and validation loss graphs
* Saved trained model as `brain_tumor_model.keras`

---

## Project Files

```text
Brain-Tumor-Detection-CNN/
│
├── Brain_Tumor_Detection.ipynb
├── brain_tumor_model.keras
├── README.md
├── requirements.txt
├── LICENSE
└── screenshots/
```

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run

Open the notebook in Google Colab or Jupyter Notebook and run all cells.

---

## Future Improvements

* Improve accuracy using Transfer Learning (MobileNetV2 or EfficientNet)
* Deploy using Flask
* Add confidence score visualization
* Build a web interface

---

## Author

RS DEEPTHI
B.Tech – Computer Science and Engineering (CSE)

---

## License

MIT License

