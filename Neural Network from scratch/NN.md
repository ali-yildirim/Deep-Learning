# Neural Network From Scratch

In this project,  I created a simple network using numPy and other basic libraries. It's meant to just apply some basics of the Neural Networks such as backpropagation, chain rule, activation functions, and some main ideas.


## Model


* Neurons: 2
* Activation Function(s): ReLU
* Input:X 
* Output: Y

<p align="left">$$ \text{* Weights: }  w_1, w_2, w_3, w_4 $$</p>
<p align="left">$$  \text{* Biases: }  b_1, b_2, b_3 $$</p>


<p align="left"><strong>Forward Pass:</strong></p>

<p align="left">$$ a = x \cdot w_1 + b_1 $$</p>
<p align="left">$$ b = x \cdot w_2 + b_2 $$</p>

<p align="left"><strong>Output:</strong></p>

<p align="left">$$ \hat{y} = \text{ReLU}(a) \cdot w_3 + \text{ReLU}(b) \cdot w_4 + b_3 $$</p>
