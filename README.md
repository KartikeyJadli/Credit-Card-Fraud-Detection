# Credit-Card-Fraud-Detection

This Repository contains the Model for the Credit Card Fraud Detection and at will provide all the necessary explaination for the whole miniproject.

The link for the dataset is : 
https://drive.google.com/file/d/1ePw7PaGlrzbj7uv6nQZEmhmoowjMR8Zi/view?usp=share_link

PROBLEM STATEMENT:

The Credit card firms and companies have an important task to detect any fraudalant credit card transactions to preventing any charges the customer has to pay even if they did not buy it. Now the problem occurs that an employee or n number of employee cannot detect any these kind of frauds by just looking at them. Here comes the main part of Data Science i.e., Machine Learning. Below is the code and explaination for the given problem statement.

We can view the dataset as follows:

![image](https://user-images.githubusercontent.com/96066261/218240832-47e480f4-2196-42c7-b395-0e372a3d5701.png)

By seeing the dataset we can see that the feature Time is measured in seconds and it has been measured since the first transaction in the dataset. Furthermore, we can conclude that the data collected is for the transactions made for 2 days as we have the maximum value for time as 172792 seconds and the time in seconds for 2 days is (24 * 3600 * 2) i.e., 172800. The features were prepared using PCA, so the physical interpretation of individual features does not make sense. 'Time' and 'Amount' are the only features that are not transformed to PCA. 'Class' is the response variable, and it has a value of 1 if there is fraud and 0 otherwise.

This dataset contains 492 frauds out of 284,807 transactions over two days.

By clearly plotting the distribution of time and distribution of amount we can see:

![image](https://user-images.githubusercontent.com/96066261/218240886-7732bbad-6d35-40d7-90a9-71bf5341bd14.png)


The train_test_split from sklearn

This splits arrays or matrices into random train and test subsets as defined by the programmer. We generally split the dataset in 4 : 1 ratio i.e., 80 % for training and 20 % for testing, if the dataset is not sufficient. But here we have a good amount of data so The split used is 7 : 3. 70 % of the dataset is used for training the model and 30 % of the data for testing the model.
