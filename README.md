# 🚀 Neurathon 2025
# 🧠 Team: DeepThinker
# 🎯Topic: Advancing Optical Coherence Tomography (OCT) Image Analysis  

## 👨‍💻 Team Members  
- **Nilabh Sarmah** (2312079)  
- **Himanshu Dixit** (2312041)  

## 🎯 Problem Statement 3  
**Objective:** Enhance OCT B-scans for improved diagnostic reliability while ensuring structural integrity, generating high-resolution images, and classifying 3D OCT volumes into distinct categories.  

---
## 📈 Project Kaggle Links: 
- https://www.kaggle.com/code/himanshuranjandixit/oct-classifier-model
- Link 2  
## 🛠️ Tech Stack  
<p align="center">
  <img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=tensorflow&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-%2300C7B7.svg?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Flask_logo.svg" alt="Flask" width="100">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="Scikit-learn" width="100">
  <img src="https://img.shields.io/badge/CNN-%234285F4.svg?style=for-the-badge">
  <img src="https://img.shields.io/badge/RNN-%237D3CC8.svg?style=for-the-badge">
</p>  

---

## 🏆 Our Approach  

### 🔹 **1. Image Denoising using Noise2Self & U-Net**  
📌 **Goal:** Remove noise artifacts while preserving retinal layer structures.  
**Architecture:** U-Net-based self-supervised denoising technique.  
  
🖼️ **Before & After Denoising:**  
![OCT Scan](images/denoise.jpg)
🖼️ **Model Summary:**  
![OCT Scan](images/WhatsApp%20Image%202025-02-17%20at%2010.41.31%20PM.jpeg)
---

### 🔹 **2. Super-Resolution Enhancement using SRGAN + CNN**  
📌 **Goal:** Improve OCT image clarity by converting low-res images to high-res using GANs.  

🖼️ **Before & After Comparison:**
**Sample Image:**
![OCT Scan](images/esrgan.jpg)

---

### 🔹 **3. Disease Classification using VGG16 + ResNet Hybrid Model**  
📌 **Goal:** Classify 3D OCT scans into:  
✅ Healthy Individuals  
✅ Diabetic Macular Edema (DME) Patients  
✅ Non-diabetic Patients with Other Ocular Diseases  

🖼️ **Model Predictions:**  

<p align = "center">
  <img src="images/Normal.jpeg" alt="Normal" width="200">
  <img src="images/Drusen.jpeg" alt="DRUSEN" width="200">
  <img src="images/Dme.jpeg" alt="DME" width="200">
  <img src="images/Cnv.jpeg" alt="CNV" width="200">
</p>

<p align="center">
  <b>Normal</b> &nbsp;&nbsp;
  <b>DRUSEN</b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>DME</b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>CNV</b>  &nbsp;&nbsp;&nbsp;
</p>


---

### 🔹 **4. Model Architecture Design (PlantUML)**  
📌 **Goal:** Create a structured UML diagram for clear visualization of our pipeline.  

📎 **[View UML Diagram] Click on the link below 👇🏻(#)**
https://img.plantuml.biz/plantuml/png/bLMnRjim4Dq5w1y8BrLGP4Y73XwAf3O2U2XQn0Kw2WnvaedGfCeZ7HX5_xqdofOfHNBGnPAFzzwzUtU4xj5pvyDUvrcUVM1hg9G1jh8Es6RFQthL714mpqJxmhwlVdRnFtd6s4V7NqiKt2oxx1W3i-D6W1mU_6qBT1nhC5QXClKtAq6Vc7ZJw6FP7i0d15qL8-gRj4IN70pu-RIau3Oqu9u0hGvUMVEsBBgQcq96NKFXatpH4rKfmQVf7219AmzrVVUvcBA3MDUAryQYmg4rv-Y9Zof0RTrnoRRUaMDTq9fAaLW1n4cJMh97RRa_4VL3VFYnOTn8-jjeUzo3yUDXKiOMt469ypW3PN9PgbPZKIaD5xraNsCDTlxNr9qOcD3s7BJ78c9B9S-APrjzfD-NLcDNcaoI6eZcTm3q7SrKzPI1etz3mF5en7_HhAru0RUondEopPteP7IjtBV3BMvYY0OO5Q8DJW2sqQ7Zl-2PROm7Lt41PteAzh6XpS_1UqihyJK-kweA6ysFlPloR5tY8lLni4gEYp-1ZfF0dMh8wVwYBkuMxFRsItoERjwIBPHfWb_asUWa1KtU7eBQu3liP4BAC7LVKeAfyu7i_bQag3nBzlTwbu6MVZ6RFzVWTTHCKzT1_TA_dtbQxaiY3McqgMb-GaEGRdjRr3LCgcRF3MtBkuYBgWiWpmOxFgzAjJbSU6IlokyYyXwCZ5-VVm00


---

### 🔹 **5. Deployment using Docker & FastAPI + Flask**  
📌 **Goal:** Deploy a lightweight & robust web interface for easy access to the model.  
  
🚀 **Live Demo:** **[Click Here](#)**

---

## 📄 Research Papers & References  
- **Noise2Self: Blind Denoising by Self-Supervision** - [Read More](https://arxiv.org/abs/1811.10980)  
- **SRGAN: Super-Resolution Using GANs** - [Read More](https://arxiv.org/abs/1609.04802)  
- **VGG16 & ResNet Hybrid Models in Medical Imaging** - [Read More](https://arxiv.org/) 

---

## 💡 Conclusion  
This project was an incredible journey filled with challenges, innovations, and discoveries. We aimed to push the boundaries of OCT image analysis, ensuring clearer, high-resolution images and accurate disease detection.  

We hope our work receives appreciation and contributes to real-world medical advancements! 🚀🎯  

---
 

