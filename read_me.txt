Overview
In this article, we’re going to discuss employee attrition prediction i.e. predicting that employee will leave the current company (or will resign from the current company) and we will do this using several machine learning algorithms (basically 6 ML algorithms) but this article is gonna be completely step by step explanation. So let’s get started.

Code:
1. Importing files
2. Reading dataset
3. Cleaning the dataset by Encoding the locations column (categorized)
4. Now we will make a function for the location column to make a new column where encoded location values will be there because our machine learning algorithm will only understand int/float values.
5. Saving the cleaned dataset into another CSV file
6. Now, from the processed data we have to separate the features and target column again.
7. Now, from one block of code, we will check the accuracy of all the model
8. Saving the best model