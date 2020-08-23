# NNtime
Building a Neural Network from scratch ? Python3

1. Reading about NNs and what they actually are

https://deepai.org/machine-learning-glossary-and-terms/neural-network#:~:text=An%20artificial%20neural%20network%20learning,output%2C%20usually%20in%20another%20form.


NN = neuron  
Piece of program that takes an input, uses network of functions to translate input into output  
No need to hard code characteristics, just give it training data, labeling what is needed and train it on it.  
Functionsn needs to be accurate and useful i.e. abstract the data, pinpoint certain data features etc. e.g. cat = 2 eyes 1 nose 1 mouth round head 2 ears  


https://medium.com/towards-artificial-intelligence/building-neural-networks-from-scratch-with-python-code-and-math-in-detail-i-536fae5d7bbf#478a  
Good medium article  

A perceptron is NN with on iL and oL no hL.  
Used for simple decision makings e.g. access denial  

Steps involved in implementation of a neural network  
1. Feedforward, where input data and random weighs are given. The random weighs are then optimized using backpropagation.  
2. Backpropagation, error calculation between predicted out and target out then use algo ( gradient descent ) to update the weight values.  

Summary:
1 Take inputs.    
2 Add bias (if required).    
3 Assign random weights to input features.    
4 Run the code for training.  
5 Find the error in prediction.  
6 Update the weight by gradient descent algorithm.  
7 Repeat the training phase with updated weights.  
8 Make predictions.  
