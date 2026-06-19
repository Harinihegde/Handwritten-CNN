# Handwritten CNN Projects

This repository contains two deep learning projects for handwritten image recognition using Convolutional Neural Networks (CNNs) implemented with PyTorch.

The projects focus on building, training, evaluating, and testing CNN models for recognizing handwritten digits and characters.

---

## Projects

## 1. Handwritten Digit Recognition

A CNN-based handwritten digit classification system that recognizes digits from **0-9**.

### Features

- Built a CNN model using PyTorch
- Trained on the MNIST dataset
- Applied data augmentation techniques to improve generalization
- Implemented image preprocessing pipeline using OpenCV
- Tested the model on custom handwritten digit images

### Techniques Used

- Convolutional Neural Networks
- Data augmentation
- Image normalization
- Noise removal
- Thresholding
- Digit cropping and alignment

### Results

- Achieved **99% test accuracy on MNIST dataset**
- Achieved **91% accuracy on custom handwritten digit images**

---

## 2. Handwritten Character Recognition

A CNN-based handwritten alphabet recognition system that classifies English characters from **A-Z**.

### Features

- Built CNN classifier using PyTorch
- Trained on EMNIST Letters dataset
- Implemented preprocessing pipeline for custom handwritten inputs
- Evaluated model performance on real-world handwritten samples

### Techniques Used

- CNN architecture design
- Image preprocessing
- Dropout regularization
- Model evaluation

### Results

- Achieved **94% test accuracy on EMNIST dataset**
- Achieved **70% accuracy on custom handwritten character samples**

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- OpenCV
- NumPy
- Matplotlib

---

## Model Architecture

Both projects use CNN architectures consisting of:

- Convolution layers for feature extraction
- ReLU activation functions
- Max pooling layers for dimensionality reduction
- Dropout layers to reduce overfitting
- Fully connected layers for classification

---

## Project Structure
├── handwritten-digit-recognition/
│ └── Handwritten_Digit_CNN.ipynb
│
├── handwritten-character-recognition/
│ └── Handwritten_Character_CNN.ipynb
│
└── README.md


---

## Learning Outcomes

Through these projects, the following concepts were explored:

- Image classification using CNNs
- Deep learning model training using PyTorch
- Data augmentation techniques
- Image preprocessing using OpenCV
- Model evaluation on custom data
- Improving model generalization

---

## Author

Harini Hegde
