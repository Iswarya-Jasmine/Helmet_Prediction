# 🪖 Helmet Detection System

A **Deep Learning–based Helmet Detection System** built using **TensorFlow/Keras**, **OpenCV**, and **Gradio** to identify whether a rider is wearing a helmet or not. This project aims to improve road safety and support smart traffic monitoring systems.

---

## 📌 Project Overview

Not wearing a helmet is one of the major causes of fatal injuries in road accidents. This project uses a **Convolutional Neural Network (CNN)** to classify images of two-wheeler riders into:

* ✅ **Helmet** – Rider is wearing a helmet
* ❌ **No Helmet** – Rider is not wearing a helmet

The system includes:

* A deep learning model for image classification
* A Gradio-based web interface for easy testing
* Google Colab–friendly implementation

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
| Test  |  70    |  84       |

---

## 📸 Demo Screenshots

### Gradio Web Interface

![Gradio UI](screenshots/UI.jpg)

### Helmet Prediction Example

<img src="screenshots/helmet.jpg" width="700"/>  

### No Helmet Prediction Example

<img src="screenshots/no_helmet.jpg" width="700"/>  

---

## 🚀 How to Use

1. Open the provided Jupyter Notebook in **Google Colab**
2. Load or train the model
3. Run the Gradio interface cell
4. Upload an image of a bike rider
5. The system will predict **Helmet / No Helmet**

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
* Gradio
* Google Colab

---

## 👩‍💻 Author

**[Your Name]**
*(Replace with your actual name)*

---

If you want, I can also:

* ✅ customize this README for **your exact dataset**,
* ✅ align it specifically with your **uploaded Notebook (`Helmet_detection.ipynb`)**, or
* ✅ format it perfectly for **GitHub**.

Just tell me 👍
