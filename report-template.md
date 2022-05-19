# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Timothy Horton

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
Kaggle needed to be installed.  The project template sucks - incorrect comments.

### What was the top ranked model that performed?
The initial model with no new features or hpo.  The others came back from kaggle with errors after 6 hours of trying.

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
Nothing found.  Converted datetime, added "hour" attribute, converted features to categories.

### How much better did your model preform after adding additional features and why do you think that is?
None at all.  After initial success, Kaggle kept giving errors for modified regressions, even after hours of trying.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
None at all.

### If you were given more time with this dataset, where do you think you would spend more time?
Finding a better course with fewer gotchas and many fewer moving parts, like AWS that takes 4 minutes to come up.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
What is the meaning of hpo1/2/3?  This is nonsensical.

|model|hpo1|hpo2|hpo3|score|
|--|--|--|--|--|
|initial|?|?|?|?|
|add_features|?|?|?|?|
|hpo|?|?|?|?|

### Create a line plot showing the top model score for the three (or more) training runs during the project.
TODO: Replace the image below with your own.
![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.
TODO: Replace the image below with your own.
![model_test_score.png](img/model_test_score.png)

## Summary
Crap course, too many moving parts, few references, no way to get past errors from kaggle.