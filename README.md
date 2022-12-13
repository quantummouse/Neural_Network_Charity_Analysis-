# Neural_Network_Charity_Analysis-



Data Preprocessing
## What variable(s) are considered the target(s) for your model? 
IS_SUCCESSFUL as we are trying to predict what projects will be successful
## What variable(s) are considered to be the features for your model? 
Features of the model were APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT
## What variable(s) are neither targets nor features, and should be removed from the input data? 
EIN And NAME were removed with others like Status being tested to be removed to see if the accuracy goes up.
Compiling, Training, and Evaluating the Model - With 2 hidden layers and neurons split 20/6 and 100 epochs the accuracy was -Loss: 0.5501151084899902, Accuracy: 0.7292128205299377 Another attempt was to remove Status from the columns. That barely had any effect. Loss: 0.5484598278999329, Accuracy: 0.728863000869751. Random Forest was tried and the accuracy did not increase - Random forest accuracy: 0.7118367346938775
## How many neurons, layers, and activation functions did you select for your neural network model, and why?
Two hidden layers were selected with 20/6 neurons and 100 epochs. Relu activation function was used. There was not a lot of difference in variation while trying to improve accuracy. 
## Were you able to achieve the target model performance? 
No. Highest was about 72%
## What steps did you take to try and increase model performance? 
Number of layers, epochs, neurons was tried, but had small effects. Random forest was tried with 60 estimators, but the accuracy went down by about a percent. 
## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation. 
The accuracy hovered around 72% - there would need to be more exploration into the data and data quality as well as differnt numbers of neurons, layers and estimators with different algorithms. A better way that would require more time would be to set up a lool that tests different parameters that are fed to it. Also examining more of the data and how it can be refined and pre processed could be a step toward better optimization. 
