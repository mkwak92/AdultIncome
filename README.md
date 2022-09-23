# Adult Income


# Predicting Income in Adults
##  The goal of this is to help predict whether an adult makes less than or above $50k based on certain features

**Author**: Matthew Kwak

### Business problem:
Make predictions about income based off the data that is provided based on features provided

### Data:
- Age: Age of the person
- Workclass: What type of work is the person in
- fnlwgt: ID of workclass (continous)
- Education:	Highest education a person has completed
- Education-Num:	Corresponding number for Education
- Maritial-Status:	Person's maritial status
- Occupation:	Occupation of person
- Relationship:	Type of relationship 
- Race: What ethnicity is the person
- Sex:	Male/Female
- Capital-Gain: Whether person has capital gain
- Capital-Loss:	Whether person has capital loss
- Hours-per-week: How many hours the person works
- Native-country: What country is the person

## Methods
- Load Data
- Data Cleaning (missing values, duplicate values, null values)
- Preprocessing
- Exploratory Vizulations
- Explantatory Vizulations
- Machine Learning
- Preprocessing
- Train/Test Split
- Regression Metrics
- PCA

## Model - Logistic Regression
# Recommendation:
- My recommendation would be to use the Logistic Regression. The Logisitic Regression had an accuracy of 85.28% with a decision threshold of .45. The Logisitc Regression had a higher R2 with .187855. Using .45 as the threshold, this model has a Type2 Error of .36. Currently, as the model is created, the Type2 error is too high and may not be able to predict if an adult made over 50k. We could perform some adjustments such as making the positive class "less than or equal to 50k, as the model was able to predict this well. 

#### 
(![AdultIncome](https://user-images.githubusercontent.com/109184607/191960121-cdf2f8ce-8ac1-469a-b31a-74340a75153a.png)

