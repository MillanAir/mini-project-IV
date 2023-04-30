# Mini-project IV

### [Assignment](assignment.md)

## Project/Goals
The goal of this project is to predict whether the loan will be approved or not.

Based on the data provided below:
1. Gender, Married, Education, Dependents, Total Income, Loan Amount, Credit History, Property Area

We have to predict the whether the loan will be approved or not.

## Hypothesis

1. Married people will have more chances of getting loan approved.

## EDA 
I have used the following techniques to explore the data:

## Process
### Distribution of Income data was skewed and had outliers. So, I used log transformation to make it normal.
### There were some missing values in the data. I used mean and mode to fill the missing values.

## Results/Demo
(fill in your model's performance, details about the API you created, and (optional) a link to an live demo)
My model's accuracy is 80%. I have created an API using Flask and deployed it on AWS. The API takes the following inputs:
- Gender, Married, Education, Dependents, Total Income, Loan Amount, Credit History, Property Area

- Based on my hypothesis, I found that large amount of married people got loan approved. However, the number of applicants in unmarried people were less than married people. Further, the ratio of getting loan approved was about the same. So, I cannot say that married people have more chances of getting loan approved.

## Challanges 
- AWS Flask deployment and pipeline building was a bit challenging.

## Future Goals
- I would like to explore more features and see if I can improve the accuracy of my model.