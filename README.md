#Medical Image Classification  

## Overview  
This repository contains deliverables for Week 4 of the AI/ML Internship. The tasks focus on using CNNs for medical image classification with two objectives:  
1. Skin Cancer Detection (ISIC Dataset).  
2. Pneumonia Detection (Chest X-Ray Dataset).  

## Tasks Details  

### 1. Skin Cancer Detection  
- **Objective**: Classify skin lesions into benign or malignant.  
- **Model**: ResNet50 with transfer learning.  
- **Techniques Used**:  
  - Data Augmentation: Random rotation, flipping, zooming, etc.  
  - Preprocessing: Resizing to 224x224, pixel normalization.  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score.  

### 2. Pneumonia Detection  
- **Objective**: Classify chest X-rays as pneumonia-positive or negative.  
- **Model**: InceptionV3 with fine-tuning.  
- **Techniques Used**:  
  - Data Augmentation: Cropping, rotation, histogram equalization.  
  - Preprocessing: Resizing to 224x224, pixel normalization.  
- **Evaluation Metrics**: Sensitivity, Specificity, ROC-AUC.  

## Deliverables  
- Python scripts for Skin Cancer and Pneumonia detection models.  
- Reports summarizing performance, insights, and challenges.  
- Saved models for future use.  

## Tools and Libraries  
- TensorFlow/Keras  
- NumPy, Pandas, Scikit-learn  
- Matplotlib, OpenCV  

## Bonus Task  
Includes exploration of ensemble models and hyperparameter tuning for performance improvement.  

## How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/AI-ML-Internship-Week4-Tasks.git
