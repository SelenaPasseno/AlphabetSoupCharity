# AlphabetSoupCharity
The following is the performance of the deep learning model created for Alphabet Soup.

Overview of the analysis: The non-profit foundation Alphabet Soup wants to design a tool that will help it select the applicants for funding with the best chance for success in their ventures.  The goal is
to design a binary classifier that can predict wheither applicants will be successful if funded by Alphabet Soup.

Results: Using bulleted lists and images to support your answers, address the following questions:

**#What variable(s) are the target(s) for your model and what variable(s) are the features for your model?**
The target for the model is to determine whther the oney used for venture was used effectively or not, therefore the target is (IS_SUCCESSFUL)
The features are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMOUNT, and SPECIAL CONSIDERATIONS.  These items have been encoded.    

**#What variable(s) should be removed from the input data because they are neither targets nor features? **
EIN, NAME, ASK_AMT have been removed as they are neither features nor targets.


#**Compiling, Training, and Evaluating the Model**

**How many neurons, layers, and activation functions did you select for your neural network model, and why?**
I utilized the tuner to select the begining activation functions, neurons and layers for my neural network.  It performed better than my best guess.

**Were you able to achieve the target model performance?** No.  I was unable to reach the target model performance.

What steps did you take in your attempts to increase model performance?  I was unable to achieve the targeted performance, however as I tried multiple times the 
analysis became worse. The first test utilised two hidden layers.  Results were .7315

Summary: The model constructed using the directions provided only resulted in a .7299 value accuracy with the tuner determining the best value accuracy of .7330.
Since this is a binary classification model, it may be better to use logistic regression model and include the same items.
