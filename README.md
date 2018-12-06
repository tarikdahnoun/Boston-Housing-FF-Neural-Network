# Boston-Housing-FF-Neural-Network
Implementing a Feedforward Neural Network to predict housing data

In this code, we define a feedforward neural network that is capable of developing a regression model suitable for the Boston housing dataset from sklearn.

In developing this model, we find that the model is convex, as we expect. However, there are two minima, and the initial code is only capable of finding the local minimum, but we want the absolute minimum. So, we include a momentum parameter and adjust the rate(~0.9) in order to find the absolute minimum.

In the same way, we use the Nesterov momentum algorithm for the same purpose, but obtain a better overall result.
