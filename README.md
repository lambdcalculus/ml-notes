# ML Notes

On a path to understand Machine Learning on a deeper level, I wrote these notes that might also help anyone trying to get ahold on the topic.

In these, I do assume the reader is comfortable with vector calculus and linear algebra, so these notes might not be the most acessible. But those topics are needed to get to the real nitty-gritty of the math behind everything, which is an important part of my goal. In a similar vein, I try to implement the algorithms "from scratch" before moving on to more abstracted versions - as "from scratch" as you can get when you already have `numpy` doing a lot of work for you, anyway.

A decent chunk of these is based on some class notes from a machine learning class from Universidade Federal do Ceará.

So far the notes cover:
* Linear Regression (explained, implemented, and used). Most of it is in `linear.ipynb`, but a more general version shows up in `logistic.ipynb`.
* Binary and Multiclass Classification tasks, including logistic regression and softmax (explanained, implemented, and used).
* Gradient Descent (explanaied, implementation, and usage).
* Stochastic Gradient Descent (explained).
* Over/Underfitting and Regularization.

And I hope to add:
* Implementation (and usage?) of Stochastic Gradient Descent.
* Explanation, implementation, and usage of a Multi-Layer Perceptron (including backpropagation).
* Explanation, implementation, and usage of a Convolutional Neural Network.
* Some more abstracted examples using Keras.