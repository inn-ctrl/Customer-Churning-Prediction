# Customer-Churning-Prediction
Predicting which retail customers are likely to stop shopping at the store.

What customers are likely to churn? What customers should we target?
What are their common features?
Which classification model performs the best?
What if we redefine the churn event to a multiclass problem, eg. no interaction/visit/transaction?


# Problem Statement

An online retail (E commerce) company wants to know the customers who are going to churn, so they can respond accordingly.

If customers that are likely to stop shopping at this retail store are identified; this is crucial for minimizing their churn and optimize retention strategies. 

* In the context of this project, churn is when a customer completely stops to buy the products. For that purpose, any one who is displaying leading traits is considered likely to churn
  
* According to Bloom Intelligence, a churn rate between 5 to 7 percent is considered acceptable. Something less than 5 is great but over 7 is a concern. 

Churning can happen due to all sorts of reasons. This project aims to identify which (if there is) is/are the reason(s) for churning. Is it one of the following? or any other? 
* unsatisfactory services
* competing products
* changing customer needs
* lack of engagement

The overall mission of this project is to not only help in retaining valuable customers by addressing customer satisfaction, but also enhance overall business profitability. 

# Dataset
The data set belongs to a leading online E-Commerce company. An online retail (E commerce) company wants to know the customers who are going to churn, so accordingly they can approach customer to offer some promos.

(Link to Kaggle: https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction )

# Data Preparation

Clean data (missing values, outliers, inconsistencies)

* Some numeric columns have nulls. Since these numbers are very few in comparison, I decided to replace those nulls with the mean of respective columns
* I performed a few checks to see if there are white spaces and if categorical data makes sense. With categorical data, I made the following assumption:

"Mobile Phone is same as Phone": Even though there are subtle differences in that one can be portable and another stationary, but they are mostly interchangeable terms. Since they are devices used to log-in to the e-commerce store, I would assume they are all smartphones in the end. So, I went with 'Mobile Phone'. 

"In prefered payment columns, CC same as Credit Card and COD is same as Cash On Delivery". So, they were fixed as well. 

"UPI is same as Unified Payment Interface". It was removed from abbreviations just to make things consistent. 

* Outliers: There are 4 outliers in 'Tenure column'- a column that shows how long a customer has been with the business.Considering that the e-commerce business is likely to have loyal customers for a longer time compared to others; this is a genuine outlier. I decide to keep them since they might provide valuable insights 

Perform EDA using to understand distribution, correlations, and patters
(example of KPIs to identify: declining purchase frequency, reduced average spending, average purchase frequency overtime, customer support interaction,  or shifts in shopping preferences,)


Create a dashboard for Performance metrics in Tableau

# Feature Engineering

Identifying necessary feature transformation (scaling numerical features, econding categorical variables, deriving new features from existing ones)

# Model Selection and Training
Choose appropriate Model and Explain the rationale

Train the model

Choose the metrics to be use

# Model Evaluation 
Evaluate the model using appropriate metrics and fine tuning

# Model Interpretation 
Interprate the model results using Feature Importance Analysis

Business Conclusion
[By analysing the KPIs, the business can target at risk customers with personalized offers, loyalty incentives, or tailored strategies aimed at increasing engagement and loyalty]

# Model Deployment
Deploy the moel into production and develop a user interface

# Monitoring 
Plan strategies to implement to ensure the model remails accurate and reliable over time

# Presentation
Summarize the entire proces including findings, insights, and recommendations from the project in the presentation- preferably a video presentation

Share it somewhere to gather the feedback
