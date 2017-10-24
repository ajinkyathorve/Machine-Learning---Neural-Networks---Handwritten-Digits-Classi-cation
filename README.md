# Machine-Learning---Neural-Networks---Handwritten-Digits-Classification

## Synopsis
Python script that uses Machine Learning (Neural Networks) to classify handwritten digits from the MNIST dataset.<br>
This project was done as a part of the CSE 574 course on Machine Learning at SUNY Buffalo.

## Usage
Some details about the project:
<p>1. The MNIST dataset consists of two parts:<br>
&nbsp;&nbsp;&nbsp;&nbsp; i. Training dataset of 60000 handwritten digits<br>
&nbsp;&nbsp;&nbsp;&nbsp; ii. Test dataset of 10000 handwritten digits<br><br>
&nbsp;&nbsp;&nbsp;We divide the original training dataset of 60000 handwritten digits into two parts:<br>
&nbsp;&nbsp;&nbsp;&nbsp; i. An actual training dataset of 50000 handwritten digits<br>
&nbsp;&nbsp;&nbsp;&nbsp; ii. Validation dataset of 10000 handwritten digits<br><br>
&nbsp;&nbsp;&nbsp;Thus, we will be working with a total of three datasets:<br>
&nbsp;&nbsp;&nbsp;&nbsp; i. Training dataset of 50000 handwritten digits<br>
&nbsp;&nbsp;&nbsp;&nbsp; ii. Validation dataset of 10000 handwritten digits<br>
&nbsp;&nbsp;&nbsp;&nbsp; iii. Test dataset of 10000 handwritten digits.
</p>

<p>2. The neural network consists of the following broad steps:<br>
&nbsp;&nbsp;&nbsp;&nbsp; i. Initialize the weights to some random numbers<br>
&nbsp;&nbsp;&nbsp;&nbsp; ii. Feedforward Propagation: In this phase, we have the parameters of the Neural Network and an input feature vector. We compute the probability that this feature vector belongs to a particular digit.<br>
&nbsp;&nbsp;&nbsp;&nbsp; iii. Backpropagation: In this phase, we calculate the error in prediction by comparing our prediction with the actual labels. Then we transmit this error backwards and update the weights accordingly.
</p>

<p>3. The neural network uses a perceptron as its building block. This perceptrom uses a sigmoid function as its activation function. The neural network consists of one hidden layer with 50 nodes. Also, it uses a regularization parameter to avoid the problem of overfitting. The number of nodes in the hidden layer and the regularization parameter can be varied to observe the effects on training time and accuracy.
</p>

<p>4. The script consists of a number of functions for activities like preprocessing, prediction, and other calculations. Appropriate comments in the script explain the various fuctions, as well as their respective inputs and outputs.
</p>

After making any desired modifications, the above script can simply be executed from the command line as shown below.
```sh
python nnScript.py
```

## Useful Links
[MNIST Database](http://yann.lecun.com/exdb/mnist/)<br>
[NumPy](http://www.numpy.org/)<br>
[SciPy](https://www.scipy.org/)<br>
