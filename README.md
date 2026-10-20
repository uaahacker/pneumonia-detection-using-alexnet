# pneumonia-detection-using-alexnet

Pneumonia detection from chest X-rays using a modified AlexNet CNN in PyTorch, with a Gradio interface on Colab.

By Ubaid Ullah — https://djangix.com/

> Dataset: [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) on Kaggle. Model: modified AlexNet (PyTorch), run in Google Colab with a Gradio interface.

---

# Pneumonia Detection using AlexNet (Google Colab + Gradio)

This project builds a **Pneumonia Detection** system using a modified **AlexNet CNN architecture**. It uses the [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) dataset from Kaggle and runs entirely on **Google Colab** with a **Gradio-based web interface** for real-time predictions.

---

## 🧠 Model Overview

- **Model**: AlexNet (Custom implementation using PyTorch)
- **Dataset**: Chest X-Ray Images (Pneumonia)
- **Interface**: Gradio for real-time predictions
- **Environment**: Google Colab

---

## 🗂 Dataset

- Source: [Kaggle Dataset Link](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- Type: Chest X-Ray images (Normal and Pneumonia)

---

## 📦 How to Run (on Google Colab)

### ✅ Step 1: Open Notebook in Google Colab

### ✅ Step 2: Upload Kaggle API Token

1. Go to [Kaggle Account](https://www.kaggle.com/account)
2. Scroll to **API** section and click **"Create New API Token"**
3. A file named `kaggle.json` will be downloaded
4. In the Colab notebook, run the following cell and upload `kaggle.json`:
