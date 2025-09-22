# Pet Image Classification

This project applies deep learning to classify pet images using the **Oxford-IIIT Pet Dataset**.

## 🚀 Methods
- **Data Preparation:** FastAI DataBlock API with regex-based labeling.  
- **Data Augmentation:** Flipping, lighting adjustments, zoom.  
- **Models:** ResNet18 and ResNet34 via transfer learning.  
- **Training:** One-cycle learning rate policy, learning rate finder, fine-tuning.  
- **Optimization:** Mixed precision training for efficiency.  
- **Evaluation:** Confusion matrix, most confused classes.  

## 🧠 Concepts Learned
- Transfer learning with pretrained CNNs.  
- Data augmentation for robustness.  
- Hyperparameter tuning with learning rate scheduling.  
- Error analysis to identify model weaknesses.  
