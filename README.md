# Build neural network to predict daily bike rental ridership.

![Neural Network](https://github.com/Lanbig/Project_1_first-neural-network/blob/master/assets/neural_network.png?raw=true)

This dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column. 

![data - number of rides](https://github.com/Lanbig/Project_1_first-neural-network/blob/master/assets/data.png?raw=true)


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

![Training loss VS Validation loss](https://github.com/Lanbig/Project_1_first-neural-network/blob/master/assets/loss_function.png?raw=true)


## Check out your predictions
Here, use the test data to view how well your network is modeling the data. If something is completely wrong here, make sure each step in your network is implemented correctly.


![Predicted VS Actual values](https://github.com/Lanbig/Project_1_first-neural-network/blob/master/assets/predicted_rides.png?raw=true)

The model predict the data pretty well, except for the last ten days. These days was the holiday and the demand for bike was different from the regular days.