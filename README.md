# Neural_Network_Charity_Analysis
The analysis is to help training a machine using data from Alphabet Soup’s business team containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.  The ultimate goal of the machine is to help predict whether an appling business would be successful if granted funding by Alphabet Soup.

## Data Preprocessing
1. What variable(s) are considered the target(s) for your model? 
The "IS SUCCESSFUL" column.

2. What variable(s) are considered to be the features for your model?

All the other columns that survived preprocessing.

3. What variable(s) are neither targets nor features, and should be removed from the input data? 

None

## Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?  

Based upon the module, I used two hidden layers with 8 and 5 neurons repectively.
![original](https://github.com/smulhern03-bootcamp/Neural_Network_Charity_Analysis/blob/main/Layers%20and%20Neurons.PNG)

This resulted in the following parameters:
![parameters](https://github.com/smulhern03-bootcamp/Neural_Network_Charity_Analysis/blob/main/Params.PNG

Which produced the following performance:
![performance](https://github.com/smulhern03-bootcamp/Neural_Network_Charity_Analysis/blob/main/Original%20Output.PNG)

2. Were you able to achieve the target model performance? 

No.  75% performance was not achieved.  

3. What steps did you take to try and increase model performance?

Three subsequent modifications were attempted to increase the performance.
### Added Layers and Neurons

![Added Layers and Neurons](https://github.com/smulhern03-bootcamp/Neural_Network_Charity_Analysis/blob/main/Added%20layers%20and%20neurons.PNG)
![Added layers and neurons results](https://github.com/smulhern03-bootcamp/Neural_Network_Charity_Analysis/blob/main/Added%20layers%20and%20neurons%20results.PNG)

### Changed Activation Type
![Changed Activation](https://github.com/smulhern03-bootcamp/Neural_Network_Charity_Analysis/blob/main/Changed%20Activation.PNG)
![Changed results](https://github.com/smulhern03-bootcamp/Neural_Network_Charity_Analysis/blob/main/Changed%20Activation%20Results.PNG)

### Increased Layers, Decreased Neurons
![More layers](https://github.com/smulhern03-bootcamp/Neural_Network_Charity_Analysis/blob/main/More%20layers%20and%20neurons.PNG)
![results](https://github.com/smulhern03-bootcamp/Neural_Network_Charity_Analysis/blob/main/More%20layers%20and%20neurons%20results.PNG)

Nothing was successful in increasing performance by .001.

## Summary
The overall results were good, not great.  72% accuracy is better than just being at 51% accuracy; however, 75% accuracy would have been idea.  Dropping columns from the data set would be probably been a better play for the model.  The data would have been less noisy resulting in less data trying to be used for training.  Due to the large nature of the dataset increasing neurons and layers could have also occurred but that may have resulted in overfitting the model.  Ultimately, dropping columns is recommended.
