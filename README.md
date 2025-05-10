# 🧠 Cancer Diagnosis with Neural Network

This project demonstrates a simple binary classification task using a neural network to diagnose whether a tumor is malignant or benign based on patient data. The dataset used is a standard breast cancer dataset.

## 📊 Dataset
The model is trained on the Cancer_data.csv

Each sample includes features computed from a digitized image of a breast mass (e.g., radius, texture, perimeter, area, etc.).

## 🧠 Model Architecture
The neural network was built using TensorFlow/Keras and consists of:

- Input layer based on number of features
- Dense layer with 512 units (tanh activation)
- Dense layer with 256 units (sigmoid activation)
- Output layer with 1 unit (sigmoid activation for binary classification)

Loss function: `binary_crossentropy`  
Optimizer: `SGD`  
Metrics: `accuracy`

## 📈 Performance
- Achieved over **98% validation accuracy** after training for 100 epochs.
- Validation loss decreased consistently, indicating good generalization.
- No signs of overfitting were observed.

## 📉 Training Visualization
Model accuracy and loss are plotted per epoch for both training and validation sets.
