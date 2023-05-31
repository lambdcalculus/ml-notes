# ML Notes

On a path to understand Machine Learning on a deeper level, I wrote these notes that might also help anyone trying to get ahold on the topic. Though, I do kind of assume the reader is comfortable with vector calculus and linear algebra, so they might not be the most acessible. But those topics are needed to get to the real nitty-gritty of the math behind everything. In a similar vein, I try to implement the algorithms "from scratch" before moving on to more abstracted versions. As "from scratch" as you can get when you already have `numpy` doing a lot of work for you, anyway.

A decent chunk of these is based on some class notes from a machine learning class from Universidade Federal do Ceará.

So far we've got:
* Linear Regression (explanation, implementation, and usage). Most of it is in `linear.ipynb`, but a more general version shows up in `logistic.ipynb`.
* Binary and Multiclass Classification tasks, including logistic regression andsoftmax (explanation, implementation, and usage).
* Gradient Descent (explained, implementation, and usage).
* Stochastic Gradient Descent (explained).
* Over/Underfitting and Regularization.

And I hope to add:
* Implementation (and usage?) of Stochastic Gradient Descent.
* Explanation, implementation, and usage of a Multi-Layer Perceptron (including backpropagation).
* Explanation, implementation, and usage of a Convolutional Neural Network.
* Some more abstract examples using Keras.