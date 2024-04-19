---
title: Introduction to Neural Networks
date: 2024-04-06 01:45:00 +0545
categories: [AI, TensorFlow]
tags: [Neural Networks]

---

## Understanding the Basics

Neural Networks is a interesting blend of biology and computer, inspired by the functionalities of our brain to tackle the complex computing problems. Neural networks are like computer programs that learn from examples, just like how we learn from experience. They're really good at spotting patterns and understanding things like pictures, speech, and language. For example, they can recognize faces in photos, understand what people are saying, predict future trends, and even chat with us like humans do.

Our brain has millions of neurons, all interconnected, forming a complex network. When one neuron wants to send a message to another neuron, it releases chemical called neurotransmitters into the synapses. It travels across the synapses and bind to receptors on the receiving neuron. The strength of these connections, analogous to the weights in a neural network that determines how much influence one has on another.

When a neuron receives input from other neuron through its dendrites, neural activation occurs. If the combined input exceeds a certain threshold.neuron fires an action potential. Whereas in case of neural network, activation function introduce non-linearity into the network and determines whether a neuron should be activated or not based on its input.

### Simple perceptron to Deep Learning
Neural Network started with something called a perceptron in 1958, thanks to Frank Rosenblatt. 

![Perceptron Model](https://miro.medium.com/v2/resize:fit:720/format:webp/1*_Zy1C83cnmYUdETCeQrOgA.png)

This network model is like simple decision making system that helps you decide whether to go for a walk or not, based on their mood & weather. Adding one or more hidden layers, the idea of perceptron is extended  to create a multi-layer perceptron model. To create a network of perceptrons, we can connect layers of perceptrons, using a multi-layer perceptron model.

_When does neural network becomes a deep neural network?_

A neural network is considered "deep" when it has multiple hidden layers in between input and output layers.

FeedForward: All the information is going from input layer all the way to the end output layer and its fully connected. Every neuron is one layer connected to anotherm neuron in next layer, so the output of one is fed as input to another perceptron.