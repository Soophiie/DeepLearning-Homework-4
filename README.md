# Homework 4 — Image Restoration  
**Visual Recognition using Deep Learning**  
**Sophie FU (Student ID: 313554802)**

---

## Task Description

The goal of this assignment is to restore clean images from degraded inputs affected by synthetic **rain and snow** artifacts.  

Given a dataset of paired images (degraded / clean), the objective is to train a model **from scratch** (no pretrained weights) to perform **image-to-image restoration**. The final output is a `.npz` file containing the restored test images in the same shape and order as the inputs.

Evaluation is based on the **Peak Signal-to-Noise Ratio (PSNR)** metric via Codabench submission.

---

## How to Run

Run the notebook using **Google Colab**.  
Before starting, mount your Google Drive and make sure the dataset is located in:
Otherwise, change the `dataset_root` path in the notebook.

---

## Requirements

This project was developed and tested with:

- Python ≥ 3.8  
- PyTorch ≥ 1.12  
- torchvision ≥ 0.13  
- NumPy  
- Matplotlib  
- OpenCV  
- tqdm  
- PIL  
- Google Colab (GPU enabled)

Optional for metrics/experiments:
- scikit-image
- lpips (if perceptual metrics are considered)

## Performance snapchot
<img width="724" alt="image" src="https://github.com/user-attachments/assets/c37ac0b2-d393-45ce-8cbf-aa2a9e4451b5" />


