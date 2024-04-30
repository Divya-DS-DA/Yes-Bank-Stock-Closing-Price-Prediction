# Yes-Bank-Stock-Closing-Price-Prediction
Problem Statement:

Intriguing Case:

Yes Bank, a prominent Indian financial institution, faced a major challenge in 2018 due to a fraud case. This situation raises an intriguing question: how did this event impact the bank's stock prices, and can predictive models effectively capture such market fluctuations?

Data Insights:

This dataset provides monthly stock prices of Yes Bank since its inception, including closing, starting, highest, and lowest prices for each month. The primary goal is to predict the bank's future closing stock price.

Project Approach
A stock (also known as equity) is a security that represents the ownership of a fraction of a corporation. This entitles the owner of the stock to a proportion of the corporation's assets and profits equal to how much stock they own. Units of stock are called "shares." The value of shares depends on the investors, whether more people are buying the stock or selling it, follows the simple supply – demand rule.

So, my aim was to apply different regression models on the given data to predict the closing price of the stock and then compare all the models to figure out the best one for this job. Following is the pathway followed during the whole process:

Started off with data overview, just to understand what’s in the dataset and in order to inspect how clean the dataset is for working.
Visualizations makes things easier so, performed exploratory data analysis and checked for data distribution.
Used log transformation to make them normally distributed features as the features were a bit skewed.
Checked for multicollinearity to check if the features are depedent or independent of each other.
Splitted the dataset into training and testing data (80% of the data is used for training & 20% of the data is being used for testing).
Created machine learning models using the following algorithms:
Linear Regression
Ridge Regession
Lasso Regression
Elastic-Net Regression
Compared model performance using different evaluation metrics in order to get the best performing model.
Machine Learning Models
