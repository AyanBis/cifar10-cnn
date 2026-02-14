# CIFAR-10 Image Classification using Convolutional Neural Networks

This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into ten object categories. The model is developed using TensorFlow and Keras and demonstrates the complete deep learning pipeline, including data preprocessing, model training, evaluation, and visualization of performance metrics.

---

## Dataset Information

The CIFAR-10 dataset consists of:

- 60,000 color images
- Image resolution of 32 × 32 pixels
- 10 distinct classes:
  - Airplane
  - Automobile
  - Bird
  - Cat
  - Deer
  - Dog
  - Frog
  - Horse
  - Ship
  - Truck

---

## Model Architecture

The CNN model includes the following components:

- Convolutional layers for feature extraction
- Max pooling layers for spatial dimensionality reduction
- Fully connected dense layers for classification
- Dropout layers to reduce overfitting
- Softmax output layer for multi-class prediction

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Features

- Data normalization and preprocessing
- CNN-based feature extraction and classification
- Training and validation performance monitoring
- Visualization of loss and accuracy curves
- Evaluation on a separate test dataset

---

## Results

The trained CNN model demonstrates effective classification performance on the CIFAR-10 dataset, with consistent generalization between training and testing data.

---

## Project Structure

CIFAR10_CNN_Project/
│── CIFAR-10 CNN.ipynb
│── README.md


---

## How to Run the Project

1. Clone the repository:

git clone https://github.com/yourusername/cifar10-cnn.git


2. Install required dependencies:

pip install tensorflow numpy matplotlib


3. Launch Jupyter Notebook and open the project file.

---

## Future Improvements

- Implementation of deeper architectures such as ResNet or VGG
- Data augmentation for improved generalization
- Hyperparameter optimization
- Transfer learning approaches

---

## Author

Ayan Biswas  
B.Tech Computer Science and Engineering  
AI/ML Researcher and Founder of Infiltrix
