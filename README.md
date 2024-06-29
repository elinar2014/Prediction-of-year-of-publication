# Prediction-of-year-of-publication
Config files for my GitHub profile.
Prediction of year of publication
In this challenge, the task is to predict the year of publication of scientific papers, based on their metadata.
Data files
The dataset is available for download on Canvas. It contains the following files:
•	train.json Download train.json: the metadata including the year of publication of all the papers in the training data.
•	test.json Download test.json: the metadata of the papers in the test data, excluding the year of publication.
Both of these files are in the JSON format. You can load them using the JSON.load function. The loaded data will consist of a list of 
Python dictionaries, with each dictionary corresponding to the record for one paper. The training records specify the year of
publication under the key year. For the test data this information is missing, and your task is to predict it. 
The other keys have descriptive names indicating the nature of the information: e.g. title, and abstract.
Evaluation metric
The evaluation metric for this task is Mean Absolute Error. Specifically, the following Python code is used for the evaluation of the predictions:
