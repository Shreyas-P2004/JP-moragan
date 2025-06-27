# Natural Gas Storage Contract 

# Objective
1) As a quantitative researcher visualize the data to find patterns and consider what factors might cause the price of natural gas to vary. This can include looking at months of the year for seasonal trends that affect the prices, but market holidays, weekends, and bank holidays need not be accounted for. Each point in the data set corresponds to the purchase price of natural gas at the end of a month, from 31st October 2020 to 30th September 2024.
Analyze the data to estimate the purchase price of gas at any date in the past and extrapolate it for one year into the future. 
Your code should take a date as input and return a price estimate.
2) Performed the credit risk analysis to train the model  that will estimate the probability of default for a borrower. Assuming a recovery rate of 10%, this can be used to give the expected loss on a loan.
3) Bicketed the FICO score which is standardized credit score quantifies the creditworthiness of a borrower to a value between 300 to 850, construct a technique for predicting the PD (probability of default) for the borrowers using these scores with the help of dynamic programming.

# Dataset Used
 <a href = "https://github.com/Shreyas-P2004/JP-moragan/blob/main/Nat_Gas.csv">Dataset</a>
 <a href = "https://github.com/Shreyas-P2004/JP-moragan/blob/main/Task%203%20and%204_Loan_Data.csv">Dataset</a>

# Questions(KPI)
- Each point in the data set corresponds to the purchase price of natural gas at the end of a month, from 31st October 2020 to 30th September 2024.
- Analyze the data to estimate the purchase price of gas at any date in the past and extrapolate it for one year into the future.
- Your code should take a date as input and return a price estimate.
- Create a prototype pricing model that can go through further validation and testing before being put into production.
- Write a function that takes these inputs and gives back the value of the contract.
- Consider all the cash flows involved in the product.
- The input parameters that should be taken into account for pricing are:

1) Injection dates. 
2) Withdrawal dates.
3) The prices at which the commodity can be purchased/sold on those dates.
4) The rate at which the gas can be injected/withdrawn.
5) The maximum volume that can be stored.
6) Storage costs.

- You should produce a function that can take in the properties of a loan and output the expected loss.
- You can also use multiple methods and provide a comparative analysis.
-  You need to create a rating map that maps the FICO score of the borrowers to a rating where a lower rating signifies a better credit score.
-  Given set number of buckets corresponding to the number of input labels for the model, she would like to find out the boundaries that best summarize the data. 

# Codes
 <a href = "https://github.com/Shreyas-P2004/JP-moragan/blob/main/JP_Morgan_task1.ipynb">Code1</a>
 <a href = "https://github.com/Shreyas-P2004/JP-moragan/blob/main/JP_Morgan_task2.ipynb">Code2</a>
 <a href = "https://github.com/Shreyas-P2004/JP-moragan/blob/main/JP_Morgan_task3.ipynb">Code3</a>
 <a href = "https://github.com/Shreyas-P2004/JP-moragan/blob/main/JP_Morgan_task4.ipynb">Code4</a>
 
 

# Process
- Imported the pandas, numpy, matplotlib, datetime , sklearn and linear regression libraries.
- Mounted the google drive and read the dataset.
- Plotted the graph for the dates vs the varying prices using matplotlib.
- Selected only the january prices and months.
- Used linear regression to the fit the model.
- Extraploated for the next year.
- Created an array for the next year price.
- Started from the last day of the year and append the dates in the array for current month and year.
- Moved to the first day of the previous month.
- Then moved back one day to get the last day of the current month using timedelta funtion.
- Reversed the array in the ascending order.
- Read the last dates for each month for the year 2025.
- Created a new dataframe for the 2025 dates and prices.
- Did the final analysis of the gas price and forecasted it.
- Predicted the graph using the historical data vs improved gas price model using the sin function.
- Calculated the various parameters in gas storage contracts such as injection rates, withdrawal dates , injection rate , injection withdrawal costs , maximum storage volume and storage cost per month.


 - Used logistic regression and decision tree methods to provide a comparative analysis.
 - Imported pandas, sklearn , Standard scaler and ROC(Reciever operating characteristic curve) and AUC curve
 - Spilted the data into fetaures and target.
 - Scaled the features.
 - Splited the data into train and the test sets.
 - Initialized the logistic regression model.
 - Trained the logistic regression model.
 - Predicted the probabbilities of the default.
 - Plotted the confusion matrix using seaborn.
 - Created the dataframes to hold the feature names and coefficients.
 - Printed the sorted features.
 - Used the loss function to trained the model.
 - Calculated the expected loss.
 - Tested the borrower features.
 - Calculated the expected loss for the borrower.
 - Plot the decision tree with a depth of 2.
 - Extracted Information about the decision path within the tree, focusing on the leaf nodes.
 - Got this ids of the leaf nodes.
 - Initialized an empty list to hold the leaf information.
 - Iterated over each leaf node.
 - Got the number of samples at the given leaf.
 - Appended the leaf information to our list.
 - Produced an array containing the counts of [class_0, class_1] for all leaves.
 - Predicted the class labels for the test set.
 - Computed the confusion matrix using decision tree algorithm.
 - Plotted the confusion matrix using seaborn.
 - Bucketed the FICO scores by importing the scipy , binom and matplotlib.
 - Loaded the consumer loan dataset into the python IDE.
 - Initialized 5 buckets for simplicity.
 - Then used the log-likelihood function to initialize the bucket boundaries.
 - Optimized the bucket boundaries.
 - Optimized the buckets.
 - Updated the data with the optimized buckets.
 - Tested the 4,5,6,7,8,9 and 10 buckets with 2 iterations each.
 - Then getting the output for the best number of the buckets using optimization.
 - Plotted the final bucketing.
 - Updated the dataframe with the optimal bucket and plotted the graph. 

