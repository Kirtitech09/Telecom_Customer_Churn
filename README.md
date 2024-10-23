# Telecom Customer Churn
What is Customer Churn?

Customer churn is defined as when customers or subscribers discontinue doing business
with a firm or service.
Customers in the telecom industry can choose from a variety of service providers and
actively switch from one to the next. The telecommunications business has an annual churn
rate of 15-25 percent in this highly competitive market.
Individualized customer retention is tough because most firms have a large number of
customers and can&#39;t afford to devote much time to each of them. The costs would be too
great, outweighing the additional revenue. However, if a corporation could forecast which
customers are likely to leave ahead of time, it could focus customer retention efforts only
on these &quot;high risk&quot; clients. The ultimate goal is to expand its coverage area and retrieve
more customers loyalty. The core to succeed in this market lies in the customer itself.
Customer churn is a critical metric because it is much less expensive to retain existing
customers than it is to acquire new customers.
To detect early signs of potential churn, one must first develop a holistic view of the
customers and their interactions across numerous channels.As a result, by addressing churn,
these businesses may not only preserve their market position, but also grow and thrive.
More customers they have in their network, the lower the cost of initiation and the larger
the profit. As a result, the company&#39;s key focus for success is reducing client attrition and
implementing effective retention strategy.


Objectives:
- Finding the % of Churn Customers and customers that keep in with the active
services.
- Analysing the data in terms of various features responsible for customer Churn
- Finding a most suited machine learning model for correct classification of Churn and
non churn customers.

The data set includes information about:

-  Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet,
online security, online backup, device protection, tech support, and streaming TV
and movies
- Customer account information – how long they’ve been a customer, contract,
payment method, paperless billing, monthly charges, and total charges
-  Demographic info about customers – gender, age range, and if they have partners
and dependents

Implementation:
Libraries: sklearn, Matplotlib, pandas, seaborn, and NumPy


------------------------------------------------------------------------------------------------------------


To address the objectives listed in your Telecom Customer Churn Prediction project, we will focus on:

Finding the percentage of churned customers.
Analyzing the data for features that contribute to churn.
Building a machine learning model for churn prediction (best suited model).
Since the objective involves classification (predicting churn or non-churn), common algorithms include Logistic Regression, Random Forest, XGBoost, and Support Vector Machines (SVM). Based on the dataset features, a good starting model would be Random Forest or XGBoost due to their ability to handle both numerical and categorical features efficiently.

Step-by-Step Python Code:
Here’s Python code that includes:

Data Preprocessing.
Exploratory Data Analysis (EDA).
Machine Learning (Random Forest as a base model).

Key Points of the Code:

Data Preprocessing:

Handled missing values in TotalCharges.
Converted categorical features to numerical values using LabelEncoder.

Random Forest Model:

Built a Random Forest Classifier, which is a good starting point for classification problems.
Evaluated performance using accuracy, confusion matrix, and classification report.

Feature Importance:
Plotted a bar graph of feature importance to analyze which features have the most impact on churn prediction.

Churn Percentage:

Calculated the percentage of customers who churned.

________________________________________________________________


To test Logistic Regression for churn prediction and see if it improves the accuracy compared to the Random Forest model, we can use the following steps:

Preprocessing: Ensure that the dataset is properly prepared.
Logistic Regression Model: Build, train, and evaluate the model.
Compare Results: Compare its performance with the Random Forest model.

Key Points:
Preprocessing: If you've already done this for Random Forest, you don’t need to repeat it, but make sure the features are properly encoded (e.g., converting categorical variables into numerical ones).

Logistic Regression Model:

Logistic Regression is a good starting point for classification problems like churn prediction because it's simpler and less prone to overfitting, especially with fewer features.
The code includes the basic model (max_iter=10000 ensures enough iterations for convergence).
Model Evaluation:

The model's accuracy is printed along with the confusion matrix and classification report (precision, recall, F1-score).
At the end, the code also compares the Random Forest model’s accuracy against the Logistic Regression model.


