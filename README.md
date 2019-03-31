# Udacity_Spark
This purpose to build this prediction model is to predict the loss of current clients.

## Initialization
The pacakges required for running these script are pyspark, seaborn, re


## File Description
Sparkify.ipython: A data clean function, which takes in raw data and output the combined datasets used in the modeling process. A typical way to call this funciton is like "python process_data.py disaster_messages.csv disaster_categories.csv"

train_classifier.py: A modeling function, which use the cleaned dataset to create a text classification model. A typical way to call this funciton is like "python train_classifier.py DisasterResponse.db classifier.pkl"

run.py The start function, which can start a webpage to display the dataset visualization and key-in message for classification. A typical way call this funciton is like "python run.py"
