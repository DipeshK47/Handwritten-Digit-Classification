# Handwritten Digit Classification using ANN on MNIST Dataset

This repository contains a project that demonstrates how to classify handwritten digits from the MNIST dataset using Artificial Neural Networks (ANN). The MNIST dataset is a well-known dataset containing images of handwritten digits (0-9) with corresponding labels.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project uses an ANN model to classify handwritten digits from the MNIST dataset. The project includes data preprocessing, model training, evaluation, and visualization of the results. This is a great starting point for understanding how to work with neural networks and image classification tasks.

## Dataset

The MNIST dataset consists of:

- 60,000 training images and 10,000 testing images.
- Each image is a 28x28 grayscale pixel image.
- Labels range from 0 to 9, representing the corresponding digit.

You can download the dataset from [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/mnist) or [Kaggle](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv).

## Model Architecture

The ANN model used in this project consists of:

- An input layer with 784 neurons (28x28 pixels flattened).
- One or more hidden layers with fully connected neurons.
- An output layer with 10 neurons, representing the digits 0-9.

The model uses activation functions such as ReLU and softmax, and the training process is optimized using an appropriate loss function and optimizer.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/DipeshK47/Handwritten-Digit-Classification.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd handwritten-digit-classification-ann
    ```

3. **Install the required dependencies**:

    You can create a virtual environment and install the dependencies using the provided `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To train the ANN model:

1. Run the jupyter notebook.

2. This script trains the model on the training set and evaluates it on the test set.

## Results

The trained model achieves a certain level of accuracy on the test set. Specific performance metrics (e.g., accuracy, loss) and visualizations (e.g., confusion matrix, sample predictions) can be found in the results notebook.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a branch for your feature or bugfix.
3. Commit your changes.
4. Push the branch and open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

                        
