# MNIST Classifier

This repository contains an MNIST digit classification model built using deep learning. The model is trained on the MNIST dataset to recognize handwritten digits (0-9).

## Features
- Loads and preprocesses the MNIST dataset
- Builds an optimized deep learning model
- Trains and evaluates the model on the MNIST dataset
- Saves the trained model for later use

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mnist-classifier.git
   cd mnist-classifier
   ```
   Ensure you have Python and necessary libraries such as TensorFlow or PyTorch installed.

## Usage

1. Run the Jupyter Notebook to train and evaluate the model:
   ```bash
   jupyter notebook 3_MNIST_Classification.ipynb
   ```
2. Follow the notebook steps to preprocess the data, build the model, train it, and evaluate the performance.

## Model Architecture
The model consists of multiple layers optimized for MNIST digit recognition. It includes:
- Convolutional layers
- Fully connected layers
- Activation functions
- Optimizers and loss functions

## Results
After training, the model achieves 98.3% accuracy in recognizing handwritten digits. Evaluation metrics such as accuracy and loss are displayed in the notebook.

## Saving and Loading Model
The trained model is saved for reuse. You can load it for predictions without retraining.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.
