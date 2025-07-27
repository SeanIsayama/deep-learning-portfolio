# 🧠 Character-Level LSTM for Shakespearean Text Generation

**CSE 151B – Deep Learning**  
**Winter 2025 @ UC San Diego**  
**Programming Assignment 3**

- 📄 [View Report (PDF)](./w25__CSE_151B_251B__PA3.pdf)  
- 🔒 Code available upon request (private repository, per course policy)

---

## 📌 Overview

In this project, we implemented character-level RNN and LSTM models to generate text in the style of Shakespeare using the TinyShakespeare dataset. This involved:

- Implementing RNN and multi-layer LSTM from scratch in PyTorch
- Training models with:
  - **Cross-entropy loss** and **gradient clipping**
  - **Teacher forcing** and **temperature scaling**
  - **Sequence length** and **hidden state tuning**
- Comparing architectures on generation quality and test loss
- Visualizing sample outputs at different training checkpoints

---

## 👨‍👩‍👧‍👦 Team Members

- **Hikaru Isayama**
- **Avi Mehta**
- **Wilson Liao**
- **Julia Wong**

---

## 🛠 My Contributions (Hikaru Isayama)

- Implemented core LSTM training loop and evaluated performance across temperatures
- Hepled tune learning rate, hidden size, and number of layers to reduce loss to **1.378**
- Led the generation and analysis of sample outputs and visualizations for the final report
- Contributed to overall report structure and experimentation design

---

## ✅ Results

Final 3-layer LSTM achieved a **test loss of 1.378**, generating coherent and stylistically consistent Shakespearean text with temperature \( T = 1 \). Explored tradeoffs between model depth, sequence length, and generation quality.

---

## ⚠️ Academic Policy

This project was completed for academic credit. Code is not public to preserve course integrity but is available upon request for recruiting purposes.