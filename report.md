# Overview of the Analysis

This notebook features multiple neural networks intended to be able to predict whether applicants will be successful if funding is provided by Alphabet Soup. 



**Data preprocessing**
- A binary variable indicating whether the business was successful was the dependent variable. 

The independent variables included in this analysis are:
- **EIN** and **NAME**: identification columns
- **APPLICATION_TYPE**: Alphabet Soup application type
- **AFFILIATION**: Affiliated sector of industry
- **CLASSIFICATION**: Government organization classification
- **USE_CASE**: Use case for funding
- **ORGANIZATION**: Organization type
- **STATUS**: Active status
- **INCOME_AMT**: Income classification
- **SPECIAL_CONSIDERATIONS**: Special considerations for application
- **ASK_AMT**: Funding amount requested
- **IS_SUCCESSFUL**: Was the money used effectively


**Compiling, Training, and Evaluating the Model**

- 4 different models were built. 
- I was not able to achieve the target model performance. 
- Several steps were taking to attempt to optimize the model
    - The number of hidden layers was increased
    - The number of nodes per layer was increased
    - Activation functions were varied
    - I reduced the number of values of certain categorical variables. 