# A Simple Neural Network for Linear Regression

In this README, I'll explain a simple neural network using the libraries in Python.

## Model

<details>
<summary><strong>Details</strong></summary>

<details>
<summary><strong>Neurons:</strong> 2</summary>

- **Activation Function(s):** ReLU
- **Input:** \( X \)
- **Output:** \( Y \)
- **Weights:** \( w_1, w_2, w_3, w_4 \)
- **Biases:** \( b_1, b_2, b_3 \)
</details>

<details>
<summary><strong>Forward Pass:</strong></summary>

$$
a = x \cdot w_1 + b_1
$$

$$
b = x \cdot w_2 + b_2
$$

</details>

<details>
<summary><strong>Output:</strong></summary>

$$
\hat{y} = \text{ReLU}(a) \cdot w_3 + \text{ReLU}(b) \cdot w_4 + b_3
$$

</details>

</details>
