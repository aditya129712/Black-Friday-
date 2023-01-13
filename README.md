# Black-Friday-Sales-Prediction

Problem Statement:
Retail is the sale of goods and services from individuals or businesses to the enduser.
The retail industry provides consumers with goods and services for their everyday
needs. In retail one of crucial part is to understand the consumer behaviour and make
various arrangements for the sales of the company.
A retail company “ABC Private Limited” wants to understand the customer purchase
behaviour (specifically, purchase amount) against various products of different categories.
They have shared purchase summary of various customers for selected high
volume products from last month.
The data set also contains customer demographics (age, gender, marital status,
city_type, stay_in_current_city), product details (product_id and product category) and
Total purchase_amount from last month.
Now, they want to build a model to predict the purchase amount of customer against
various products which will help them to create personalized offer for customers against
different products.
Data
Variable Definition
User_ID User ID
Product_ID Product ID
Gender Sex of User
Age Age in bins
Occupation Occupation (Masked)
City_Category Category of the City (A,B,C)
Stay_In_Current_City_Year
Number of years stay in current city
Marital_Status Marital Status
Product_Category_1 Product Category (Masked)
Product_Category_2 Product may belongs to other category also
(Masked)
Product_Category_3 Product may belongs to other category also
(Masked)
Purchase Purchase Amount (Target Variable)

Your model performance will be evaluated on the basis of your prediction of the
purchase amount for the test data (test.csv), which contains similar data-points as train
except for their purchase amount. Your submission needs to be in the format as shown
in "SampleSubmission.csv".
We at our end, have the actual purchase amount for the test dataset, against which your
predictions will be evaluated. Submissions are scored on the root mean squared error
(RMSE). RMSE is very common and is a suitable general-purpose error metric.
Compared to the Mean Absolute Error, RMSE punishes large errors
Where y hat is the predicted value and y is the original value.
Find key metrics and factors and show the meaningful relationships between attributes. Do
your own research and come up with your findings.


![image](https://user-images.githubusercontent.com/54885297/212358242-cac03867-c5f9-45fc-8b05-e9b73d7f565c.png)


Approach-
The detailed architecture of the Black Friday Sales Analysis has been divided into step by step process which gives an idea about the Project -
(1)Export the data from database to importing the data into Jupyter notebook by using pandas library.
(2) And for data cleaning process Use the Pandas Library.
(3)And for visualize the data, visualization library such Matplotlib and seaborn is used for the purpose.
(4) Again, P #powerbi #github andas library is used for the Feature engineering Purpose
(5) Then Scikit learn library is used for feature selection , model training, hyperparameter tuning and model evaluation of the data. (6) And finally, deploying the trained data into Power Bi for creating an interactive dashboard.
