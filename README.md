# Newsletter Churn Prediction 
## The Problem:
* We are given a company newsletter service dataset, containing various information on the usage details and other information about each user
* Given this dataset, we must build a predictive model predicting whether people will opt out of the newsletter
* The predictive model(s) must have as high an accuracy as possible, given the dataset and it’s limitations

## The Data:
The dataset consists of roughly 700,000 samples which were collected from the newsletter subscribers. The information collected is as follows:
* The user’s unique ID along with their domain and how their engagement status with the newsletter has changed
* If their engagement status has changed to opt out then the opt out time and date is also collected
* The date they signed up for the newsletter and lifetime statistics such as their number of opens and clicks as well as their last open and last click time and date and their lifetime messages
* Some personal information which includes their geolocation, their prefered device, their name, and finally, their reading preference list
* Our Y column(target) is ‘Engagement’
* The dataset can be downloaded at https://s3.amazonaws.com/orim-misc-data/assessment/subscribers.csv
![Alt Text](https://github.com/rohan-chandr/Newsletter-Churn-Prediction-/blob/master/data.jpg)

## The Solution:
https://github.com/rohan-chandr/Newsletter-Churn-Prediction-/blob/master/Newsletter-Churn.ipynb

## The Results:
* Decision Tree:
    * Opt-out Accuracy: 60.8%
    * Subscribed Accuracy: 67.6%
* SVM:
    * Opt-out Accuracy: 77.3%
    * Subscribed Accuracy: 85.1%
* Random Forest:
    * Opt-out Accuracy: 96.5%
    * Subscribed Accuracy: 80%

For detailed results,along with a rough explanation of each algorithm and the steps taken to implement, check out the following:
https://github.com/rohan-chandr/Newsletter-Churn-Prediction-/blob/master/Rohan-Churn_prediction.pdf

## How this could impact Businesses:
Actively prevent customer turnover by intervening with at-risk customers(potentially saving companies millions, depending on number of subscribers)



