# 🌿Plant Disease Detection System for Sustainable Agriculture
A Convolutional Neural Network (CNN)-based deep learning solution to detect and classify plant diseases using images. This system aims to assist farmers—especially small-scale and rural farmers—in early identification of crop diseases to enable timely intervention and promote sustainable agricultural practices.

# 🚀 Project Overview
Plant diseases can drastically impact food production and economy. Manual identification of diseases is time-consuming and often inaccurate. This project provides an automated tool that leverages CNN to identify various plant diseases through image recognition, supporting better crop health management.

# 🎯 Objectives
- Develop a CNN model to detect and classify plant diseases with high accuracy.
- Apply image preprocessing and augmentation to enhance model generalization.
- Evaluate the model's performance using standard metrics.
- Deploy the trained model via a simple web interface to assist real-world farmers.

# 📁 Dataset Preparation
 # Categories
 - Healthy leaves
 - Diseased leaves (multiple disease classes per crop)

# 🗂️ Directory Structure
```bash
dataset/
  train/
    healthy/
    tomato_blight/
    potato_early/
    ...
  test/
    healthy/
    tomato_blight/
    potato_early/
    ...
```

# 🔄 Image Preprocessing & Augmentation
- Resize images
- Normalize pixel values
- Augmentations:
  - Rotation
  - Horizontal/Vertical flipping
  - Zoom
  - Brightness variation
  - Shifting

# 🏗️ Model Architecture
A custom CNN model composed of:
- Convolutional layers
- Pooling layers
- Dropout layers for regularization
- Fully connected (Dense) layers

# 📊 Model Evaluation
Evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Error analysis on misclassified samples

# 🌐 Deployment
- Web application allows users to upload a leaf image.
- The system returns a prediction: either Healthy or specific Disease Category.
- Provides a user-friendly interface to encourage adoption by farmers.

# 📌 Future Work
- Extend the model to cover more plant species and disease types.
- Mobile application support for in-field diagnosis.
- Integration with advisory systems for treatment suggestions.
