# Colab-Report

Problem 1: (Refer to Loss_&_Accuracy.xlsx spreadsheet attached)
1.	An MLP for CIFAR10 with best model recommended after experiments in python notebook consist of following parameters:
* Number of epochs=30
* Batch size = 128
* Number of neurons in a layer = 700 & 10
* Number of layers = 2
* Learning rate = normal
* Activation functions = ‘relu’ & ‘softmax’
* Dropout rates = normal
* Optimizer = ‘rmsprop’

This model provides an accuracy of 50.05% which outputs to be max out of the 15 experiments done on parameters.

2.	The model isn’t that good. This model underfits data and thus requires a lot of hyperparameters to be tuned. I would improve this model by playing around with the parameters. But even after that a stage comes where the accuracy can reach maximum till 54-55% and the data overfits.

https://www.youtube.com/watch?v=ryTOdYnFPHU&feature=youtu.be
