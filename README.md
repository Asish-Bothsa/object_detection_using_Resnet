# 🧠 Object Detection using ResNet

This project demonstrates object detection using a ResNet-based deep learning model. The entire workflow is implemented in a Jupyter Notebook using **Google Colab with a free T4 GPU**, enabling fast and scalable model training and inference.

---

## 🚀 Project Overview

This project aims to detect objects in images using a pretrained **ResNet** (Residual Network) model. It leverages deep learning techniques to recognize and classify multiple objects and draw bounding boxes around them in an image.

Key Highlights:
- Built and tested using **Google Colab** with **T4 GPU**
- Leverages **Transfer Learning** using a pretrained ResNet model
- Efficient visualization of bounding boxes on test images
- Clean and modular implementation in a single Jupyter notebook

---

## 📁 Files Included

- `Object_detection_using_Resnet.ipynb` — The core notebook containing:
  - Data loading
  - Model definition using ResNet
  - Training and evaluation steps
  - Output visualization

---

## 🔍 Features

- 📦 Transfer Learning with pretrained **ResNet**
- ⚡ GPU-accelerated training via **Google Colab**
- 🧪 Easy to test on custom images
- 💡 Code comments and modular cells for easy understanding

---

## 💻 How to Run

> No setup needed if using Google Colab.

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Enable GPU via **Runtime > Change runtime type > Hardware accelerator: GPU**.
3. Run the notebook cells step by step.

Alternatively, run locally:

```bash
git clone https://github.com/yourusername/object-detection-resnet.git
cd object-detection-resnet
pip install -r requirements.txt
jupyter notebook Object_detection_using_Resnet.ipynb

- Framework:TensorFlow/Keras