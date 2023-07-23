# Job Runtime Prediction Assignment

Welcome to the Data Scientist Student Position Assignment! 
In this assignment, your objective is to create a model that predicts the run time buckets in hours for jobs that run on Intel's private cloud. 
We will provide you with a dataset containing job features and their corresponding run times in seconds. 
Your task is to build a pipeline for predicting job runtimes of the test set.

## Dataset Description

The train dataset provided for this assignment consists of the following columns:

- Features_i: Each job is represented as a row of features that describe various aspects of the job.
- Seconds: The time it took for each job to run, represented in seconds.

## Task
### [Google Colab Assignment Notebook](https://drive.google.com/file/d/1OQ2j2iG1uphHp0NKGO9Ruo_ForaaORGS/view?usp=sharing)
Your task is to create a pipeline for predicting job runtimes in hours. 
We expect you to follow the framework of the given example model provided in the notebook.
Make sure you create a copy of this notebook to work on your own google drive.
However, you are free to use any model of your choice, as long as it adheres to the provided example's structure.

## Evaluation

Your pipeline will be evaluated on an external test set that we provide. 
This test set does not contain the run time values and is sampled from the same distribution as the training dataset you will be given. 
The performance of your model will be measured using a function provided in the notebook.

## Submission Instructions

Please ensure that your submission includes the following components:

1. **Code for the Pipeline:** Include all the code used for creating the pipeline by downloading the google colab notebook file (Job Runtime Prediction Assignment.ipynb).

2. **"y_preds.csv" File:** Provide a CSV file named "y_preds.csv" that contains the predicted run time buckets in hours for the test set.

## Scoring

We have provided a function in the notebook to calculate the score based on a list of y_predictions and y_labels. 
This function will be used to evaluate the performance of your model on the test set.

## Important Notes

- Code should run on Google Colab notebook.
- Avoid overly complex deep learning solutions, focusing on efficient machine learning models instead.
- Ensure your code is well-documented and easy to understand.
- Feel free to use any libraries and tools you find suitable for the task.
- If you use any external sources or references in your solution, provide proper citations.



We hope this assignment will provide you with an opportunity to showcase your data science skills and creativity.

If you have any questions or clarifications, please don't hesitate to reach out to us.

Good luck!
