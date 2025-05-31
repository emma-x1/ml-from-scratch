# neural-network

Based on Andrej Karpathy's Micrograd tutorial

Micrograd is an autograd engine that performs backpropogation, similar to PyTorch. 
Given a function with multiple inputs, it computes the gradient (derivative) with respect to each input.

This is the heart of a neural network - if we can compute the derivative of an output WRT inputs, we can tune the hyperparameters to approach a function minimum