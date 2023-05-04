# Learning-Activations-in-Neural-Networks
The structure and operation of biological neural networks serve as the basis for artificial neural networks (ANNs), which are computational models. ANNs are employed in a variety of applications, such as classification, regression, and prediction. We will give an example of creating an ANN in Python using a softmax activation function, a categorical cross-entropy loss function, one hidden layer, and back propagation in this report.  The neural network is given nonlinearity through the application of activation functions, which enables it to simulate intricate interactions between input and output variables. The softmax function ensures that the sum of all output values is equal to 1 and converts each input value to a value between 0 and 1. In the output layer, this function is frequently used to solve multi-class classification issues.

The neural network's performance can be evaluated using the loss function. The categorical cross-entropy loss function, which is frequently employed for multi-class classification issues, is what we used in this example. The difference between the output values that were predicted and the actual output values is measured by the categorical cross-entropy loss function.  A procedure called backpropagation is employed to train the neural network. The backpropagation algorithm updates the weights in the neural network by first calculating the gradient of the loss function with respect to each weight.
In this instance, we have applied the backpropagation techniques described below:
•	To determine the output values for each sample in the training set, use forward propagation.
•	Make a loss function calculation using the output values.
•	Utilise the chain rule to determine the gradient of the loss function with respect to each weight in the neural network.
•	Update the neural network's weights using the gradients.

In order to train the neural network, we followed these procedures:
•	Randomise the neural network's weights and biases upon initialization.
•	repeat for a predetermined number of epochs.
•	For each sample in the training set, carry out forward propagation.
•	Make a loss function calculation using the output values.
•	Update the weights in the neural network through backpropagation.
•	For the given number of epochs, repeat steps 3-5.

A dataset made up of 100 randomly selected samples and 10 input features was used to train the neural network. Three categories were created from the output. One hidden layer of the neural network contained 5 neurons. The number of epochs was set to 500, and the learning rate was set to 0.01.

Epoch 0, Loss: 1.2587
Epoch 100, Loss: 1.1907
Epoch 200, Loss: 1.1536
Epoch 300, Loss: 1.1325
Epoch 400, Loss: 1.1193

The loss function decreased with each epoch, indicating that the neural network was learning to classify the input data accurately.

