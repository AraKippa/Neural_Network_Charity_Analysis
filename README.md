# Neural_Network_Charity_Analysis
Mod 19

##Purpose of this analysis was to determine whether applicants will be successful if funded by Alphabet Soup. 
- 
##Data Preprocessing
- What variable(s) are considered the target(s) for your model? I used the "is successful' column as the target variable.
- What variable(s) are considered to be the features for your model? Features that were relevant to the model included, application type, income and ask amount.
- What variable(s) are neither targets nor features, and should be removed from the input data? I dropped application type to >500 to tighten up the data while dropping EIN and Name as irrelavent categorical variables.
##Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why? I chose 6 and 3 as it was a relatively small database, once it was processed. 
- Were you able to achieve the target model performance? No, the best accuracy I got was 65 when I increased the epochs to 200, leaving all other variables the same.
- What steps did you take to try and increase model performance? I tried increasing the hidden layer nodes to 8,5. I increased epochs to 200 and I switched the activation from relu to sigmoid.
##ummary of the results 
- My resutlts were best, as stated with running extra epochs [epochs](url). They were ok with switching relu/sigmoid activations [swithc](url) and they were terrible with increasing [nodes](url).
- Future ecommendations include increasing the app type cut off to 1000, might eliminate some variance skew.  Trying one layer or three layers. Playing with the different optimizer options on keras. there are eight listed on their [website](https://keras.io/api/optimizers/)
