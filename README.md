# Convolutional Neural Network (CNN) Demo

This project demonstrates a Convolutional Neural Network (CNN) implementation from scratch using PyTorch. The notebook covers the entire process, from data preparation to model training, evaluation, and testing.

## Key Features

- **Dataset Preparation**:  
  The project includes transformations for converting data into PyTorch tensors and reshaping it for CNN input.

- **Custom Dataset Class**:  
  A `CNNDataset` class is implemented to handle the dataset efficiently, enabling easy batching and shuffling.

- **Model Architecture**:  
  The CNN model is built using PyTorch's `nn.Module`, with layers designed for image classification tasks.

- **Training Pipeline**:  
  The training loop handles forward propagation, backpropagation, and gradient updates, leveraging GPU acceleration when available.

- **Evaluation**:  
  The model's performance is evaluated using metrics such as accuracy and loss, with plots to visualize training progress.

## Objectives

- Understand the architecture and workings of CNNs.
- Learn to implement CNNs using PyTorch.
- Explore training and optimization techniques for deep learning models.


## Usage

1. Load the dataset and apply transformations.
2. Train the CNN model using the provided training pipeline.
3. Evaluate the model performance on a validation/test dataset.
