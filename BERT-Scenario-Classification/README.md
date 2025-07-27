# 🧠 Optimizing BERT Representations for Scenario Classification

**CSE 151B – Deep Learning**  
**Winter 2025 @ UC San Diego**  
**Programming Assignment 4**

- 📄 [View Report (PDF)](./W25___CSE_151B_251B___PA4.pdf)  
- 🔒 Code available upon request (private repository, per course policy)

---

## 📌 Overview

In this project, we explored transformer-based architectures and contrastive learning for scenario classification on the Amazon MASSIVE dataset. Key components included:

- Fine-tuning a baseline **BERT** model on 18-class multilingual intent data
- Applying advanced fine-tuning techniques such as:
  - **Stochastic Weight Averaging (SWA)**
  - **Cosine learning rate scheduling**
- Implementing contrastive learning using:
  - **Supervised Contrastive Loss (SupCon)**
  - **SimCLR** with dropout-based augmentation
- Comparing performance across:
  - Standard cross-entropy training
  - Contrastive learning objectives
  - Parameter-efficient finetuning with **LoRA**

---

## 👨‍👩‍👧‍👦 Team Members

- **Hikaru Isayama**
- **Avi Mehta**
- **Wilson Liao**
- **Julia Wong**

---

## 🛠 My Contributions (Hikaru Isayama)

- Fine-tuned BERT with SWA, cosine scheduling, and hyperparameter tuning
- Implemented SupCon and SimCLR training heads with dropout-based augmentation
- Integrated **LoRA** for parameter-efficient finetuning using HuggingFace PEFT
- Led error analysis, visualizations, and final reporting

---

## ✅ Results

- Achieved **91.5% test accuracy** using SimCLR with SWA and cosine decay
- SimCLR outperformed SupCon and standard CE loss in both accuracy and loss
- LoRA models reached near-parity with full finetuning at only **1% trainable params**

---

## ⚠️ Academic Policy

This project was completed for academic credit. Code is not public to preserve course integrity but is available upon request for recruiting purposes.