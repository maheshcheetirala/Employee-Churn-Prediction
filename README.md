# Employee-Churn-Prediction
This Project aims at predicting the Employee churn using Machine learning.<br>
Data import and cleaning done using python pandas library<br>
Ordianl and Nominal categories are converted into numerical using categorical codes and pandas dummies<br>
No missing values are present in the dataset<br>
Train test split done using sklearn library<br>
Decison tree algorith was built using default features and gini impurity<br>
The model was overfitted hence pruned the tree by using max depth and min_sample_leafs attributes<br>
Next the model was further improved by making the classes balanced<br>
cross validation was used with 10 folds<br>
Finally Grid search CV was implemented to tune the model and choose best parameters<br>
