# Neural-Network-Project---Multilayered-Perceptron-trained-with-Backpropagation

This project is a Neural Network (Machine Learning) implementation that performs supervised learning (Classification problem) using python programming language. It is an implementation of Multilayered Perceptron trained with Backpropagation. The implementation was tested on two datasets (Image Recognition Task Execution Times in Mobile Edge Computing and RasberryPI) from the UCI Machine Learning repository. 

As this project is a low-level implementation of the neural network architecture and the backpropagation method. Data preprocessing was conducted in order to prepare the datasets for the classification (Regression) task. This implementation compares two activation functions (the Sigmoid function and the Hyperbolic Tangent function) in order to measure their effect on the performance of the Neural Network in performing the classification task.

The project was implemented in such a way it asks the user to input the following: the number of hidden layers within the neural network, the number of epochs, the batch size, the learning rate, and the momentum. The implementation also prompts the user to select either of the activation functions (1= Sigmoid Function and 2 = Hyperbolic Tangent function). 

After inputting the above-mentioned parameters: the Neural Network trains the data, tests the data, and prints out the output (expected outcome, predicted outcome, mean error, train data set Loss value calculation, test error, and some plots i.e. visualizations). 

Since the project was implemented using python, the following python libraries were used: Numpy, Pandas, MatplotLib, and seaborn. 

At the end of the implementation, the implementation recorded a 90% prediction accuracy.
