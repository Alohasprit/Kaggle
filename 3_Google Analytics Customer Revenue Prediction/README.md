[Google Analytics Customer Revenue Prediction](https://www.kaggle.com/c/google-analytics-customer-revenue-prediction)

[Description]('./image/Description.jpeg')



# **2. Evaluation:**

**Root Mean Squared Error (RMSE)**

Submissions are scored on the root mean squared error. RMSE is defined as:

where y hat is the predicted revenue for a customer and y is the natural log of the actual revenue value.

**Submission File**

For each fullVisitorId in the test set, you must predict the natural log of their total revenue in PredictedLogRevenue. The submission file should contain a header and have the following format:

fullVisitorId,PredictedLogRevenue
0000000259678714014,0
0000049363351866189,0
0000053049821714864,0
etc.
