# Neural Network

The neural network of this repository has the below structure.

This network has 2 inputs, a hidden layer with 2 neurons (h1 and h2). and an output layer with 1 neuron (O1). Notice that the inputs for O1 are the outputs from h1 and h2.

# Neurons

A neuron is the fundamental building block of a neural network. Its function involves receiving input signals, performing mathematical computations on these inputs, and generating a single output.

# Forward Propagation

The feedforward process can be summarized as follows:

1.The input data is fed into the input layer of the neural network.

2.The input signals are passed through the first layer of neurons, where they are transformed by a weighted sum of the inputs and biases, and then passed through an activation function.

3.The output of the first layer is then passed as input to the next layer of neurons, where the process is repeated until the final layer is reached.

4.The output of the final layer represents the output of the neural network, which can be used to make a prediction or classification based on the input data.

## Activation Fucntion

An activation function is a mathematical function that is applied to the output of each neuron in a neural network.
The sigmoid activation function is a commonly used activation function in neural networks. It is a mathematical function that maps any input value to a value between 0 and 1, which makes it useful for modeling probabilities or binary classification tasks.

The sigmoid function is defined as:

f(x) = 1 / (1 + exp(-x))

# Backward Propagation

Backpropagation is an algorithm used to train neural networks by adjusting the weights and biases of the neurons in the network in order to minimize the difference between the predicted output and the actual output. It is a form of supervised learning, where the network is given a set of labeled training data and uses this data to learn how to make predictions on new, unseen data.

During the training process, the input data is passed through the neural network using the current weights and biases to compute the output of each neuron. The error between the predicted output and the actual output is then computed with loss function, and this error is used to adjust the weights and biases in the network using the backpropagation algorithm.

## Loss Function

Mean squared error (MSE) loss is a widely-used loss function in machine learning and statistics that measures the average squared difference between the predicted values and the actual target values.

