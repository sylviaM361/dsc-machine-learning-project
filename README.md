# dsc-machine-learning-project
Vaccine Project
Target variables
The **feature variables** consist of all the other relevant columns that may influence vaccination behavior. These variables include demographic information, health behaviors, and opinions about vaccines.

Some columns are removed when creating the feature dataset:
- The column h1n1_vaccine is separated from the dataset to create the target variable (y), since it represents the outcome we want to predict. It is then removed from the feature dataset (X) to prevent the model from using the answer during training.

- seasonal_vaccine is removed to avoid potential data leakage since it is another vaccination outcome.
- respondent_id is removed because it is only a unique identifier and does not contribute meaningful information for prediction.

After separating the dataset into features (X) and the target variable (y), we print the shapes of both datasets to confirm the number of observations and variables being used in the modeling process.
