# telecom-churn-case-study



Multivariate Logistic Regression - Telecom Churn Example
Let's now look at the process of building a logistic regression model in Python.


You will be looking at the telecom churn prediction example. You will use 21 variables related to customer behaviour (such as the monthly bill, internet usage etc.) to predict whether a particular customer will switch to another telecom provider or not (i.e. churn or not).


Problem Statement
You have a telecom firm which has collected data of all its customers. The main types of attributes are:

Demographics (age, gender etc.)
Services availed (internet packs purchased, special offers taken etc.)
Expenses (amount of recharge done per month etc.)


Based on all this past information, you want to build a model which will predict whether a particular customer will churn or not, i.e. whether they will switch to a different service provider or not. So the variable of interest, i.e. the target variable here is ‘Churn’ which will tell us whether or not a particular customer has churned. It is a binary variable - 1 means that the customer has churned and 0 means the customer has not churned.


Please find the churn dataset [here](https://ml-course2-upgrad.s3.amazonaws.com/Multivariate+Logistic+Regression+-+Model+Building/churn_data.csv).

Please find the internet_data dataset [here](https://ml-course2-upgrad.s3.amazonaws.com/Multivariate+Logistic+Regression+-+Model+Building/internet_data.csv).

Please find the customer_data dataset [here](https://ml-course2-upgrad.s3.amazonaws.com/Multivariate+Logistic+Regression+-+Model+Building/customer_data.csv).

Please find the data dictionary [here](https://ml-course2-upgrad.s3.amazonaws.com/Multivariate+Logistic+Regression+-+Model+Building/Telecom+Churn+Data+Dictionary.csv)



Please find the Logistic Regression code file here

So, here’s what the data frame churn_data looks like:

Data Frame 1:  churn_data
Data Frame 1: churn_data
Also, here’s the data frame customer_data:

Data Frame 2: customer_data
Data Frame 2: customer_data
Lastly, here’s the data frame internet_data:

Data Frame 3: internet_data
Data Frame 3: internet_data
Now, as you can clearly see, the first 5 customer IDs are exactly the same for each of these data frames. Hence, using the column customer ID, you can collate or merge the data into a single data frame. We'll start with that in the next segment.

## Contact
Created by [@sanjayakumarsahoo] - feel free to contact me!

