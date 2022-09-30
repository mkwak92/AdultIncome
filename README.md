# Adult Income


# Predicting Income in Adults
##  The goal of this is to help predict whether an adult makes less than or above $50k based on certain features

**Author**: Matthew Kwak

### Business problem:
Make predictions about income based off the data that is provided based on features provided. We are able to predict a person's income range and analyze if some factors are more influenced to receive a higher income. This is important to show that young people who are thinking about going possibly dropping out of school or want to attend higher education that staying in school will provide stabile income. We can also see if there is a race and gender pay gap. 

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

## Analysis/Trends
- While reviewing the dataset, it was found that our of the total females, only around 11% made over 50k while around 30% of males made over 50k. This is a 1:3 difference of the amount of males making over 50k than females. We do have twice as many males than females which may contribute to the percentage disparity for income. 

![gender_income](https://user-images.githubusercontent.com/109184607/193179542-67c44330-fab3-4e79-985d-e5a18ccea598.png)

![gender](https://user-images.githubusercontent.com/109184607/193181059-ccf6f7bb-4c69-4a9c-bfc3-59158c52d35f.png)

- Another disparity that was found, was the Race and the percentage of over 50k. While the Asian-Pac-Islander and White races had around 25% of their population make over 50k, the Amer-Indian-Eskimo, Black, Other  races only had around 11% of their population make above 50k. The dataset is also very heavily White dominated. 

![race_income](https://user-images.githubusercontent.com/109184607/193179817-6dd9e1a4-7eff-4cfe-92cd-3abe0c503516.png)

![race](https://user-images.githubusercontent.com/109184607/193181006-1a81d09b-2fc8-4948-b52e-a8371ae9493b.png)

## Model - Logistic Regression
# Recommendation:
- My recommendation would be to use the Logistic Regression. The Logisitic Regression had an accuracy of 85.28% with a decision threshold of .45. Using .45 as the threshold, this model has a Type2 Error of .36. Currently, as the model is created, the Type2 error is too high and may not be able to predict if an adult made over 50k. If we were to use this model, it could help predict how much effect education, occupation, and race lead to higher income. 
- An accuracy of 85.28% is fairly strong especially with this training data having 36,592 rows data. This model was able to predict the make less than 50k income at 92%, so my recommendation would be to use this model to help predict this group. By researching this group more, we can figure out ways to create more equity in features such as education and occupation to the groups who need it most.
#### 
![AdultIncome(2)](https://user-images.githubusercontent.com/109184607/191960458-4a40ec92-b0bd-46d3-8d58-526a513df6cb.png)


