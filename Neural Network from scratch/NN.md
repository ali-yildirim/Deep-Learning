# Model

<h3 align="center">Model</h3>

* Neurons: 2
* Activation Function(s): ReLU
* Input:X 
* Output: Y
* Weights: $$ w_1, w_2, w_3, w_4 $$
* Biases:> $$  b_1, b_2, b_3 $$

<p align="center"><strong>Forward Pass:</strong></p>

<p align="center">$$ a = x \cdot w_1 + b_1 $$</p>
<p align="center">$$ b = x \cdot w_2 + b_2 $$</p>

<p align="center"><strong>Output:</strong></p>

<p align="center">$$ \hat{y} = \text{ReLU}(a) \cdot w_3 + \text{ReLU}(b) \cdot w_4 + b_3 $$</p>
