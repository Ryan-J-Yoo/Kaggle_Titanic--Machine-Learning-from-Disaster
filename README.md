# Kaggle_Titanic: Machine Learning from Disaster

This is a guided project to familiarize and practice data analytic process: <br>
- **Data exploration**: to find patterns in the data
- **Feature engineering**: to create new features from those patterns or through pure experimentation
- **Feature selection**: to select the best subset of our current set of features
- **Model selection/tuning**: training a number of models with different hyperparameters to find the best performer. <br> 

The data set is from [Kaggle](https://www.kaggle.com/c/titanic/data). 

In data exploration, we looked into each feature to better understand the correlations and importance to the target feature (**'Survived'**). In feature engineering, a new feature(**'isalone'**) was introduced. In feature selection, we used the built in function RFECV to select the best features. In model selection and tuning, three different models (KNeighborsClassifier, LogisticRegression, RandomForestClassifier) were compared, and GridSearch method was used to select the best parameters as well as evaluate the best-score model.

Given only one new feature (**'isalone'**) was created, we get the conclusion that random forest model has the best performance. To get a better result, we can go back to feature engineering process to creat new features that might be beneficial to model training.
