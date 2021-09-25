

# END3 Assignment 1

### 1 What is a neural network neuron?

Neural network neuron or perceptron is a node or unit in Neral network, it doesn't hold any value but holds and activation function and edges with weights.
It takes weights from previous layer's neurons or gives weights to next layer's neurons as input, and computes the activation function. The activation function can be changed to get optimum values of weights. First the values are calculated in activation function then fed forward to next layers. once the final layer is reached we recalculate the weights in backwards with the values of neurons using gradient descend, this is called back propagation. The weights are optimised in this way according to the number of epochs.Neural Network is best suited for non linear problems with better accuracy.

### 2 What is the use of learning rate?
Learning rate is used to get the optimal values of the weights. while calculating the gradients we multiply learning rate with gradient and subtract it from the previous value of the weight. we do this to minimise the loss function, when we use learning rate the minimal value can be reached much faster or in lesser epochs. 
Keeping the learning rate in smaller values is suggested as the resultant weight can jump or move away from the minimum values, so learning rate helps to converge in minimum number of steps.

### 3 How are weights initialized?
Weights are initialised randomly with normal distribution. we specify the mean and standard deviation to control the spread of the randomly initialised weights. The random distribution will give some values to weights initially which will be optimised once the NN is trained.

### 4 What is "loss" in a neural network?

The deviation from the calculated output from the original output is called loss. The loss can be mean square error or root mean square error. It is usually the difference between the expected output and calculated output.


### 5 What is the "chain rule" in gradient flow?
To minimise the loss, we recalculate the all weights in all layers of NN. while we recalculating the weights the partial derivatives of the loss function is used. As loss function is dependent on the other weights, we need to calculate its partial derivative. to do this, we use chain rule where we differentiate from the last layer to the first layer. This is chain rule.  
