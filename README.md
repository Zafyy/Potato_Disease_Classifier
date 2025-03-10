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
Model: "Sequential"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 Resizing (Resizing)         (None, 256, 256, 3)       0         
                                                                 
 Conv2D (Conv2D)             (None, 254, 254, 32)      896       
                                                                 
 MaxPooling2D (MaxPooling2D  (None, 127, 127, 32)      0         
 )                                                               
                                                                 ...(6 conv blocks)...
=================================================================
Total params: 183,747

# 📊 Performance Metrics

Metric	   Training	    Validation	  Test
_________________________________________________________________
Accuracy	  99.48%	      100%	      100%
Loss	      0.0189	      0.0064	    0.0063
