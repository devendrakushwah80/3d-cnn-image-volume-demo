# 3D CNN Image Volume Demo

This project demonstrates how a simple **3D Convolutional Neural Network (Conv3D)** can be applied to image data by converting a 2D image into a 3D volume.

## 📌 Overview

* A single image is loaded and resized
* The image is stacked multiple times to simulate a 3D volume
* A basic 3D CNN model is built using TensorFlow/Keras
* The model processes the volume and outputs a prediction

This project is useful for understanding:

* 3D Convolutions
* Volumetric data processing
* Basics of deep learning with Conv3D

---

## 📂 Project Structure

```
├── 3D_CNN_Image_Volume_Demo.ipynb
├── Dog.png
├── requirements.txt
└── README.md
```

---

## ⚙️ Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🚀 How It Works

1. Load an image using OpenCV
2. Resize it to a fixed dimension
3. Normalize pixel values
4. Stack the image to create a 3D volume
5. Pass the volume through a Conv3D model

---

## 🧠 Model Architecture

* Conv3D Layer
* MaxPooling3D Layer
* GlobalAveragePooling3D
* Dense Layer

---

## 📊 Output

* Model summary
* Prediction output from the network

---

## 🧪 Use Cases

* Medical imaging (MRI, CT scans)
* Video processing
* 3D object recognition

---

## ⚠️ Note

This is a **demo project** for learning purposes and does not perform real classification training.

---

## 👨‍💻 Author

Devendra Kushwah
