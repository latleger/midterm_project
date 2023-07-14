# Midterm Project

## Project Goals
Build a model to predict who would most likely survive the Titanic

## Process
1. Download data from Kaggle
2. Clean and Review data
3. Create EDAs and Models - we built two separate EDA and models to compare
4. Compare and evaluate results
5. Create Visualizations
6. Present findings

## Results

For this dataset, I tried to use a Linear Model, however, the outputs were skewed. I realized classification models would work better for this dataset. 

I also used a Logistical Regression Model to confirm accuracy. I used Survived as my dependent variable and Ticket class, Sex, Age, Relatives, and Embarked as my independent variables. 

I also used the Random Forest model on the Titanic dataset to predict survival based on the same variables. The model has noted Ticket class and Sex are Feature Importance, which is similar to the heatmap correlation. First-class passengers are more likely to survive due to their wealth and access to lifeboats. Female passengers are more likely to survive due to the priority given to women and children. Passengers with fewer relatives are more likely to survive due to their care from other passengers. Age and embarked are also correlated with survival, but to a lesser extent.

Therefore, based on the data, a 1st class woman in her 20s, travelling with 3 or fewer relatives would be most likely to survive. 

## Challenges

My biggest challenge was agreeing on a dataset. 

## Future Goals

Look for more correlations in the data and build a better model to increase accuracy. 

