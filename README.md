**DSG-assignment**<br />
===
To predict whether a given mushroom sample is edible or poisonous.

**ML algorithms used:**
* Random Forest
* Xgboost
* Gradient Boosting Classifier

**Approach**<br />
1.First data-visualisation and data-preprocessing is done.<br />
2.The training data is divided into train and test sets.Cross-validation is applied on train set to help fine-tune each of the 3 models if needed.<br />
3.The 3 are than compared based on their accuracy on test set. The best one is selected.<br />
4.The final predictions are made on mushroom-test.csv after doing the same data-preprocessing on it as on mushroom-train.csv.<br />
