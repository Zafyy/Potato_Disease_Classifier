# 🥔 Potato Disease Classification System  
**A Deep Learning Solution for Agricultural Health Monitoring**  

![TensorFlow](https://img.shields.io/badge/TensorFlow-2.12.0-orange)
![License](https://img.shields.io/badge/License-MIT-blue)
![Accuracy](https://img.shields.io/badge/Test_Accuracy-100%25-brightgreen)

## Prediction Example
![image](https://github.com/user-attachments/assets/e607769e-5f0f-4766-8db6-fec42d0c5c9f)


A production-ready CNN model that classifies potato leaf diseases with 100% accuracy. Built with TensorFlow/Keras, this system helps farmers detect Early Blight, Late Blight, and Healthy plants through leaf image analysis.

## ✨ Key Features
- **Real-time Data Augmentation** - Flip/Rotation transforms
- **Optimized CNN Architecture** - 6-layer convolutional network
- **Model Interpretability** - Prediction confidence visualization
- **Cross-Format Export** - .h5 & SavedModel support

# 🧠 Model Architecture

A 6-layer convolutional neural network (CNN) designed for potato disease classification. Built with TensorFlow/Keras, this architecture achieves high accuracy while maintaining computational efficiency.

## Key Features

- **Input Preprocessing:**  
  - Automatic resizing to 256x256  
  - Normalization

- **Convolutional Blocks:**  
  - 6 Conv2D layers with ReLU activation

- **Downsampling:**  
  - MaxPooling2D layers for feature reduction

- **Output Layer:**  
  - Softmax activation for 3-class classification

- **Total Parameters:**  
  - 183,747 trainable parameters

# 📊 Performance Metrics

The model achieves state-of-the-art performance on the PlantVillage potato disease dataset, demonstrating robust generalization across training, validation, and test sets.

### Key Results

- **Training Accuracy:** 99.48%
- **Validation Accuracy:** 100%
- **Test Accuracy:** 100%

- **Training Loss:** 0.0189
- **Validation Loss:** 0.0064
- **Test Loss:** 0.0063
