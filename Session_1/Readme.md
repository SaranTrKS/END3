# END3

### 1 What is a neural network neuron?

Neural network neuron or perceptron is a node or unit in Neral network, it doesn't hold any value but holds and activation function and edges with wieghts.
It takes weights from previous layer's neurons or gives weights to next layer's neurons as input, and computes the activation function. The activation function can be changed to get optimum values of weights. First the values are calculated in activation function then fed formward to next layers. once the final layer is reached we recalculate the weights in backwards with the values of neurons using gradient descend, this is called back propagation. The weights are otimised in this way according to the number of epochs.Neural Network is best suited for non linear prblems with better accuracy.

### 2 What is the use of learning rate?
Learning rate is used to get the optimal values of the weights. while calulating thegradients we multiply learning rate with gradient and subtract it from the previous value of the weight. we do this to mininse the loss function, when we use learning rate the minimal value can be reached much faster or in lesser epochs. 
Keepnig the learning rate in smaller values is suggested as the resultant weight can jump or move away from the minimum values, so learning rate helps to converge in minimum number of steps.

### 3 How are weights initialized?
Weights are initialised randomly with noraml distributiuon. we spcify the mean and standard deviation to control the spread of the randomly initialised weights. The random distribution will give some values to weights intially which will be optimised once the NN is trained.

### 4 What is "loss" in a neural network?







### 5 What is the "chain rule" in gradient flow?
