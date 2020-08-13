# Machine Learning Engineer Program

This repository is a project portfolio for the "Machine Learning Engineer" certification program by Udacity. This program prepares students for a career as a machine learning engineer by helping them learn machine learning tool sets and understand various regression, classification and other machine learning algorithm and their performance metrics. 

The "Machine Learning Engineer" program is made up of 5 projects, including a capstone project. Each project has its own rubric and program coaches at Udacity review the projects based on these rubrics. To complete the program, all project must be reviewed and approved by the coach.

Each folder in this repository is a collection of the working and data files for a project. The name of the folder starts with a subject of machine learning instructed in the program, followed by the title of the project associated with that subject. The coach's review of the project is saved as "Project_Review_by_Coach" in PDF format.

---

## Model Evaluation and Validation

Skills/knowledge learned:
- Using NumPy to explore data and investigate the latent features of a dataset
- Training and testing models
- Analyzing learning performance and identify potential problems, such as errors due to bias or variance
- Applying techniques to improve the model, such as cross-validation and grid search

### Project: "Predicting Boston Housing Prices"

For this project, I need to use supervised learning techniques to predict the price of houses in Boston. Practices such as splitting datasets, cross validation, evaluation metrics for classification are also discussed. The goal is to choose the best performing model from many options and get familiar with hyper-parameter tuning. The dataset for this project is a modified version of the famous Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing). The dataset consists of 489 data points, with each datapoint having 3 features.

---

## Supervised Learning

Skills/knowledge learned:
- Identifying when preprocessing is needed and how to apply it
- Establishing a benchmark for a solution to the problem
- Understanding what each of several supervised learning algorithms and their arguments accomplish
- Evaluating how each algorithm performs as the best solution model to the problem

### Project: "Finding Donors for CharityML"

The task for this project is to analyze a census dataset and identify possible donors with supervised learning algorithms for a charity organization. Students are expected to select and compare different supervised learning models and choose the best performing one.

The dataset for this project is a modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* by Ron Kohavi. (https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf). The original dataset is hosted on https://archive.ics.uci.edu/ml/datasets/Census+Income.

---

##  Deep Learning

Skills/knowledge learned:
- Understanding the architecture of convolutional neural network (CNN) models, including how different design of layers and kernel size can change the result
- Understanding the challenges involved in putting together a series of models designed to perform various tasks in data processing pipeline

### Project: "CNN Dog Breed Classifier"

The task for this project is to build CNN models that process an image of a dog. The algorithm would be able to give an estimate of the dog's breed. If an image of a human instead of dog is processed, the model would identify the resembling dog breed. Students are expected to select and compare different models and choose the best performing one. 

---

## Unsupervised Learning

Skills/knowledge learned:
- Applying preprocessing techniques such as feature scaling and outlier detection
- Interpreting data points that have been scaled, transformed, or reduced from PCA
- Analyzing PCA dimensions and construct a new feature space
- Clustering data to find hidden patterns in a dataset
- Assessing information provided by cluster data 

### Project: "Creating Customer Segments"

The task for this project is to apply unsupervised learning techniques on the customer dataset of a wholesale distributor in Lisbon, Portugal. At first, a small subset of the sample is selected to determine if any product category is highly correlated with one another. After scaling each product category and removal of unwanted outliers, PCA transformation is applied to the data and different clustering algorithms implemented to segment the transformed customer data. The goal is to identify hidden customer segments in the dataset.

---

## Capstone Project

The task for capstone project is to solve a problem of my choice by applying machine learning algorithms and techniques I have learned from the program. 

The guidelines below are followed throughout this project:

1. Define the problem 
2. Investigate potential solutions and performance metrics
3. Analyze the problem through visualization and data exploration
4. Select the algorithms and metrics based on the analysis and implement them
5. Collect the results of algorithm models and validate the values
6. Construct conclusions 

The question I wanted to answer in this project is "what factors predict strong retention and graduation rate in U.S. higher education institutions?" A research finding shows that Americans with a bachelor’s degree can earn a million dollars more throughout their entire career in comparison to those without. However, what makes one school better in retention and graduation rate than others? I analyzed the data collected by the U.S. government on 6,806 U.S. higher education institution and applied supervised learning algorithms to identify a few strong predictors out of 190 factors. 

Skills/knowledge learned:
- Researching and investigating a real-world problem
- Applying specific machine learning algorithms and techniques 
- Analyzing and visualizing the data and results for validity
- Documenting and writing a report of the work
