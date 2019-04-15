# cnn-showcase
A tiny neural network that shows the strenghts and weaknesses of deep learning.

Trained on the [CIFAR-10 dataset](https://www.cs.utoronto.ca/~kriz/cifar.html), this neural network is used to show what a deep learning can and can not do.

## Strengths

* It classifies off-center images correctly.
* It classifies a lego model of a firetruck correctly.

## Weaknesses

* It thinks a fictional frog is a deer, probably because it detects an antler silhouette.
* It thinks a black hole is a ship, because it wasn't trained to classify black holes. (Imagine if the model is actually right...

## TL;DR

Deep learning models (or any machine learning model for that matter) can only do what they were trained for. Put them even a micrometer out of context, and the weirdest stuff will appear.
