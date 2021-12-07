# Deep Learning Homework: Charity Funding Predictor

## Background/Overview

The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful. With our knowledge of machine learning and neural networks, we will use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Data Preprocessing:

### What variable(s) are considered the target(s) for your model?
*The variable we are considered as the target for our model is the Is_Succesful varriable

### What variable(s) are considered to be the features for your model?
*The following were consider to be the feature for our model

APPLICATION_TYPE

AFFILIATION

CLASSIFICATION

USE_CASE

ORGANIZATION

STATUS

INCOME_AMT

SPECIAL_CONSIDERATIONS

ASK_AMT

### What variable(s) are neither targets nor features, and should be removed from the input data?
*The following variables are neither target nor features EIN and NAME are both used solely for identification purposes and are not adding value to the algorithm.

## Compiling, Training, and Evaluating the Model

Multiple attempts were done to optimize the model, how the most successful model was a single layered "relu" model but made it go through 100 epochs. It was unable to get over 72% and was therefore unable to meet the perfomance goal. In an attempted the model with different variations of layers (from 1-3) with epochs between 100-200 and with different types of neurons, the overall successful model was the single layered "relu" model.

## Summary: 

Overall the dataset has provided succficent amount ot optimizing and provided an over all high rating of >70%. Recomendation would e to attempt to remove any additional columns for the data to limit the scope and focus on the main contrubiting columns as there was to much infomation that was deemend "garbage". The program would also recommend in ploting the data and visubalize the data to determine more points to consider. 
