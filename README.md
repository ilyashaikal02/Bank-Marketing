Introduction : Marketing to potential clients has always been a crucial challenge in achieving success for banking institutions. It’s not a surprise that banks usually deploy mediums such as social media, customer service, digital media, and strategic partnerships to reach out to customers. But how can banks market to a specific location, demographic, and society with increased accuracy? With the inception of machine learning, reaching out to specific groups of people has been revolutionized by using data and analytics to provide detailed strategies to inform banks which customers are more likely to subscribe to a financial product. In this project on bank marketing with machine learning, I will explain how a particular Portuguese bank can use predictive analytics from data science to help prioritize customers who would subscribe to a bank deposit

Data description : The data set is based on the direct marketing campaigns of a Portuguese banking institution. These marketing campaigns were based on phone calls. More than one contact with a client was required in order to know if the product (a bank term deposit) was subscribed by a client or not. The classification goal is to predict if a client will subscribe to the bank's term deposit (yes or no).

The dataset contains 21 columns, including the output (y). I am going to discard the output column and use the remaining columns to find the most relatable independent variables (x) that will be able to predict if a customer will subscribe to a bank deposit or not.

In this project I will demonstrate how to build a model predicting clients subscribing to a bank's term deposit in Python using the following steps:

- Data Exploration

- Feature Engineering

- Building training/Validation/Test Samples

- Model Selection

- Model Evaluation

Through this project, we created a machine learning model that is able to predict how likely clients will subscribe to a bank term deposit. The best model was gradient boosting classifier with optimized hyperparameters. The model's performance is 79.5%.

A precision of 0.82 divided by a prevalence of 0.50 gives us 1.6, which means that the machine learning model helps us 1.6 times better than randomly guessing. The model was able to catch 62% of customers that will subscribe to a term deposit.
