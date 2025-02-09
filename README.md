# Bayesian-Classification :
This repository contains the implementation of Bayes Classifiers for Classification Tasks in Statistical Pattern Recognition. The assignment focuses on implementing classification models from scratch, analyzing decision boundaries, and evaluating performance using various metrics.

🚀  **Assignment Overview**\
The task is to build Bayes classifiers with different covariance matrix assumptions on three datasets:

🟢 **Dataset 1**: Linearly separable classes (3 classes, 2D)\
<img width="656" alt="figr5" src="https://github.com/user-attachments/assets/db50a2d6-5342-499c-8723-06109d52b7e4" />

🔵 **Dataset 2**: Nonlinearly separable classes (2 or 3 classes, 2D)\
<img width="653" alt="LSD 4 c" src="https://github.com/user-attachments/assets/913a6c49-52b3-4061-b3cf-27e37ec454f2" />

🟡 Dataset 3: Real-world vowel dataset (2D - formant frequencies F1 and F2)

📌 **Classification Methods**\
We assume Gaussian class-conditional densities and build four different Bayes Classifiers:

1️⃣ Same covariance matrix across all classes (σ²I - diagonal matrix)\
2️⃣ Full covariance matrix (Σ) shared across all classes\
3️⃣ Diagonal covariance matrix, different for each class\
4️⃣ Full covariance matrix, different for each class

📊 **Performance Metrics**\
The evaluation includes:

✅ Confusion Matrix\
✅ Classification Accuracy\
✅ Precision, Recall, F1-score (Per-Class & Mean)\
✅ Constant Density Contour Plots\
✅ Decision Region Plots (For Each Dataset & Class Pairs)





🔹 Decision Boundaries
Decision surfaces between classes are formed using log-likelihood ratios, computed from the Gaussian densities.
For same covariance assumption, decision boundaries are linear.
For different covariance matrices, boundaries become quadratic.
