I implemented the Simple Linear Regression Model on the boston housing dataset. Steps which i performed to build the the model in order to predict the prices of houses are as follows:

1. Imported the Boston dataset from the sklearn dataset repository.
2. Printed the value of the boston dataset to understand what it contains.
3. Created a correlation matrix that measures the linear relationships between the variables.
4. Used the heatmap function from the seaborn library to plot the correlation matrix.
5. After analyzing the heatmap, I choose RM (average number of rooms per dwelling) as the Independent Variable because the correlation was 0.7 (Strong Positive Correlation) with MEDV (prices). MEDV is our dependent (target) variable.
6. Applied the linear regression model to predict the house prices.
7. Read the csv file that contain the rooms without house pricing.
8. Predicted the prices of the house based on the number of rooms then exported the CSV file that contain rooms with predicted house prices.

All files are attached in this repository for reference.

Thanks & Regards
Zeeshan Ali
