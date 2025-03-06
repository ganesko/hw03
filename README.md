[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YAqJ2nm6)
# hw03

## Description
The purpose of this homework is to practice LDA, QDA, Naive Bayes, and comparing models by looking at classification errors. 

## Instructions

For this assignment you will work with the camera_dataset.csv included in this repository. Add a column to your dataset called "pRange". For each camera, pRange should be "high" if the camera's price is greater than $399, "medium" if it is less than or equal to $399 but greater than $150, and "low" otherwise. "pRange" is the class your models will predict. In your models, use all variables except Model and Price to predict pRange.    

For your models below, use camera's released before 2005 (from 1994 - 2004) as training data, and cameras released beyond 2005 (2005 - 2007) as testing data.  

### Part 1: LDA 

Fit an LDA model to your data. 

What proportion of high, medium, and low does your training data have for pRange? 

Predict pRange for your test data. Generate the confusion matrix for your predictions. What is the overall error rate? What is the error rate within each pRange class? Does error seem to be particularly bad within any one class? 


### Part 2: QDA

Fit a QDA model to your data. 

Predict pRange for your test data. Generate the confusion matrix for your predictions. What is the overall error rate? What is the error rate within each pRange class? Does error seem to be particularly bad within any one class? How does this differ (or not) from what you saw in your LDA model?  


### Part 3: Naive Bayes 

Fit a Naive Bayes model to your data. 

Predict pRange for your test data. Generate the confusion matrix for your predictions. What is the overall error rate? What is the error rate within each pRange class? Does error seem to be particularly bad within any one class? How does this differ (or not) from what you saw in your LDA and QDA models? 

### Part 4: Model Assumptions

Think about the assumptions that each model you generated makes. Which do you think is most realistic for this particular dataset? 

Did the model that theoretically models this data best perform the bets among all the models you tried? Explain your answer.  
   

## Submission and Grading
Please see the assignment overview from the course website for submission instrucitons and rubric. 