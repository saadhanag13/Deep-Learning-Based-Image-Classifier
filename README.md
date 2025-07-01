## Fashion MNIST Image Classifier

A deep learning project that uses Convolutional Neural Networks (CNNs) built with TensorFlow/Keras to classify fashion items from the Fashion MNIST dataset. This project demonstrates fundamental knowledge in image processing, neural network design, and model evaluation.

## 📂 Project Overview
Objective: Classify grayscale images (28x28) into 10 categories of fashion items.

Tech Stack: Python, TensorFlow, Keras, NumPy, Matplotlib

Dataset: Fashion MNIST — 70,000 images (60K training, 10K testing)

## 🛠️ Features & Workflow
✅ Data normalization

✅ One-hot encoding for multi-class classification

✅ CNN architecture with Conv2D, MaxPooling, Dropout layers

✅ Model evaluation using accuracy, loss, and visualizations

✅ Clear visualization of test images

✅ Saved trained model as .h5 file

## 🚀 Model Architecture

##### Input Layer: (28x28 grayscale image)→ Reshape → Conv2D (32 filters) → MaxPooling → Conv2D (64 filters) → MaxPooling → Flatten → Dropout(0.25) → Dense(128, relu)→ Dense(10, softmax)

## 📊 Training Results
Training Accuracy: ~99%

Test Accuracy: ~91–93%

Epochs: 5

Loss Function: Categorical Crossentropy

Optimizer: Adam

## 🧑‍💻 Author
#### Saadhana Ganesa Narasimhan
MSc Graduate | Aspiring AI/ML Engineer | Passionate about real-world deep learning applications
