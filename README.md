# ML-Credit-Approval


The program first feeds the dataset into pandas, preprocesses it, and then divides it into training and test sets. Depending on the column's data type, the preprocessing procedures also involve removing certain columns, replacing "?" with NaN values, imputing missing values with the mean or the most common value, one-hot encoding categorical features, and scaling the features. Following preprocessing, the code creates predictions using the test data and fits a logistic regression model to the training data. The model's accuracy score and confusion matrix are then calculated, and GridSearchCV is used to figure out the best hyperparameter values.
