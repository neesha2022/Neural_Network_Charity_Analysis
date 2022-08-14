## Neural_Network_Charity_Analysis


### Overview of the analysis: Explain the purpose of this analysis.
Create a binary classifier capable of predicting whether applicants will be successful if funded by Alphabet Soup. Three technical analysis deliverables was required along with a written report. 

-Preprocessing Data for a Neural Network Model

-Compile, Train, and Evaluate the Model

-Optimize the Model

### Data Preprocessing

What variable(s) are considered the target(s) for your model?
Used IS_SUCCESSFUL to indicate that the money was successfully funded by AlphabetSoup.

What variable(s) are considered to be the features for your model?
The following - affiliation, use case, organization type, status and the income amount are the features of the model.

What variable(s) are neither targets nor features, and should be removed from the input data?
The EIN and NAME columns were removed to improve code efficiency.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
We started with two hidden layers with 80 and 30 neurons.

Were you able to achieve the target model performance?
Model accuracy was under 75% and not a good measure to predict the outcome of the charity donations.

What steps did you take to try and increase model performance?
We used bucketing to ASK_AMT and organized the different values by intervals. 

### Summary
The model did not reach the target of 75% accuracy and we can conclude that the model is not outperforming.
