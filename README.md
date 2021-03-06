# Espalier
A feed-forward neural network library that uses the computational graph approach to compute the gradients. This library supports ANNs of arbitrary size as defined by the user.

> Espalier is the horticultural and ancient agricultural practice of controlling woody plant growth for the production of fruit, by pruning and tying branches to a frame - Wikipedia

![Computational Graph](https://colah.github.io/posts/2015-08-Backprop/img/tree-eval-derivs.png)

## Getting Started:

### Prerequisites:
This implementation makes use of just Python and Numpy. Matplotlib was used for testing the network and plotting graphs to observe it's learning.

### Activation functions:
* Sigmoid
* ReLU
* Softmax
* Linear (No activation, only linear transform)

### Loss functions:
* L1 Loss
* L2 Loss
* Cross Entropy
* SVM Loss

### Optimizers:
* SGD
* Momentum

![Computational Graph](https://github.com/achyudhk/Dense-Net/blob/master/doc/accuracy.png?raw=true)

## Contributing:
When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change. Ensure any install or build dependencies are removed before the end of the layer when doing a build. Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.

## License:
This project is licensed under the MIT License - see the LICENSE.md file for details

_(Computational graph image source: https://colah.github.io/)_
