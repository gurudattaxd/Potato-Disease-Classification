# Potato-Disease-Classification
This deep learning project applies Convolutional Neural Networks (CNNs) to image classification of potato leaves into three classes: Healthy, Early Blight, and Late Blight. Based on pattern analysis in the leaves, the model detects diseases with high accuracy, enabling farmers and researchers to act early and prevent loss of crops.


• Achieved 95% accuracy in detecting Healthy, Early Blight, and Late Blight conditions.

• Deployed using FastAPI & TensorFlow Serving for real-time inference with 30% reduced latency.


# Sample Results 

![image](https://github.com/user-attachments/assets/8af139bf-b9aa-40f6-9758-36c51f3e8fb9)



# Project Overview

Potato plants are prone to fungal infections like Early Blight and Late Blight, which can severely affect crop yield. This project aims to:

• Train a Convolutional Neural Network (CNN) to classify potato leaves into three categories:
  🟢 Healthy
  
  🟠 Early Blight
  
  🔴 Late Blight

• Achieve high accuracy using TensorFlow and data augmentation techniques.
• Deploy the model using FastAPI for real-time predictions.


# Tools Used

🔹 Programming: Python, TensorFlow, Scikit-learn

🔹 Deep Learning: Convolutional Neural Networks (CNNs)

🔹 Data Processing: Pandas, OpenCV, NumPy

🔹 Deployment: FastAPI, TensorFlow Serving

🔹 Visualization: Matplotlib, Seaborn



# Dataset Details

The dataset consists of 2,152 labeled images, categorized as:
🟢 Healthy: 152 images

🟠 Early Blight: 1,000 images

🔴 Late Blight: 1,000 images


Dataset source: https://www.kaggle.com/datasets/faysalmiah1721758/potato-dataset


# Model Architecture & Training

• Used Convolutional Neural Network (CNN) with 3 convolutional layers, ReLU activation & MaxPooling.
• Optimized using Adam optimizer & Categorical Crossentropy loss.
• Applied Batch Normalization & Dropout (0.5) to reduce overfitting.

Training Performance: 
• Achieved 95% accuracy on test data.
• Used TensorFlow data augmentation to improve generalization.


#  Results & Real-World Applications

• Can be integrated into agriculture apps for automated disease detection.
• Helps farmers detect infections early, reducing crop loss.


# Contact & Acknowledgments

Created by Gurudatta Bidkar
Email: gurudattaxd@gmail.com


