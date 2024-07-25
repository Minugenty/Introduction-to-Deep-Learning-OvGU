# Introduction to Deep Learning - OvGU

This repository contains the solutions for programming exercises submitted as part of the course Introduction to Deep Learning offered by the AI Lab group of the Faculty of Informatik in OvGU, Magdeburg

## 1. Let the Tensors flow

- Implemented and trained first deep model on the well-known MNIST image classification task. Familiarize yourself with the Tensorflow library.

## 2. Let the Tensors board?

- Got to know TensorBoard, Tensorflow’s built-in visualization suite, and used it to diagnose some common problems with training deep models. 

## 3. Keras and CNN

- Got to know Keras, the high-level neural network API in Tensorflow. Also created a better model for the MNIST dataset using convolutional neural networks.

## 4. ResNets

- Experimenting ResNet on CIFAR-10 

## 5. Text Classification with RNNs (Part 1)

 - Experimented how to assign a single label to input sequences of arbitrary length - text. 
 - Implemented RNNs at the low level. 
 - Explored the kinds of problems that arise when working with sequence data, specifically text.

 ## 6. Text Classification with RNN (Part 2)

 - Experimented on ways to improve the previous implementation. 
 - Implemented RNN using Keras to simplify the code. 
 - Used more advanced architectures such as LSTMs, stacked RNNs, bidirectional RNNs.

 ## 7. Attention-based Neural Machine Translation
  
  - Implemented a model for neural machine translation using a Transformer, following a TF tutorial.

  ## 8. Word2Vec
  - Experiment an example of self-supervised learning, where we have data without labels, and are constructing a task directly from the data (often some kind of prediction task) in order to learn deep representations,
  - Understand how Softmax with a very large number of classes is problematic, and getting to know possible workarounds.
  - Explored the idea of word embeddings.

  ## 9. Introspection
  - Implemented gradient-based model analysis both for creating saliency maps (local) and for feature visualization (global). 

  ## 10. Self-Supervised Learning
  - Explored self-supervised methods for extracting features from unlabeled data, and then use those features for supervised tasks.
    - Define a self-supervised task.
    - Build a network to solve the task. 
    - Train the model.
    - Build a small “classification head” on top of the self-supervised model.
    - Train the classification network on labeled data.




