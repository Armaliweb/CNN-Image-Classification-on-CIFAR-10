# CNN Image Classification on CIFAR-10

This repository contains the implementation and report for **Project #4 – CNN Image Classification**, part of the CSC 4301 *Introduction to Artificial Intelligence* course (Spring 2024).

---

## Overview
The goal of this project is to train **Convolutional Neural Networks (CNNs)** to classify images from the **CIFAR-10 dataset** (60,000 32×32 color images across 10 classes).  
We experimented with multiple architectures and hyperparameters to improve performance and studied how machines "learn to see" the world.

---

## Team
- Chaimae Attouch  
- Nisrine Noussi  
- Wijdane Khaoua  

**Supervisor:** Prof. Rachidi Tajjeddine  

---

##  Contents
- `report/` — Project report (PDF/Markdown)  
- `notebooks/` — Jupyter notebooks with model implementations  
- `results/` — Accuracy plots, confusion matrices, and logs  
- `README.md` — Project overview and setup instructions  

---

## 🛠️ Implementation
We built three different CNN models:
1. **Model 1** – Baseline CNN with convolution, pooling, and dense layers.  
2. **Model 2** – Improved CNN with more filters, batch normalization, and dropout.  
3. **Model 3** – Deeper CNN with regularization and larger convolution blocks.  

Hyperparameters explored:
- Learning Rate
- Dropout Rate
- Optimizer (Adam, RMSprop, SGD, etc.)
- Batch Size

---

##  Results
- Best performing model: **Model 2**  
- Training accuracy: ~65%  
- Test accuracy: ~43%  
- Extensive experiments showed that optimal hyperparameters **individually** do not always combine into the best collective performance.  

---

## Demonstration
Watch the project video presentation here:  
👉 [YouTube Video](https://youtu.be/VliIBF64Wbs?si=ynVbe-l7LyPvufL8)

---

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/cnn-cifar10.git
   cd cnn-cifar10
