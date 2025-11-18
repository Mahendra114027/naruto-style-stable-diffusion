# SDXL Fine-Tuning for Naruto-Style Image Generation (LoRA)

This project demonstrates how to fine-tune the **Stable Diffusion XL (SDXL)** model using **LoRA (Low-Rank Adaptation)** to generate images in a **Naruto-inspired anime style**.  
The included notebook provides a complete, resource-efficient training pipeline suitable for **Google Colab**.

---

## 🚀 Project Overview

This repository provides a full workflow for:

- Preparing a Naruto-style training dataset  
- Configuring SDXL for LoRA fine-tuning  
- Training on limited GPU memory
- Saving LoRA weights  
- Running inference to generate new anime-style images  

The pipeline is designed to run even on **Colab T4 GPUs**.

---

### 🏋️ Training Instructions
	1.	Upload your dataset to Google Colab or Google Drive.
	2.	Open and run stable_diffusion_naruto.ipynb.
	3.	Modify configs (learning rate, batch size, LoRA rank) as needed.
	4.	Train until convergence.
	5.	Download your LoRA weights from the output directory.

---
