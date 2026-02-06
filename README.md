# 🪖 Helmet Detection System

A **Deep Learning–based Helmet Detection System** built using **TensorFlow/Keras** and **OpenCV** to identify whether a rider is wearing a helmet or not. This project aims to improve road safety and support smart traffic monitoring systems through a **Google Colab live demo**.

---

## 📌 Project Overview

Not wearing a helmet is one of the major causes of fatal injuries in road accidents. This project uses a **Convolutional Neural Network (CNN)** to classify images of two-wheeler riders into:

* ✅ **Helmet** – Rider is wearing a helmet
* ❌ **No Helmet** – Rider is not wearing a helmet

The system includes:

* A deep learning model for image classification
* **Live image upload and prediction inside Google Colab**
* Real-time detection output with bounding boxes and text results

---

## 🧠 Model Details

* **Architecture:** Custom CNN
* **Input Size:** 224 × 224 RGB image
* **Output Classes:**

  * `Helmet`
  * `No Helmet`
* **Loss Function:** Binary Crossentropy
* **Optimizer:** Adam
* **Regularization:** Dropout + Data Augmentation
* **Framework:** TensorFlow / Keras

---

## 📊 Dataset Structure

```
helmet_dataset/
├── train/
│   ├── helmet/
│   └── no_helmet/
└── test/
    ├── helmet/
    └── no_helmet/
```

### Class Distribution

| Split | Helmet | No Helmet |
| ----- | ------ | --------- |
| Train | 280    | 330       |
| Test  | 70     | 84        |

*(Train–test split created manually from the Kaggle dataset.)*

---

## 📸 Demo Screenshots

### Google Colab Live Demo

![Colab UI](helmet/output.jpg)

### Helmet Prediction Example

<img src="helmet/img1.jpg" width="700"/>  

### No Helmet Prediction Example

<img src="helmet/img2.jpg" width="700"/>  

---

## 🚀 How to Use (Colab Live Demo)

1. Open the provided **Helmet_detection.ipynb** in **Google Colab**
2. Run all cells sequentially
3. Use the **Colab upload widget** to upload an image
4. The model will process the image and display:

   * The detected image with bounding boxes
   * Text output: **“Helmet detected” / “No helmet detected”**

> **Note:** If your trained model file is large, store it in Google Drive and load it in Colab.

---

## ⚠️ Limitations

* Works best on clear images with visible riders
* Performance may drop in low light, blur, or crowded scenes
* Intended for **educational and demonstration purposes only**

---

## 🧾 Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* Google Colab

---

## 👩‍💻 Author

**[Iswarya Jasmine]**




* align this **exactly with your uploaded notebook (`Helmet_detection.ipynb`)**, or
* add a **Results & Accuracy section**, or
* format this perfectly for **GitHub README** with badges and icons.
