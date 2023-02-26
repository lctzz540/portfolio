---
title: GNN model for ECG5000 dataset
publishDate: 2023-Feb-26
img: /assets/ecg.jpeg
img_alt: description
description: |
  GNN Deep Learning model I have developed for research
tags:
  - Artificial Intelligent
  - Pytorch
  - Torch Geometric
---

My model is a deep neural network designed for ECG classification tasks. It consists of several convolutional layers followed by batch normalization and max pooling operations. The output of the convolutional layers is then flattened and fed into a fully connected layer, which is followed by a softmax activation function to produce the class probabilities. We have used the cross-entropy loss function to optimize the network parameters during training, and the Adam optimizer to update the weights

Github repository: <https://github.com/lctzz540/ECG-Pytorch>
