# AI-CA5-P1: Image Classification using Feed Forward Neural Networks

## Project Description

This is Project No.5, and its aim is to implement Forward Feed neural networks for classifying images. In Forward Feed neural networks, each image is first flattened and given as a vector as network input. Each element of this vector (equivalent to one pixel of the image) represents a property of the image, and the goal is to predict the corresponding input image class correctly.

For this project, images are used to train and test the model. The values of each pixel in the images are in the range between 0 to 255.

## Phase One: Data Preprocessing

To prepare the data for the neural network, the following steps are taken:

1. The dataset is split into training and testing sets using a test size of 33%.

2. The data is scaled so that the value of each pixel is between 0 and 1 before feeding it to the neural network. This data normalization is essential as it helps speed up learning and leads to faster convergence. Not normalizing the data can lead to issues such as getting stuck in flat regions in the domain or numerical problems.

## Phase Two: Completion of incomplete parts of the neural network

### Dataloader Class

The `Dataloader` class is responsible for preparing the dataset for the neural network. It takes the dataset information, including features and labels, the number of classes, batch size, and whether to shuffle the dataset.

### Activation Functions

Several activation functions are implemented for the neural network, including:
- Identical
- Relu
- LeakyRelu
- Sigmoid
- Softmax
- Tanh

### Cross-Entropy Loss Function

The `CrossEntropy` class represents the cross-entropy loss function, which measures the difference between two probability distributions. It is commonly used in neural networks.

## Phase Three: Data Classification

### Training Sample Code

Sample code for building and training a neural network model is provided. It includes setting up the input shape, defining the architecture of the neural network, and specifying the learning rate and activation function.

### Network Weighting

The sample code is run with different learning rates to observe the effects on training and testing accuracy and loss. This helps determine the optimal learning rate for the model.

### Activation Function Effect

The sample code is run with different activation functions to observe their effects on the model's performance.

### Batch Size Effect

The sample code is run with different batch sizes to evaluate how batch size impacts training and testing results.

-Note: If you want dataset, you can contact me.
