# Neural_Network_Charity_Analysis

## Project Overview
The purpose of this project is to use neural netwroks to develop a machine learning model to predict which applicants for funding will be succesful based on histroical data provided by the client.

## Results
There were six questions that were to be addressed by this model.
- What vairable(s) are considered targe(s) for the model? IS_SUCCESSFUL
- What variable(s) are considered to be the features for your model? APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT
- What variable(s) are neither targets nor features, and should be removed from the input data? EIN, and NAME as these two contain ungroupable data
- How many neurons, layers, and activation functions did you select for your neural network model, and why? The model was set-up as follows
  - Output layer with sigmoid activation
  - Two hidden layers
    - First hidden layer had 80 nodes with activation set to relu
    - Second hidden layer had 30 nodes with activation set to relu
  - Epochs was set to 100
- Were you able to achieve the target model performance? The target performance of >75% accuracy was not achieved.
- What steps did you take to try and increase model performance? A third hidden layer with 20 nodes was added. When that did not increase accuracy, sigmoid and tanh respectively were used for activation. Additional options that were not explored included, dropping more columns from the data, chaning the number of nodes per layer, and changing the number of epochs.

## Summary
The model used could not achieve the required 75% accuracy. A random forest classifer model would be the next model to try. It works similarly to a neaural network but may provide a more robust and efficient analysis on large datasets.
