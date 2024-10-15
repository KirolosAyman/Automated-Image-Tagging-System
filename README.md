# Automated-Image-Tagging-System 🌿🔍

This project is a **Plant Disease Recognition System** built using **TensorFlow** and **Streamlit**. It helps users detect diseases in plants by analyzing images of plant leaves. The model identifies different types of plant diseases with high accuracy using a pre-trained neural network.

![Plant Disease Recognition](home_page.jpeg)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Kaggle Notebook](#kaggle-notebook)
---

## Introduction

Plant diseases can cause significant damage to crops if not identified in time. This system aims to assist farmers and researchers in recognizing plant diseases quickly and efficiently through machine learning. By uploading an image of a plant, the system provides a prediction on whether the plant is healthy or diseased.

---

## Features

- **Disease Detection**: Recognizes multiple plant diseases.
- **User-Friendly Interface**: Simple and intuitive Streamlit web interface.
- **Real-time Predictions**: Upload an image and get instant feedback.
- **Scalable Model**: Built with TensorFlow for high performance.

---

## Dataset

This project uses the **PlantVillage dataset**, which contains images of healthy and diseased plant leaves across 38 different classes. The dataset has been augmented to improve model performance.

- **Training Images**: 70,295
- **Validation Images**: 17,572
- **Test Images**: 33 (used for prediction demo)

---

## Installation

To get started with this project, follow these steps:

### Prerequisites

- Python 3.x
- TensorFlow
- Streamlit
- Pillow (for image processing)
- NumPy


## Usage

1. **Run the Streamlit App**:

    ```bash
    streamlit run main.py
    ```

2. **Upload an Image**: Go to the **Disease Recognition** page, upload an image of a plant leaf, and click **Predict**.

3. **View Prediction**: The model will output whether the plant is healthy or the type of disease detected.

---

## Model

The model is a convolutional neural network (CNN) trained using TensorFlow. It was trained on the PlantVillage dataset, which contains over 87,000 images of plant leaves labeled with 38 different disease categories.

---

## Results

The model achieved high accuracy in identifying plant diseases. It is capable of recognizing diseases such as:

- **Apple Scab**
- **Black Rot**
- **Cedar Apple Rust**
- **Corn Gray Leaf Spot**
- **Tomato Bacterial Spot**
- **And many more...**

---

## Kaggle Notebook

You can also check out the **Plant Disease Detection System** notebook on Kaggle:  
[Plant Disease Detection System on Kaggle](https://www.kaggle.com/code/kirolosayman/plant-disease-detection-system-ll)
