# Sparkify
This purpose to build this prediction model is to predict the loss of current clients.

## Initialization
The pacakges required for running these script are pyspark, seaborn, re


## File Description
Sparkify.ipynb: the jupyter file that relates to the data exploration, data modeling process. The final output of this scrpit is a trained model.

## Results
### Model Evaluation and Validation
In the very begining of this study, I am meant to use Logistic Regression Model instead of this Random Forest. However, per quick test run, the model metrics score is not as high as expected. Therefore, I switch to use Random Forest, which successfully increases the result as expected. In terms of the model hyperparameters, as per my past experience with scikit-learn package, the num of trees and tree depath are two areas worthwhile to try.

### Justification
By using level, gender to train the model, the successfully rate to predict the loss of client is around 85%. We have tried following methods to achieve this result.
- testing on different models; 
- tuning the model hyperparameters; 
- using cross validation 


## Conclusion
### Reflection
As per above modeling process, we now have generated a well trained model that can be used to predict if the user will lose based on gender and level details. Throughout this study, the build of model pipeline is silghtly difficult especially when we need to deal with multiple categorical variables.

### Improvement
For furture cases, we could try to include the number of variables considered, trying to achieve a better F1 Score. Meanwhile, the current model is run on a local machine to predict static data. A better way to do this is to deploy this model to a server so that once the user is labelled with high potential to lose, we could quick find out and take actions.
