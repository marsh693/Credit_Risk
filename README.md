# Credit_Risk

# Overview of Analysis

The purpose of this Credit analysis is to predict credit risk using different forms of machine learning. Finding a model that will effictevly predict credit rick will create a more reliable lending process for those involved. An effective model can also be useful for finding candidates who would be a better fit for a loan compared to those who would not be the best fit.

# Results

Shown below are some of my results from this module

<img width="704" alt="image" src="https://user-images.githubusercontent.com/109708202/227730945-d6eaee5d-2fca-46ea-962d-cf43cd460bb3.png">
 - This images shows the results from the RandomOverSampler
 - THe RandomOVerSampler recieved a score of 49.9%
 
<img width="706" alt="image" src="https://user-images.githubusercontent.com/109708202/227731040-9800d367-242a-4036-8f03-6a13dfd936e0.png">
  - This image shows the results from the SMOTE oversampling
  - The SMOTE received an accuracy of 66.1%

<img width="709" alt="image" src="https://user-images.githubusercontent.com/109708202/227731087-86d1a31d-350d-41ce-b6aa-d69dd3620904.png">
 - This image shows results from the undersampling
 - The undersampling received an accuracy of 66.1%

<img width="702" alt="image" src="https://user-images.githubusercontent.com/109708202/227731252-6dfb2264-2f92-4514-9fb1-78e2c3e32d07.png">
 - This image shows results from SMOTEENN
 - The SMOTEENN received a score of 66.1%

# Summary

With the algorithims that I was able to get to work it seems that 3 of the 4 were receiving the same score. This could be due to an error in the code that I wrote because 3 out of 4 models receiving the same score my be cause for concern. If each model received similar scores that would be more ideal because this would create different paths to determine credit risk. But since all three were receiving the same accuracy score, using the one model that received the different score would not be the best road to go because the score from the RandomOverSampling model only predicts a 50/50 chance of credit risk; which is not ideal. 
