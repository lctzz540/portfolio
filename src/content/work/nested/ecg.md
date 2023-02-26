---
title: GNN model for ECG5000 dataset
publishDate: 2023-Feb-26
img: /assets/ecg.jpeg
img_alt: description
description: |
  This app is created by myself for encode and storage MCQ question. Users can create their own MCQ question bank to prepare for the exam as well as share it with others to review with just a text file. Currently, many exam questions are stored in the form of traditional text, so taking advantage of it as an application can increase your review performance.
tags:
  - Artificial Intelligent
  - Pytorch
  - Torch Geography
---

My model is a deep neural network designed for ECG classification tasks. It consists of several convolutional layers followed by batch normalization and max pooling operations. The output of the convolutional layers is then flattened and fed into a fully connected layer, which is followed by a softmax activation function to produce the class probabilities. We have used the cross-entropy loss function to optimize the network parameters during training, and the Adam optimizer to update the weights
