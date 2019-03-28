# TensorFlow Regressions

Code using TensorFlow regressions in javascript in order to understand the mathematics and programming techniques that are used in the most common Machine Learning algorithms.

*** Note: to open web links in a new window use: _ctrl+click on link_**

## Table of contents

* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info

The Machine-Learning course contains 13 sections and 1 Appendix, as listed below:

**Section 1: What is machine learning?** Solving machine-learning problems, link to Github starter pack, identifying relevent data, dataset structure, observation data. Store as an array of inner arrays.

**Section 2: Algorithm Overview** K-Nearest Neighbor (KNN), the Lodash javascript library, chaining lodash functions, creating and testing a KNN algorithm.

The k-nearest neighbors (KNN) algorithm is a simple, supervised machine learning algorithm that can be used to solve both classification and regression problems. It’s easy to implement and understand, but becomes significantly slower as the size of that data in use grows.

KNN finds the distances between a query and all the examples in the data, selecting the specified number examples (K) closest to the query, then votes for the most frequent label (in the case of classification) or averages the labels (in the case of regression).

Using Random Test Data, Gauging Accuracy by comparing actual reult with testset.

Normalisation

**Section 3: Tensor JS** Tensor Shape and Dimension. Dimensions (mostly 1 and 2 dimensional arrays will be used).

Elementwise Operations: const data = tf.tensor([1,2,3]). Tensors with disimilar shapes can still be added together. Broadcasting, Logging Tensor Data using data.print(), Tensor Accessors using data.get(), tensors cannot be modified. Creating Slices of Data, Tensor Concatenation.

**Section 4: Applications of Tensorflow** KNN with regression - example using house prices on a map - predict price using regression and k=2 (the 2 nearest houses) for example, KNN with Tensorflow, Sorting Tensors, Loading CSV data.

**Section 5: Getting Started with Gradient Descent** Linear Regression, Gradient Descent, MSE, Derivatives, Multiple Terms.

**Section 6: Gradient Descent with Tensorflow** Data Loading, Formulating the Training Loop, MSE Slopes, Matrix Multiplication.

**Section 7: Increasing Performance with Vectorized Solutions** Refactoring, Model Accuracy, Data Processing, Standardization, Rate Optimization.

**Section 8: Plotting Data with Javascript** Plotting MSE values.

**Section 9: Gradient Descent Alterations** Batch and Stoastic Gradient Descent. Iterating over Batches, Making predictions with the model.

**Section 10: Natural Binary Classification** Logistic Regression, The Sigmoid Equation, Decision Boundaries.

**Section 11: Multi-Value Classification** Multinominal Logistic Regression. Smart Refactor, Multi-Column Weights, Classifying Continuous Values, Sigmoid v Softmax.

**Section 12: Image Recognition in Action** Handwriting Recognition, Flattening Image Data, Accuracy Gauge.

**Section 13: Performance Optimization** Handling Large Datasets, Minimising Memory Usage, Releasing References, Optimising Tensorflow Memory Usage, TF Tidy, Plotting Cost History.

**Appendix: Custom CSV Loader** Loading CSV files, A Test Dataset, Custom Value Parsing, Extracting Data Columns, Splitting Test and Training.

## Screenshots

![Example screenshot](./img/.png)

## Technologies

* [TensorFlow.js v0.1.7](https://js.tensorflow.org/), an open-source hardware-accelerated JavaScript library for training and deploying machine learning models.

* [@tensorflow/tfjs-node v0.2.1](https://www.npmjs.com/package/@tensorflow/tfjs-node), a node.js tensorflow package.

* [node.js v10.15.0 LTS](https://nodejs.org)

* [Lodash v4.17.11](https://lodash.com/), a modern JavaScript utility library delivering modularity, performance & extras. It has lots of methods but is slow.

* [Javascript playground](https://stephengrider.github.io/JSPlaygrounds/), a sandbox for writing javascript code and seeing the result on the right.

## Setup

It was necessary to install Python on my PC for this to compile.

## Code Examples

## Features

* feature

## Status & To-Do List

* Status: .

* To-Do: add detail to General Ino section. Add screen-shots of individual projects.

## Inspiration

Code from Udemy Course [Machine Learning With Javascript](https://www.udemy.com/machine-learning-with-javascript/learn/v4/content).

## Contact

Created by [ABateman](https://www.andrewbateman.org) - feel free to contact me!
