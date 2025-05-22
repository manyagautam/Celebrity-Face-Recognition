# Celebrity Face Recognition using VGGFace Model

Welcome to the **Celebrity Face Recognition** project! This repository demonstrates a deep learning-based face recognition system using the **VGGFace** model. The system identifies and verifies celebrity faces from a dataset using pre-trained facial embeddings.

---

## 🔍 Project Overview

This project is designed to detect and recognize celebrity faces from images using transfer learning and the VGGFace model architecture. Built and tested in Google Colab, it automates the process from dataset loading and preprocessing to model evaluation and prediction.

> ✅ **Live Environment**: Built and tested in Google Colab using TensorFlow/Keras  
> 📁 **Dataset**: [Kaggle - Celebrity Faces Dataset](https://www.kaggle.com/datasets/)

---

## 🚀 Features

- 💡 **Deep Learning Powered**: Uses VGGFace (based on VGG16) for accurate face embeddings.
- 📦 **Dataset Handling**: Automatically fetches, extracts, and prepares the celebrity face dataset.
- 📸 **Face Embedding**: Generates embeddings to compare and classify faces.
- 🧠 **Recognition Pipeline**: Face detection → Embedding → Classification.
- 📊 **Highly Modular**: Cleanly structured code to plug-and-play different models or datasets.
- 📈 **Scalable**: Suitable for extending to real-time recognition or custom datasets.

---

## 🛠️ Tech Stack

- Python 3.9+
- TensorFlow / Keras
- VGGFace (via `keras-vggface`)
- Google Colab
- NumPy, Matplotlib, shutil, urllib, zipfile

---

## 🧪 How It Works

1. **Data Download & Preprocessing**  
   Downloads celebrity face images from a Kaggle-hosted ZIP file, extracts them, and prepares them for training.

2. **Embedding Extraction**  
   Uses VGGFace (pre-trained on millions of faces) to extract facial embeddings.

3. **Model Training**  
   Embeddings are used to train a classifier (e.g., SVM or KNN) to identify which celebrity is in the image.

4. **Prediction**  
   Given a new input image, the model predicts which celebrity the face most closely resembles.

---

## 📌 Project Highlights (Why It’s Resume-Worthy)

- 🎯 Demonstrates practical application of **transfer learning** in facial recognition.
- 🔁 Hands-on with real-world data preprocessing and automation.
- 🤖 Showcases skills in **computer vision, neural networks, and data engineering**.
- ✅ Built for scalability and production-ready adaptation.

---

## 📂 Repository Structure

```bash
Celebrity_Face_Recognition_VGGFace_Model/
│
├── Celebrity_Face_Recognition_VGGFace_Model.ipynb  # Main Google Colab notebook
├── README.md                                        # Project documentation
└── requirements.txt                                 # Dependencies (optional)
