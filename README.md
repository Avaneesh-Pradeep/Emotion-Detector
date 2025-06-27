# Facial-Emotion-Detector

This project trains a Convolutional Neural Network using transfer learning to recognize facial expressions across seven categories (Happy, Sad, Angry, etc.). The model leverages EfficientNet-B0 via PyTorch's `timm` library.

---

## Objective
To fine-tune a pretrained CNN model to classify images of facial expressions using a labeled dataset.

---

## Approach
- Preprocessed input images using **Albumentations** and OpenCV with transformations like resizing and flipping
- Fine-tuned a pretrained **EfficientNet-B0** model using PyTorch and the `timm` library
- Used **weighted cross-entropy loss** to address class imbalance
---

## Results
- Achieved **~71%** validation accuracy
- Model performed best on clear expressions like *Happy* and *Neutral*

---

## Acknowledgment
This project is based on a **guided project from Coursera**: *“Facial Expression Recognition with PyTorch”*
The notebook was extended and fine-tuned as part of independent learning.

---

## 🛠️ Technologies
- Python
- PyTorch
- Albumentations, OpenCV
- timm (EfficientNet models)
