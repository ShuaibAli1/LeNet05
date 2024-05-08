# Optimized LeNet-5 Model on MNIST Dataset

This project implements an optimized version of the classic LeNet-5 convolutional network model to recognize handwritten digits from the MNIST dataset. Enhancements include batch normalization and improved initialization, targeting higher accuracy.

## Project Structure

- `model.py`: Contains the code for the model architecture and training.
- `requirements.txt`: Lists all the necessary Python libraries.
- `train.ipynb`: Jupyter notebook for training the model in a step-by-step format.

## Model Description

The LeNet-5 model used in this project is a convolutional neural network that includes several layers:
- Convolutional layers with ReLU activation and He uniform initializer.
- Average pooling layers to reduce spatial dimensions.
- Batch normalization layers to stabilize and speed up training.
- Dense layers with softmax activation for classification.

