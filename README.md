# Neural Network Charity Analysis

## Overview

The purpose of this analysis was to use the neural network machine learning process to analyze data.  We used a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing 

- The target variable is the column "Is Successful".
- The rest of the columns, besides the target variable and any dropped columns, are the feature variables.
- The variables that were removed from the data were the columns "EIN" & "NAME"

<img src="https://github.com/bwheeler98/Neural_Network_Charity_Analysis/blob/e91992730555ddb3ebedd4e6bb63ffd09e3a88eb/Screen%20Shot%202022-08-05%20at%2010.44.33%20AM.png" width="700" height="350">

### Evaluating the Model

- I was not able to achieve the target accuracy of 75%.  The model with the closest accuracy to the target was the first model.  The first model had an accuracy score of 73%.  There was a 3 attempts to optimize the model to get the target accuracy.  For all 3 attempts I dropped an exra column, "AFFILIATION".  For the first attempt I increase the nodes of each hidden layer by 10.  I also increased the cutoff numbers for the replace application and replace class variables to 800 and 1500 respectively.  For the second attempt I kept the model the same as the previous attempt, but decreased the epochs to only 50 instead of 100.  For the third attempt I decreased the cutoff for the replace application and replace class variables to 400 and 1000 respectively.  I also increased the epochs to 75.  

## Summary

In conclusion, the best accuracy score my models were able to achieve was 73%.  One way to improve this analysis is to do a deeper dive on what exactly the data columns represent.  This would improve our knowledge of which columns should be dropped or which columns need to be kept.  Instead of using a neural network to analyze this data we could use a unsupervised logistic regression.
