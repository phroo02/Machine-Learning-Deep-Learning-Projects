# PASCAL VOC Multi-Label Image Classification

This project applies deep learning for **multi-label classification** using the PASCAL VOC 2007 dataset.

## 🚀 Methods
- **Data Preparation:** Custom `get_x` and `get_y` functions for images and multi-label targets.  
- **DataBlock:** `ImageBlock` + `MultiCategoryBlock`.  
- **Splitters:** Custom function based on CSV validation column.  
- **Augmentation:** Random resized crops and transformations.  
- **Model:** ResNet18 backbone with transfer learning.  

## 🧠 Concepts Learned
- Multi-label classification with one-hot vectors.  
- Parsing structured datasets (CSV → labels).  
- Importance of custom data splitters.  
- Applying data augmentation to complex datasets.  
