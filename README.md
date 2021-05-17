# Neural_Network_Charity_Analysis
Neural Networks and Deep Learning Models

## Overview
Purporse of this analysis was to help the Alphabet Soup determine if deep learning can help choose which charities will be successful.


## Results

### Data Preprocessing
1. **What variable(s) are considered the target(s) for the model?** 
The target variable is the dependent variable, y.  

2. **What variable(s) are considered to be the features for the model?** 
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT. These variables are the independent variables, x.

3. **What variable(s) are neither targets nor features, and should be removed from the input data?** 
The identification columns EIN and NAME were not used.

### Compiling, Training, and Evaluating the Model
1. **How many neurons, layers, and activation functions were selected for the neural network model, and why?** 
8 neurons were in the first hidden layer and 5 neurons were in the second hidden layer. 

2. **Was target model performance achieved?** 
Performance of 75% accuracy was not achieved by the target model. 

3. **What steps were taken to try and increase model performance?** 
In an attempt to optimize model performance, a third hidden layer was added with 15 neurons and the activation functions were adjusted. The first hidden layer maintained the ReLU activation function, however the second and third layers utilized the Sigmoid activation function. Unfortunately, performance of 75% was not achieved by the optimized model. 


## Summary
It's recommended to adjust the number of hidden layers and neurons, along with the corresponding activation functions for each layer. If possible, additional data added to the dataset could also create better results.
