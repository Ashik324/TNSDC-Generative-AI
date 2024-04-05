# TNSDC-Generative-AI
# CIFAR-10 Image Classification with TensorFlow and Keras

This repository contains code for training a convolutional neural network (CNN) using TensorFlow and Keras to classify images from the CIFAR-10 dataset. Additionally, it includes code for visualizing the training process and displaying sample images from the dataset.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**: First, clone this repository to your local machine using the following command:

    ```bash
    git clone https://github.com/yourusername/cifar10-image-classification.git
    ```

2. **Install Dependencies**: Before running the code, make sure you have the necessary dependencies installed. You can install them using pip:

    ```bash
    pip install tensorflow matplotlib
    ```

3. **Run the Code**: Navigate to the project directory and run the Python script:

    ```bash
    cd cifar10-image-classification
    python cifar10_classification.py
    ```

## Description

The `cifar10_classification.py` script loads the CIFAR-10 dataset, defines a CNN architecture using TensorFlow's Keras API, trains the model, and visualizes the training process along with sample images from the dataset.

## Model Architecture

The model architecture is as follows:

- Input Layer: 32x32x3 RGB images
- Convolutional Layer: 32 filters, kernel size (3,3), ReLU activation
- Max Pooling Layer: Pool size (2,2)
- Convolutional Layer: 64 filters, kernel size (3,3), ReLU activation
- Max Pooling Layer: Pool size (2,2)
- Convolutional Layer: 64 filters, kernel size (3,3), ReLU activation
- Flatten Layer
- Fully Connected Layer: 64 units, ReLU activation
- Output Layer: 10 units (corresponding to class labels)

## Results

After training the model, the script visualizes the training and validation accuracy over epochs using matplotlib. It also displays a grid of 25 sample images from the CIFAR-10 dataset along with their corresponding class labels.

## Dataset

The CIFAR-10 dataset contains 60,000 images categorized into 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Acknowledgments

This project is based on TensorFlow and Keras documentation and tutorials. The CIFAR-10 dataset is provided by the Canadian Institute for Advanced Research (CIFAR).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project by opening issues or pull requests. If you have any questions or suggestions, don't hesitate to contact us. Thank you for your interest in our work!
