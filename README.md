**DSG-assignment**<br />
===
To predict whether a given mushroom sample is edible or poisonous.

**ML algorithms used:**
* Random Forest
* Xgboost
* Gradient Boosting Classifier

**Python libraries used:**
* Pandas
* Numpy
* Sklearn

**Approach**<br />
1.I performed data-visualisation by some plots.<br />
2.Than I used one-hot encoding and checked for missing values in the dataset (data-preprocessing).<br />
3.I divided the traing data into seperate train and test sets. Cross-validation is applied on train set to help fine-tune each of the 3 models but since the CV_accuracy for all 3 came out to be 1 so I didn't engage hyperparameter tuning .<br />
4.The 3 are than compared based on their accuracy on test set. The best one is selected.<br />
5.I made the final predictions on mushroom-test.csv after doing the same data-preprocessing on it as on mushroom-train.csv.<br />
