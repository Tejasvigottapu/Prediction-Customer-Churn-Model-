
REPORT ON THE DATASET

1. In the process of fitting and predicting the model, i used libraries namely pandas, numpy, matplotlib and seaborn.

2. Then reading the csv file. 

3. For handling the missing values
a) isnull() function - if any null value exists it gives true   
b) To check the existences of null values visually i have used the following code: 
 sns.heatmap(df.isnull(),yticklabels=False, cmap='viridis')
c) For more clarity, how many missing values exists in each column:
df.isnull().sum()

4. Encoding the categorical data, here basically the categorical data is converted to numerical data this will help in the upcoming steps.

5.Next, we will be seeing that which all columns are more correlated with Churn by using the following code 
df.corr()

6. And found that SeniorCitizen, PaperlessBilling and MonthlyCharges are more correlated with Churn and plotted a pairplot and histogram.

7. Then made the independent variables(x) and dependent variable(y).

8. Followed by splitting the data into train and test.

9. By using the Logistic Regression we fit the model by model.fit() function and predict it by using model.predict() function.

10. Then for checking the accuracy we use the function model.score() and got 0.7375 accuracy.

11. At last we design a confusion matrix by using confusion_matrix() function by using the actual and the predicted values as arguments.

The problem that i faced during project is while submitting the google form my gmail id not working so i have used my friend's gmail id and i am not ablw to make new gmail id because i was running out of time. I am Really sorry for my actions and i make sure this will not happen again. 

