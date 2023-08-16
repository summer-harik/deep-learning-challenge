# Deep Learning Challenge
## Overview 
This analysis uses a neural network to predict whether potential funding applicants will be successful.
## Results
Data Preprocessing:

1. The IS_SUCCESSFUL variable is the target for the model.
2. The rest of the columns are the features for the model.
3. The EIN and NAME variables were dropped from the dataframe because they were neither targets nor features.

Compiling, Training, and Evaluating the Model:

1. I started with two hidden layers, 6 neurons each, and both using the "relu" activation function to start out. 
2. I was not able to achieve the target model performance.
3. I tried three hidden layers with 16, 16, and 8 neurons each while using the "tanh" activation function to see if I could improve the model's accuracy.

## Summary
Overall, I was not able to get the model's accuracy above 73%. I could try the kerastuner function in order to get the optimal number of layers and neurons to improve the model's accuracy.
