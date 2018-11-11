# Google_revenue_analysis

This is the repository for the kaggle challage<br />
## Google Analytics Customer Revenue Prediction<br />
### Predict how much GStore customers will spend<br />


### What am I predicting?<br />
We are predicting the natural log of the sum of all transactions per user. Once the data is updated, as noted above, this will be for all users in test_v2.csv for December 1st, 2018 to January 31st, 2019. For every user in the test set, the target is:<br />
yuser=∑i=1ntransactionuseri<br />
targetuser=ln(yuser+1)<br />
Note that the dataset does NOT contain data for December 1st 2018 to January 31st 2019. You must identify the unique fullVisitorIds in the provided test_v2.csv and make predictions for them for those unseen months.<br />


the jupyter notebook is selft explanatory.<br />

I have excluded the hits and custom dimentions columns which were added in the dataset recently as the dtata was not getting loaded.
and the analysis has been done taking 9lakh training points and 3lakh testing point because of limited computational power. <br />

A small overview of the analysis would be as follows <br />

1. data processing: <br />
Here I analysed the data and cleaned it. wherein I flattened json columns, convereted date to proper format, filled null values, analysed the columns which are not important and deleted them. <br />

2. visualization: <br />
Here I visualized the dependence of our target column revenue on various attributes and made conclusions <br />

3. prediction: <br />
here i ran the data through an algorithm to make the necessary predictions <br />


