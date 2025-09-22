# Head Pose Estimation (Regression)

This project applies CNN regression to estimate head positions using the **BIWI Head Pose Dataset**.

## 🚀 Methods
- **Data Preparation:** Extracted head pose coordinates from `.pose.txt` files.  
- **Calibration:** Used calibration data to compute correct coordinates.  
- **DataBlock:** `ImageBlock` + `PointBlock` for regression tasks.  
- **Augmentation:** Resizing, normalization with ImageNet stats.  
- **Model:** ResNet18 with `y_range` constraints.  
- **Training:** One-cycle learning rate policy.  

## 🧠 Concepts Learned
- Regression with CNNs (predicting 2D coordinates).  
- Designing custom label extraction functions.  
- Splitting validation sets by subject (generalization).  
- Visual evaluation of regression outputs.  
