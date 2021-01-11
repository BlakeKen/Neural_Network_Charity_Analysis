# Neural_Network_Charity_Analysis

## Overview

The purpose was to create a binary classifier that is capable of predicting whether applicants will be successful funded based on organizations that have received funding in the past.

## Results
* Data preprocessing 
  * The target variable is the is-successful column
  * Features: NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT,SPECIAL_CONSIDERATIONS, and ASK_AMT
  * Data Removed:EIN because its not important and it would throw things off, STATUS because the number never changed
 
* Compiling,Training, and Evaluating the Model
  * There are 3 hidden layers in the optimized model. Adding it boosted the accuracy above .75.
  * The target model performance was achieved. 
  * Stepsincreased model performance Using a sigmoid function instead of relu for the activation in the second layer as well as the added 3rd layer, using data points for the names
  
## Summary 

  Overall, The accuracy in the end was increased to 79%. Applicants who have applied more than 3 times have a good chance. Random forest decision trees or logistic regression could also have pleasing results because they work well with binary classification
    
      
