# Classification of Mushroom: 

## Summary
- Got the dataset about mushroom from Kaggle.
- Aim is to predict if the mushroom is poisonous or not.
- Splitted the training and the test data by 70/30 ratio.
- Used different machine learning models for the classification and measured their accuracy using cross validation.


## Data Collection
- Link to the dataset: https://www.kaggle.com/uciml/mushroom-classification

## Data Exploration(Exploratory Data Analysis)
- Found some '?' in the stalk-root column so replaced it with the mode of the column.
- Plotted different bar plots to know about distribution of mushroom for the features.

## Data Preprocessing
- Used Lable Encoder to encode the features as the data was categorical.
- After using Label Encoder did one hot encoding

## Train and Test Split
- Now that we have cleaned our data, we will do the test and train split using the train_test_split function.
- We will use 70% of the data as the training data and the remaining 30% as the test data.

## Result
### Accuracy
- Mean cross validation accuracy of `logistic regression` turned out to be 0.9996.
- Mean cross validation accuracy of `Gaussian Naive Bayes` turned out to be 0.9525.
- Mean cross validation accuracy of `Decision Tree Classifier` turned out to be 0.9998.
- Mean cross validation accuracy of `Random Forest Classifier` turned out to be 1.0.

- Decision Tree Classifier is the best classifier among all based on accuracy.




