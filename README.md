## Overview
This project explores different neural network architectures for image classification using the CIFAR-10 dataset.

The objective is to compare the performance of:
- Artificial Neural Networks (ANN)
- Convolutional Neural Networks (CNN)
- Transfer Learning and Fine-Tuning techniques

## Models Implemented
- ANN (Dense layers with flattened input)
- CNN with different geometries (Conv2D, Pooling)
- Transfer Learning using a pretrained CNN and fine-tuning

## Techniques Used
- Data normalization
- Dropout for regularization
- EarlyStopping and ReduceLROnPlateau callbacks
- Hyperparameter experimentation:
  - kernel sizes
  - strides
  - padding

## Results
- ANN achieved limited performance due to loss of spatial information
- CNN significantly improved accuracy by capturing image features
- Transfer Learning provided further performance gains and faster convergence

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Key Learnings
- Importance of spatial information in image tasks
- Impact of CNN architecture design
- Practical use of transfer learning and fine-tuning
