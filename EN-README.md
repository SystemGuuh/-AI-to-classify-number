# AI goals

### Implementation of MLP (Multilayer Perceptron) without Specialized Libraries

- Implement a Multilayer Perceptron (MLP) artificial neural network without using specialized libraries for artificial neural networks.
- One hidden layer will be used.
- Training with the Backpropagation algorithm in its Gradient Descent version.

#### Datasets for Training and Testing

- OR, AND, and XOR datasets for quick correctness tests of the implementation.
- CARACTERES dataset referring to the exercise in L. Fausett's book, including clean and noisy versions.

#### Data Structure

- In logic gates problems, the last column represents the label, while the others are descriptive attributes.
- In the character recognition problem, the last seven columns form the label, allowing different approaches in composing values for label construction.

#### Output Files

- File with the hyperparameters of the neural network architecture and initialization hyperparameters.
- File containing the initial weights of the network.
- File with the final weights of the network.
- File containing the error made by the neural network in each iteration of the training.
- File with the outputs produced by the neural network for each test data.

---

### Implementation of CNN (Convolution Neural Network) with TensorFlow

- Implement a Convolution Neural Network (CNN) with multiple hidden layers and a dense layer at the end of the structure.
- Use the MNIST dataset to test the neural network.

#### Tasks for the MNIST Dataset

- Multiclass task: The neural network should respond correctly to all numbers.
- Binary classification task: The network should be trained to recognize only two selected numbers. The pairs of numbers can vary during the tests.

#### CNN Implementation

- The implementation can be done with a framework of the group's choice.
- The group can choose to use raw data or extracted features, such as HOG descriptor, LBP, Histogram of Blocks, or Haar wavelet transform. One of the approaches must be presented obligatorily, while presenting both is beneficial for the evaluation of the group's work.

#### Output Files

- File containing the hyperparameters of the neural network architecture and initialization hyperparameters.
- File with the initial weights of the network.
- File containing the final weights of the network.
- File with the error made by the neural network in each iteration of the training.
- File with the outputs produced by the neural network for each test data.

For more information about the MNIST dataset, visit: [MNIST Dataset](https://www.tensorflow.org/datasets/catalog/mnist?hl=pt-br)

