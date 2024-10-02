# Report: Predict Bike Sharing Demand with AutoGluon Solution
Sahar Youssef

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
I realize when I tried to submit my predictions that I need to do more reasearchs and read more documentation on the Autogluon models .Also the changes that were needed to the output of the predictor to submit my results were to set the negative values to zero.

### What was the top ranked model that performed?
the top ranked model that performed was: "WeightedEnsemble_L3"

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
Through the exploratory analysis I found that it's better to split the datetime to more features like : year, month , day, hour in order to explore more those features . Also I found that it's better to change the season and weather to category.

### How much better did your model preform after adding additional features and why do you think that is?
The model improved from score of 1.79972 to a score of 0.61562. I think the reason is because that I split the datetime to to more features  : year, month , day and hour.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
The model performs better than the initial model but a little bit worse than the model with more features.

### If you were given more time with this dataset, where do you think you would spend more time?
If I was given more time with this dataset, I think I will spend more time discovering the hyperparameters tuning and trying to improve the model more by using diffrent parameters.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|--|--|--|--|--|
|initial|default|default|default|1.79972|
|add_features|default|default|default| 0.61562|
|hpo|GBM|KNN|RF|0.73264|

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![train.png](img/train.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![test.png](img/test.png)

## Summary
In conclusion, Through this project I learned that autogluon models are a strong tool for automation ML workflow.Also we should analyse the data and try to add more features in order to try to improve the model results. Add to that, the hyberparameters tuning is a strong tool also to try to improve the model, but we should try diffrent hyperparameters in order to find the suitable one that gives us a better results.
