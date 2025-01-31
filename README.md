# Neural Networks: Zero to Hero by Andrej Karpathy 🧠🚀

This repository contains my Jupyter Notebook files on the neural networks course taught by [Andrej Karpathy](https://github.com/karpathy). The course covers neural network basics and progresses to more advanced topics. Each lecture is represented as a Jupyter Notebook file (.ipynb).

[YouTube playlist](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)

[Andrej's Repo](https://github.com/karpathy/nn-zero-to-hero)

## Lectures 📚

### Lecture 1: The spelled-out intro to neural networks and backpropagation: building [micrograd](https://github.com/karpathy/micrograd)</strong>
    
- Introduction to gradients and calculating the slope of a function using small increments (numerical differentiation)
- Recreating micrograd (Value class) to create mathematical expressions that can be automatically backpropagated
- Visualizing mathematical expressions with a computational graph composed of the operations tracked by micrograd
- Manual backpropagation for a simple neuron model and its activation function (tanh)
- Backpropagate using pytorch.
- Building a basic neural network (multi-layer perceptron) from scratch using micrograd and applying the tanh activation function.
- Using the neural network for a simple dataset and performing forward and backward passes (training) to minimize the loss (squared error) through gradient descent.


### Lecture 2: The spelled-out intro to language modeling: building [makemore](https://github.com/karpathy/makemore)
    
- Bigram Generation:
    1. Creating bigrams from the dataset and counting their occurrences.
    2. Visualizing the bigram frequency using a heatmap.
- Probability Calculations:
    1. Initializing probability matrix 'P' based on bigram counts for each character.
    2. Smoothing the model to prevent zero probabilities. (Opcional)
    3. Generating new words using the trained model.
- Model Quality Evaluation:
    - Calculating the likelihood and negative log likelihood of the data with respect to model parameters.
- Neural Network Approach - Bigrams:
    1. Building a simple neural network for bigram prediction.
    2. Performing a forward pass using random weights and one-hot encoding.
    3. Exponentiating log counts to obtain counts and converting to probabilities using softmax.
- Optimization:
    1. Implementing gradient descent to optimize the neural network.
    2. Incorporating regularization to the loss function.
- Sampling from the trained neural network to generate new words.
