# Titanic-Machine-Learning-from-Disaster-MATLAB
The goal of this project is predicting the survival of passengers based on a set of data. Necessary data is retrieved from
 Kaggle competition "Titanic: Machine Learning from Disaster".
 
## Basic Usage 
* .m files should be opened with MATLAB. 
* Datasets should be in the same path with the code, if not path of the datasets must be set manually or fixed in the code.
```
titanic_train = readtable('titanic_train.csv');
titanic_test = readtable('titanic_test.csv');
```
* Project consists a for loop for calculating the average accuracy for a number of iterations. Hence it will take longer time to perform calculations, it is initially set to zero. You can change it if you want to calculate the average/general accuracy score.

* For exporting .csv file the local file path must be changed in the code.
```
writetable(Resulttable, 'resultedtable.csv');
```
 
## Predictions_for_Kaggle
Contains training, optimization of the training model, and performing prediction for partitioned training set's test data and kaggle's test data. Exports .csv file for Kaggle submission. Submission has 0.78947 score in Kaggle competition.

## Titanic_with_DecisionTree
In this file prediction and testing is only done by using training data to calculate average accuracy. It has about 0.80380 average score.
![Kaggle result](https://github.com/ozlemkorpe/Titanic-Machine-Learning-from-Disaster-MATLAB/blob/master/images/treegraph.jpg)


## Results
![Kaggle result](https://github.com/ozlemkorpe/Titanic-Machine-Learning-from-Disaster-MATLAB/blob/master/images/kaggle.png)
## Authors
* **Özlem Körpe** - *Initial work* - [ozlemkorpe](https://github.com/ozlemkorpe)

