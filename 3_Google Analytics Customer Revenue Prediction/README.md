[Google Analytics Customer Revenue Prediction](https://www.kaggle.com/c/google-analytics-customer-revenue-prediction)

# **1. Description:**

The 80/20 rule has proven true for many businesses–only a small percentage of customers produce most of the revenue. As such, marketing teams are challenged to make appropriate investments in promotional strategies.
RStudio, the developer of free and open tools for R and enterprise-ready products for teams to scale and share work, has partnered with Google Cloud and Kaggle to demonstrate the business impact that thorough data analysis can have.
In this competition, you’re challenged to analyze a Google Merchandise Store (also known as GStore, where Google swag is sold) customer dataset to predict revenue per customer. Hopefully, the outcome will be more actionable operational changes and a better use of marketing budgets for those companies who choose to use data analysis on top of GA data.

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
