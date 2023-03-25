# Gold-price-prediction
## Introduction
Historically, gold had been used as a form of currency in various parts of the world including USA. In present times, precious metals like gold are held with central banks of all countries to guarantee re-payment of foreign debts, and also to control inflation which results in reflecting the financial strength of the country.
Forecasting rise and fall in the daily gold rates, can help investors to decide when to buy (or sell) the commodity.
We in this project would forecast gold rates using the most comprehensive set of features and would apply various machine learning algorithms such as Random Forest Regressor. We also identify the attributes that highly influence the gold rates.

## Random Forest Regressor
Random Forest Regression is a supervised learning algorithm that uses ensemble learning method for regression. Ensemble learning method is a technique that combines predictions from multiple machine learning algorithms to make a more accurate prediction than a single model. It operates by constructing several decision trees during training time and outputting the mean of the classes as the prediction of all the trees.
The basic idea behind this is to combine multiple decision trees in determining the final output rather than relying on individual decision trees. Random Forest has multiple decision trees as base learning models.
The flow-chart depicting Random Forest Algorithm is shown below :
![2023-03-25](https://user-images.githubusercontent.com/95615695/227709131-30b8a8e2-c04a-4df7-9204-fc8839a47ea6.png)

The diagram above shows the structure of a Random Forest. You can notice that the trees run in parallel with no interaction amongst them. A Random Forest operates by constructing several decision trees during training time and outputting the mean of the classes as the prediction of all the trees. To get a better understanding of the Random Forest algorithm, let’s walk through the steps:
* Pick at random k data points from the training set.
* Build a decision tree associated to these k data points.
* Choose the number N of trees you want to build and repeat steps 1 and 2.
* For a new data point, make each one of your N-tree trees predict the value of y for the data point in question and assign the new data point to the average across all of the predicted y values.
## WORK FLOW
![2023-03-25 (1)](https://user-images.githubusercontent.com/95615695/227709360-dd94162d-235b-49b2-87a8-1fabf42f28f3.png)
## CONCLUSION
Hence as we saw in our implementation, we first train a machine learning model, then use the trained model for prediction. Similarly, any model can be made much more precise, by feeding a very large dataset, to get a very accurate score. 
