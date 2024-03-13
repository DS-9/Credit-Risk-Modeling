# Credit Risk Modeling
                        
Credit risk modeling using machine learning is a technique lenders use, to find out the level of credit risk, related to extending credit to a borrower. Organizations use credit risk modeling using ML, including insurance corporations, banks, investment enterprises, and government treasuries. Sometimes, individual people use credit risk modeling to loan away their own money strategically. Credit risk modeling is crucial anywhere people are borrowing money. Machine Learning models are being used to protect against increasingly sophisticated fraud attempts.  
      
## Extreme Gradient Boosting (XGBoost) algorithm
XGBoost is a powerful machine learning tool that is used to predict the likelihood of default for a borrower. It uses a combination of decision trees and gradient boosting to create a highly accurate model that can be used to assess credit risk. The key strength of XGBoost is its efficient data structure called a histogram-based algorithm. It allows for faster training times and improved accuracy.
A general pipeline of how XGBoost looks like following:
Initialize the first decision tree with the entire dataset.
For each subsequent tree, use the residuals from the previous tree as the target variable.
Fit the new tree to the residuals and add the predicted values from this tree to the previous predictions.
Repeat steps 2 and 3 for a fixed number of iterations or until the performance on a hold-out validation set stops improving.
Combine the predictions from all trees to make a final prediction.
