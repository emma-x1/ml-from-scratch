# Under construction - notebooks for learning ML from scratch

Credit goes to Neel Nanda's GPT 2 from scratch, and Andrej Karpathy's Micrograd

# Originally: autograd-engine

Based on Andrej Karpathy's Micrograd tutorial

Micrograd is an autograd engine that performs backpropogation, similar to PyTorch. 
Given a function with multiple inputs, it computes the gradient (derivative) with respect to each input.

This is the heart of a neural network - if we can compute the derivative of an output WRT inputs, we can tune the hyperparameters to approach a function minimum.
When we do this with respect to the loss function, we train a neural network towards desired output.
