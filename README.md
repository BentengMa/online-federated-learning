# Online federated learning on medical data streaming

Private repository for online federated learning.

## Abstract

Federated learning can learn a model from massive client device but does not access the personal data whereon. However, current federated learning methods largely ignored the fact that considerable amounts of new data are collected between uploading gradients. Repeatedly calculating the gradients on historical data may waste large amounts of computational resources and even undermine performance. To address this issue, this paper proposes an {\it online federated learning} to learn models from the data streaming on client devices.

## Datasets

ISIC2018/2019 
Note: These dataset did not split train, valid, and test dataset. We need to split it manually.

## Model

* ResNet
* MobileNet

## Weight update protocol

* Base optimizer
  * SGD
    * Momentum
    * Weight decay
  * Adam
  * Adagrade
  
## Evaluation factor

* Regret

## Compared method

* FedAvg
* FedMA
* Base online learning methods
