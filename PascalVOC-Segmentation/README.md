# 🧠 Semantic Segmentation with CNNs on PASCAL VOC-2012

**CSE 151B – Deep Learning**  
**Winter 2025 @ UC San Diego**  
**Programming Assignment 2**

- 📄 [View Report (PDF)](./CSE_151B_251B__PA2_W2025.pdf)  
- 🔒 Code available upon request (private repository, per course policy)

---

## 📌 Overview

In this project, we implemented and trained convolutional neural networks (CNNs) for pixel-level classification on the PASCAL VOC-2012 dataset. This involved:

- Constructing fully convolutional architectures (e.g., ResNet-based FCN, U-Net)
- Handling 21-class semantic segmentation using weighted cross-entropy
- Using advanced training techniques like:
  - **Cosine annealing** for learning rate scheduling
  - **Batch normalization** and **Xavier initialization**
  - **Early stopping** and class imbalance handling
- Benchmarking multiple architectures (ResNet backbone vs. custom encoder-decoder)
- Visualizing predictions and analyzing pixel-wise metrics

---

## 👨‍👩‍👧‍👦 Team Members

- **Hikaru Isayama**
- **Avi Mehta**
- **Wilson Liao**
- **Julia Wong**

---

## 🛠 My Contributions (Hikaru Isayama)

- Implemented custom deep encoder-decoder and fine-tuned ResNet-based FCN
- Co-designed training workflow with cosine annealing, batch norm, and early stopping
- Helped tune class-weighted loss to improve per-class segmentation performance
- Created result visualizations and contributed to analysis in the final report

---

## ✅ Results

Achieved **72% pixel accuracy** and **0.1055 mean IoU** on the VOC-2012 validation set. Learned the tradeoffs between parameter count, training stability, and segmentation quality.

---

## ⚠️ Academic Policy

This project was completed for academic credit. Code is not public to preserve course integrity but is available upon request for recruiting purposes.