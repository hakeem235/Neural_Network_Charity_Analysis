# Neural Network Charity Analysis


## Overview of the analysis:

Use your machine learning and neural network knowledge from this project to use the functions in this dataset. Create a binary classifier that tells the client whether an applicant will succeed in Alphabet Soup. This dataset includes 34,000+ organizations funded by Alphabet Soup. There are several columns that capture metadata for each organization. B. Type of Organization and Use of Funds. This project consists of three steps:
Preprocess data for neural networks, compile, train, evaluate models, and finally optimize models. 
___

## Results:
___
## Data Preprocessing

#### What variable(s) are considered the target(s) for your model?
The variable we are targeting in this module is the `IS_SUCCESSFUL` column.
#### What variable(s) are considered to be the features for your model?
The features that we are using are every column except the ones that we will drop.
#### What variable(s) are neither targets nor features, and should be removed from the input data?

First features we drop are the `EIN` & `NAME` because we expect both features to have little to do with our outcome.
___
## Compiling, Training, and Evaluating the Model

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?

This model is made with an input features & two hidden layers. The first hidden layer has 80 neurons, the second has 30 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function `relu` & the output layer is `sigmoid`.
#### Were you able to achieve the target model performance?
#### What steps did you take to try and  increase model performance?

___
## Summary


