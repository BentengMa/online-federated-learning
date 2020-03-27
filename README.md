# Online federated learning

Private repository for online federated learning.

## Abstract

Federated learning can learn a model from massive client device but does not access the personal data whereon. However, current federated learning methods largely ignored the fact that considerable amounts of new data are collected between uploading gradients. Repeatedly calculating the gradients on historical data may waste large amounts of computational resources and even undermine performance. To address this issue, this paper proposes an {\it online federated learning} to learn models from the data streaming on client devices.

## Datasets

* MNIST
* CIFAR-10
* CIFAR-100

## Model

* ResNet
  * ResNet-18
  * ResNet-101
* VGG
* MobileNet

## Weight update protocol

* Base optimizer
  * SGD
    * Momentum
    * Weight decay
  * Adam
  * Adagrade
  
