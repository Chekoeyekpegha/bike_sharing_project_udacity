# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### AKPOJICHEKO EYEKPEGHA
AKPOJICHEKO EYEKPEGHA
## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: Add your explanation
What I realised was there were some negative values which was advised by the template to convert them to 0 which I did. I do not know the reason why but the negative values were probably unwanted outliers?
### What was the top ranked model that performed?
TODO: Add your explanation
WeightedEnsemble_L2
## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: Add your explanation

### How much better did your model preform after adding additional features and why do you think that is?
TODO: Add your explanation
There was only a little difference between my initial and new feature model. I believe the new feature I created was probably not the best feature that can be created.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: Add your explanation
After trying different parameters, there was a significant reduction in the root mean square error, which is relatively a high performance among my submissions  



### If you were given more time with this dataset, where do you think you would spend more time?
TODO: Add your explanation
I would spend more time in understanding the dataset and creating better new features, if possible more than one feature. If the new features minimises the root mean square error (rmse)greatly, It is more likely to be reduced even more with the best hyperparameter tuning. I would also spend more time in choosing the best hyperparameter with scikit learn 



### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
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
TODO: Add your explanation
This is my first time using Amazon sage maker with Autogluon and I find it interesting, I hope to learn, understand and practice more to build my skills in machine learning using AWS. The inspirations from my code were gotton from the autogluon website, Udacity knowledge page and questions answered on stack overflow(On how to set negative values to zero)
https://www.geeksforgeeks.org/python-pandas-dataframe-astype/#:~:text=astype()%20method%20is%20used,existing%20column%20to%20categorical%20type.&text=Basic%20Level%20Course-,DataFrame.,type%20to%20another%20data%20type
https://auto.gluon.ai/stable/tutorials/tabular_prediction/tabular-indepth.html?highlight=hyperparameter