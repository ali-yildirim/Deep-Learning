<h3 style="text-align: center;">Model</h3>

<ul class="centered-list" style="text-align: center;">
  <li><strong> Neurons:</strong> 2</li>
  <li><strong> Activation Function(s):</strong> ReLU</li>
  <li><strong> Input:</strong> \( X \)</li>
  <li><strong> Output:</strong> \( Y \)</li>
  <li><strong> Weights:</strong> \( w_1, w_2, w_3, w_4 \)</li>
  <li><strong> Biases:</strong> \( b_1, b_2, b_3 \)</li>
</ul>

<p style="text-align: center;"><strong>Forward Pass:</strong></p>

<p style="text-align: center;">$$ a = x \cdot w_1 + b_1 $$</p>
<p style="text-align: center;">$$ b = x \cdot w_2 + b_2 $$</p>

<p style="text-align: center;"><strong>Output:</strong></p>

<p style="text-align: center;">$$ \hat{y} = \text{ReLU}(a) \cdot w_3 + \text{ReLU}(b) \cdot w_4 + b_3 $$</p>