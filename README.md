# Prediction-of-year-of-publication

The task description is
 to predict the year of publication of scientific papers, based on their metadata files

The dataset is available for download. It contains the following files:
•	train.json Download train.json: the metadata including the year of publication of all the papers in the training data.
•	test.json Download test.json: the metadata, excluding the year of publication of the papers in the test data.
Both of these files are in the JSON format.
The training records specify the year of publication under the key year.
For the test data this information is missing, and the task is to predict it. 
The other keys have descriptive names indicating the nature of the information: e.g. title, and abstract.

Evaluation metric

The evaluation metric for this task is Mean Absolute Error. Specifically,
the following Python code is used for the evaluation of the predictions:
