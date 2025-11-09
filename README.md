# CIFAR-10-MLP-Baseline
This notebook was developed for **AA 5750: Contemporary Issues in Analytics (Deep Learning Module)**.   It explores how simple multilayer perceptrons (MLPs) perform on the CIFAR-10 dataset before moving to CNNs.

This work focuses on concept mastery and experimentation rather than code optimization.  The notebook retains its original structure and outputs to reflect the authentic academic workflow.

## Overview
- **Dataset:** CIFAR-10 (60 000 images, 10 classes)  
- **Model:** MLP with hidden layers [640, 320, 160]  
- **Regularization:** Dropout + BatchNorm  
- **Optimizer:** Adam (lr = 1e-3)  
- **Result:** ≈ 53 % test accuracy  

## Concepts Covered
- Dataset loading & transforms via `torchvision`
- Model definition and training loops in PyTorch
- Comparative optimizer performance (SGD vs Adam)
- Overfitting control using Dropout and BatchNorm
- Accuracy tracking and loss visualization

## How to Run
**Colab:** Upload `AA5750_Week_2.ipynb` and run top-to-bottom (no setup needed).  
**Local:**
```bash
pip install -r requirements.txt
jupyter notebook AA5750_Week_2.ipynb
