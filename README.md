# Deep-Learning-Challenge

Report on the Deep Learning Challenge:

Overview of the analysis: 
The purpose of this analysis is to use deep learning neural networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The dataset contains more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

Results:

Data Preprocessing
-	What variable(s) are considered the target(s) for your model?
The target variable for this model is the IS_SUCCESSFUL column. This column indicates whether the money was used effectively.

-	What variable(s) are considered to be the features for your model?
The features for this model are the APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT columns.

-	What variable(s) are neither targets nor features, and should be removed from the input data?
The EIN and NAME columns are neither targets nor features and should be removed from the input data.

Compiling, Training, and Evaluating the Model
-	How many neurons, layers, and activation functions did you select for your neural network model, and why?
The program used 2 hidden layers with 80 and 30 neurons respectively. The first layer used the relu activation function and the second layer used the sigmoid activation function. The relu activation function is used to identify the positive values in the dataset and the sigmoid activation function is used to identify the negative values in the dataset.
Then the program was ramped up in the three test waves to test different neurons sets to change the numbers and then on the third test we added in two additional layers. 

-	Were you able to achieve the target model performance?
No, the target model performance was not achieved. The model accuracy was 72.6% and the target model performance was 75%. On test 2 there were a few that got tot he score of 74% but did not stay there.

-	What steps did you take to try and increase model performance?
The steps taken to try and increase model performance were to change the number of neurons in the hidden layers, add additional hidden layers, and change the activation functions.

Summary:
The deep learning neural network model was not able to achieve the target model performance of 75%. The model accuracy was 72.6%. The model accuracy could be increased by adding more neurons and hidden layers to the model.