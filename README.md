# Business-problem-using-DNN
Churn model is a tool that is used by banks to predict whether a customer will leave a bank or not depending on many many factors like his/her age, occupation, salary etc. A deep neural network is used for making this tool.
## Basic knowledge of a DNN
It is a class of neural networks with more than one hidden layer 'technically'. But in practice there are many more hidden layers. Each unit of every layer does a summation of weights multiplied by the inputs to that unit. Then an activation function is applied for learning non-linear correlations. The output of one such unit is the input for the next layer. 
## Back-propagating the errors
The output from an output layer is used for calculating the gradient. This gradient is back-propagated for updating weights and biases. Weights and biases get updated by their contribution to the error. An optimisation algorithm like SGD, Adam etc is used for this purpose. <br/>
<br/>
![dnn](https://cdn-images-1.medium.com/max/800/1*dnvGC-PORSoCo7VXT3PV_A.png)
## Activation Functions
* ReLu, sigmoid and tanh are the most popular hidden layer activation functions used.
* For output layer the activation functions used commonly are softmax and sigmoid.
![acativation](https://cdn-images-1.medium.com/max/1600/1*A_Bzn0CjUgOXtPCJKnKLqA.jpeg)
## Installation
### Download the data
* Clone this repository to your computer.
* Get into the folder using cd Business-problem-using-NNs.
### Installing the requirements
* pip install keras
* pip install tensorflow
## Usage
* Run each cell in the ANN.ipynb file
