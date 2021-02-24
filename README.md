# ThyroidDetection

This project helps to build a classification method to predict the type of Thyroid based on the  training data.
The user can send data in multiple sets of files in batches at a given location. Data will contain different classes of thyroid and 30 columns of different values.
Apart from training files, we also require a "schema" file from the user, which contains all the relevant information about the training files such as: 

Name of the files, Length of Date value in FileName, Length of Time value in FileName, Number of Columns, Name of the Columns, and their datatype. 
Requirements.txt file consists of all the packages that you need to deploy the app in the cloud. 
Main.py is the entry point of our application, where the flask server starts.  predictionFromModel.py file where the predictions take place based on the data we are giving input to the model.
