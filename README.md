# Neural Network Charity Analysis


## Overview of the analysis:

Use your machine learning and neural network knowledge from this project to use the functions in this dataset. Create a binary classifier that tells the client whether an applicant will succeed in Alphabet Soup. This dataset includes 34,000+ organizations funded by Alphabet Soup. There are several columns that capture metadata for each organization. B. Type of Organization and Use of Funds. This project consists of three steps:
Preprocess data for neural networks, compile, train, evaluate models, and finally optimize models. 
___

## Results:

### Data Preprocessing

##### What variable(s) are considered the target(s) for your model?
The variable we are targeting in this module is the `IS_SUCCESSFUL` column.
##### What variable(s) are considered to be the features for your model?
The features that we are using are every column except the ones that we will drop.
##### What variable(s) are neither targets nor features, and should be removed from the input data?

First features we drop are the `EIN` & `NAME` because we expect both features to have little to do with our outcome.
___
## Compiling, Training, and Evaluating the Model

##### How many neurons, layers, and activation functions did you select for your neural network model, and why?

This model is made with an input features & two hidden layers. The first hidden layer has 80 neurons, the second has 30 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function `relu` & the output layer is `sigmoid`.
##### Were you able to achieve the target model performance?
Although we the target for the model was to be `75%` or above, I was not able to reach the target.
##### What steps did you take to try and  increase model performance?
Some of the steps I took to try and make the model more accurate were adding hidden layers, changing the activation type, changing the number of epochs and changing the number of neurons in each layer.
___
## Summary
The accuracy of the model was finally `72%`. Starting with one dataset, I tried to predict whether the project would succeed with all the features I used, but I discarded two features that seemed unrelated. We didn't get the `72%` accuracy we wanted because we might have had to remove more features that could affect the actual performance of the neural network. The best way to improve model accuracy is to have more data. Adding hard data to this model will make the accuracy of this model more specific. 