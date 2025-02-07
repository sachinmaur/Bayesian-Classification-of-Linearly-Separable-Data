# Bayesian-Classification-of-Linearly-Separable-Data
**Statistical Pattern Recognition - CS616 / CS612 Assignment 1 🔬**\
  This repository contains the implementation of Bayes Classifiers for Classification Tasks in Statistical Pattern Recognition (CS616 / CS612 Lab). The assignment focuses on implementing classification models from scratch, analyzing decision boundaries, and evaluating performance using various metrics.\
🚀 **Assignment Overview**\
The task is to build Bayes classifiers with different covariance matrix assumptions on three datasets:\
🟢 Dataset 1: Linearly separable classes (3 classes, 2D)\
🔵 Dataset 2: Nonlinearly separable classes (2 or 3 classes, 2D)\
🟡 Dataset 3: Real-world vowel dataset (2D - formant frequencies F1 and F2)
📌 **Classification Methods**\
We assume Gaussian class-conditional densities and build four different Bayes Classifiers:\
1️⃣ Same covariance matrix across all classes (σ²I - diagonal matrix)\
2️⃣ Full covariance matrix (Σ) shared across all classes\
3️⃣ Diagonal covariance matrix, different for each class\
4️⃣ Full covariance matrix, different for each class
📊 **Performance Metrics**\
The evaluation includes:\
✅ Confusion Matrix\
✅ Classification Accuracy\
✅ Precision, Recall, F1-score (Per-Class & Mean)\
✅ Constant Density Contour Plots\
✅ Decision Region Plots (For Each Dataset & Class Pairs)
##📖 **Mathematical Formulation & Theory**\
##**🔹 Bayes Theorem:**\
A Bayesian classifier is based on posterior probabilities computed as:\
$$P(C_k | x) = \frac{P(x | C_k) P(C_k)}{P(x)}$$


