# Logistic-regression-algorithm


This is a simple implementation of logistic regression from the scratch.
In Logistic Regression, we don’t directly fit a straight line to our data like in linear regression. Instead, we fit a S shaped curve, called Sigmoid, to our observations.

Steps on how to implement logistic regression from scratch

Define a sigmoid function. Which returns the probability of an event, which is always between 0 and 1.

Define an error function. Which returns how far the prediction is from the actual value

Define a log loss function. Which is just takes into account the uncertainty of your prediction based on how much it varies from the actual label. This gives us a more nuanced view into the performance of our model

Update the weight and bias of the model, by using gradient descent approach. By constantly taking steps to decrease the error. 

How do we know what weight should be bigger or smaller. We do this by getting the derivative of the loss function with respect to the weight and bias. Which is the negative of the gradient. 
