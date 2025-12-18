# 🩺 Explainable Vision-Language Model for Radiology Reports

**Team Olymp**  
**Central Asian University**

## 👥 Team Members
- **220785** — Haydaraliyev Nurmuhammad  
- **221110** — Madaminov Muhammadamin  

---

## 📌 Project Overview

This project implements an **Explainable Vision-Language Model (VLM)** for radiology that is capable of:

- Analyzing medical images  
- Generating radiology-style textual reports  
- Performing multi-label medical concept classification  
- Providing visual explanations using **Grad-CAM**

The system is designed as a **research and educational prototype** to demonstrate how explainable AI can improve transparency and trust in medical imaging applications.

---

## 🎯 Motivation

Radiology is a critical component of modern healthcare, but:

- Manual interpretation of medical images is time-consuming  
- Radiologists face increasing workloads  
- Many AI systems operate as black boxes  

Our goal is to develop a system that **assists radiologists**, not replaces them, by combining:
- Image understanding  
- Natural language generation  
- Visual explainability  

---

## 📂 Dataset

We use the **ROCOv2 Radiology dataset**, obtained from Hugging Face.

**Dataset features:**
- Medical images  
- Radiology-related captions  
- Suitable for vision-language learning  

The dataset is loaded using:
```python
from datasets import load_dataset

ds = load_dataset("eltorio/ROCOv2-radiology")
