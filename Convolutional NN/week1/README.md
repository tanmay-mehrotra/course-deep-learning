In this week's tutorial, I learnt about Convolutional Neural Networks (CNN) and implemented it first by my own and then later by using Tensorflow.

## Why CNN ?
If we starting treating every pixel of an images as its own feature and feed it as an input to network then soon we will realize we have too many weights to train for and at some time it becomes infeasible to train such a network. With the aid of filters we can start detecting edges (ex : vertical, hortizontal edges) and use only this information in our network. Convolution is a mathmatical operation where convolve a filter with a image to get an output which has information about the edges in the picture.

Apart from filters I have also used pooling(max/avg) layers which also helps in two ways:
1. reduces dimensions of the image
2. It generalises the results from a convolutional filter - making the detection of features invariant to scale or orientation changes

This quora article does a great job in explaining pooling : https://www.quora.com/What-is-max-pooling-in-convolutional-neural-networks

## Contents
There are two notebooks in this weeks assignments:
1.  I implemented feed forward pass for the CNN on my own (without aid od any library). Primary purpose of this assignment is to get well versed with convolution operation.
2. Used Tensor flow library to create a Neural network for correctly detecting images present in SIGNS (numbers 1-5 represented as images of hand signs)dataset.

