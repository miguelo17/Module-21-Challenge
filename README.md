# Module-21-Challenge
#  OVERVIEW
The purpose of this challenge was to identify the meaninful values in the dataset such as we can see in the graphs and then with that consideations of application and classification make the model.
#  RESULTS
##  Data Preprocessing
  ### What variable(s) are the target(s) for your model?
  In the binary classification it was the "IS SUCCESFUL", in a multi class the APPLICATION and CLASSIFICATION
  ### What variable(s) are the features for your model?
  They are the categorical values ['APPLICATION_TYPE','AFFILIATION','CLASSIFICATION','USE_CASE','ORGANIZATION','INCOME_AMT','SPECIAL_CONSIDERATIONS']
  ### What variable(s) should be removed from the input data because they are neither targets nor features?
  The object columns, such as T3, T4
## Compiling, Training, and Evaluating the Model
 ### How many neurons, layers, and activation functions did you select for your neural network model, and why?
  I selected 12 for the first layer, and 24 for the second layer because the more neurons the more features it can learn, also because of the symmetrical pattern to have double the neurons in the second layer.
 ### Were you able to achieve the target model performance?
  I was not able to reach 75% of accuracy maybe by applyng another normalization or getting more data samples from the data set.
 ### What steps did you take in your attempts to increase model performance?
 I expected to reach by applying several strategies alone and combined such as increasing the number of neurons, increasing number of epochs, but i was not able to reach 75% by making these.
#  SUMMARY
The model successfully processed and classified application data but fell short of the target accuracy, improvements such as advanced feature engineering, different optimization techniques, or alternative model architectures can help us get a better output.
