# Drug Classification Using Neural Networks - Assignment - 5 (Data-1202)

## Description

In the DATA 1200 course, we worked on a project using an Artificial Neural Network (ANN). The project involves training the model with data, testing how well it works, and improving it. We will write the code in Python using a neural network model from the Phyton library.

To share our work and help others follow along, we will set up a GitHub repository. 
It will include:

A README.md file explaining the project, how the code is organized, how to set it up, and how to run it.
The Python code for the ANN.
Information in the README.md about common problems and how to fix them.
Using GitHub helps keep track of changes and allows others to collaborate and use our project easily.

The script preprocesses the data, splits it into training and test sets, scales the features, trains a neural network model, and evaluates its performance using confusion matrix and classification report.

## Getting Started

We will be using a csv file "drugsetdata.csv" which has the data of Age,	Sex,	BP,	Cholesterol,	Na_to_K, Drug

For this script, we used Jupyter.

### Installing

Clone the repository:
   
    - https://github.com/stevensam07/Assignment-5.git
  
  ### Prerequisites

Ensure you have Python installed on your machine. This script also requires the following Python libraries:

    - import pandas as pd
    - import numpy as np
    - import matplotlib.pyplot as plt
      %matplotlib inline

### Running the Tests

Run the HTML attached to run the Tests on the Model

    - Assignment 4 (2).html

### Breakdown of Tests

The model's performance is evaluated using a confusion matrix and classification report. It calculates the precision, recall, F1-score, and accuracy for the five drug categories (drugA, drugB, drugC, drugX, drugY).

The following evaluation metrics are used:

Precision: The accuracy of positive predictions.

Recall: The ability of the model to identify all relevant instances of a drug.

F1-score: A weighted average of precision and recall.

Accuracy: The overall correctness of the model.

### Deployment

You can deploy this model in an application where drug prescriptions need to be predicted based on patient features. The model can be integrated into a web app or medical diagnostic system.

### Author

Steven Sam / 100940630 - Durham College, Oshawa, Ontario Canada

### License

This project is licensed under the MIT License.

### Acknowledgments

Inspiration for the project was taken from various machine learning tutorials and online video and used references:

`https://gist.github.com/PurpleBooth/109311bb0361f32d87a2`

`https://www.linkedin.com/learning/git-essential-training-19417064`
    

