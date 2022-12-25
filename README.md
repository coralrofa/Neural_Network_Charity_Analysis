# Neural Network Charity Analysis

## Overview of the analysis

Use Neural Networks and Deep Learning Models to create a binary classifier capable of predicting whether an application to the Alphabet Soup grant program  will be successful if funded.

## Resources

CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 
Information in data set: 

*	EIN and NAME—Identification columns
*	APPLICATION_TYPE—Alphabet Soup application type
*	AFFILIATION—Affiliated sector of industry
*	CLASSIFICATION—Government organization classification
*	USE_CASE—Use case for funding
*	ORGANIZATION—Organization type
*	STATUS—Active status
*	INCOME_AMT—Income classification
*	SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
*	IS_SUCCESSFUL—Was the money used effectively

## Results: 

### 	Data Preprocessing

* What variable(s) are considered the target(s) for your model?

   S_SUCCESSFUL—Was the money used effectivel

* What variable(s) are considered to be the features for your model?
    APPLICATION_TYPE—Alphabet Soup application type
    
    AFFILIATION—Affiliated sector of industry
    
    CLASSIFICATION—Government organization classification
    
    USE_CASE—Use case for funding
    
    ORGANIZATION—Organization type
    
    STATUS—Active status
    
    INCOME_AMT—Income classification
    
    SPECIAL_CONSIDERATIONS—Special consideration for application
    
    ASK_AMT—Funding amount requested

* What variable(s) are neither targets nor features, and should be removed from the input data?
  
    EIN and NAME—Identification columns

###	Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?

    110 neurons split into 2 layers (75 & 35) as a starting point

* Were you able to achieve the target model performance?
    
75_35.png
No improvement after modifications to increase performance

* What steps did you take to try and increase model performance?
    
    Adding more neurons to a hidden layer: 100 & 50 layers  with 100 epochs
    
    Adding more hidden layers 3 layers 150, 75, 35 layers with 100 epochs

    Reducing the number of epochs to the training regimen.75 & 35 Layets with 50 epochs

## Summary: 

*Performance obtained 73%

* Recommendations to improve model: attempt adjusting the input date

  Dropping more or fewer columns:
      
      Drop organization
  
  Adjust bins:
    
      Bin application type at < 100, < 500 or < 1000
  
      Bin classification at < 500, < 1000
