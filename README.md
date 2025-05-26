
# Brain Tumor Diagnosis using CNN

This project involves detecting brain tumors from MRI images using a Convolutional Neural Network (CNN). It is a binary classification task designed to distinguish between tumor and non-tumor cases.

## Dataset

The dataset used for training and evaluation is publicly available on Kaggle:  
[Brain MRI Images for Brain Tumor Detection – Kaggle](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

The dataset contains a total of 253 labeled MRI images, with 155 images of brains with tumors and 98 images without tumors.

## Model Summary

The model is built using a CNN architecture implemented in TensorFlow/Keras. It includes multiple convolutional and pooling layers, followed by fully connected layers and a final sigmoid output for binary classification.

## Training Details

- **Optimizer:** Adam  
- **Loss Function:** Binary Cross-Entropy  
- **Metric:** Accuracy  
- **Batch Size:** Defined in the code  
- **Validation:** Performed during training to monitor model performance and avoid overfitting

## Results

The model achieved strong accuracy on both training and validation sets. It effectively classifies MRI images into tumor and non-tumor categories using deep learning techniques.
