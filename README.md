# Gender_Pay_Salary_Prediction

## Introduction

This python project is developed based on the three datasets collected from Kaggle.com at: https://www.kaggle.com/theoviel/kagglers-gender-pay-gap-salary-prediction. The three datasets: surveySchema.csv, freeFormResponses.csv, multiple-ChoiceResponses.csv.

For this project, I choose multiple-ChoiceResponses.csv to analyze. This dataset includes 23860 observations of male and female who took part in the survey. It contains 395 columns for personal information and the related. 

## Tasks

# 1. 
Calculate the median income of male employees and the median income of female employee in the population (look the set of all employees in the datasets as the population).

# 2. 
Draw an overlaid graph to show the histograms of the incomes of female and male employees in the population (the two histograms will be displayed in the same graph with different colors).

# 3.
Use the random sampling, empirical distribution, sample comparison, bootstrap, hypothesis testing as well as A/B testing we discussed in the class to analyze the income gap between female and male employees.

    * Select a sample from the population.
    * Draw the income histogram for the sample, calculate the median income of the sample, and draw a reddot and a yellow dot of the female median income and male median income of the population, respectively, in the histogram.
    * Draw the histogram of the test statistic of the sample, and draw a red dot to show the corresponding teststatistic of the population (e.g. the difference of the median incomes between female and male employees) in the diagram.
    * Write a procedure to use bootstrap to produce at least 5000 samples and Draw the histogram of the test statistic of the bootstrap samples.
    * Define confidence interval and P-value to validate the hypothesis you defined
