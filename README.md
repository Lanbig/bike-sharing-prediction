# Build neural network to predict daily bike rental ridership.

<p align="center">
<img src="https://github.com/Lanbig/Project_1_first-neural-network/blob/master/assets/neural_network.png" width="400">
</p>

This dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column. 

<p align="center">
<img align="center" src="https://github.com/Lanbig/Project_1_first-neural-network/blob/master/assets/data.png" width="400">
</p>

## Tasks for implementing models:
* Implement the sigmoid function to use as the activation function. Set self.activation_function in __init__ to your sigmoid function.
* Implement the forward pass in the train method.
* Implement the backpropagation algorithm in the train method,  including calculating the output error.
* Implement the forward pass in the run method.


## Training the network
Choose the number of iterations
Choose the learning rate
Choose the number of hidden nodes

*The more hidden nodes you have, the more accurate predictions the model will make.*

### Set the hyperparameters here ###
* iterations = 20000 
* learning_rate = 0.05
* hidden_nodes = 30
* output_nodes = 1

<p align="center">
<img align="center" src="https://github.com/Lanbig/Project_1_first-neural-network/blob/master/assets/loss_function.png" width="400">
</p>

## Check out your predictions
Here, use the test data to view how well your network is modeling the data. If something is completely wrong here, make sure each step in your network is implemented correctly.

<p align="center">
<img align="center" src="https://github.com/Lanbig/Project_1_first-neural-network/blob/master/assets/predicted_rides.png" width="450">
</p>

The model predicts the data pretty well, except for the last ten days. These days was the holiday and the demand for bike was different from the regular days.
