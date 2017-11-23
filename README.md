# Tensorflow problem sheet solution

## Introduction
The following is a 4th year in-class assignment for Emerging technologies. These problems relate to the Python package Tensorflow. We will again use the famous iris data set.

### What are Tensorflow & Keras?

###### [Tensorflow](https://www.tensorflow.org/)

TensorFlow™ is an open source software library for numerical computation using data flow graphs. Nodes in the graph represent mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them. The flexible architecture allows you to deploy computation to one or more CPUs or GPUs in a desktop, server, or mobile device with a single API.

###### [Keras](https://keras.io/)

Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow. It was developed with a focus on enabling fast experimentation. Being able to go from idea to result with the least possible delay is key to doing good research.

## Assignment Specification

### 1. Use Tensorflow to create model

Use Tensorflow to create a model to predict the species of Iris from a flower’s sepal width, sepal length, petal width, and petal length.

### 2. Split the data into training and testing

Split the data set into a training set and a testing set. You should investigate the best way to do this, and list any online references used in your notebook. If you wish to, you can write some code to randomly separate the data on the fly.

### 3. Train the model

Use the testing set to train your model.

### 4. Test the model

Use the testing set to test your model, clearly calculating and displaying the error rate.