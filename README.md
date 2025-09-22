# Machine Learning & Deep Learning Projects

This repository contains three projects developed in Python using Jupyter Notebooks.  
They explore **computer vision, classification, and regression tasks** using PyTorch & FastAI.

---

## 📂 Projects Overview

### 1. Pet Image Classification (Single-Label Classification)
- **Dataset:** Oxford-IIIT Pet Dataset  
- **Techniques:**  
  - Transfer Learning (ResNet18, ResNet34).  
  - Data augmentation (flips, lighting, zoom).  
  - Mixed precision training (`to_fp16()`).  
  - One-cycle learning rate policy.  
- **Concepts Explored:**  
  - FastAI DataBlock API.  
  - Error analysis (confusion matrix, most confused classes).  
  - Architecture & hyperparameter comparison.  

---

### 2. PASCAL VOC 2007 Multi-Label Classification
- **Dataset:** PASCAL VOC 2007 (objects with multiple labels per image).  
- **Techniques:**  
  - Multi-category classification (`MultiCategoryBlock`).  
  - Custom label parsing from CSV.  
  - Custom splitter for train/validation sets.  
  - Data augmentation with RandomResizedCrop.  
- **Concepts Explored:**  
  - Multi-label learning with one-hot encodings.  
  - Interpreting predictions for multiple classes.  
  - Training CNNs for complex image datasets.  

---

### 3. Head Pose Estimation (Regression)
- **Dataset:** BIWI Head Pose Dataset.  
- **Techniques:**  
  - CNN regression with `PointBlock`.  
  - Custom label extraction from calibration files.  
  - Subject-based validation splitting.  
  - Data normalization & augmentations.  
- **Concepts Explored:**  
  - Using CNNs for regression tasks (predicting coordinates).  
  - Handling custom datasets.  
  - Visual evaluation of predictions.  

---

## 🛠️ Tools & Libraries
- **Python**  
- **PyTorch**  
- **FastAI**  
- **Scikit-learn, Pandas, Numpy**  
- **Matplotlib, Seaborn**  

---

## 📊 Skills Demonstrated
- Single-label & multi-label classification.  
- CNN regression for pose estimation.  
- Data preprocessing & augmentation.  
- Transfer learning & fine-tuning.  
- Model evaluation & interpretation.  
- Experimentation with architectures & hyperparameters.  
