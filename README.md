# Bank-customer-churn
### Table of Contents

1. [Installation](#installation)
2. [The process of data analysis](#analysis)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The codes is written in Python 3. To run the codes, please make sure you have installed some libraries, like numpy, pandas, seaborn, etc.

## The process of data analysis (based on CRISP-DM process) <a name="analysis"></a>
- Busineess understanding <br>
For this project, I was interestested in using the bank customer churn to address the questions below:
1. What are the main factors, which affect the customer churn?
2. How does these main factors affect the customer churn?
3. Which is the best method to predict the churn?
4. Whether the SMOTE method can improve the prediction accuracy?

- Data understanding <br>
The bank customer churn data was obtained from Kaggle. It is stored in a csv file, named as "bank customer churn dataset". It has 14 columns, called features, including row number, customer id, surname, credit score, geography, gender, age, tenure, balance, number of products purchased through the bank, whether has a credit card, whether is an active member, estimated salary, and whether exited from the bank. <br>

- Prepare data <br>
The categorical data, like the features geography and gender was handled with one-hot encoding.
After checking the missing values in this dataset, it showed no missing values.

- Data modeling <br>
Studied the correlation between every features and churn outcome. <br>
Divided the whole data into training data and test data. <br>
Built several machine learning models (Gaussian naive bayes, logistic regression, linear discriminant analysis, quadratic discriminant analysis, decision tree, support vector machine, k-nearest neighbors, random forest) to predict the customer churn.

- Evaluate the results <br>
Evaluated the predictions with accuracy, f1 score, and confusion matrix.

## Results<a name="results"></a>

Some findings can be found [here](https://medium.com/@ZiyangZhang/what-matters-for-bank-customer-churn-fae204a35b8c).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to bank customer churn data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/santoshd3/bank-customers).  Otherwise, feel free to use the code here as you would like! 

