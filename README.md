#Team: DeepThinker
Neurathon - ML Hackathon Submission

#🚀 Project Title: Advancing Optical Coherence Tomography (OCT) Image Analysis

🏆 Participants:

Nilabh Sarmah (2312079)

Himanshu Dixit (2312041)

🔬 Problem Statement 3: OCT Image Analysis

Key Objectives:

✅ Remove noise artifacts from OCT B-scans to enhance image clarity and diagnostic reliability.✅ Maintain the structural integrity of retinal layers during the de-noising process.✅ Generate high-resolution OCT B-scans from low-resolution images to combat motion artifacts and improve diagnostic utility.✅ Preserve fine details critical for early disease detection.✅ Classify 3D OCT volumes into:

Healthy individuals 🏥

Diabetic patients with Diabetic Macular Edema (DME) 🩺

Non-diabetic patients with other ocular diseases 👁️
✅ Achieve high classification accuracy with interpretable results.✅ Develop an end-to-end automated pipeline for OCT image enhancement and disease classification to assist ophthalmologists.

🛠️ Tech Stack

Technology

Description

 TensorFlow

Deep Learning Framework

 PyTorch

Model Development

 Docker

Containerization

 FASTAPI

Model Deployment API

🧠 CNN

Convolutional Neural Networks

🔄 RNN

Recurrent Neural Networks

📌 Our Approach

1️⃣ Denoising using Noise2Self & U-Net 🏗️

Applied Noise2Self for self-supervised denoising.

Integrated U-Net architecture to enhance image quality.

🔽 Placeholder for image comparison (Noisy vs. Denoised vs. Original)

2️⃣ Super Resolution using SRGAN + CNN 🎚️

Implemented SRGAN (Super-Resolution Generative Adversarial Network) to upsample OCT images.

Improved diagnostic utility by enhancing fine details.

🔽 Placeholder for image comparison (Before vs. After Super Resolution)

3️⃣ OCT Image Classification using VGG16 + ResNet Hybrid Model 🏥

Designed a hybrid deep learning model combining:

VGG16 for feature extraction.

ResNet50 for deep representation learning.

Classified images into: Healthy, DME, and Other Ocular Diseases.

🔽 Placeholder for sample OCT images with labels (Normal, DME, DRUSEN, CNV)

4️⃣ Model Architecture & UML Design 🎨

Used Figma and PlantUML to design the system architecture.

UML Diagram showcasing data flow and model pipeline.

🔽 Link to UML Design (Placeholder)

5️⃣ Deployment with Docker, FastAPI, Flask & HTML 🚀

Deployed the end-to-end system using Docker containers.

Built a FastAPI + Flask backend for handling API requests.

Created a minimalistic HTML UI for smooth user interaction.

🔽 Deployed Model Link (Placeholder)

📄 Research Papers & References 📚

Paper 1: Noise2Self for Self-Supervised Denoising

Paper 2: SRGAN for Image Super-Resolution

Paper 3: Hybrid CNN Models for Medical Image Classification

🎉 Conclusion

Throughout Neurathon, we poured in relentless effort, working on cutting-edge AI techniques to enhance and classify OCT images. Our model ensures high-quality image restoration and precise disease classification, paving the way for better ophthalmic diagnostics.

We hope our solution is well-received, and we look forward to valuable feedback from the judges! 🤞✨
