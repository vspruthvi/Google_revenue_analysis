# Google_revenue_analysis

This is the repository for the kaggle challage<br />
## Google Analytics Customer Revenue Prediction<br />
### Predict how much GStore customers will spend<br />


### What am I predicting?<br />
We are predicting the natural log of the sum of all transactions per user. Once the data is updated, as noted above, this will be for all users in test_v2.csv for December 1st, 2018 to January 31st, 2019. For every user in the test set, the target is:<br />
yuser=∑i=1ntransactionuseri<br />
targetuser=ln(yuser+1)<br />
Note that the dataset does NOT contain data for December 1st 2018 to January 31st 2019. You must identify the unique fullVisitorIds in the provided test_v2.csv and make predictions for them for those unseen months.<br />

