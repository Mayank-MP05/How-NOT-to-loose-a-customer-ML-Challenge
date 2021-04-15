# How-NOT-to-loose-a-customer-ML-Challenge
### Problem
Churn rate is a marketing metric that describes the number of customers who leave a business over a specific time period. . Every user is assigned a prediction value that estimates their state of churn at any given time. This value is based on:

#### User demographic information
Browsing behavior
Historical purchase data among other information
It factors in our unique and proprietary predictions of how long a user will remain a customer. This score is updated every day for all users who have a minimum of one conversion. The values assigned are between 1 and 5.

### Task
Your task is to predict the churn score for a website based on the features provided in the dataset.

### Data description
The dataset folder contains the following files:

```
train.csv: 36992 x 25
test.csv: 19919 x 24
sample_submission.csv: 5 x 2
```

```score = 100 x metrics.f1_score(actual, predicted, average="macro")```
