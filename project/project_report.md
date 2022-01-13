# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### YULIANA ANDREA FERNANDEZ CARVAJAL

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
Negative values needed to be removed and predictions assigned to the appropriate dataset.

### What was the top ranked model that performed?
The model performed better when new features were added.

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
It was found that the behavior by hours provides a lot of information and for this reason this variable is added. The hour is taken of the datetime.

### How much better did your model preform after adding additional features and why do you think that is?
The behavior is much better because the new variable provides a lot of information to the models.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
The model improved but not too much.

### If you were given more time with this dataset, where do you think you would spend more time?
I would spend more time adjusting the hyperparameters of the models.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|score|
|--|--|
|initial|1.39|
|add_features|0.52|
|hpo|0.50|

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)