# How does a neutral net work
**[Neural networks](https://theconversation.com/what-is-a-neural-network-a-computer-scientist-explains-151897)  are a type of `machine learning model`**
**that are loosely inspired by the human brain.They are composed of nodes or "neurons" organized in layers,**
**and they learn patterns from data by adjusting the strength of connections, or "weights", between these neurons.Let's break this down a bit**

# Neurons and Layers
**Each neuron takes some input, performs a simple operation on it, and produces an output. In the case of neural networks,
the input to a neuron is the output of several other neurons from the previous layer, each multiplied by a `weight`.**

**The first layer of the neural network is called the input layer, and it is responsible for receiving the raw input data. 
The last layer is the output layer, and it produces the final output of the model.** 

# Activation Functions
**Each neuron applies an "activation function" to the weighted sum of its inputs.
The activation function is a mathematical function that introduces non-linearity into the model, enabling it to learn complex patterns.**

# Forward Propagation
**The process of calculating the output of a neural network by passing the input data through each layer is called forward propagation.
 For each neuron, the outputs of the previous layer (or the input data for the first layer) are multiplied by the weights, summed, and then the activation function is applied.**
 
# Cost Function
**In order to learn from data, the neural network uses a `cost function` (also called a loss function) to measure how far off its predictions are from the actual values.
The goal of learning is to minimize this cost function.**

# Backward Propagation (Backpropagation)
**Backpropagation is the process by which neural networks learn. 
 It involves calculating the gradient of the cost function with respect to each weight in the network, which indicates how much changing that weight would affect the cost.
 Then, each weight is adjusted in the opposite direction of its gradient to decrease the cost. 
 This process is repeated many times, each time using a new batch of data, until the network performs well.**
 
 # Optimizers
 **Optimizers are algorithms used to change the attributes of your neural network such as weights and learning rate in order to reduce the losses.
 Optimizers help to get results faster.**
 
![](/images/logo.png "fast.ai's logo")
