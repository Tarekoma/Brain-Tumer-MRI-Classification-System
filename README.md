<div align="center">

# 🧠 Brain Tumor Classification using MRI
### An AI-Powered Deep Learning System for Brain Tumor Detection

**Enhancing diagnostic accuracy, reducing human error, and accelerating medical decision-making — empowering radiologists, not replacing them.**

</div>

---

## 📖 Overview

The **Brain Tumor Classification System** is an AI-driven medical imaging tool designed to detect and classify brain tumors from MRI scans using deep learning. It leverages the **MobileNet** architecture to automatically distinguish between four tumor types with high precision, supporting neurologists, oncologists, and radiologists in making faster and more reliable diagnoses.

> 🎬 Video Demo : **[Watch Video Demo](https://1drv.ms/v/c/47438efdb3ee2559/IQDpOt93IP4dQLvBiS0qZZRcAfrgs1ixCbQgwYIY4-jany8?e=JMRJNk)**

> 🔬 Colab Notebook : **[View Colab Notebook](https://colab.research.google.com/drive/1Bu1ZigCHqkvk4IWmleBegZMP_G3AYLyH?usp=sharing)**

---



## 🔍 Problems We Solve

| # | Problem |
|---|---------|
| 1 | Manual MRI interpretation is time-consuming and prone to human error |
| 2 | Delayed tumor detection leads to missed early-stage treatment windows |
| 3 | Limited access to specialist radiologists in remote and underserved areas |
| 4 | Inconsistent classification results across different medical professionals |
| 5 | High computational cost of traditional deep learning models for real-time use |

---

## ✨ Core Features

### 🤖 AI Capabilities

| Feature | Description |
|---|---|
| 🧠 **Tumor Classification** | Classifies MRI scans into 4 categories: Glioma, Meningioma, Pituitary, and No Tumor |
| ⚡ **MobileNet Architecture** | Lightweight depthwise separable convolutions for fast, efficient inference |
| 🎯 **High Accuracy** | Achieves **91.6%** accuracy, outperforming standard CNNs (84.1%) |
| 🩻 **MRI & CT Support** | Processes both MRI and CT scan images for flexible clinical use |
| 🔄 **Benign vs. Malignant** | Distinguishes between benign and malignant cases with high precision |

### 🏥 System Capabilities

- 📁 Processes and classifies brain MRI images automatically
- 📊 Trained on **7,023 labeled images** across 4 tumor classes
- 🚀 Optimized for **real-time and mobile applications** due to lightweight design
- 🖥️ User-friendly interface for seamless integration into clinical workflows
- 📈 Supports treatment planning and tumor progression tracking

---

## 🗂️ Dataset Description

| Property | Detail |
|---|---|
| 📦 **Total Images** | 7,023 MRI scans |
| 🏋️ **Training Set** | 5,712 images |
| 🧪 **Testing Set** | 1,311 images |
| 🏷️ **Classes** | Glioma · Meningioma · Pituitary · No Tumor |
| 🔗 **Source** | [Kaggle — Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) |

---

## 🤖 Model Comparison

| Model | Accuracy |
|---|---|
| ✅ **MobileNet** *(chosen)* | **91.6%** |
| 🔷 Xception | 91.6% |
| ⬜ Standard CNN | 84.1% |

> ⚙️ MobileNet was selected for its **efficiency and speed** without sacrificing accuracy — making it ideal for real-time clinical deployment on resource-constrained devices.

---

## 🏥 Applications

| Application | Description |
|---|---|
| 🏨 **Hospitals & Clinics** | Assists radiologists, neurosurgeons, and oncologists in tumor detection and classification |
| 📡 **Telemedicine** | Enables remote diagnosis and second opinions for better accessibility |
| 💊 **Personalized Treatment** | Helps doctors track tumor progression and optimize individual treatment plans |

---

## 🚀 Implementation Plan

1. **Data Collection** — Sourced 7,023 labeled MRI images across 4 tumor categories from Kaggle
2. **Preprocessing** — Image normalization, augmentation, and train/test splitting
3. **Model Selection** — Benchmarked MobileNet, Xception, and standard CNNs
4. **Training** — Fine-tuned MobileNet on the brain tumor dataset via Google Colab
5. **Evaluation** — Validated accuracy, precision, and recall on the 1,311-image test set
6. **Deployment** — Integrated model into a user-friendly diagnostic interface

---

## 🎯 Objectives

- ✅ Automate brain tumor detection from MRI scans using deep learning
- ✅ Achieve classification accuracy exceeding traditional CNN baselines
- ✅ Deliver a lightweight, real-time-ready model suitable for clinical environments
- ✅ Support early detection to improve patient outcomes in neurology and oncology
- ✅ Reduce diagnostic workload and human error for medical professionals

---

## 👥 Team

| Name | Role |
|---|---|
| Tarek Omar | Team Leader |
| Beshoy Osama | ML Engineer |
| Amira Kamal | Web Developer |
| Abdallah Gaber | Data Scientist |
| Youssef Moustafa | Data Scientist |

---
