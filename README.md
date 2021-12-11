### Banknote authentication prediction with RandomForest with hyperparameter tuning

AIM:
Our goal is to create a model that can help predict whether a note is genuine or not.

Dataset Used:
It can be found at my repository.

![download](https://user-images.githubusercontent.com/86251750/145685022-a76e8601-cda0-4d1c-ae32-1e4a6673a82e.png)

## using RandomForest for prediction:

Random forest is a type of supervised learning algorithm that uses ensemble methods (bagging) to solve both regression and classification problems. The algorithm operates by constructing a multitude of decision trees at training time and outputting the mean/mode of prediction of the individual trees.

The fundamental concept behind random forest is the wisdom of crowds wherein a large number of uncorrelated models operating as a committee will outperform any of the individual constituent models.

The reason behind this is the fact that the trees protect each other from their individual errors. Within a random forest, there is no interaction between the individual trees. A random forest acts as an estimator algorithm that aggregates the result of many decision trees and then outputs the most optimal result.

![randomforest](https://miro.medium.com/max/480/1*w-b0xHDoUsCcwx4nY3x5Og.gif)

** Evaluting model performance**

                precision   recall   f1-score   support

           0       1.00      0.98      0.99       124
           1       0.98      1.00      0.99        82

    accuracy                           0.99       206
