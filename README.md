<h1 align="center">
  <a href=#>
    <img src="https://github.com/zalandoresearch/fashion-mnist/blob/master/doc/img/embedding.gif" width="50%"/>
  </a>  
  <br>
  Fashion MNIST Classifier
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vcwild/fashion-mnist-classifier">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/vcwild/fashion-mnist-classifier">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
  <a>
</p>

## Implementation
- [Notebook](Fashion_MNIST_Classification.ipynb)
- [Underlying Model1](model_checkpoints/fashion_mnist_cnn_model.h5)
- [Underlying Model2](model_checkpoints/fashion_mnist_cnn_model2.h5)
- [Underlying Model3](model_checkpoints/fashion_mnist_cnn_model3.h5)


## Scoring

### With Model 1

Training accuracy: 0.9207
Testing accuracy: 0.8900

### With Model 2 (Best)

Training accuracy: 0.9245
Testing accuracy: 0.9100

### With Model 3

Training accuracy: 0.7800
Testing accuracy: 0.8200


## Summary
### Model

Following three models are experimented in this project: 
<img src='images/models.png'/> 

### Optimizer

Adam (SGD)\
Adam optimization is a stochastic gradient descent method that is based on adaptive estimation of first-order and second-order moments.

### Loss Function

Sparse categorical crossentropy
