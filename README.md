# Neural_Network_Charity_Analysis
## Overview
Using machine learning and neural networks, create a binary classifier that is capable of predicting whether applicants will be successful if invested in by the company

## Results
* Our target variable is the 'IS_SUCCESSFUL' column.
* The features of the model are all other columns except the "IS_SUCCESSFUL" column
* The original number of neurons in the model is 8 neurons and 5 neorons in the first hidden layer and second layer, respectively. The first optimization attempt had two hidden layers with 6 neorons in the first hidden layer and 4 neorons in the second. Then, I tried three hidden layers with 8 neurons in each layer. Finally, in the third attempt the model had two hidden layers of 4 neurons and changed the number of epochs to 250.
* I was unable to achieve an accuracy over 75% for any of the model

## Summary
The best result I was able to obtain was an accuracy of 72.64%. A different model with more hidden layers and neurons might be able to get a better result.
