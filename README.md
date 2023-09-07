code is based on in-class activities and checking through the solved folder

## Analysis

### Data Preprocessing

* What variable(s) are the target(s) for your model?
  * "Is-Successful" is the target

* What variable(s) are the features for your model?
  * NAME, APPLICATION, TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT,SPECIAL_CONSIDERATIONS, STATUS, and ASK_AMT
* What variable(s) should be removed from the input data because they are neither targets nor features?
  * EIN can be dropped because it isn't important to the target and will confuse the system
  
### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
    * I chose three layers and two activation functions. I was able to get about 80% accuracy with that combination.
* Were you able to achieve the target model performance?
    * yes, but I would like to get it a bit higher.
* What steps did you take in your attempts to increase model performance?
    * I subbed in different activation funcitons and added an additional layer. I simply experimented until I got good results.

### Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
  I was able to predict the success of a program with about 81% accuracy based on the number of times they applied, the Classification and Status. 
  A deep forest model is ideal for classification problems, so I would recommend using that for further analysis. 
