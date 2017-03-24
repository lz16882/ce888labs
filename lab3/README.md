# Lab3


In the Ipython notebook I created

* Load the data from `bank-additional-full.csv`
* Use the classifier ExtraTreesClassifier with 100 estimators on the data with outcome/output variable "y"
* Convert to dummies using `df_dummies = pd.get_dummies(df)`
* Use`del df_copy["y_no"]` and `del df_copy["duration"]` delete columns "y_no" and "duration"
* Plot histogram of the label `y_yes` as followed
![snsfig](./snsfig.png?raw=true)
* Use outcome `y_yes` Get the values and run a classifier based on outcome `y_yes`. The Dummy ACC value is 0.90.	
* Report the results of 10-Kfold stratified cross-validation: ACC: 0.82 (+/- 0.14)
* Get sample importances as followed and a confusion matrix
![importances](./importances.png?raw=true)

![confusion_new](./importances.png?raw=true)


