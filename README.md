# Employee-Churn-Prediction
This Project aims at predicting the Employee churn using Machine learning.
Data import and cleaning done using python pandas library.
Ordianl and Nominal categories are converted into numerical using categorical codes and pandas dummies.
No missing values are present in the dataset.
Train test split done using sklearn library.
Decison tree algorith was built using default features and gini impurity.
The model was overfitted hence pruned the tree by using max depth and min_sample_leafs attributes.
Next the model was further improved by making the classes balanced.
cross validation was used with 10 folds.
Finally Grid search CV was implemented to tune the model and choose best parameters.
