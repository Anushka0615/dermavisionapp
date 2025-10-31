# 🩺 Deep Learning–Based Classification System for Human Skin Diseases

**Live Demo:** [DermavisionApp on Hugging Face Spaces](https://huggingface.co/spaces/anukhatua15/dermavision)  
**GitHub Repository:** https://github.com/Anushka0615/dermavisionapp.git  

---

## 📘 Project Overview  
This project presents an AI-based system for **automated classification of human skin diseases** using deep learning.  
A lightweight **MobileNetV2** model was trained on the **ISIC 2019 dataset** to identify four common skin disease categories with **88.24 % accuracy**.  

The **DermavisionApp** web interface allows users to upload a skin image and receive instant predictions with confidence scores.  
Additional features include optional patient metadata (age, sex, medical history) and a **“Find a Dermatologist”** locator that redirects users to Google Maps.

---

## 🎯 Objectives  
- Build an accurate CNN-based skin disease classifier.  
- Preprocess and analyze dermatological images for feature extraction.  
- Evaluate performance using Accuracy, Precision, Recall, and F1-Score.  
- Deploy a real-time, user-friendly web app for diagnosis assistance.  

---

## 🧠 Methodology  
- **Architecture:** MobileNetV2 (Transfer Learning)  
- **Loss Function:** Sparse Categorical Cross-Entropy  
- **Optimizer:** Adam (with learning-rate scheduling)  
- **Metrics:** Accuracy | Precision | Recall | F1-Score | Confusion Matrix  
- **Frameworks / Tools:** Python | TensorFlow/Keras | NumPy | Pandas | Matplotlib | Seaborn  
- **Development Environment:** Google Colab / Jupyter Notebook  
- **Deployment Framework:** Flask  

---

## 🧩 Dataset  
- **Dataset Used:** [ISIC 2019 Challenge Dataset](https://www.isic-archive.com)  
- **Classes:** 4 skin disease categories  
- **Preprocessing:** resizing (224×224), normalization, augmentation, class balancing.  

**References:**  
Tschandl et al., *HAM10000 Dataset*, Scientific Data (2018).  
World Health Organization, *Skin Diseases Fact Sheet* (2023).

---

## ⚙️ Model & Performance  
| Metric | Value |
|:--|:--|
| Architecture | MobileNetV2 |
| Accuracy | **88.24 %** |
| Precision | Balanced across classes |
| Recall | Balanced across classes |
| Environment | Google Colab |

- Minor misclassifications between visually similar diseases.  
- Patient metadata improves reliability.  
- Confidence score aids interpretability.  

---

## 🗂️ Repository Structure  
