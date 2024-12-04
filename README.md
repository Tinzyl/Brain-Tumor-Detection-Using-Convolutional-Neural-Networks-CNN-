# 🧠 Brain Tumor Detection Using Convolutional Neural Networks (CNN)

This project implements a binary classification model using CNNs to detect brain tumors from grayscale MRI images. The model classifies images into **Brain Tumor** or **Healthy** categories.

---

## 🌟 Project Highlights

- **Dataset Preprocessing**: Rescaled images and applied grayscale transformation. 🖼️
- **Custom CNN Model**: Developed a CNN for binary classification. 🤖
- **High Accuracy**: Achieved **99.3% validation accuracy** after training. 📈
- **Model Deployment Ready**: Saved the trained model for future use. 💾

---

📊 **Data Overview**

Dataset:

MRI images categorized into two folders: Brain_Tumor and Healthy.

Images are resized to 150x150 and converted to grayscale.

Classes: Binary classification (Brain_Tumor, Healthy).

🤖 **Model Details**

Architecture:

Input Layer: 150x150 grayscale image.

Convolutional Layers: Two convolutional layers with ReLU activation.

Pooling Layers: Max pooling layers for down-sampling.

Dense Layers: Fully connected layer with 512 neurons.

Dropout: Applied 20% dropout to prevent overfitting.

Output Layer: Binary classification using sigmoid activation.

Loss Function: Binary Cross-Entropy

Optimizer: Adam

🧪 **Model Performance**

Training Accuracy: 99.7%

Validation Accuracy: 99.3%

Loss Trend: Validation loss converged within 5 epochs.
