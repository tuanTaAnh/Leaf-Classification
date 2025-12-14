# Leaf Classification (Maize Leaf Disease)

This repository contains a Convolutional Neural Network (CNN) project for **maize leaf disease classification**, developed as part of the **M507C – Methods of Prediction** coursework.

The project focuses on analyzing how different **training strategies and architectural choices** affect model performance under a **limited dataset setting**.

---

## Project Overview

- **Task:** Multi-class image classification of maize leaf conditions
- **Classes:**
  - Blight
  - Common Rust
  - Gray Leaf Spot
  - Healthy
- **Model:** Custom CNN (TensorFlow / Keras)
- **Dataset size:** ~4,200 images  
  - Train: ~2,900  
  - Validation: ~670  
  - Test: ~600  

---

## Key Features

- Controlled experimental design with **10 experiments**
- Comparison of:
  - Optimizers (SGD vs Adam)
  - Learning rates
  - Dropout regularization
  - Activation functions
  - Architectural changes
- Data augmentation for improved generalization
- Detailed evaluation using:
  - Accuracy / loss curves
  - Confusion matrix
  - Classification report
- Visual data exploration:
  - Class distribution
  - Brightness distribution by class

---

## Best Model Summary

- **Optimizer:** Adam  
- **Learning rate:** 1e-4  
- **Dropout:** 0.5  
- **Data augmentation:** Flip, rotation, zoom, brightness
- **Test accuracy:** ~83%

The results show that **training strategy and regularization** have a stronger impact than increasing model complexity.

**Ta Anh Tuan**  
Course: *M507C – Methods of Prediction*  
GitHub: tuanTaAnh
